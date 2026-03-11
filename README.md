# TelecomXparte2
Análise Preditiva de Evasão de Clientes (Churn)
Descrição do Projeto

Este projeto tem como objetivo analisar os fatores relacionados à evasão de clientes e desenvolver modelos preditivos capazes de identificar quais clientes possuem maior probabilidade de cancelar o serviço.

A proposta envolve desde o tratamento e exploração dos dados até a construção e avaliação de modelos de machine learning, permitindo gerar insights estratégicos para retenção de clientes.

Objetivos

Realizar o pré-processamento dos dados

Tratar variáveis categóricas e numéricas

Verificar a proporção da evasão de clientes

Aplicar técnicas de balanceamento de classes, quando necessário

Analisar correlações e selecionar variáveis relevantes

Explorar padrões entre características dos clientes e a evasão

Construir modelos preditivos para classificação

Avaliar o desempenho dos modelos

Etapas do Projeto
1. Limpeza e preparação dos dados

Remoção de colunas irrelevantes

Verificação de valores ausentes

Ajuste de tipos de variáveis

Codificação de variáveis categóricas (encoding)

Padronização ou normalização, quando necessário

2. Análise exploratória dos dados

Proporção entre clientes que evadiram e os que permaneceram

Estatísticas descritivas das variáveis numéricas

Distribuição das principais variáveis

Análise de correlação entre atributos

3. Análises direcionadas

Foram realizadas análises específicas para identificar possíveis padrões relacionados à evasão, como:

Tempo de contrato × Evasão

Total gasto × Evasão

Cobrança mensal × Evasão

Método de pagamento × Evasão

Serviços contratados × Evasão

Foram utilizados gráficos como:

Boxplots

Histogramas

Gráficos de barras

Scatter plots

4. Modelagem preditiva

O conjunto de dados foi dividido em treino e teste para avaliar a capacidade de generalização dos modelos.

Exemplos de divisão:

70% treino / 30% teste
ou

80% treino / 20% teste

Foram construídos pelo menos dois modelos de classificação para prever a evasão de clientes.

5. Avaliação dos modelos

Os modelos foram comparados com base em métricas como:

Acurácia

Precisão

Recall

F1-score

Matriz de confusão

Tecnologias e Bibliotecas Utilizadas

Python

Pandas

NumPy

Matplotlib

Seaborn

Plotly

Scikit-learn

Estrutura do Projeto
├── dados/
├── notebooks/
├── imagens/
├── README.md
└── requirements.txt
Principais Insights

Alguns fatores podem estar associados a uma maior chance de evasão, como:

Menor tempo de permanência

Maior sensibilidade a cobranças

Determinados métodos de pagamento

Perfil de consumo e contratação de serviços

A análise preditiva permite transformar esses padrões em apoio à tomada de decisão, ajudando empresas a atuarem preventivamente na retenção de clientes.

Resultados Esperados

Ao final do projeto, espera-se:

Identificar variáveis mais relevantes para a evasão

Compreender o perfil dos clientes com maior risco de churn

Comparar o desempenho de diferentes modelos preditivos

Gerar uma base analítica para estratégias de retenção

Como Executar

Clone este repositório:

git clone https://github.com/seu-usuario/seu-repositorio.git

Acesse a pasta do projeto:

cd seu-repositorio

Instale as dependências:

pip install -r requirements.txt

Execute o notebook ou script principal.

Conclusão

Este projeto demonstra como técnicas de análise de dados e machine learning podem ser aplicadas para entender e prever a evasão de clientes. Mais do que construir modelos, a proposta é gerar inteligência de negócio a partir dos dados.

Autora

Alessandra de Oliveira Rosalino
Projeto desenvolvido para fins acadêmicos e de aprendizado em análise de dados e modelagem preditiva.
