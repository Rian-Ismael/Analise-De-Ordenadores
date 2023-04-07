# Analise-De-Ordenadores
Plotando gráfico de ordenadores (SelectionSort, insertionSort, mergeSort, quickSort e bubbleSort).

Dados adquiridos a partir da execução do código presente em $Algoritmo$. 

sort.data dados a ser plotado utilizando R.

Em R:
library('ggplot2')
data = read.table('sort.data’, header = T)
ggplot(data, aes(x = sample, y = time, colour = alg)) + geom_line()
