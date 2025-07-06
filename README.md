# MVP_Analise_Dados_Boas_Praticas

🦠 Análise Exploratória e Pré-processamento de Dados COVID-19
Este projeto é parte do MVP (Mínimo Produto Viável) da pós-graduação em Ciência de Dados, com foco em análise exploratória (EDA) e pré-processamento de dados relacionados à vulnerabilidade à COVID-19.

📌 Objetivo
Explorar e preparar um conjunto de dados estáticos sobre características populacionais, ambientais, demográficas e de saúde pública com o intuito de investigar hipóteses relacionadas ao risco de hospitalização por COVID-19.

📊 Base de Dados
O dataset utilizado é o COVID-19 Unified Dataset (Static), disponibilizado pela Johns Hopkins University.
Foram utilizadas variáveis como:

Prevalência de doenças (obesidade, diabetes, hipertensão, etc.)

Poluição do ar (PM2.5, NO₂)

Acesso a serviços de saúde

Indicadores populacionais

Variável alvo: Risk_High (risco estimado de hospitalização por COVID-19)

🔍 Hipóteses analisadas
Qual doença pré-existente apresenta maior fator de risco estimado para hospitalização por COVID-19?

A qualidade do ambiente e do clima urbano interfere na incidência de doença pulmonar crônica?

O acesso a serviços de saúde impacta diretamente o risco estimado para hospitalização?

🧪 Etapas Realizadas
Leitura e limpeza do dataset

Tratamento de valores ausentes

Análise univariada e bivariada com gráficos (histogramas, boxplots, mapas de calor)

Normalização dos dados com MinMaxScaler

Seleção e interpretação de variáveis com base na correlação com a variável alvo

🛠️ Ferramentas Utilizadas
Python (Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn)

Google Colab

Jupyter Notebook

📁 Estrutura do Projeto

📦 projeto-covid19-mvp
├── README.md                       # Documentação do projeto

├── LICENSE  

├── requirements.txt               # Bibliotecas necessárias

├── data/
│   └── COVID-19_Static.csv        # Base de dados utilizada

├── notebooks/
│   └── analise_exploratoria_preprocessamento.ipynb  # Notebook principal


👩‍💻 Autora

*Amanda Amaral*

Pós-graduanda em Ciência de Dados
