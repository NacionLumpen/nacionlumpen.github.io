---
layout: post
title:  "NL19: relevancia y búsqueda"
date:   2018-10-06 00:00:00
categories: podcast
spreaker: https://www.spreaker.com/user/nacionlumpen/nl19-relevancia
itunes: https://itunes.apple.com/es/podcast/nacion-lumpen/id1023465004?l=en&mt=2
track-mp3: https://api.spreaker.com/download/episode/15897249/nl19_relevant.mp3
---

¿Alguna vez te has preguntado qué base de datos se utiliza para implementar
motores de búsqueda? Si se lo preguntas a Sebastián te gruñirá que para eso no
se utilizan bases de datos sino sistemas de recuperación de la información
cuya arquitectura e historia es totalmente diferente al de las bases de datos
SQL tradicionales y que son algo fascinante, como para hacer al menos un
episodio de Nación Lumpen.

Como te puedes imaginar, el episodio que hoy te traemos es exactamente esto
pero no hubiesa sido posible sin dos invitados de lujo:

 - **Óscar Huarte**, actualmente PO del equipo de relevancia en Stratio y con más
     de 15 años de experiencia con sistemas de búsqueda.
 - **Julien Meynet**, científico de datos en Letgo y gran experto en búsqueda cuya
     experiencia se remonta a los 2000s en Yahoo.

Con ellos, vuestros locutores habituales:

 - [Álvaro Castellanos](https://github.com/alvarocaste), que toma el rol de
     presentador en este episodio.
 - [Sebastián Ortega](https://twitter.com/_sortega), vuestro pesado de
   siempre.

La dedicatoria del episodio es doble:

 - A Vannevar Bush, por introducir la idea del Memex en 1945 en su artículo [As We Might Think](https://www.theatlantic.com/magazine/archive/1945/07/as-we-may-think/303881/).

   <img src="/img/memex.jpg" style="width: 50%"/>

 - A [Stephen Robertson](http://www.staff.city.ac.uk/~sb317/), uno de los
   inventores del mágico BM25

Enlaces/referencias:

 - El [libro](https://nlp.stanford.edu/IR-book/information-retrieval-book.html)
   más clásico. Eso sí, la mayoría de su contenido se sigue utilizando en 2018.
 - [Survey](http://www.staff.city.ac.uk/~sb317/papers/foundations_bm25_review.pdf) que detalla BM25
 - [Curso en Coursera](https://www.coursera.org/learn/text-retrieval) sobre
     text retrieval
 - Principales productos tecnológicos:
    - Apache Lucene https://lucene.apache.org/
    - Apache Solr https://lucene.apache.org/solr/
    - Elasticsearch https://www.elastic.co/
    - Vespa http://vespa.ai/
 - Las palabras se suelen distribuir siguiendo [power laws](https://en.wikipedia.org/wiki/Power_law)
 - [Soundex](https://en.wikipedia.org/wiki/Soundex) es una forma de considerar
   la fonética de las palabras. Algo similar está detrás de la magia de buscar
   “Estifen jokins” en Google y [encontrar lo que queremos](https://www.google.com/search?hl=es&q=estifen+jokins&oq=estifen+jokins)
 - Ejemplo de uso de Lucene para sugerir mnemónicos: https://github.com/sortega/mms
 - La métrica favorita de Julien: MRR.
     Expected Reciprocal Rank for Graded Relevance, O. Chapelle et al. CIKM 2009
     http://olivier.chapelle.cc/pub/err.pdf
 - No dejen de leer a Leon Bottou para aprender sobre "counterfactual
     learning". Counterfactual Reasoning and Learning Systems: The Example of
     Computational Advertising,  Leon Bottou et al.  JMLR 2013
     http://jmlr.org/papers/v14/bottou13a.html
