---
title: "Analítica de Negocios"
subtitle: "<br/> Actividades"
author: "PhD.(C) Orlando Joaqui-Barandica"
institute: "Pontificia Universidad Javeriana de Cali"
date: "2023"
output:
  xaringan::moon_reader:
    lib_dir: libs
    css: 
      - default
      - rladies
      - rladies-fonts
      - fonts_mtheme.css
      - sydney.css
      - style.css
    seal: false  
    nature:
      ratio: 16:9
      highlightStyle: github
      highlightLines: true
      countIncrementalSlides: false

---




class: inverse, left, bottom
background-image: url("img/fondo.jpg")
background-size: cover


# **Analítica de Negocios**
----

## **<br/> Actividades**

### PhD.(C) Orlando Joaqui-Barandica
### 2023





---
name: hola
class: inverse, middle, center

<img style="border-radius: 60%;" src="img/jave.jpg"
width="150px"
/>

# Pontificia Universidad Javeriana de Cali

--

## Programa de Economía
---




.pull-left[

<br><br><br><br><br>

<img src="img/gif1.gif" width="110%" />
]

<br><br><br><br><br>


.pull-right[
# Orlando Joaqui-Barandica
### [www.joaquibarandica.com](https://www.joaquibarandica.com)
 *PhD.(C) in Industrial Engineering* 
 
 *MSc. Applied Economics*
 
 *BSc. Statistics*
]

---

name: menu
background-image: url("img/back2.jpg")
background-size: cover
class: left, middle, inverse

# Contenido

----


.pull-left[
### <!--html_preserve--><i class="fa fa-sort-numeric-up" role="presentation" aria-label="sort-numeric-up icon"></i><!--/html_preserve--> [Actividad 1](#Act1)

### <!--html_preserve--><i class="fa fa-sort-numeric-up" role="presentation" aria-label="sort-numeric-up icon"></i><!--/html_preserve--> [Actividad 2](#Act2)


]


.pull-right[


]

---


name: Act1
class: inverse, center, middle

# <!--html_preserve--><i class="fa fa-sort-numeric-up" role="presentation" aria-label="sort-numeric-up icon"></i><!--/html_preserve-->
# Actividad 1
----

.right[
.bottom[
####  [<!--html_preserve--><i class="fa fa-bell" role="presentation" aria-label="bell icon"></i><!--/html_preserve-->](#menu)
]
]


# 🥸


---

# 🤯 Actividad 1

.pull-left[

<img src="https://media.giphy.com/media/eKZrQHSu8IHFPQk40D/giphy.gif" width="90%"/>

]

.pull-right[

### Seleccione 3 países de su preferencia, descargue de [🔗 OECD DATA](https://data.oecd.org/interest/short-term-interest-rates.htm) la variable:

* `Short-term interest rate`.

## .orange[Realice un gráfico de cajas en dónde compare la distribución de la variable para los 3 países.]

* **Se debe presentar en un informe dinámico en `Rmarkdown`**

]

---



name: Act2
class: inverse, center, middle

# <!--html_preserve--><i class="fa fa-sort-numeric-up" role="presentation" aria-label="sort-numeric-up icon"></i><!--/html_preserve-->
# Actividad 2
----

.right[
.bottom[
####  [<!--html_preserve--><i class="fa fa-bell" role="presentation" aria-label="bell icon"></i><!--/html_preserve-->](#menu)
]
]


# 🥸


---

class: center, middle

# 🤯 Actividad 2

<br>

.pull-left[

### Para esta actividad (Y muy posiblemente las siguientes) trabajaremos con la librería de wooldridge en R. Es necesario que la instales.

<br>

### `library(wooldridge)`

<br>

#### .orange[Cada conjunto de datos presentado debe ser buscado en la ayuda (`Help`) de R. Con el fin de identificar las descripciones de las variables.]

]

.pull-right[

<br><br>

* **Es necesario que cada punto sea apoyado con visualizaciones gráficas realizadas en `ggplot2`**

* **Se debe presentar en un informe dinámico en `Rmarkdown`**

<br>

----
### Las visualizaciones son una rúbrica importante en la evaluación.
----

]


---



# 🤯 Actividad 2


## Punto 1


Para este ejercicio emplee la base de datos `WAGE1.RAW`


> 1. Determine el nivel educativo promedio de la muestra. ¿Cuáles son los niveles de educación menor y mayor?

> 2. Determine el salario promedio por hora (wage) en la muestra. ¿Parece ser alto o bajo? 

> 3. ¿Cuántas mujeres (females) hay en la muestra? ¿Cuántos hombres?


---


# 🤯 Actividad 2


## Punto 2


Para responder estas preguntas emplee la base de datos `BWGHT.RAW`

> 1. ¿Cuántas mujeres hay en la muestra (male = 0) y cuántas de las informantes fumaron durante un embarazo?

> 2. ¿Cuál es la cantidad promedio de cigarros consumidos por día (cigs)? ¿Es el promedio, en este caso, una medida representativa de la mujer “típica”? Explique.

> 3. Entre las mujeres que fumaron durante el embarazo, ¿cuál es la cantidad promedio de cigarros consumidos por día? ¿Cuál es la relación de esto con su respuesta al inciso ii) y por qué?

> 4. Determine el promedio de fatheduc (años de educación del padre) en la muestra. ¿Por qué se emplean sólo 1 192 observaciones para calcular este promedio?

> 5. Dé el ingreso familiar promedio (famine) y su desviación estándar en dólares.



---


# 🤯 Actividad 2


## Punto 3

Los datos de `MEAP01.RAW` pertenecen al estado de Michigan en el año 2001. Emplee estos
datos para contestar las preguntas siguientes.

> 1. Determine los valores mayor y menor de math4. ¿Es lógico este intervalo? Explique.

> 2. ¿Cuántas escuelas tienen una tasa perfecta de aprobados en el examen de matemáticas? ¿A qué porcentaje del total de la muestra corresponde esta cantidad?

> 3. ¿En cuántas escuelas la tasa de aprobados en matemáticas es exactamente 50%?

> 4. Compare el promedio de las tasas de aprobados en matemáticas y en lectura. ¿Cuál de estas pruebas es más difícil de aprobar?

> 5. Encuentre la correlación entre math4 y read4. ¿Qué concluye?

> 6. La variable exppp es gasto por alumno. Determine el promedio y la desviación estándar de exppp. ¿Parece haber una gran variación en el gasto por alumno?


---





class: inverse, center, middle
background-color: #122140

.pull-left[

.center[
<br><br>

# Gracias!!!

<br>



### ¿Preguntas?

<br>


<img src="img/qr-code.png" width="49%" style="display: block; margin: auto;" />


]


]


.pull-right[

<br> 
<br> 
<img style="border-radius: 50%;" src="img/avatar.png"
width="150px"
/>

### [www.joaquibarandica.com](https://www.joaquibarandica.com)

<!--html_preserve--><i class="fa fa-envelope" role="presentation" aria-label="envelope icon"></i><!--/html_preserve--> orlando.joaqui@javerianacali.edu.co

<img src="img/Logo.jpg" width="120%">

]


<br><br><br>









