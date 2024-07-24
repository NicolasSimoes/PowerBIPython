# Análise de Vendas de Supermercado


O projeto visa criar um dashboard interativo para a análise de vendas em um supermercado, utilizando a biblioteca Streamlit em combinação com Plotly para visualização de dados. O objetivo é fornecer uma visão abrangente e mensal do desempenho de vendas, incluindo métricas de faturamento, tipos de produtos vendidos, formas de pagamento e avaliações por filial.

## Funcionalidades Implementadas pelo Código

1. **Importação e Preparação dos Dados:**
   - **Leitura dos Dados:** O código lê um arquivo CSV contendo dados de vendas (`supermarket_sales.csv`) e converte a coluna "Date" para o tipo de dado datetime. Em seguida, organiza os dados por data e cria uma nova coluna "Month" para agregação mensal.
   - **Filtragem Mensal:** Utiliza um seletor de mês na barra lateral para filtrar os dados de acordo com o mês selecionado pelo usuário.

2. **Criação de Visualizações:**
   - **Faturamento Diário por Cidade:** Utiliza um gráfico de barras para mostrar o faturamento diário (`Total`) por cidade ao longo do mês selecionado. Isso permite acompanhar como o faturamento varia dia a dia.
   - **Faturamento por Tipo de Produto:** Cria um gráfico de barras horizontal para comparar o faturamento por tipo de produto dentro do mês. Isso ajuda a identificar quais produtos têm maior impacto nas vendas.
   - **Faturamento por Filial:** Apresenta um gráfico de barras que resume o faturamento total por filial (`City`). Facilita a comparação do desempenho financeiro entre diferentes filiais.
   - **Faturamento por Tipo de Pagamento:** Exibe um gráfico de pizza que mostra a distribuição do faturamento por tipo de pagamento, fornecendo insights sobre as preferências de pagamento dos clientes.
   - **Avaliações por Filial:** Cria um gráfico de barras para mostrar a média das avaliações (`Rating`) por filial. Isso ajuda a avaliar o desempenho das filiais em termos de satisfação do cliente.

## Implementação com Streamlit e Plotly
- Python 3.7 ou superior
- Bibliotecas:
  - `streamlit`
  - `pandas`
  - `plotly`
- **Streamlit:** Utilizado para criar uma interface web interativa. Permite ao usuário selecionar o mês de interesse e visualizar as diferentes métricas em tempo real.
- **Plotly:** Utilizado para criar gráficos dinâmicos e interativos que são exibidos na interface do Streamlit. Esses gráficos facilitam a exploração e a análise dos dados.

O projeto proporciona uma maneira acessível e visualmente atraente de analisar o desempenho de vendas do supermercado, similar ao que se pode alcançar com o Power BI, mas utilizando ferramentas Python como Streamlit e Plotly.

Este projeto utiliza Streamlit e Plotly para criar uma aplicação interativa de análise de dados de vendas de um supermercado. A aplicação permite visualizar diversos aspectos das vendas, como faturamento por unidade, tipo de produto mais vendido, contribuição por filial, desempenho das formas de pagamento e avaliações por filial, com uma visão mensal.
## Você pode instalar as bibliotecas necessárias com o seguinte comando:
```bash
pip install streamlit pandas plotly
```

## Para rodar o projeto
Utilize o comando :
```bash
streamlit run PowerBi.py
```






