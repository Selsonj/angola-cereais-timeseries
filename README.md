🌾 Previsão da Produção de Cereais em Angola (2002–2028)

Este projeto utiliza técnicas de Séries Temporais para prever a produção de cereais em Angola com base em dados históricos da FAOSTAT.
O objetivo é demonstrar como a Ciência de Dados pode gerar insights relevantes para setores estratégicos como a agricultura.

📊 Dataset

Fonte: FAOSTAT

Período: 1961 – 2023 (Mas analisado apenas de 2002 - 2023)

Variável analisada: Produção anual de cereais (em toneladas)

🛠️ Tecnologias Utilizadas

Python 3.12

Pandas

Matplotlib / Seaborn

Statsmodels (ARIMA, Holt-Winters)

Scikit-learn (avaliação de métricas)

🔎 Metodologia

Análise exploratória dos dados (EDA)

Visualização das tendências históricas.

Identificação de quebras estruturais (ex: 2008 em diante).

Modelagem preditiva

Teste de diferentes modelos de séries temporais.

Melhor resultado: ARIMA(1,1,1)+c com MAPE = 4.84%.

Previsão futura (2024–2028)

Produção projetada próxima de 4 milhões de toneladas em 2028.

📈 Resultados
Histórico vs Teste (MAPE 4.84%)

Previsão para 5 anos

🚀 Conclusão

A produção de cereais em Angola apresenta tendência de crescimento, mas para sustentar este avanço, políticas públicas e melhorias na logística e armazenamento serão fundamentais.

Este mini-projeto demonstra como Data Science pode apoiar a tomada de decisões no setor agrícola.

📂 Estrutura do Repositório
angola-cereais-timeseries/
│── data/                
│── notebooks/           
│── imagens/             
│── README.md            
