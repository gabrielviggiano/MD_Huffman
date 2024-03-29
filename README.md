# Algoritmo de Compressão Huffman

### Alunos:
Gabriel Viggiano Fonseca, Gabrielle Azevedo Duda e Romildo Costa

# Explicação Teórica
A codificação de Huffman é um método de compressão que usa as probabilidades de ocorrência dos símbolos no conjunto de dados a ser comprimido para determinar códigos de tamanho variável para cada símbolo. Ele foi desenvolvido em 1952 por David A. Huffman que era, na época, estudante de doutorado no MIT, e foi publicado no artigo "A Method for the Construction of Minimum-Redundancy Codes".

Uma árvore binária completa, chamada de árvore de Huffman é construída recursivamente a partir da junção dos dois símbolos de menor probabilidade, que são então somados em símbolos auxiliares e estes símbolos auxiliares recolocados no conjunto de símbolos. O processo termina quando todos os símbolos forem unidos em símbolos auxiliares, formando uma árvore binária. A árvore é então percorrida, atribuindo-se valores binários de 1 ou 0 para cada aresta, e os códigos são gerados a partir desse percurso.

O resultado do algoritmo de Huffman pode ser visto como uma tabela de códigos de tamanho variável para codificar um símbolo da fonte. Assim como em outros métodos de compressão, os símbolos mais comuns são geralmente representados usando-se menos dígitos que os símbolos que aparecem com menos frequência.


# Problema Proposto
O problema proposto consiste em implementar o algoritmo de Huffman aqui descrito em alguma linguagem de programação. O algoritmo deverá receber uma palavra como entrada (texto) e realizar os seguintes passos: <br>
  1 – Pegar o texto e implementar um algoritmo que retorna a frequência dos caracteres.<br>
  2 - Construir a tabela de codificação; <br>
  3 – Codificar um texto como exemplo; <br>
  4 – Descodificar o texto. <br>

# Implementação
Para a implementação utilizamos a linguagem Python, por possuir de maneira mais acessível bibliotecas de apoio.

### Trechos mais Importantes
<b>Classe Nó:</b>

![Alt text](https://github.com/gabrielviggiano/MD_Huffman/blob/master/classeNo.png?raw=true "classeNo")<br>


<b>Classe Lista_Nos:</b>

* Funções que inserem a raiz e os elementos:
![Alt text](https://github.com/gabrielviggiano/MD_Huffman/blob/master/insereraizelemento.png?raw=true "insere")<br>

* Função que cria lista

![Alt text](https://github.com/gabrielviggiano/MD_Huffman/blob/master/criarLista.png?raw=true "criarLista")<br>

* Função que cria a árvore

![Alt text](https://github.com/gabrielviggiano/MD_Huffman/blob/master/criarArvore.png?raw=true "criarArvore")<br>

<b> Classe ArvoreHuffman: </b>

* Função que codifica

![Alt text](https://github.com/gabrielviggiano/MD_Huffman/blob/master/codificador.png?raw=true "criarArvore")<br>

* Função que descodifica

![Alt text](https://github.com/gabrielviggiano/MD_Huffman/blob/master/decodificador.png?raw=true "criarArvore")<br>

* Função que gera a tabela de Huffman:

![Alt text](https://github.com/gabrielviggiano/MD_Huffman/blob/master/tabelinha.png?raw=true "criarArvore")<br>

# Resultados e Análise
* Saída no terminal

![Alt text](https://github.com/gabrielviggiano/MD_Huffman/blob/master/saida_huffmann.png?raw=true "criarArvore")<br>

# Bibliografia

https://pt.wikipedia.org/wiki/Codifica%C3%A7%C3%A3o_de_Huffman

https://docs.python.org/2/library/collections.html

https://sites.google.com/site/tecprojalgoritmos/problemas/arvore-de-huffman

http://professor.ufabc.edu.br/~francisco.massetto/ni/Aula6.pdf



