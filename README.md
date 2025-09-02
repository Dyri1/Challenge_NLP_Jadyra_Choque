# Emotion Classification with NLP Models

Este proyecto implementa y compara distintos modelos de clasificación de emociones en textos cortos (tweets). Se evalúan enfoques tradicionales y basados en deep learning, incluyendo combinaciones con embeddings de BERT.

## 📂 Contenido
- **Preprocesamiento de datos**: carga y limpieza de dataset en formato TSV.  
- **Modelos implementados**:  
  - TF-IDF + SVM  
  - BiLSTM  
  - BiLSTM + BERT  
  - Random Forest  
  - GSI-UPM Style (BERT + TF-IDF + SVM)  
- **Evaluación**: métricas de *accuracy*, *f1-macro*, *f1-weighted*, clasificación por clase y matrices de confusión.  
- **Visualización**: gráficos comparativos de métricas.  

📊 Resultados
Rendimiento Global (comparación de modelos)
Modelo	Accuracy	F1 Macro	F1 Weighted
TF-IDF + SVM	0.3285	0.1599	0.3360
BiLSTM	0.3629	0.1467	0.3374
BiLSTM + BERT	0.3786	0.1576	0.3549
Random Forest	0.4396	0.1200	0.3386
GSI-UPM (BERT + TF-IDF + SVM)	0.5747	0.3988	0.5703

Métricas por clase (GSI-UPM Style)
Clase	Precision	Recall	F1-score
Anger	0.4444	0.3967	0.4192
Disgust	0.2500	0.1200	0.1622
Fear	0.6000	0.2000	0.3000
Joy	0.5523	0.5057	0.5280
Others	0.6535	0.7148	0.6828
Sadness	0.5702	0.5227	0.5455
Surprise	0.1296	0.1892	0.1538
