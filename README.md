# Clasificador-de-Ideologia-Politica-Tesis
El trabajo de grado tiene como propósito estudiar estudiar el desempeño de un *mecanismo de clasificación* tomando como referencia los siguientes niveles de experimentación:

1. **Preprocesamiento**: Técnicas mediante las cuales removemos información de los tweets originales
2. **Técnicas de Representación**: Los programas necesitan vectores para trabajar no palabras, por lo que elegir la correcta técnica para obtener estos vectores es crucial
3. **Algoritmos de clasificación**: Técnicas que toman como entrada los vectores correspondientes a cada uno de los personajes y le asigna una etiqueta de ideología de acuerdo a su contenido.


**Preprocesamiento**
Se estudian procesamientos de distintas intensidades como dejar el tweet original, otros intermedios como normalizar a minúsculasy removiendo la puntuación excesiva y algunos mas agresivos que incluyen el remover stopwords, palabras con longitud menor a la deseada, etc.


**Representación**
Se estudian los siguientes algoritmos:
1. Representaciones frecuentistas: Bag of Words y TF IDF
2. Embeddings: Word2Vec y FastText
3. Transformers: BETO (Spanish BERT model)


**Clasificación**
Algunos de los algoritmos considerados son los siguientes:

1. Support Vector Machine
2. Logistic Regression
3. Decision Tree
4. Random Forest
5. AdaBoost
6. Redes Neuronales Convolucionales
7. Arquitecturas personalizadas para Fine Tuning
