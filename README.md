# Análise Exploratória de Dados — Diabetes

## Sobre o projeto

Este projeto tem como objetivo realizar uma análise exploratória de dados clínicos relacionados ao diabetes, utilizando Python para investigar a distribuição das variáveis, comparar grupos com e sem diabetes e identificar padrões e associações nos dados.

A análise também aborda a qualidade da base, com foco na investigação de valores zero em variáveis clínicas e na avaliação de como seu tratamento influencia os resultados.

## Objetivos

* Explorar e compreender a estrutura da base de dados.
* Analisar a distribuição das variáveis clínicas, como glicose e idade.
* Comparar as características dos grupos com e sem diabetes.
* Investigar valores zero potencialmente inválidos ou indicativos de dados ausentes.
* Avaliar as correlações entre as variáveis.
* Comparar os resultados das correlações antes e depois do tratamento dos valores zero.
* Interpretar os resultados considerando as limitações dos dados.

## Ferramentas e tecnologias

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Google Colab

## Etapas da análise

1. Carregamento e exploração inicial da base de dados.
2. Análise da estrutura, dos tipos de dados e dos valores ausentes.
3. Exploração da distribuição das variáveis clínicas.
4. Comparação das distribuições de idade e glicose entre os grupos com e sem diabetes.
5. Investigação de valores zero em variáveis clínicas.
6. Tratamento dos valores zero selecionados como possíveis dados ausentes, preservando a base original.
7. Análise da matriz de correlação e visualização por meio de um mapa de calor.
8. Comparação das correlações antes e depois do tratamento dos dados.
9. Interpretação dos resultados e registro das limitações da análise.

## Fonte dos dados

**Base de referência:** Pima Indians Diabetes Database, disponibilizada no Kaggle.

[Consultar a base no Kaggle](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database)

O arquivo CSV utilizado na análise é carregado diretamente de um repositório público no GitHub. A equivalência exata entre esse arquivo e a versão disponibilizada no Kaggle não foi verificada.

## Principais observações

A análise identificou diferenças nos níveis de glicose e na distribuição das idades entre os grupos com e sem diabetes.

Na análise de correlação após o tratamento dos valores zero, a glicose apresentou a maior correlação positiva com a variável indicadora de diabetes, seguida pelo IMC e pela insulina.

Também foram identificados valores zero em cinco variáveis clínicas. Esses valores foram tratados como ausentes em uma cópia da base para investigar seu impacto nas análises, mantendo os dados originais preservados.

Os resultados são exploratórios. As correlações identificadas não demonstram causalidade, e as limitações relacionadas aos valores ausentes devem ser consideradas na interpretação dos resultados.

## Como visualizar o projeto

O notebook `analise_exploratoria_diabetes.ipynb` contém os códigos, gráficos, tabelas e interpretações desenvolvidos durante a análise.

O arquivo pode ser visualizado diretamente pelo GitHub ou executado no Google Colab.

## Autora

**Thamiris Damasceno Pereira**

Projeto desenvolvido durante a formação em Ciência de Dados, com o objetivo de aplicar conceitos de análise exploratória, tratamento de dados e visualização utilizando Python.
