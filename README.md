# Economic-Research-Seminar
---
title: "Tesis"
author: "E Edison Achalma Mendoza"
date: "`r Sys.Date()`"
output: 
  html_document:
    toc: yes
    toc_float: yes
    theme: united
    code_download: yes
  pdf_document:
    toc: yes
subtitle: Crecimiento económico y pobreza en el departamento Ayacucho, periodo 2000-2019
---

<center>

![](Images\0_1_Caratula\Logo.png){width=250}

</center>


```{r setup, include=FALSE}
knitr::opts_chunk$set(echo = TRUE)
```

# RESUMEN
Fusce mauris. Vestibulum luctus nibh at lectus. Sed bibendum, nulla a faucibus
semper, leo velit ultricies tellus, ac venenatis arcu wisi vel nisl. Vestibulum diam. Aliquam
pellentesque, augue quis sagittis posuere, turpis lacus congue quam, in hendrerit risus eros
eget felis. Maecenas eget erat in sapien mattis porttitor. Vestibulum porttitor. Nulla facilisi.
Sed a turpis eu lacus commodo facilisis. Morbi fringilla, wisi in dignissim interdum, justo
lectus sagittis dui, et vehicula libero dui cursus dui. Mauris tempor ligula sed lacus. Duis
cursus enim ut augue. Cras ac magna. Cras nulla. Nulla egestas. Curabitur a leo. Quisque
egestas wisi eget nunc. Nam feugiat lacus vel est. Curabitur consectetuer.

# ABSTRACT
Fusce mauris. Vestibulum luctus nibh at lectus. Sed bibendum, nulla a faucibus
semper, leo velit ultricies tellus, ac venenatis arcu wisi vel nisl. Vestibulum diam. Aliquam
pellentesque, augue quis sagittis posuere, turpis lacus congue quam, in hendrerit risus eros
eget felis. Maecenas eget erat in sapien mattis porttitor. Vestibulum porttitor. Nulla facilisi.
Sed a turpis eu lacus commodo facilisis. Morbi fringilla, wisi in dignissim interdum, justo
lectus sagittis dui, et vehicula libero dui cursus dui. Mauris tempor ligula sed lacus. Duis
cursus enim ut augue. Cras ac magna. Cras nulla. Nulla egestas. Curabitur a leo. Quisque
egestas wisi eget nunc. Nam feugiat lacus vel est. Curabitur consectetuer.

# PRÓLOGO
Suspendisse vel felis. Ut lorem lorem, interdum eu, tincidunt sit amet, laoreet vitae,
arcu. Aenean faucibus pede eu ante. Praesent enim elit, rutrum at, molestie non, nonummy
vel, nisl. Ut lectus eros, malesuada sit amet, fermentum eu, sodales cursus, magna. Donec eu
purus. Quisque vehicula, urna sed ultricies auctor, pede lorem egestas dui, et convallis elit erat
sed nulla. Donec luctus. Curabitur et nunc. Aliquam dolor odio, commodo pretium, ultricies
non, pharetra in, velit. Integer arcu est, nonummy in, fermentum faucibus, egestas vel, odio.
Suspendisse vitae elit. Aliquam arcu neque, ornare in, ullamcorper quis, commodo eu,
libero. Fusce sagittis erat at erat tristique mollis. Maecenas sapien libero, molestie et, lobortis
in, sodales eget, dui. Morbi ultrices rutrum lorem. Nam elementum ullamcorper leo. Morbi
dui. Aliquam sagittis. Nunc placerat. Pellentesque tristique sodales est. Maecenas imperdiet
lacinia velit. Cras non urna. Morbi eros pede, suscipit ac, varius vel, egestas non, eros.
Praesent malesuada, diam id pretium elementum, eros sem dictum tortor, vel consectetuer
odio sem sed wisi.

# I. PLANTEAMIENTO DEL PROBLEMA

## 1.1. Enunciado del problema
La Organización para la Cooperación y el Desarrollo Económicos (2018), afirma que
“la desigualdad económica es el distinto reparto de los ingresos, los activos o el bienestar entre
el conjunto de habitantes”.
Latino américa es la región más desigual de la región en términos socio económicos;
según Lustig (2011), “la región latinoamericana es 19% más desigual que el África
subsahariana, 37 más desigual que el este asiático y 65% más desigual que los países
desarrollados”. En efecto América Latina es, hoy, la región sin guerras más desigual del
planeta: más que India, más que algunos países de África Subsahariana.
La desigualdad socio económica impide luchar contra la pobreza, ampara a los grupos
vulnerables de vivir en la pobreza sin acceso a un trabajo decente, servicios básicos,
exposición a una nutrición malsana o falta de vivienda digna. Se excluye el estatus social y los
individuos y familias continúan existiendo.
En este sentido es evidente la importancia de entender la pobreza. Ravallion, Datt, y
Walle (1991), afirman que la pobreza alude a niveles de vida. " Esto es: ¿cuántas personas no
pueden satisfacer ciertas necesidades predeterminadas de consumo y acceso amplio a bienes
públicos (servicios de salud, educación, vivienda)?"
Según el Instituto Nacional de Estadística e Informática (2000) “La pobreza es una
condición en la cual una o más personas tienen un nivel de bienestar inferior al mínimo
socialmente aceptado.”
Las estadísticas indican que desde el año 2000 se ha conseguido reducir la tasa de
incidencia de la pobreza en el Perú. El siguiente cuadro del Banco Mundial se presenta la tasa
de incidencia de la pobreza, en relación a la base de la línea de pobreza nacional (% de la
población) para el periodo 2004 – 2019

Donde precisa que la tasa de incidencia de la pobreza entre 2004 y 2019 se redujo en
38.5%. señala también que el principal periodo de reducción fue entre 2004 y 2011.
Los años 2002 a 2016 la tasa de pobreza bajo de 54,30% a 20,7% y la extrema
pobreza de 24.2% a 3.8%, ya que, en los gobiernos de Alejandro Toledo, Alan García y
Ollanta Humana la tasa de pobreza se redujo en 5,2%, 21,4%, 7,03% y la extrema pobreza en
10,4%, 7,5%; 2,54%, respectivamente, llegando para el año 2018 con 20,50% de pobreza y
2,8% de extrema pobreza, con predisposición a seguir descendiendo.
La tasa de pobreza pasó de 54% en 1990 a 20,50% para 2018 y la extrema pobreza de
24.2% a 2.8% en el mismo periodo de años, reduciéndose significativamente la pobreza y
extrema pobreza en 33,5% y 21.4% respectivamente; esto como consecuencia del crecimiento
económico sostenido, lo cual implicó un aumento del gasto social, aumento de la inversión
pública y una mejora en la calidad y focalización de los programas sociales.
En los periodos 2001 a 2010, la pobreza decreció en 23,5 puntos porcentuales, al pasar
de 54,8% a 31,3% en el 2010.

Mientras que en año 2017, 6 millones 906 mil de personas (21,7%), se encontraban en
situación de pobreza, lo que significa que estas personas tenían un nivel de gasto por debajo
del costo de la canasta básica de consumo. Comparando este resultado con los niveles del año
2016, se puede observar que la tasa de pobreza ha aumentado en 1,0%, equivalente a 375.000
pobres, más que en 2016.

En 2019, el índice de pobreza monetaria afectó al 20,2% de la población del país,
manteniendo casi el mismo nivel que en 2018; Así lo publicó el INEI, de acuerdo con los
resultados de la Encuesta Nacional de Hogares (ENAHO) 2019. También señaló que la población en pobreza es considerada la población promedio. el gasto está por debajo del valor de la línea de pobreza (PL), el equivalente monetario de una canasta de productos básicos y alimenticios.

Cuando se habla de pobreza también se hace referencia a la desigualdad social; un
grupo social que es excluido ya que no cuenta con el mismo acceso a los recursos que otros
grupos con poder si tienen, estas diferencias están marcadas con claridad entre las zonas
urbanas y rurales.
La aplicación errada de políticas públicas ha pronunciado aún más las diferencias, ya
que no se ha permitido una integración de la multiculturalidad con la que cuenta el Perú, y
muy por el contrario ha ocasionado un marcado distanciamiento entre ellos.
En un contexto de crecimiento económico sostenido, es necesario mejorar la
formulación y aplicación de las políticas del país, en objetivos puntuales de desarrollo y
asistencia social con el firme objetivo de combatir la pobreza a largo plazo mejorar los
estándares de vida de su población en conjunto.

## 1.2. Formulación del problema

### 1.2.1. Problema general
¿Cómo la desigualdad socioeconómica determina el grado de pobreza en el
departamento de Ayacucho, periodo 2000-2019?

### 1.2.2. Problemas específicos
¿Cuál es la influencia del empleo en el IDH en el departamento de Ayacucho, periodo
2000-2019?
¿Cuál es la incidencia del índice de Theilen en la determinación de grado de pobreza en
el departamento de Ayacucho, periodo 2000-2019?
¿Como el desempleo influye en el índice de Gini en el departamento de Ayacucho,
periodo 2000-2019?

# II. OBJETIVOS

## 2.1. Objetivo general
Establecer cómo de la desigualdad socioeconómica incide en la pobreza en el
departamento de Ayacucho, periodo 2000-2019.

## 2.2. Objetivos específicos
Analizar cómo el empleo influye en el Índice de Desarrollo Humano en las zonas rurales
de Ayacucho.
Determinar cuánto el Índice de Theilen influye en el Grado de pobreza.
Identificar de qué manera el desempleo determina el índice de Gini en el departamento
de Ayacucho.

# III.JUSTIFICACIÓN

## 3.1. Justificación teórica
La pobreza es un problema mundial que se ha venido combatiendo a lo largo de los
años, cada país en forma individual ha implementado medidas y políticas con el único fin de
reducir su nivel de pobreza o extrema pobreza. En caso particular de Perú, a pesar de los
índices favorables en la reducción de la pobreza, en determinadas zonas se observa un margen
significativo en la desigualdad socioeconómica el cual es paralelo al índice del nivel pobreza.

Es importante analizar el comportamiento de los índices de pobreza contrastado con
indicadores de la desigualdad socioeconómica; para así poder establecer efectividad o
importancia a lo largo del tiempo. Crear conocimiento dentro de la relación establecida entre
estos indicadores, de manera que se contraste con la teoría económica ya conocida o se
generen nuevos aportes.

## 3.2. Justificación practica
Este trabajo tiene una justificación practica porque con él podrá ser posible su
aplicación a la realidad para poder hacer frente a la desigualdad socioeconómica que
predomina en distintas regiones en particular y sobre todo hacer frente a la pobreza que tanto
sufrimiento ocasiona a una gran parte de la población peruana.

Los resultados de la presente investigación podrán aportar a ver mejor el panorama del
país y con él se podrán diseñar estrategias de políticas públicas con los que en un mediano
plazo podamos obtener resultados más eficaces en la reducción de la pobreza y la desigualdad
socioeconómica en el Perú; además del gran aporte que significara para la toma de decisiones
a nivel de gobierno.

## 3.3. Justificación metodológica
Para realizar la investigación sobre la influencia de la desigualdad socioeconómica en
la pobreza se empleará el método hipotético deductiva, es decir, iremos de los general a lo
particular; primero se hará una visión general de la desigualdad socioeconómica y de la
pobreza de la región Latinoamérica para posteriormente, estudiar el caso particular de Perú.

# IV. MARCO TEÓRICO

## 4.1. Marco histórico

### 4.1.1. Enfoque Subjetivo
De La Piedra (1984), afirma que la pobreza subjetiva “significa considerar que
cualquier individuo o familia puede opinar sobre qué tan bien se están satisfaciendo sus
necesidades básicas, en otras palabras, sobre el grado al cual ella misma piensa que sus
medios les sirven para alcanzar sus fines”. Por tanto, de acuerdo a este juicio se le considera
pobre o no pobre.

### 4.1.2. Enfoque Relativo
Según Townsend (1962), en su enfoque de la privación relativa, “se concibe un umbral
del ingreso, de acuerdo con el tamaño y el tipo de familia, por debajo del cual el abandono o la
exclusión de la membresía activa de la sociedad se acentúa en forma desproporcionada”.

Para Murillo Alfaro (1993), “en el enfoque de pobreza relativa, la felicidad de un
individuo o de una familia no depende de su nivel absoluto de consumo o gasto, sino de su
nivel de logro en las relaciones con otros miembros de la sociedad”. El punto de partida es
buscar un punto de referencia que pueda ser una media o un grupo social específico. Así, la
pobreza se define como un estado de necesidades básicas insatisfactorias en relación con la
sociedad.

### 4.1.3. Enfoque absoluto
Sen (1981), enfatiza que “existe un núcleo innegable de privación absoluta en la idea
de pobreza, que conduce a manifestaciones visibles de muerte por hambre, desnutrición y
penuria en un diagnóstico de la pobreza, sin tener que indagar primero en un panorama
relativo”. Por lo cual, la idea de pobreza relativa integra y no reemplaza el enfoque de pobreza
autoritaria.

## 4.2. Marco referencial 
La desigualad socioeconómica es un tema de poca frecuencia y permanente interés.
Según Cotler (2011), en los años de 1960 la forma de pensar sobre la desigualdad
socioeconómica estaba influenciado por la sociología funcionalista - estructuralista, así como
el Marxismo.

Así, se puede decir que, en las ciencias sociales peruanas, dos enfoques que pretenden
ser "gran teoría" han sido muy influyentes desde la década de 1960: el funcionalismo
estructural y el marxismo.

Según Jiménez (2016), la desigualdad es un problema porque afecta a la calidad de
vida de las personas y restringe las capacidades y libertades individuales.

Por tanto, la desigualdad se considera como una externalidad negativa donde las
personas o familias no están dispuestos a tolerar altos niveles de desigualdad. Figueroa,
(2001).

En cuanto a la pobreza, en términos monetarios, alude a la falta de ingresos para poder
cubrir el costo de una canasta básica de consumo; por otro lado, la carencia de ingresos
suficientes "está asociada a la carencia del capital humano necesario para acceder a ciertos
empleos", o a la falta de "capital financiero, tierra y conocimientos gerenciales y tecnológicos
para desarrollar una actividad empresarial", CEPAL (2000).

Si hacemos referencia a un enfoque más complejo, analizamos al premio Noble
Amartya Sen, quien menciona: "la pobreza debe concebirse como la privación de capacidades
básicas y no meramente como la falta de ingresos, que es el criterio habitual con el que se
identifica la pobreza" (Sen, 2000). Además, el autor afirma que "cuanto mayor sea la cobertura
de la educación básica y de la asistencia sanitaria, más probable es que incluso las personas
potencialmente pobres tengan más oportunidades de vencer la miseria" (Sen, 2000).

Otro enfoque para considerar es el de la ya conocida pobreza humana; este enfoque
propuesto por el Programa de las Naciones Unidad para el Desarrollo (PNUD) afirma que "el
concepto de pobreza humana considera que la falta de ingreso suficiente es un factor
importante de privación humana, pero no el único"; por lo tanto, se debe tener en cuenta que
no todo empobrecimiento puede relacionarse únicamente con el ingreso. "Si el ingreso no es la suma total de la vida humana, la falta de ingreso no puede ser la suma total de la privación
humana" PNUD (2000).

Para Mendoza y García (2006), la pobreza puede tener cambios más significativos
manteniéndose un crecimiento económico, pero también es imprescindible el accionar del
Estado en la promoción de equidad de oportunidades de desarrollo de la persona (inversión en
capital humano) el cual, en un largo plazo, mediante el incremento de la productividad,
favorecerá también al crecimiento económico el cual se hará sostenible de forma automática.

Boragina (2006), en su artículo, afirma que existen tres falacias económicas las cuales
en la economía moderna quedan desfasadas absolutamente, él afirma que: la riqueza es
dinámica, la producción y distribución son un único fenómeno y que el valor es el que genera
trabajo; de esta manera, señala que al aferrarnos a las teorías de la economía antigua estamos
perpetuando la pobreza en el mundo.

## 4.3. Sistema teórico 

### 4.3.1. Desigualdad Socio económica y la Pobreza 
Desigualdad socio económica. La desigualdad socioeconómica es un problema
actual, producto del desarrollo desigual entre las diferentes regiones del mundo y la
imposición de ciertas ideologías o definiciones, el precio de unas personas en relación con
otras. De hecho, la desigualdad socioeconómica está en la raíz de la discriminación, ya que la
desigualdad incluye un trato diferente de quienes se encuentran en desventaja económica,
social o moral.

La Pobreza. Las Naciones Unidas (2021), afirma que “la pobreza va más allá de la
falta de ingresos y recursos para garantizar medios de vida sostenibles. Es una cuestión de
derechos humanos”. Entre las diferentes manifestaciones de la pobreza se encuentran: el
hambre, la desnutrición, la falta de una vivienda digna y el acceso limitado a otros servicios
básicos como la salud o la educación.

Para el BID “la pobreza es la privación de bienestar, entendiendo el bienestar un
concepto bastante complejo y amplio, y su nivel más básico abarca aspectos como la
alimentación, vestido, salud, y vivienda”

Mientras para el Banco Mundial (2018), “la pobreza no solo implica falta de ingresos
y consumo: también se manifiesta por bajos niveles de educación, resultados insatisfactorios
en salud y nutrición, falta de acceso a servicios básicos.”

Según INEI, (2007) “la pobreza se define como un grupo de personas que no alcanzan
un nivel mínimo de satisfacción para una serie de necesidades básicas relacionadas con la
salud, la nutrición, la educación, la vivienda y otros.”

### 4.3.2. Empleo e Índice de Desarrollo Humano (IDH) 
### 4.3.3. Índice de Theilen y grado de pobreza
### 4.3.4. Desempleo e Índice de Gini

## 4.4. Marco conceptual 
### 4.4.1. Desigualdad socioeconómica 
### 4.4.2. La Pobreza 
### 4.4.3. Empleo 
### 4.4.4. Índice de Desarrollo Humano (IDH) 
### 4.4.5. Índice de Theilen 
### 4.4.6. Grado de pobreza
### 4.4.7. Desempleo 
### 4.4.8. Índice de Gini

# V. HIPÓTESIS
## 5.1. Hipótesis general
La desigualdad socioeconómica determina negativamente el grado de pobreza en el
departamento de Ayacucho, periodo 2000-2019.

## 5.2. Hipótesis especifica 
El empleo afecta inversamente al IDH en el departamento de Ayacucho, periodo
2000-2019.

El índice de Theilen se relaciona directamente al grado de pobreza en el departamento
de Ayacucho, periodo 2000-2019.

El desempleo influye directamente en el índice de Gini en el departamento de
Ayacucho, periodo 2000-2019.

# VI.VARIABLES E INDICADORES 

## 6.1. Desigualdad socio-económica y dimensiones 

### 6.1.1. Variable causa 
X= Desigualdad socioeconómica
Indicadores:
Empleo
Índice de Theilen
Desempleo

### 6.1.2. Variable efecto 
## 6.2. Operacionales de variables y dimensiones 

# VII.METODOLOGÍA

## 7.1. Tipo y nivel de investigación 
Por el tipo de investigación, la presente investigación reúne las condiciones
metodológicas de una investigación longitudinal según el alcance temporal investigación
aplicada, en razón que se utilizaron conocimientos de las ciencias económicas a fin de
aplicarlas en desigualad socioeconómica y la pobreza en el departamento Ayacucho, periodo
2000-2019.

### 7.1.1. Tipo de investigación 
De acuerdo a la naturaleza del estudio de la investigación reúne por su nivel las
características de un estudio descriptivo explicativo y correlacional.

### 7.1.2. Nivel de investigación 

## 7.2. Población y muestra

### 7.2.1. Población 
Según Córdova (2006), la población o universo es la totalidad de personas u objetos
que tienen una o más características medibles o contables de naturaleza cualitativa o
cuantitativa.

Para Hilario (2020), la población es un conjunto de elementos que posee
características similares.

### 7.2.2. Muestra
## 7.3. Fuentes de información 
Los datos usados son de nivel secundario, es decir, son datos ya procesados. Se ha
recurrido a la información brindada por las páginas del INEI y BCRP, pues son las
instituciones que han venido desarrollando diferentes encuestas y estudios a lo largo de los
años y han consignado datos fidedignos los cuales pueden emplearse en todo tipo de
investigación que lo requiera.

## 7.4. Diseño de investigación
Para el diseño de nuestra investigación emplearemos un tipo de investigación no
experimental, el cual a su vez es longitudinal porque nuestra variable se estudia para
determinar o evolución en el tiempo.

## 7.5. Técnicas e instrumentos
### 7.5.1. Técnicas 
Las principales técnicas que se utilizaran en esta investigación para el análisis de series
de tiempo son:

Las metodologías econométricas y

estadística inferencial

### 7.5.2. Instrumentos 

Los principales instrumentos que se aplicarán en las técnicas son:

Stata

Excel

Eviews

# VIII. REFERENCIAS BIBLIOGRÁFICAS

# CONCLUSIONES
1. Nam dui ligula, fringilla a, euismod sodales, sollicitudin vel, wisi. Morbiauctor lorem
non justo. Nam lacus libero, pretium at, lobortis vitae, ultricies et,tellus. Donec aliquet,
tortor sed accumsan bibendum, erat ligula aliquet magna,vitae ornare odio metus a mi.

2. Nam dui ligula, fringilla a, euismod sodales, sollicitudin vel, wisi. Morbiauctor lorem
non justo. Nam lacus libero, pretium at, lobortis vitae, ultricies et,tellus. Donec aliquet,
tortor sed accumsan bibendum, erat ligula aliquet magna,vitae ornare odio metus a mi.

3. Nam dui ligula, fringilla a, euismod sodales, sollicitudin vel, wisi. Morbiauctor lorem
non justo. Nam lacus libero, pretium at, lobortis vitae, ultricies et,tellus. Donec aliquet,
tortor sed accumsan bibendum, erat ligula aliquet magna,vitae ornare odio metus a mi.

# RECOMENDACIONES
1. Nam dui ligula, fringilla a, euismod sodales, sollicitudin vel, wisi. Morbiauctor lorem
non justo. Nam lacus libero, pretium at, lobortis vitae, ultricies et,tellus. Donec aliquet,
tortor sed accumsan bibendum, erat ligula aliquet magna,vitae ornare odio metus a mi.

2. Nam dui ligula, fringilla a, euismod sodales, sollicitudin vel, wisi. Morbiauctor lorem
non justo. Nam lacus libero, pretium at, lobortis vitae, ultricies et,tellus. Donec aliquet,
tortor sed accumsan bibendum, erat ligula aliquet magna,vitae ornare odio metus a mi.

3. Nam dui ligula, fringilla a, euismod sodales, sollicitudin vel, wisi. Morbiauctor lorem
non justo. Nam lacus libero, pretium at, lobortis vitae, ultricies et,tellus. Donec aliquet,
tortor sed accumsan bibendum, erat ligula aliquet magna,vitae ornare odio metus a mi.


## R Markdown

This is an R Markdown document. Markdown is a simple formatting syntax for authoring HTML, PDF, and MS Word documents. For more details on using R Markdown see <http://rmarkdown.rstudio.com>.

When you click the **Knit** button a document will be generated that includes both content as well as the output of any embedded R code chunks within the document. You can embed an R code chunk like this:

```{r cars}
summary(cars)
```

## Including Plots

You can also embed plots, for example:

```{r pressure, echo=FALSE}
plot(pressure)
```

Note that the `echo = FALSE` parameter was added to the code chunk to prevent printing of the R code that generated the plot.
