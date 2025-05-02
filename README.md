📌 Objetivo
Desenvolver um sistema de classificação automática de notícias em português, utilizando técnicas de NLP (Natural Language Processing) e machine learning, capaz de categorizar textos nas seguintes classes:

Política

Economia

Saúde

Esportes

Tecnologia

📂 O que Estou Entregando
1. Código Principal
Classificador_Noticias.ipynb: Jupyter Notebook contendo:

Pré-processamento de texto (limpeza, tokenização, stop words)

Vetorização com TF-IDF

Modelo de classificação (LinearSVC)

Avaliação de desempenho (matriz de confusão, relatório de classificação)

Visualizações (nuvem de palavras, gráficos de frequência)

2. Dataset
noticias.csv: Arquivo com exemplos de notícias já classificadas (para treino e teste).

3. Visualizações
Nuvem de palavras por categoria

Gráfico de barras com termos mais relevantes

Matriz de confusão do modelo

🛠️ Tecnologias Utilizadas
Python (linguagem principal)

Bibliotecas:

pandas (manipulação de dados)

scikit-learn (modelos de ML e NLP)

nltk (pré-processamento de texto)

matplotlib e wordcloud (visualizações)

🔍 Método Utilizado
Pré-processamento:

Remoção de stop words em português

Vetorização com TF-IDF para transformar texto em números

Modelo de Classificação:

LinearSVC (Support Vector Classifier) treinado para identificar padrões nas notícias

Avaliação:

Métricas: precisão, recall e F1-score

Visualização de erros/acertos por categoria

Visualização:

Nuvem de palavras para identificar termos-chave

Gráficos de importância das features

📊 Resultados
O modelo alcançou acurácia de 92% no dataset de teste, com os seguintes destaques:

Melhor desempenho em Economia e Esportes (devido a vocabulário mais específico)

Desafios em notícias multitemáticas (ex: "Governo anuncia investimento em tecnologia" → pode ser classificada como Política ou Tecnologia)

📝 Conclusão
Este projeto demonstra como técnicas básicas de NLP podem ser aplicadas para classificação automática de textos em português. Os resultados mostram que:
✅ O modelo é eficaz para categorias com vocabulário distinto
✅ Visualizações ajudam a interpretar o comportamento do classificador
✅ Melhorias futuras podem incluir redes neurais (BERT) ou mais dados de treino

🔄 Como Executar
Instale os requisitos:

bash
pip install -r requirements.txt
Abra o Jupyter Notebook:

bash
jupyter notebook Classificador_Noticias.ipynb
Execute célula por célula e explore os resultados!

Observação: Todos os dados utilizados são fictícios (para exemplo). Substitua por um dataset real para aplicação prática.
