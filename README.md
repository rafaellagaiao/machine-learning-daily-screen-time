# 📱 Análise Exploratória: Tempo de Tela em Crianças
Este projeto tem como objetivo realizar uma Análise Exploratória de Dados (EDA) sobre os hábitos de tempo de tela em crianças, investigando como diferentes fatores (idade, atividades, comportamento, entre outros) influenciam o uso de dispositivos eletrônicos. Além disso, utilizou-se o processo de Machine Learning com modelagem de clusters (K-Means) para segmentar crianças por padrões de uso de telas, com validação via Silhouette Score.

🎯 Objetivo
O estudo busca responder perguntas como:

* Qual a média de tempo de tela por faixa etária?
* Como o tempo de tela se relaciona com o comportamento e desenvolvimento da criança?
* Existem padrões significativos entre diferentes perfis de crianças?

🧰 Tecnologias Utilizadas
* Python (Jupyter Notebook)
* pandas – Manipulação de dados
* numpy – Operações numéricas
* seaborn e matplotlib – Visualizações gráficas
* plotly – Gráficos interativos
* sklearn - Machine Learning

📂 Estrutura do Projeto

├── children_screen_time.ipynb   # Notebook principal da análise

├── README.md                    # Documentação do projeto

🔍 Etapas da Análise
1. Carregamento dos dados
2. Limpeza e tratamento de dados ausentes
3. Análise descritiva das variáveis
4. Visualizações para identificação de padrões
5. Treino do aprendizado de máquina com K-Means
6. Predição
7. Conclusões e insights finais

📈 Principais Descobertas
* Há uma correlação positiva entre idade e tempo de tela.
* 15% dos casos foram outliers (uso exclusivamente educacional, sugerindo viés cultural ou socioeconômico.
* Classificação de novos dados em clusters com 90% de precisão (baseado em validação cruzada).
