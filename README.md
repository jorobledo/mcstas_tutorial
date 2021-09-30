# Tutorial de McStas
[![McStas](https://img.shields.io/badge/Software-McStas-brightgreen)](https://mcstas.org/)

El objetivo de este tutorial es aprender a utilizar McStas para comenzar a simular experimentos de Dispersión a Bajo Ángulo de Neutrones (SANS, del inglés *Small Angle Neutron Scattering*). 

## Instalación de McStas

Este tutorial está basado en McStas 2.7. Los pasos para instalar McStas difieren según el sistema operativo que esté utilizando.

Referencias:

* [mcstas oficial page](http://www.mcstas.org/download/)
* [Instrucciones de instalación](https://github.com/McStasMcXtrace/McCode/blob/master/INSTALL-McStas-2.x/README.md)

## Documentación:

La carpeta documentación tiene la presentación powerpoint en la que se describe una pequeña introducción a McStas y su uso para simular experimentos de neutrones. Está orientada a SANS, en particular a los instrumentos que serán incorporados en el Laboratorio de Haces de Neutrones (LAHN).

## Ejemplos

### 1.) Primera simulación

El instrumento que se describe en esta carpeta es de los más simples posibles. La idea es entender cómo funciona el código, cómo visualizar el instrumento con el mcgui, cómo realizar una primera simulación y finalmente cómo visualizar los resultados de la simulación.

### 2.) SANS

En este caso, se presenta un primer instrumento de SANS ideal, donde veremos cómo se pueden incluir las distintas componentes necesarias. Se experimentará sobre una muestra definida en base a la componente ``SANS_guinier`` ([SANS_Guinier.comp](http://www.mcstas.org/download/components/2.7/contrib/SANS_Guinier.html)) , que aprovecha la existencia de una integral analítica (ver [Guinier SAS model](https://www.sasview.org/docs/user/models/guinier.html)).
