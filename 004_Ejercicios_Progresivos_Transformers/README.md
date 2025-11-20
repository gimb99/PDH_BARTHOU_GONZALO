# TP NLP: Ejercicios Progresivos con Transformers

## Descripción

Este trabajo práctico individual consiste en una serie de ejercicios progresivos que exploran aplicaciones reales de Procesamiento de Lenguaje Natural (NLP) utilizando modelos Transformer preentrenados. Cada ejercicio aborda un caso de uso concreto (clasificación de sentimientos, NER, QA) para comprender la implementación y limitaciones de estos modelos.

## Objetivo

Aplicar conceptos teóricos de NLP mediante la resolución práctica de problemas comunes utilizando modelos Transformer. Se busca familiarizarse con librerías clave del ecosistema Hugging Face y evaluar el desempeño de los modelos en tareas específicas.

## Stack Tecnológico

- **Python**
- **Transformers (Hugging Face)**
- **PyTorch**
- **Pandas**
- **Google Colab** (Entorno de ejecución original)

## Estructura del Proyecto

- `gbg_guía_de_ejercicios_progresivos.ipynb`: Notebook con los ejercicios 1, 2, 3 y el desafío autónomo.
- `README.md`: Este archivo.

## Contenido del Notebook

1.  **Ejercicio 1: Moderación de Comentarios en Redes Sociales**: Clasificación de sentimientos en español usando `beto-sentiment-analysis`.
2.  **Ejercicio 2: Extracción Automática de Información de CVs**: Uso de NER para extraer entidades clave (nombres, organizaciones, ubicaciones) con `PlanTL-GOB-ES/roberta-base-bne-capitel-ner`.
3.  **Ejercicio 3: Chatbot de Soporte Técnico Automático**: Implementación de Question Answering (QA) basado en contexto con `mrm8488/distill-bert-base-spanish-wwm-cased-finetuned-spa-squad2`.
4.  **Ejercicio 4: Desafío Autónomo**: Análisis de sentimiento de reseñas de clientes usando `finiteautomata/beto-sentiment-analysis`.

## Instrucciones de Uso

1.  Asegúrate de tener instaladas las dependencias listadas en la sección "Stack Tecnológico".
2.  Abre el notebook `gbg_guía_de_ejercicios_progresivos.ipynb` en Google Colab o en tu entorno local.
3.  Ejecuta las celdas secuencialmente.

## Aprendizajes Clave

- Cómo cargar y usar modelos preentrenados de Hugging Face para diferentes tareas de NLP.
- Aplicación de modelos a casos de uso específicos (clasificación, NER, QA).
- Evaluación de resultados y limitaciones de los modelos (por ejemplo, dificultades con ironía en sentimientos o recorte de entidades en NER).
- Trabajo autónomo con tareas de NLP.

## Autor

- Gonzalo B.
- Técnicas de Procesamiento de Imágenes
- Año: 2025