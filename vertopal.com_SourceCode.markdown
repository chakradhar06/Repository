::: algorithm
::: algorithmic
Zero Based Indexing for the Matrix, One Based Index for the Strings

$edit[i][0] \gets i \hfill \forall i$
$edit[0][j] \gets j \hfill \forall j$

$insert \gets 1 + edit[i][j-1]$ $delete \gets 1+ edit[i-1][j]$
$replace \gets 1 + edit[i-1][j-1]$ $match \gets edit[i-1][j-1]$
$edit[i][j] \gets match$ $edit[i][j] \gets min(insert, delete, replace)$
:::
:::
