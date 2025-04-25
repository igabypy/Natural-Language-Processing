# Tweet Sentiment Analysis 📝💬

Proyecto exploratorio de análisis de sentimientos en Twitter usando Python y NLP clásico.  
El cuaderno `SentimentsTweet.ipynb` documenta todo el flujo, desde la carga de datos hasta un clasificador base listo para producción.

## Contenidos
- **01_Exploración y limpieza**  
  - Carga de `train.csv` y `test.csv`  
  - Análisis de valores ausentes & tipos de dato  
  - Visualización de frecuencias y nubes de palabras
- **02_Pre-procesado**  
  - Normalización: minúsculas, stop-words, lematización  
  - Tokenización y generación de features TF-IDF
- **03_Modelado**  
  - Baseline `LogisticRegression` + `Pipeline` de scikit-learn  
  - Métricas: accuracy, F1, matriz de confusión


## Requisitos
```bash
python>=3.9
pandas
scikit-learn
matplotlib
wordcloud

