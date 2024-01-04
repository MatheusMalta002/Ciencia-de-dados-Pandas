# Correspondência de strings com distância de Levenshtein

### Objetivo
* Este projeto visa desenvolver habilidades de limpeza de dados e manipulação de strings.
  
### Motivação
* No mundo real, a coleta de dados geralmente envolve diferentes origens, como APIs, bancos de dados, planilhas e intervenção humana. Por isso, é provável que esses dados apresentem padrões distintos.

### Explicação
* Neste projeto, possuo dois conjuntos de dados que contêm nomes de organizações listadas no site da Forbes. No entanto, os nomes das empresas em um arquivo CSV estão na forma como os clientes reconhecem a empresa, enquanto no outro estão os nomes completos das empresas, por exemplo: Apple versus Apple Inc.
  
* Para um ser humano, identificar que "AECOM" e "AECOM TECHNOLOGY CORPORATION" representam a mesma empresa é fácil. Contudo, como podemos fazer com que a máquina pense de maneira semelhante a um humano?

* Para essa tarefa, pretendo utilizar a distância de Levenshtein, implementada na biblioteca fuzzywuzzy do Python. Essa biblioteca retorna um valor numérico de 0 a 100, representando a similaridade entre duas strings.

### Bibliotecas Python
* Pandas
* Itertools
* FuzzyWuzzy
