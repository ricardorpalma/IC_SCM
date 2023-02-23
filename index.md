--- 
title: "IC & SCM Post COVID_19"
author: 'Editores: Ricardo R. Palma y Gustavo A. Masera'
date: "2023-02-23"
output:
  html_document:
    df_print: paged
documentclass: book
bibliography:
- book.bib
- packages.bib
url: https://github.com/ricardorpalma/IC_SCM
cover-image: images/coverMZA.png
description: |
  This is a minimal example of using the bookdown package to write a book.
  set in the _output.yml file.
  The HTML output format for this example is bookdown::bs4_book,
biblio-style: apalike
csl: "chicago-fullnote-bibliography.csl"
site: bookdown::bookdown_site
---

# Introducción {-}


Este libro es una compilación de los trabajos de investigación y estancias de investigadores de varios colegas de latino américa y caribe. Guestavo Masera y Ricardo Palma desean agradecer a todos los colaboradores que nos han confiado sus materiales para que los editemos en esta publicación. Como docentes investigadores de la Universidad Nacional de Cuyo hemos vivido este fenómeno singular de tiempo que denominamos la pandemia del post-covid-19 y como los autores de los capítulos incluidos, tenemos la convicción que la existencias de nuevas estrategias emergentes y prácticas innovadoras que mejoras la resiliencia y han demostrado innovación de la gestión de las infraestructuras críticas y las cadenas de suministros.

![Infraestructuras Críticas y Cadenas de Suministros Post COVID-19](images/coverMZA.png)

## Agradecimientos: {-}


Este libro digital ha sido financiado en parte por las siguientes instituciones y por la amable cesión de derechos de publicación de los autores de cada capítulo.
Entre otros nso gustaría agradecer a:


- Programa Imeroamericano de Ciencia y Tecnología para el Desarrollo

![Red CyTED](images/cyted.png)

y al grupo de trabajo de CyTED 
[link](https://themys.sid.uncu.edu.ar/rpalma/En_Desarrollo/about.html)


- Asociación Grupo Montevideo de Universidades
![AUGM](images/augm.png)


- Secretaría de Ciencia Técnica y Posgrado de la Universidad Nacional de Cuyo


![SECTYP](images/siip-investigacionposgrado.jpg)



Prefacio por Ricardo Palma y  Dr. Gustavo Masera


Sin dudas uno de los actores más destacados en el escenario de la post-pnademia ha sido el CHATGPT. Si le preguntásemos a esta entidad creada por *openai.com*. Le preguntamos entorno a estas cuestiones al bot y esto es lo que nos dice:

    Hola podemos hablar en español ?
    
    - ¡Hola! Claro, podemos hablar en español. ¿En qué puedo ayudarte?
    
    ¿ que impactos a tenido el covid-19 en las cadenas de suministros de latinoamerica y caribe?
    
    - El COVID-19 ha tenido un impacto significativo en las cadenas de suministro de Latinoamérica y el Caribe. 
    A continuación, se presentan algunos de los principales impactos que ha tenido la pandemia en esta región:

    Interrupción de la cadena de suministro:  ...

1- Las restricciones a la movilidad y las medidas de cierre de fronteras han dificultado la importación y exportación de bienes y han restringido el flujo de la cadena de suministro en toda la región.

2- Aumento de los costos: El aumento de la demanda de ciertos productos, la escasez de suministros y la interrupción de la cadena de suministro han aumentado los costos de los productos y servicios.

3- Cambio en la demanda: La pandemia ha cambiado la demanda de productos y servicios, lo que ha afectado la producción y distribución de bienes.

4- Disminución en la productividad: Las medidas de distanciamiento social, el cierre de empresas y la disminución de la movilidad han afectado la productividad de las empresas en la región.

5- Nuevas oportunidades de negocio: La pandemia ha llevado a una mayor adopción de tecnologías digitales y ha abierto nuevas oportunidades de negocio en línea.

En resumen, la pandemia ha tenido un impacto significativo en las cadenas de suministro de Latinoamérica y el Caribe, lo que ha llevado a cambios en la demanda, aumento de los costos y la interrupción de la cadena de suministro.

Se puede decir que el impacto del COVID-19 en la región ha sido muy significativo y complejo, y que la situación post-covid en Latinoamérica aún es incierta. La recuperación económica puede ser lenta y desigual, y las cadenas de suministro pueden enfrentar nuevos desafíos en el futuro. Es importante seguir monitoreando la situación y tomar medidas adecuadas para adaptarse a los cambios y desafíos que surjan en el futuro. En especial luego del conflicto con Ucrania-Rusia En general, el libro puede ser una fuente valiosa de información y perspectivas sobre la gestión de la cadena de suministro en la región, y puede ayudar a los lectores a entender mejor los desafíos actuales y futuros.


Que ***chatgpt*** catalogie así este trabajo no hace más que hablar muy bien de los autores de cada capítulo, pero sólo por haber incluido este texto en el libro el software de revisión de plagio editorial urkund nos castiga con un 3% de índice de plagio.

## ¿Por qué escribir un libro sobre algo que la inteligencia artificial podría escribir miles de páginas? {-}

Justamente por que esta es una obra creada por la gente y para la gente. Cada uno de nosotros , editores y autores de los capípulos vivimos en esta región. Trabajamos, comemos, enseñamos, cultivamos, cosechamos, compramos y vendemos, viajamos y hasta escribimos canciones y poemos; todo en este escenario de tanta diversidad y con tantos parecidos que llamamos latinoamérica. 

Este libro contiene en los diferentes capítulos la mirada interna y externa,  *** "en la  enesperanza de poder ver global y actuar local ***" . Pero en esta oportunidad como editores hemos querido rescatar sobre todo las experiencias exitosas así como los fracasos de las cosas que la pandemia nos obligó a desarrollar para adaptarnos a un mundo totalmente nuevo y desconocido.


Uno de los capítulos que recomendamos tener en cuanta es el Cap. 6 en el que **Alexis Sdrigotti** nos señala la importancia que durante y post pandemia han tenido las infraestructuras críticas, pero para poner de manifiesto este paradigma ha elegido el caso de Jaón.

Los impactos que el precio de los combustibles tienen ha quedado referido en varios capítulos (Cap.2 Aruani et al.^[https://ricardorpalma.github.io/IC_SCM/escenarios-energeticos-globales.html]y Cap. 10[Riera et al. ]) pero también esto nos abre una ventana de incertidumbres para la región ya que los fertilizantes que nuestra manufactura de origen agropecuario tiene un enrome componente energético.

La innovación se hace presente con una de las modalidades que el COVID impuso en la argentina y está relacionada con el turismo rural que fué clave por las posibilidades de aislamiento que brindó en la peor parte del aislamiento obligatorio y preventiv, pero que llegó para quedarse. Ver Cap. 4 Da Rosa et al. ^[eliasemmanueldarosa99@gmail.com]

Cada capítulo restante contribuye a brindar una perspectiva innovadora de las mejores prácticas y estrategias que en nuestro contexto se han implementado y aún se siguen implementando en torno a las oportunidades y dificultades que este nuevo panorama implica para la región

**Esperamos que disfruten este material**

**ISBN 978-987-88-8016-7**
- *Infraestructura crítica y cadenas de suministros post-Covid* 
- Editores Ricardo R Palma. & Gustavo Masera (autores varios)
- 1a edición para el profesor - Guaymallén - Mendoza - Argentina 2023.
- Libro digital, EPUB
- Clasificación    1. Investigación Comparativa. I. Título.    CDD 621.4807
- El contenido de algunos capítulos ha sido compartido por los autores bajo la atribución Creative Common Contents 4.0 Internacional

El diseño de la página de web y la estética está protegido por el ISBN

Este libro no tiene valor comercial , apoya la iniciativa del Open Access respetando la decisión sobre sus capítulos en forma individual. 
Puedes utilizar contenido siempre que refieras a los autores de cada capítulo
Esta en una Licencia de Cultura Libre.

<center>
<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Licencia Creative Commons" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png" /></a><br />Esta obra está bajo una <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Licencia Creative Commons Atribución 4.0 Internacional</a>.
<\center>






978-987-88-8016-7
**Cámara Argentina del Libro**
2 Marzo del 2023

![ISBN ARG](images/isbn_2_arg.png)




## Indicaciones para colaboradores {-}

Este libro puede ser intervenido por los lectores.
Para solicitar errores que pudiesen haberse filtrado o incluso para agregar material a los capítulos se dispone de los medios de intervención provistos por Markdown / GitHub
Este breve explicación le permite ver la sintaxis y métodos de agregar contenidos.


Por consultas y para solicitar versión .mobi o e-pub escribir a: [rpalma@uncu.edu.ar](mailto:rpalma@uncu.edu.ar)



