# Trabajo Integrador Individual: Pipeline completo de NLP
## Descripción
Este directorio tendrá como propósito asignado la extracción, exploración y análisis de un corpus de texto de tipo periodístico.

Se ha elegido como temática principal el sector de tecnología, con énfasis en el término "privacidad", y tomando de contexto artículos periodísticos recientes (desde 2020 a 2025, aproximadamente). La finalidad de este filtrado es explorar las siguientes hipótesis que están mejor elaboradas en el notebook [/notebook/analisis_integrador.ipynb]:

* ¿Son realmente necesarias las nuevas exigencias en los términos y condiciones modificados?

* ¿Por qué se necesitan nuevas regulaciones año tras año de parte de protección de datos?

* ¿El factor económico de redistribución de datos personales sigue siendo tan presente como hace 5 años?

La hipótesis que planteo es que si bien se vió enlentecido el proceso de nuevos requerimientos que involucren vender nuestra privacidad de datos personales, sigue siendo igual de relevante que durante la década pasada.

## Información del Corpus
El corpus seleccionado está compuesto por las siguientes fuentes elegidas:

* https://derechodelared.com/
* https://www.anred.org/
* https://www.pagina12.com.ar/

Se omiten otros sitios periodisticos como Clarin, La Nación e Infobae ya que no proporcionaban suficiente información relevante al filtro que queremos aplicar

## Técnicas de NLP Aplicadas
- Preprocesamiento de texto (limpieza, tokenización, stop words)
- Análisis con Bag of Words (BoW) y TF-IDF
- Análisis con Word Embeddings (spaCy)

## Principales Hallazgos
Soon...

## Tecnologías Utilizadas
- Python 3.x
- Google Colaboratory
- pandas, numpy
- scikit-learn
- spaCy
- matplotlib, seaborn

## Instrucciones de Reproducción
1. Clonar este repositorio
2. Instalar dependencias: `pip install -r requirements.txt`
3. Ejecutar el notebook: `jupyter notebook notebooks/analisis_integrador.ipynb`

## Limitaciones y Trabajo Futuro
- Tamaño de corpus > Se deberá ampliar en algún momento el volumen para lograr obtener distribuciones más realistas de palabras usadas
- Stopwords > Actualmente se dispone de una lista de stopwords custom que puede ampliarse para omitir ciertas palabras que aportan poco contexto
- WebScraping > Obtener Autores de fuentes de forma más optimizada, no se ha podido extraer la data de muchas urls utilizadas

## Autor
Gonzalo B. - @gimb99
Trabajo Integrador - NLP - 25/09/2025

## Dependencias

```
pandas>=1.3.0
numpy>=1.21.0
scikit-learn>=1.0.0
spacy>=3.4.0
matplotlib>=3.5.0
seaborn>=0.11.0
nltk>=3.7.0
wordcloud>=1.8.0
jupyter>=1.0.0
os
re
collections / Counter
BeautifulSoup
requests
shutil
```

## Notas
Este notebook está diseñado como un ejercicio integrador, combinando varios temas importantes del procesamiento del habla


