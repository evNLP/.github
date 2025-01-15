# Repositorios de evNLP

Este documento describe cada repositorio disponible en la organización [evNLP](https://github.com/orgs/evNLP/repositories). Los proyectos están orientados a distintas áreas del procesamiento del lenguaje natural (NLP), abordando tareas como clasificación de texto, traducción automática y modelos de atención.

<br>

### [self_attention](https://github.com/evNLP/self_attention)
Este proyecto está dedicado a la implementación de modelos basados en Transformers, específicamente el mecanismo de autoatención. Los modelos desarrollados en este repositorio son ideales para tareas como resumen de texto, clasificación y traducción automática.  
**Características principales**:
- Implementación de módulos de autoatención desde cero en PyTorch.
- Ejemplos de uso en tareas como modelado de secuencias y análisis de texto.
- Base para entender y extender modelos más avanzados como BERT y GPT.

<br>

### [lstm_attention](https://github.com/evNLP/lstm_attention)
Este repositorio implementa un modelo de atención en combinación con LSTM (Long Short-Term Memory). Se centra en tareas como la traducción automática y mejora la capacidad del modelo para enfocarse en las partes más relevantes de las secuencias de entrada.  
**Características principales**:
- Uso de atención mecánica para identificar palabras clave en un texto.
- Optimización para la traducción automática inglés-español.
- Implementación en PyTorch, con tutoriales y ejemplos detallados.

<br>

### [instruct](https://github.com/evNLP/instruct)
Este proyecto proporciona un marco para crear instrucciones que permitan ajustar modelos como Mistral y GPT-2 a tareas específicas. Es útil para personalizar modelos de lenguaje general para aplicaciones concretas.  
**Características principales**:
- Scripts para personalización y ajuste fino de modelos preentrenados.
- Ejemplos de ajuste para generación de texto, clasificación y más.
- Guías paso a paso para implementar personalización en diferentes datasets.

<br>

### [classification_strategies](https://github.com/evNLP/classification_strategies)
En este repositorio se exploran y comparan distintas estrategias para clasificación multinomial, abarcando modelos tradicionales y redes neuronales modernas.  
**Características principales**:
- Comparación entre algoritmos como Naive Bayes, regresión logística y clasificadores neuronales.
- Ejercicios prácticos con PyTorch y sklearn.
- Aplicaciones en análisis de sentimiento, categorización de texto y más.

<br>

### [glove](https://github.com/evNLP/glove)
Aquí se desarrollan modelos que utilizan embeddings preentrenados de GloVe para mejorar las representaciones semánticas en tareas de clasificación. Estos embeddings permiten representar palabras en un espacio vectorial en función de su contexto.  
**Características principales**:
- Integración de embeddings GloVe para tareas como análisis de sentimiento.
- Modelos basados en LSTM y otros arquitecturas recurrentes.
- Ejemplos para cargar y usar embeddings en PyTorch.

<br>

### [bow](https://github.com/evNLP/bow)
Este repositorio se centra en el modelo Bag of Words (BOW) para la representación de texto. Incluye herramientas para construir matrices BOW y realizar comparaciones entre textos basados en frecuencia de palabras.  
**Características principales**:
- Métodos para crear representaciones BOW a partir de corpus de texto.
- Comparación entre documentos utilizando métricas como coseno de similitud.
- Ideal para tareas de clasificación y recuperación de información.

<br>

Estos repositorios están diseñados para ofrecer herramientas prácticas y educativas para investigadores, estudiantes y desarrolladores interesados en el campo del procesamiento del lenguaje natural. ¡Explora cada uno y lleva tus proyectos al siguiente nivel!
