---
layout: default
---




## Introducción

El Open Source o código abierto ha cambiado la cultura de trabajo de los desarrolladores, supone un nuevo modelo de trabajo al que se están sumando las grandes compañías, esta nueva forma de colaboración esta alterando las reglas del juego en el mundo tecnológico y empresarial. El open source de esta era trata mas de estrategias comerciales corporativas que de comunidades independientes colaborando entre ellas. 
Hemos seleccionado 6 proyectos open source que utilizan git como herramienta de colaboración. En este análisis nos centramos en la actividad de los desarrolladores tomando como referencia los 10 últimos meses contando desde marzo que fue cuando inicio de la pandemia del COVID-19.

## Metodología

Hemos utilizado **GrimoireLab** que es un conjunto de herramientas  open source basadas en Python para recuperar, organizar y visualizar datos relacionados con el desarrollo de software (Commit, Issues, Autores, Colaboradores).
Lo proyectos alojados en Git que hemos analizado son:

* Openshift
* Kubernetes
* Docker
* Coreos
* Cointainer
* Ansible
* Chef
* Puppet

Con los datos procesados por Grimoirelab hemos creado  en Kibana varias visualizaciones que nos han permito realizar el análisis de la actividad y la relación que mantienen estos proyectos.

* Actividad en el repositorio en Git de cada **commit** ejecutado en el repositorio Git por los autores agrupados por semana y la media agrupados por 4 semanas

![red_social_projectcommitAuthor]({{ site.baseurl }}/assets/images/commitAuthor.png)
Actividad de los autores de cada uno de los proyectos analizados


### Relacion entre los proyectos 

![red_social_project]({{ site.baseurl }}/assets/images/red_social_project.png)

### Areas de Codigo

![red_social_project]({{ site.baseurl }}/assets/images/areas_codigo.png)
