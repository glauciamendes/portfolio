Análise de Leitura Pessoal - 2024
Este projeto apresenta uma análise das leituras realizadas ao longo de 2024, utilizando Python no Google Colab. 
Foram explorados padrões de leitura, distribuição de gêneros e tipos de mídia, além de aplicação de técnicas de clusterização e regressão linear.

Resumo do Projeto
Total de livros lidos: 27

Período analisado: Janeiro a Dezembro de 2024

Distribuição de Gêneros:
Thriller Psicológico (40%)
Ficção (22%)
Técnico (14%)
Não-ficção (14%)
Biografia (7%)

Proporção por Tipo de Mídia:
Físico: 44%
Audiobook: 33%
Kindle: 22%
Padrão de Leitura:
Picos de leitura ocorreram em janeiro e dezembro, com uma leve tendência de queda ao longo do ano, conforme identificado por uma regressão linear.

Técnicas Utilizadas
Visualização de Dados: Gráficos de barras, linha, treemap e heatmaps com Matplotlib e Seaborn.
Clusterização:
Aplicação do algoritmo K-means, resultando em dois clusters:
Cluster 1: Thriller Psicológico;
Cluster 0: Biografia, Ficção, Técnico e Não-ficção;
Regressão Linear: Modelagem da tendência de leitura ao longo do tempo utilizando statsmodels.

Ferramentas: 
Python ( Libs: Pandas, Matplotlib, Seaborn, Scikit-learn, Statsmodels);
Google Colab;
Google Sheets API

Como Executar
Clone o repositório.
Instale as dependências:
pip install -r requirements.txt
Abra o notebook no Google Colab e execute as células.

Conclusão
Este projeto demonstrou como a análise de dados pode ser utilizada para identificar padrões pessoais de leitura. 
A aplicação de técnicas estatísticas e de machine learning contribuiu para uma melhor compreensão do comportamento de leitura ao longo do ano.

