# ordenacao-tempo

Experimento de Análise de Algoritmos de Ordenação
Introdução
Este experimento tem como objetivo comparar o desempenho de cinco algoritmos de ordenação amplamente utilizados: MergeSort, QuickSort, BubbleSort, InsertionSort e SelectionSort. A avaliação desses algoritmos foi realizada em três cenários diferentes: números aleatórios, números decrescentes e números crescentes. Analisar os tempos de execução em diferentes contextos oferece insights valiosos sobre a eficiência relativa desses algoritmos.

Metodologia
Implementação dos Algoritmos de Ordenação:
MergeSort: Algoritmo de ordenação por divisão e conquista que divide a lista em sublistas ordenadas, combinando-as para obter a lista final ordenada.
QuickSort: Algoritmo de ordenação por divisão e conquista que seleciona um pivô e organiza os elementos ao redor dele.
BubbleSort: Algoritmo de ordenação que compara elementos adjacentes e os troca se estiverem na ordem errada.
InsertionSort: Algoritmo de ordenação que constrói uma sequência ordenada, inserindo elementos não ordenados na posição correta.
SelectionSort: Algoritmo de ordenação que seleciona repetidamente o menor (ou maior) elemento e o move para a posição correta.
Geração de Dados:
Três conjuntos de dados com 10.000 elementos cada foram criados: números aleatórios, números decrescentes e números crescentes.
Avaliação de Desempenho:
Cada algoritmo foi executado 10 vezes para cada cenário.
O tempo de execução foi medido utilizando System.currentTimeMillis().
Para cada cenário, o tempo médio de execução foi calculado a partir das 10 execuções.
Resultados Obtidos
Números Aleatórios:
MergeSort: 1 ms
QuickSort: 0 ms
BubbleSort: 64 ms
InsertionSort: 7 ms
SelectionSort: 17 ms
Números Decrescentes:
MergeSort: 0 ms
QuickSort: 19 ms
BubbleSort: 60 ms
InsertionSort: 7 ms
SelectionSort: 17 ms
Números Crescentes:
MergeSort: 0 ms
QuickSort: 26 ms
BubbleSort: 0 ms
InsertionSort: 0 ms
SelectionSort: 16 ms
Discussão e Conclusões
O QuickSort mostrou-se o algoritmo mais eficiente em diversos cenários, com tempos de execução próximos a 0 ms em muitos casos.
O BubbleSort foi o menos eficiente, especialmente com conjuntos de dados aleatórios, onde seu tempo de execução foi significativamente maior.
O SelectionSort surpreendeu ao superar o QuickSort em cenários de dados crescentes, indicando que, em certos contextos, algoritmos aparentemente simples podem se destacar.
A escolha do algoritmo de ordenação deve considerar o contexto específico em que será aplicado, pois cada algoritmo possui pontos fortes e fracos.
Este experimento proporcionou uma compreensão detalhada da eficiência dos algoritmos de ordenação em diferentes situações, contribuindo para uma visão mais aprofundada de suas complexidades e aplicações no campo da ciência da computação.
