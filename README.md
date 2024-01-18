# Descrição
O projeto visa analisar e prever índices econômicos, centrando-se no INPC e IPCA no Brasil. Utilizei pandas, scikit-learn, matplotlib, seaborn, dash e plotly para manipulações e visualizações.
# 1. Aquisição e Pré-processamento dos Dados
Os dados foram obtidos diretamente do repositório de dados do IBGE utilizando a biblioteca basedosdados.
Realizou-se a renomeação de colunas para melhor clareza e coesão no conjunto de dados.
Aplicou-se técnicas de filtragem para selecionar categorias específicas relevantes para análise.
# 2. Exploração e Visualização
Utilizando gráficos de dispersão, linhas e barras, exploramos a variação mensal e anual do peso em diferentes categorias.
Aplicou-se uma regressão linear para realizar previsões de peso mensal para janeiro de 2024.
# 3. Análise de Correlação e Estatísticas
Calculou-se a variação anual média por categoria e apresentou-se visualmente por meio de gráficos de barras.
Criou-se uma matriz de correlação entre o peso mensal e a variação anual, visualizada através de um mapa de calor.
# 4. Dashboard Interativo
Desenvolveu-se um dashboard interativo usando o framework Dash, permitindo a visualização dinâmica dos dados.
Incluiu gráficos interativos que exibem o peso mensal por categoria, variação mensal por categoria, variação anual por categoria e peso mensal por ano.
# Como Executar
Instale as dependências necessárias usando pip install -r requirements.txt.
Execute o script projeto.py para carregar os dados, realizar a análise e iniciar o dashboard.
# Conclusão
Este projeto oferece uma análise abrangente e visualmente atraente dos índices econômicos INPC e IPCA no Brasil. A utilização de técnicas de machine learning, visualizações gráficas e um dashboard interativo proporciona uma compreensão mais profunda dos padrões e tendências desses índices ao longo do tempo.
