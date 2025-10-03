# Trabajo Integrador Individual: Pipeline completo de NLP
## Descripción
Este directorio tendrá como propósito asignado la extracción, exploración y análisis de un corpus de texto de tipo periodístico.

Se ha elegido como temática principal el sector de tecnología, con énfasis en el término "privacidad", y tomando de contexto artículos periodísticos recientes (desde 2020 a 2025, aproximadamente). La finalidad de este filtrado es explorar las siguientes hipótesis que están mejor elaboradas en el [notebook](notebook/analisis_integrador.ipynb)

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
Si bien no responden necesariamente las pretenciones de la hipótesis planteada, se encontraron las siguientes relaciones de términos:
- La presencia de "capitalismo" en las relaciones de Política, Seguridad y el Derecho de los usuarios
- La presencia de "seguridad" como posible justificativo para desamparar la Privacidad de los usuarios

Asímismo, se encuentran varias menciones de países de Europa (incluyendo esta vez a Gran Bretaña) con los avances de legislaciones relacionadas a vulnerar el derecho a la privacidad del usuario promedio en pos de incrementar la seguridad con mayor cibervigilancia a través de aplicaciones de mensajería o que utilicen modelos de Inteligencia Artificial. 

No se hacen muchas menciones de países latinoamericanos en esta cuestión, lo cual puede ser por seguir dichas tendencias europeas pasado un cierto tiempo.

Los clusters generados a partir del corpus seleccionado tiene distribuciones balanceadas y separadas en 5 temas posibles, lo cual fue una sorpresa considerando que se pensó tomar una menor variedad en la selección de asuntos de artículos periodísticos.

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

## Notas
Este notebook está diseñado como un ejercicio integrador, combinando varios temas importantes del procesamiento del habla


