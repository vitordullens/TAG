# To do

- [X] São fornecidos 4 arquivos (top_datasets.zip), contendo 4 grafos com números de vértices de 10, 100, 10.000, 100.000, listando como pares de números inteiros por linha o vértice, e seu respectivo adjacente. Essas adjacências são todas consideradas direcionadas (i.e. são dígrafos). Implemente dois (2) diferentes algoritmos de ordenação topológica (ps. Indique explicitamente com citação de fonte quais algoritmos e separe-os em funções diferentes), execute-os nos 4 dígrafos, imprima na tela as maiores ordenações atingidas em cada grafo, e gráficos de execução temporal (x(tempo):y(nós)) para os 2 algoritmos. Indique em quais circunstâncias (i.e. dos 4 tamanhos) a escolha de algoritmo a ser feita, imprimindo na tela essas opções justificadas pelos gráficos.

# Requirements

- Have ```g++``` installed;
- Have ```gnuplot``` installed;

# Compile

```g++ -o main main.cpp```

# Notes

- To show the ordered graph, uncomment ```showResults()``` in line 193.