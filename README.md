# Desafio_DNC---Python-Machine-Learning-
Projetos derivados do curso de Cientista de Dados da DNC School, com foco na aplicação avançada da linguagem Python utilizando Machine Learning.

____________________________________________________________________________________________________________



## ✴Projeto 4: Análise e Previsão de Retorno sobre Investimento em Publicidade✴
## ✅Contexto:

Este projeto tem como objetivo analisar e prever o desempenho dos investimentos em publicidade online de uma empresa. A empresa investe mensalmente em plataformas como YouTube, Facebook e jornais, e registra todos os gastos com publicidade e os retornos de vendas gerados.

## ✅Objetivos:

- Análise de Dados: Explorar a relação entre gastos com publicidade e retornos de vendas para identificar fatores impactantes na geração de leads.
- Modelo de Predição: Desenvolver um modelo para estimar o retorno de vendas com base no investimento em publicidade.

## ✅Dados:
- Gastos com Publicidade: Valores investidos mensalmente.
- Retornos de Vendas: Valores de vendas associados aos investimentos.
- 
## ✅Metodologia:
- Análise Exploratória de Dados (EDA): Identificar padrões e tendências.
- Modelagem: Aplicar técnicas de machine learning para construir um modelo preditivo.
- Avaliação: Ajustar o modelo para melhorar a precisão das previsões.

_______________________________________________________________________________________________________________



## ✴Projeto 5: Prepare seu dataset para modelagem de dados✴
## ✅Contexto:

Este projeto visa a limpeza e organização de dados para o cálculo de indicadores RFM (Recência, Frequência e Ticket Médio) de clientes em um e-commerce. A análise RFM é fundamental para entender o comportamento dos clientes e otimizar estratégias de marketing. O objetivo é preparar um dataset a partir de um arquivo CSV fornecido, realizando operações de limpeza e transformação para calcular e exportar métricas RFM.

## ✅Objetivos:

- Limpeza e Preparação de Dados: Remover dados nulos, duplicados e outliers.
- Ajustar tipos de dados e criar colunas adicionais conforme necessário.
- Exportação de Resultados: Gerar um arquivo CSV contendo as métricas RFM para cada cliente.
- Cálculo de Indicadores RFM:

Recência (R): Tempo desde a última compra do cliente.

Frequência (F): Quantidade total de compras realizadas pelo cliente.

Ticket Médio (M): Média do valor gasto por compra do cliente.

## ✅Metodologia:

- Importação e Inspeção de Dados: Carregar o dataset e inspecionar as primeiras linhas e tipos de dados.
- Tratamento de Dados: Valores Nulos/ Valores Inválidos/ Duplicatas.
- Correção de Tipos de Dados: Ajustar tipos de dados para CustomerID e InvoiceDate.
- Tratamento de Outliers: Remover valores extremos de quantidade e preço unitário.
- Criação de Colunas Adicionais: Adicionar coluna para o preço total de cada compra.
- Cálculo de Métricas RFM: Calcular Recência, Frequência e Ticket Médio por cliente.
- Exportação: Gerar um CSV com as métricas RFM calculadas.

__________________________________________________________________________________________________



## ✴Projeto 6: Preveja os usuários com alta chance de deixar seu Streaming
## ✅Contexto:

Este projeto visa desenvolver um modelo de classificação para prever a probabilidade de cancelamento (churn) de assinaturas em uma plataforma de streaming. Compreender o perfil dos usuários que têm mais chance de deixar a plataforma é crucial para implementar estratégias que reduzam a perda de clientes e melhorem a retenção.

## ✅Objetivos: 

- Análise Exploratória de Dados (EDA): Explorar e entender os dados fornecidos para identificar padrões e preparar os dados para modelagem.
- Preparação dos Dados: Limpar e preparar os dados para treinamento dos modelos.
- Modelagem: Construir e avaliar modelos de classificação, incluindo Regressão Logística e Random Forest.
- Avaliação e Tuning: Ajustar os modelos para melhorar a precisão das previsões.

## ✅Metodologia:

### 1. Importação e Inspeção de Dados
- **Carregamento do Dataset**: Carregar o dataset e examinar as primeiras linhas para obter uma visão inicial dos dados.
- **Análise Descritiva**: Realizar uma análise descritiva para entender a distribuição e os tipos de dados presentes.
- **Identificação de Valores Faltantes**: Identificar e quantificar valores ausentes no dataset.

### 2. Tratamento dos Dados
- **Substituição de Valores Ausentes**: Substituir valores ausentes (NaN) por 0 nas colunas relevantes para garantir a integridade dos dados.
- **Remoção de Registros Nulos**: Remover registros com valores nulos em colunas críticas como `gender`, `subscription_type` e `age`.
- **Conversão de Coluna Binária**: Converter a coluna `churned` de valores binários para categóricos (`'No'`/`'Yes'`) para facilitar a análise.
- **Ajuste de Tipos de Dados**: Garantir que todos os tipos de dados estejam corretos e consistentes para a modelagem.

### 3. Modelagem dos Dados
### Regressão Logística
- **Definição de Variáveis**: Definir as variáveis preditoras (X) e a variável alvo (y).
- **Divisão do Dataset**: Dividir o dataset em conjuntos de treino e teste para avaliação do modelo.
- **Treinamento e Avaliação**: Treinar o modelo de regressão logística e avaliar seu desempenho utilizando métricas apropriadas.

### Random Forest
- **Implementação de Grid Search**: Utilizar Grid Search para encontrar os melhores hiperparâmetros para o modelo de Random Forest.
- **Treinamento e Avaliação**: Treinar o modelo com os melhores hiperparâmetros e avaliar seu desempenho.

### 4. Avaliação e Otimização
- **Comparação de Modelos**: Comparar o desempenho dos modelos utilizando métricas como precisão, recall e F1-score.
- **Ajuste de Parâmetros**: Ajustar os parâmetros dos modelos para melhorar a acurácia e reduzir o erro.

___________________________________________________________________________________________________



## ✴Projeto 7: Análise de Clusterização de Clientes para E-Commerce modelo de análise das métricas RFV
## ✅Contexto:

Você foi contratado por uma empresa de e-commerce para melhorar a segmentação de seus clientes. A empresa deseja entender melhor o comportamento de compra de seus clientes para personalizar campanhas de marketing e otimizar estratégias de vendas. O objetivo é agrupar os clientes com base em seu comportamento de compra, utilizando técnicas de clusterização para identificar padrões e características comuns.

## ✅Objetivos: 

Desenvolver um modelo de clusterização para agrupar os clientes com base em seu comportamento de compra, considerando métricas de Recência, Frequência e Valor Monetário (RFM). A segmentação permitirá à empresa identificar padrões e perfis de clientes para personalizar campanhas de marketing e otimizar suas estratégias.


## ✅Metodologia:
### 1. Análise Exploratória dos Dados
- **Carregamento e Inspeção**: Importar o dataset e revisar suas primeiras linhas.
- **Descrição Estatística**: Obter estatísticas descritivas e visualizar distribuições das variáveis.
- **Verificação de Dados**: Identificar e tratar dados nulos, duplicados, outliers e inconsistências.

### 2. Pré-processamento dos Dados
- **Normalização**: Escalar as variáveis para garantir contribuição equitativa ao modelo.
- **Seleção de Variáveis**: Identificar e utilizar variáveis relevantes para a clusterização.
- **Limpeza de Dados**: Remover ou corrigir dados nulos, duplicados e outliers.

### 3. Seleção e Implementação do Algoritmo de Clusterização
- **Escolha do Algoritmo**: Selecionar o algoritmo adequado (K-Means, DBSCAN, Hierárquico, Mean Shift).
- **Determinação do Número de Clusters**: Utilizar métodos como Elbow ou Silhouette Score para definir a quantidade ideal de clusters.
- **Execução**: Aplicar o algoritmo escolhido para gerar e analisar os clusters.

### 4. Análise dos Clusters
- **Identificação de Padrões**: Examinar os clusters para identificar características e padrões comuns entre os clientes.
- **Visualização**: Utilizar gráficos e visualizações para facilitar a interpretação dos clusters.

### 5. Interpretação dos Resultados e Recomendações
- **Descrição dos Perfis**: Detalhar o perfil de compras dos clientes em cada cluster.
- **Utilidade para a Empresa**: Explicar como a segmentação pode melhorar a personalização das campanhas de marketing.
- **Ações Recomendadas**: Sugerir estratégias baseadas nos insights obtidos para otimizar as campanhas e melhorar o desempenho do e-commerce.

## ✅Resultados Esperados

- **Clusters Definidos**: Identificação de grupos de clientes com comportamentos de compra semelhantes.
- **Insights de Segmentação**: Padrões e características que podem ser utilizados para personalizar campanhas e estratégias.
- **Recomendações Práticas**: Ações sugeridas para a empresa com base nos clusters e perfis de clientes identificados.
