### 📊 MVP - Machine Learning em Jogos de Tabuleiro  

#### 🎲 Aprendizado Não Supervisionado
Este projeto tem como objetivo aplicar técnicas de **aprendizado não supervisionado**, com foco em algoritmos de **clustering**, para explorar e analisar um conjunto de dados contendo avaliações e informações sobre jogos de tabuleiro.  
A abordagem será estruturada por meio da construção de um pipeline, que permitirá a execução sequencial e automatizada das etapas, buscando identificar agrupamentos naturais entre os jogos e os jogadores, revelando padrões ocultos, tendências emergentes, fatores de popularidade que impulsionam o sucesso de um jogo e comportamentos recorrentes dentro da comunidade.  
A qualidade dos agrupamentos será avaliada por meio de métricas internas e externas, como o índice de Silhouette, Davies-Bouldin, Calinski-Harabasz e validação cruzada, com o objetivo de assegurar a consistência estatística dos agrupamentos e facilitar a interpretação dos padrões identificados.  

#### 🧩 Dataset
O conjunto de dados foi obtido na plataforma Kaggle [fonte: https://www.kaggle.com/datasets/andrewmvd/board-games] e reúne informações extraídas do site BoardGameGeek (BGG), uma das maiores comunidades online dedicadas a jogos de tabuleiro.

#### 📌 Pipeline de dados
- Pré-processamento dos dados: limpeza, tratamento de valores (ausentes e inconsistentes), codificação e padronização de atributos.
- Redução de dimensionalidade: feature selection e uso de técnicas como PCA e t-SNE para facilitar a visualização e melhorar a performance dos modelos.    
- Clustering: aplicação dos algoritmos K-Means, DBSCAN e Hierarchical para identificar agrupamentos significativos.  
- Avaliação dos agrupamentos: utilizando métricas internas como Silhouette Score, Davies-Bouldin e Calinski-Harabasz, além de estratégias de validação cruzada para testar a consistência dos resultados em diferentes subconjuntos dos dados.  
- Visualização analítica: geração de gráficos e exploração de dados para facilitar a interpretação dos agrupamentos e extração de insights relevantes.

#### 💼 Ferramentas Utilizadas  
- Linguagem: Python  
- Bibliotecas: Pandas, NumPy, Math, Seaborn, Matplotlib, Plotly, Sklearn, Scikit-learn, Scipy.cluster  
- Ambientes: Jupyter Notebook, Google Colab  
- Documentação: GitHub, Markdown  

#### 🚀 Resultados Esperados  
- Identificação de padrões de comportamento entre jogadores e jogos.  
- Segmentação de jogos por características e popularidade.  
- Análise de correlações entre mecânicas de jogo e níveis de popularidade.
- Exploração de tendências temporais no comportamento dos jogadores e na popularidade dos jogos.
- Mapeamento de perfis de jogadores com base em preferências, estilos de jogo e avaliações.  
