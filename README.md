# 📊 Dashboard de Vendas de Planos Móveis - Projeto DIO

Este projeto foi desenvolvido como parte de um desafio prático para o **Bootcamp de Engenharia de Dados com Python, ETL e Machine Learning** da [DIO](https://www.dio.me/). O objetivo foi criar uma solução de visualização de dados que permitisse a análise de desempenho de vendas de planos de telefonia (fictícios da TIM) de forma dinâmica e intuitiva.

## 🚀 O Desafio
O desafio consistiu em transformar dados brutos em insights acionáveis, simulando um ambiente real de análise de vendas onde gestores precisam acompanhar KPIs (Key Performance Indicators) mensalmente.

## 🛠️ Tecnologias e Ferramentas
- **Excel (Office 2013):** Utilizado como ferramenta principal para modelagem de dados e construção do dashboard.
- **Python (Pandas & NumPy):** Utilizado para a geração da base de dados sintética, garantindo volume e variabilidade para os testes.
- **Tabelas Dinâmicas:** Para sumarização rápida dos dados.

## 📈 Funcionalidades do Dashboard
O dashboard apresenta três visões principais que se atualizam automaticamente conforme o mês selecionado no filtro lateral:

1.  **Total de Vendas no Mês (KPI):** Exibe a Receita Mensal Recorrente (MRR) gerada pelas novas adesões.
2.  **Melhor Vendedor no Mês (Destaque):** Identifica automaticamente o vendedor com maior volume financeiro de vendas, utilizando lógica de comparação dinâmica.
3.  **Quantidade de Planos Vendidos (Gráfico):** Um gráfico de barras horizontais que compara a performance entre as diferentes categorias de planos (Pre Top, Controle, Black e Black Família).

## 💡 Insights Gerados
- Identificação de sazonalidade nas vendas por meio do filtro de meses.
- Análise de mix de produtos: qual plano tem maior saída e qual gera mais receita.
- Reconhecimento de talentos: monitoramento do desempenho individual da equipe de vendas.

## 📝 Como utilizar
1. Abra o arquivo `.xlsx`.
2. Utilize o painel de **Segmentação de Dados** à esquerda para escolher o mês desejado.
3. Todos os gráficos e indicadores serão atualizados instantaneamente para refletir os dados do período selecionado.
