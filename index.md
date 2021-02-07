---
layout: default
---


![ActividadProyectos]({{ site.baseurl }}/assets/images/ActividadProyectos.png)



## **Introducción**

El Open Source o código abierto ha cambiado la cultura de trabajo de los desarrolladores, supone un nuevo modelo de trabajo al que se están sumando las grandes compañías, esta nueva forma de colaboración esta alterando las reglas del juego en el mundo tecnológico y empresarial. El open source de esta era trata mas de estrategias comerciales corporativas que de comunidades independientes colaborando entre ellas. 
Hemos seleccionado 6 proyectos open source que utilizan git como herramienta de colaboración. En este análisis nos centramos en la actividad de los desarrolladores tomando como referencia los 10 últimos meses contando desde marzo que fue cuando inicio de la pandemia del COVID-19.

## **Metodología**

Hemos utilizado **GrimoireLab** que es un conjunto de herramientas  open source basadas en Python para recuperar, organizar y visualizar datos relacionados con el desarrollo de software (Commit, Issues, Autores, Colaboradores).
Lo proyectos alojados en Git que hemos analizado son:

* Openshift
* Kubernetes
* Docker
* Coreos


Con los datos procesados por Grimoirelab hemos creado  en Kibana varias visualizaciones que nos han permito realizar el análisis de la actividad y la relación que mantienen estos proyectos.

Hemos tomado como referencia para esta publicacion el siguiente post: 
* https://blog.bitergia.com/2020/03/19/second-round-covid-19-vs-open-source-development/ 


### Actividad de los repositorios

La visualizacion muestra la actividad total de los 4 proyectos que no es mas que la suma de las contribuciones por cada **commit** ejecutado por los autores.

![ActividadProyectos]({{ site.baseurl }}/assets/images/ActividadProyectos.png)

* **Actividad Commit**

En la ilustración se observa los **commit** realizados por los autores y la media móvil agrupada por 4 semanas.

![commitAuthor]({{ site.baseurl }}/assets/images/commitAuthor.png)

* **Comparacion Actividad 2019 -2020**

Comparando la actividad de los 4 proyectos entre 2019 y 2020 se observa que un incremento de la actividad en los meses de abril, agosto, octubre y diciembre de 2020.

![ActividadComparadaAñoAnterior]({{ site.baseurl }}/assets/images/ActividadComparadaAñoAnterior.png)

* **Tendencia Actividad 2020**

La imagen contiene 4 metricas: Contribuciones, Medias moviles (8 semanas), la Media y la Tendencia tendencia. Se puede concluir que en este período analizado (enero/diciembre 2020) hay un tendencia creciente en las contribuciones.

![TendenciaActividadRepositoro]({{ site.baseurl }}/assets/images/TendenciaActividadRepositorio.png)

## Analisis de la actividad por poryecto

La participación de determinadas empresas que contribuyen en estos proyectos es evidente debido a su necesidad tecnologica y volumen de negocio. Las visualizaciones muestran una lista de empresas que lideran el top ten de contribuciones y que casi siempre son las mismas.

### Actividad Openshift

![ActividadOpenshif]({{ site.baseurl }}/assets/images/ActividadOpenshift.png)
### Actividad Kubernetes

![ActividadKubernetes]({{ site.baseurl }}/assets/images/ActividadKubernetes.png)
### Actividad Docker

![ActividadDocker]({{ site.baseurl }}/assets/images/ActividadDocker.png)
### Actividad CoreOS

![ActividadCoreos]({{ site.baseurl }}/assets/images/ActividadCoreos.png)

## Conclusiones

* Las empresas que colaboran y contribuyen al desarrollo de estos proyectos lo hacen por su necesidad tecnológica y estrategia de negocio.
* La pandemia no ha sido amenaza para el desarrollo de estos proyectos que como se ha visto en términos generales hay una tendencia creciente en su actividad. 




## Publicado por Alex Martínez
## email: superlinuxec@gmail.com