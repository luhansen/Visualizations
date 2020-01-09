# Algoritmos de visualização para dados educacionais

para executar os algoritmos é necessário instalar:
  - jupyter notebook
  - R studio

Em cada etapa do pré processamento é gerado um arquivo .csv.

O arquivo all.csv contem as informações cruas que foram utilizadas.

Já os arquivos:
  - meninas.csv
  - meninos.csv
  - materias.csv
  - materia_aluno.csv

São resultados do primeiro pré processamento, onde as colunas são analisadas, as informações são divididas e corrigidas.

O código para o primeiro pré processamento está nos arquivos: analise_estrutura.Rmd e arrumar_estrutura.Rmd

Na pasta make_binary tem um arquivo em python para binarizar os dados (binarizar_meninas.ipynb). ATENÇÃO: é necessário informar de qual arquivo .csv deseja binarizar os dados. Gerando assim um arquivo .csv com os dados binarizados.

Na pasta make_binary tem 2 arquivos .csv, com dados das meninas e dos meninos binarizados.

Para utilizar os algoritmos de visualização PCA e HeatMap é necessário os arquivos binarizados, o algoritmo Coordenadas Paralelas pode utilizar os dados categóricos. Os algoritmos das visualizações podem ser executas em qualquer ordem, dependem apenas do arquivo .csv.





