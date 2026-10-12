# Projeto-de-Analise-de-Dados
# Análise de Cancelamento de Clientes com Python

Projeto de análise de dados desenvolvido em Python com o objetivo de identificar os principais fatores relacionados ao cancelamento de clientes e avaliar possíveis ações para reduzir esse índice.

A análise parte de uma base com aproximadamente 50 mil registros de clientes e utiliza técnicas de tratamento, exploração e visualização de dados para encontrar padrões de comportamento associados ao cancelamento.

## Objetivo do projeto

O objetivo principal foi responder a duas perguntas:

- Quais fatores estão mais relacionados ao cancelamento dos clientes?
- Quais ações poderiam contribuir para reduzir a taxa de cancelamento?

## Tecnologias utilizadas

- Python
- Pandas
- Plotly
- Jupyter Notebook

## Etapas da análise

O projeto foi desenvolvido seguindo as seguintes etapas:

1. Importação da base de dados
2. Visualização inicial das informações
3. Remoção de colunas que não contribuíam para a análise
4. Tratamento de valores vazios
5. Análise da taxa de cancelamento
6. Criação de gráficos para analisar o impacto de cada variável
7. Identificação dos principais fatores associados ao cancelamento
8. Aplicação de filtros para simular possíveis melhorias

## Tratamento dos dados

A coluna `CustomerID` foi removida por não contribuir diretamente para a análise.

Também foram identificados valores vazios na base, que foram removidos utilizando:

```python
tabela = tabela.dropna()
