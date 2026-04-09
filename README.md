# ✈️ **Acidente da Air India em Ahmedabad - Análise de um Conjunto de Dados de Vídeos do YouTube**

Este projeto utiliza **técnicas de Processamento de Linguagem Natural** para realizar uma análise de sentimentos ao avaliar a opinião pública durante eventos de crise, faz uma análise de mídias sociais para investigar padrões de engajamento em notícias recentes e faz uma análise textual dos conteúdos relacionados a desastres e eventos críticos.

# 📜 **Workflow do Projeto**
 
**1.Etapa de pré-processamento do texto**
 
  1.1 Remoção de línguas distintas ao inglês
 
  1.2 Remoção de pontuação
 
  1.3 Reemoção de números
 
  1.4 Tokenização
 
  1.5 Remoção de Stopwords
 
  1.6 Lematização
  
**2.Visualização do texto processado**
  
  2.1 Cálculo das frequências dos termos
  
  2.2 Gráfico Barplot
  
  2.3 Nuvem de palavras

  
**3. Análise de sentimento**
  
  3.1 Definição do Rótulo de Sentimento (Variável Alvo)
  
  3.2 Divisão dos dados em treino e teste
  
  3.3 Vetorização de Texto (Transformando Texto em Números)
  
  3.4 Treinando o modelo com regressão logística
  
  3.5 Avaliação do Modelo

  
**4. Modelagem**
  
  4.1 Regressão Logistica

  4.2 Random Forest

# Insights Chave
Nuvem de palavras
<img width="1183" height="615" alt="image" src="https://github.com/user-attachments/assets/d452dca2-3f3e-4db4-be94-f2c2e0ddb0d9" />

# Resultados do Projeto:
## Utilizando modelo de regressão logística:

O modelo conseguiu ter uma precisão de 86% para sentimentos negativos, 77% para sentimentos neutros e 75 % para sentimentos positivos, de modo geral o modelo tem uma acurácia de 80%.
Esses resultados indicam que o modelo tem uma boa previsão para sentimetnos negativos, porém, para sentimentos neutros e positivos há dificuldades em se avaliar.
Mas de modo geral, apresenta uma acurácia de 80% dos casos analisados.

O teste de validação cruzada foi realizado de maneira a avaliar o desempenho do modelo de forma mais robusta e confiável, chegando a um score médio de 72,51%. 
NOTA: Resultados acima de 70% para modelos de analise de sentimentos é um bom resultado principalmente devido a dificuldade de interpretar comentários.

## Conclusão:

O modelo de regressão linear logistica apresentou resultados satisfatórios para a classificação de sentimentos apresentando os maiores índices de precisão e acurácia.
Porém, todos os modelos apresentados tiveram um resultado pior ao classificar comentários neutros, principalemnte após a implentação do n-gram na tentativa de buscar um contexto.


# 🛠️ **Tech Stack**

🐍 **Python**

📊 **Pandas**

🔢 NumPy 

🤖 NLP (NLTK / spaCy / Transformers) 

📈 Visualization (Matplotlib / Seaborn / Plotly) **
