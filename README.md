# Análise Planos de Telefonia


## Descrição do Projeto
Este projeto tem como objetivo desenvolver um modelo que possa analisar o comportamento do cliente e recomendar um dos planos mais recentes de uma companhia telefônica fictícia.

## Ferramentas e Bibliotecas Utilizadas
- **Python**: Linguagem principal utilizada para a análise.
- **Pandas**: Biblioteca para manipulação e análise de dados.
- **Sklearn**: Biblioteca para construção de modelo de machine learning.

## Tabela
Para este projeto temos um conjunto de dados que já foi pré-processado.

Cada observação no conjunto de dados contém informações comportamentais mensais sobre um usuário. As informações dadas são as seguintes:
- **calls** — número de chamadas
- **minutes** — duração total da chamada em minutos
- **messages** — número de mensagens de texto
- **mb_used** — Tráfego de internet usado em MB
- **is_ultra** — plano para o mês atual (Ultra - 1, Smart - 0)

## Metodologia

### Análise Exploratória de Dados
1. Importar as bibliotecas necessárias
2. Carregar e visualizar os dados
3. Identificar se existem valores ausentes ou duplicados

### Preparação do conjunto para o modelo
1. Identificação das features e target do modelo
2. Divisão dos conjuntos em teste e treino

### Construindo e testando modelos

#### Árvore de Decisão
- Seleção de hiperparâmetros
- Treino
- Teste
- Acurácia

#### Floresta Aleatória
- Seleção de hiperparâmetros
- Treino
- Teste
- Acurácia

#### Regressão Logística
- Treino
- Teste
- Acurácia

## Resultados
Considerando apenas a acurácia como métrica para avaliação do modelo, aquele que apresentou o melhor resultado foi o modelo de Árvore de Decisão. Por isso recomendamos que o mesmo seja utilizado.

## Aprendizados
- **Análise de dados**: interpretação e extração de insights valiosos a partir de grandes volumes de dados.
- **Preparação do conjunto para aplicações em Machine Learning**: separação do conjunto original em teste e treino, além da seleção das features e target do modelo.
- **Aplicação de modelos de Machine Learning**: aplicação, seleção de hiperparâmetros, teste e avaliação do modelo.
- **Documentação de projetos**: elaboração de documentação clara e detalhada para garantir que o projeto seja compreensível e replicável.
- **Utilização de bibliotecas e ferramentas**: aplicação prática de diversas bibliotecas e ferramentas do ecossistema Python.
- **Tomada de decisões baseadas em dados**: uso de insights derivados da análise de dados para orientar decisões estratégicas.
