# Algoritmo de Compressão Huffman

### Alunos:
Gabriel Viggiano Fonseca, Gabrielle Azevedo Duda e Romildo Costa

# Explicação Teórica
A codificação de Huffman é um método de compressão que usa as probabilidades de ocorrência dos símbolos no conjunto de dados a ser comprimido para determinar códigos de tamanho variável para cada símbolo. Ele foi desenvolvido em 1952 por David A. Huffman que era, na época, estudante de doutorado no MIT, e foi publicado no artigo "A Method for the Construction of Minimum-Redundancy Codes".

Uma árvore binária completa, chamada de árvore de Huffman é construída recursivamente a partir da junção dos dois símbolos de menor probabilidade, que são então somados em símbolos auxiliares e estes símbolos auxiliares recolocados no conjunto de símbolos. O processo termina quando todos os símbolos forem unidos em símbolos auxiliares, formando uma árvore binária. A árvore é então percorrida, atribuindo-se valores binários de 1 ou 0 para cada aresta, e os códigos são gerados a partir desse percurso.

O resultado do algoritmo de Huffman pode ser visto como uma tabela de códigos de tamanho variável para codificar um símbolo da fonte. Assim como em outros métodos de codificação, os símbolos mais comuns são geralmente representados usando-se menos dígitos que os símbolos que aparecem com menos frequência.


# Problema Proposto
O problema proposto consiste em implementar o algoritmo de Huffman aqui descrito em alguma linguagem de programação. O algoritmo deverá receber uma palavra como entrada (texto) e realizar os seguintes passos: <br>
  1 – Pegar o texto e implementar um algoritmo que retorna a frequência dos caracteres.<br>
  2 - Construir a tabela de codificação; <br>
  3 – Codificar um texto como exemplo; <br>
  4 – Descodificar o texto. <br>

# Implementação
Para a implementação utilizamos a linguagem Python, por possuir ótimos bibliotecas de apoio.

### Trechos mais Importantes
Classe Nó:

![Alt text](https://github.com/gabrielviggiano/MD_Huffman/blob/master/classeNo.png?raw=true "classeNo")<br>



Classe Lista_Nos:


Classe ArvoreHuffman:

# Resultados e Análise


# Bibliografia



