### 📊 MVP — Machine Learning em Jogos de Tabuleiro  

#### 🎲 Aprendizado Não Supervisionado
Este projeto tem como objetivo aplicar técnicas de **aprendizado não supervisionado**, com foco em algoritmos de **clustering**, para explorar e analisar um conjunto de dados contendo avaliações e informações sobre jogos de tabuleiro.  
A abordagem será estruturada por meio da construção de um pipeline, que permitirá a execução sequencial e automatizada das etapas, em busca de identificar agrupamentos naturais entre os jogos e os jogadores, revelando padrões ocultos, tendências emergentes, fatores de popularidade e comportamentos recorrentes dentro da comunidade.  
A avaliação da qualidade dos agrupamentos será realizada por meio de métricas, como por exemplo, Silhouette score, Davies-Bouldin, Calinski-Harabasz e validação cruzada, assegurando a robustez e a interpretabilidade dos resultados.  

#### 🧩 Dataset
O conjunto de dados foi obtido na plataforma Kaggle [fonte: https://www.kaggle.com/datasets/andrewmvd/board-games] e reúne informações extraídas do site BoardGameGeek (BGG), uma das maiores comunidades online dedicadas a jogos de tabuleiro.

#### 📌 Pipeline de dados
- Pré-processamento dos dados: limpeza, tratamento de valores (ausentes e inconsistentes), codificação e padronização de atributos.
- Redução de dimensionalidade: uso de técnicas como PCA e t-SNE para facilitar a visualização e melhorar a performance dos modelos.    
- Algoritmos de clustering: aplicação do K-Means, DBSCAN e Hierarchical Clustering para identificar agrupamentos significativos.  
- Avaliação da qualidade dos agrupamentos: utilizando métricas internas como Silhouette Score, Davies-Bouldin e Calinski-Harabasz, além de estratégias de validação cruzada para testar a consistência dos resultados em diferentes subconjuntos dos dados.  
- Visualização analítica: geração de gráficos e exploração de dados para facilitar a interpretação dos agrupamentos e extração de insights relevantes.

#### 💼 Ferramentas Utilizadas  
- Linguagem: Python  
- Bibliotecas: Pandas, NumPy, Math, Seaborn, Matplotlib, Plotly, Sklearn, Scikit-learn  
- Ambientes: Jupyter Notebook, Google Colab  
- Versionamento e Documentação: GitHub, Markdown  

#### 🚀 Resultados Esperados  
- Identificação de padrões de comportamento entre jogadores e jogos.  
- Segmentação de jogos por características e popularidade.  
- Análise de correlações entre mecânicas de jogo e níveis de popularidade.
- Exploração de tendências temporais no comportamento dos jogadores e na popularidade dos jogos.
- Mapeamento de perfis de jogadores com base em preferências, estilos de jogo e avaliações.  
