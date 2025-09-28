# Projeto E-commerce – Análise de Vendas

Este projeto realiza uma análise de vendas de um e-commerce a partir de relatórios em CSV.

## Objetivos
- Preencher colunas faltantes: quantidade, preço e datas de venda
- Criar coluna de produtos a partir de SKU/Style
- Calcular faturamento por produto e período
- Identificar os 10 produtos mais vendidos
- Visualizar a evolução mensal de faturamento
- Gerar estatísticas descritivas das vendas

## Estrutura do repositório
- `data/`
  - `raw/` – arquivos CSV originais
  - `processed/` – arquivos CSV limpos e preenchidos
- `notebooks/` – notebook com análise (`analise_vendas.ipynb`)
- `README.md` – este arquivo
- `requirements.txt` – dependências Python usadas no projeto

## Observações
- Alguns dados, como quantidade, preço e datas, foram preenchidos para possibilitar análise completa
- Nomes de produtos foram criados a partir de SKU/Style para visualização nos gráficos
- Todos os gráficos e estatísticas foram gerados no Jupyter Notebook

#Análises Gráficas

##Faturamento Mensal

![Faturamento Mensal] 