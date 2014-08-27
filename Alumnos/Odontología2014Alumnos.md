# Alumnos - Odontología 2014
## Descripción
Aquí presentamos los resultados de las encuestas de `evaluación institucional` llevada a cabo en julio del 2014 en la que se recabaron datos de los `alumnos de la Carrera de Odontología` de la Facultad de Ciencias de la Salud (Sede Asunción) de la Universidad del Norte. La encuesta consistió en un formulario de `91 preguntas` evaluando cada una de las siguientes dimensiones:

* __Dimensión 1: Organización & Gestión__
    * 1.1: Organización
    * 1.2: Gestión
* __Dimensión 2: Proyecto Académico__
    * 2.1: Objetivos de carrerra y Perfil de Egreso
    * 2.2: Plan de estudios
    * 2.3: Proceso enseñanza-aprendizaje
    * 2.4: Evaluación del proceso enseñanza-aprendizaje
    * 2.5: Investigación y extensión
* __Dimensión 3: Personas__
    * 3.1: Directivos
    * 3.2: Docentes
    * 3.3: Estudiantes
    * 3.4: Personal administrativo y de apoyo
* __Dimensión 4: Recursos__
    * 4.1: Infraestructura, equipamientos e insumos

El formulario de encuesta también incluyó preguntas acerca del `Curso` (1er., 2do., 3er y 4to y 5to cursos). Se obtuvieron `193` formularios de respuestas, los cuales fueron cargados en una base de datos en formato `.csv` para su análisis estadístico. Los datos fueron preprocesados y analizados con [R](http://www.r-project.org) versión 3.1.0. Este documento fue redactado utilizando MarkDown en [RStudio](http://www.rstudio.com) versión 0.98.501 y el paquete [knitr](http://cran.r-project.org/web/packages/knitr/index.html) versión 1.6 de [Yihui Xie](http://yihui.name/knitr).


```r
# Establecemos las opciones globales
require(knitr)
opts_chunk$set(echo = FALSE, warning = FALSE, message = FALSE, fig.height = 8, fig.width = 13)
```



***

## Resultados
### Distribución por Cursos
![plot of chunk Cursos](figure/Cursos.png) 

***

### Dimensión 1.1 - Organización
![plot of chunk Q11](figure/Q111.png) ![plot of chunk Q11](figure/Q112.png) ![plot of chunk Q11](figure/Q113.png) ![plot of chunk Q11](figure/Q114.png) ![plot of chunk Q11](figure/Q115.png) ![plot of chunk Q11](figure/Q116.png) ![plot of chunk Q11](figure/Q117.png) ![plot of chunk Q11](figure/Q118.png) 

***

### Dimensión 1.2 - Gestión
![plot of chunk Q12](figure/Q121.png) ![plot of chunk Q12](figure/Q122.png) ![plot of chunk Q12](figure/Q123.png) ![plot of chunk Q12](figure/Q124.png) ![plot of chunk Q12](figure/Q125.png) ![plot of chunk Q12](figure/Q126.png) ![plot of chunk Q12](figure/Q127.png) ![plot of chunk Q12](figure/Q128.png) ![plot of chunk Q12](figure/Q129.png) 

***

### Dimensión 2.1 - Objetivos de la carrera y Perfil de Egreso
![plot of chunk Q21](figure/Q211.png) ![plot of chunk Q21](figure/Q212.png) ![plot of chunk Q21](figure/Q213.png) ![plot of chunk Q21](figure/Q214.png) ![plot of chunk Q21](figure/Q215.png) 

***

### Dimensión 2.2 - Plan de Estudios
![plot of chunk Q22](figure/Q221.png) ![plot of chunk Q22](figure/Q222.png) ![plot of chunk Q22](figure/Q223.png) ![plot of chunk Q22](figure/Q224.png) ![plot of chunk Q22](figure/Q225.png) ![plot of chunk Q22](figure/Q226.png) 

***

### Dimensión 2.3 - Proceso enseñanza-aprendizaje
![plot of chunk Q23](figure/Q231.png) ![plot of chunk Q23](figure/Q232.png) ![plot of chunk Q23](figure/Q233.png) ![plot of chunk Q23](figure/Q234.png) ![plot of chunk Q23](figure/Q235.png) ![plot of chunk Q23](figure/Q236.png) ![plot of chunk Q23](figure/Q237.png) ![plot of chunk Q23](figure/Q238.png) ![plot of chunk Q23](figure/Q239.png) 

***

### Dimensión 2.4 - Evaluación del proceso enseñanza-aprendizaje
![plot of chunk Q24](figure/Q241.png) ![plot of chunk Q24](figure/Q242.png) ![plot of chunk Q24](figure/Q243.png) 

***

### Dimensión 2.5 - Investigación & extensión
![plot of chunk Q25](figure/Q251.png) ![plot of chunk Q25](figure/Q252.png) ![plot of chunk Q25](figure/Q253.png) ![plot of chunk Q25](figure/Q254.png) ![plot of chunk Q25](figure/Q255.png) ![plot of chunk Q25](figure/Q256.png) ![plot of chunk Q25](figure/Q257.png) ![plot of chunk Q25](figure/Q258.png) ![plot of chunk Q25](figure/Q259.png) ![plot of chunk Q25](figure/Q2510.png) 

***

### Dimensión 3.1 - Directivos
![plot of chunk Q31](figure/Q311.png) ![plot of chunk Q31](figure/Q312.png) ![plot of chunk Q31](figure/Q313.png) ![plot of chunk Q31](figure/Q314.png) 

***

### Dimensión 3.2 - Docentes
![plot of chunk Q32](figure/Q321.png) ![plot of chunk Q32](figure/Q322.png) ![plot of chunk Q32](figure/Q323.png) 

***

### Dimensión 3.3 - Estudiantes
![plot of chunk Q33](figure/Q331.png) ![plot of chunk Q33](figure/Q332.png) ![plot of chunk Q33](figure/Q333.png) ![plot of chunk Q33](figure/Q334.png) ![plot of chunk Q33](figure/Q335.png) ![plot of chunk Q33](figure/Q336.png) 

***

### Dimensión 3.4 - Personal administrativo y de apoyo
![plot of chunk Q34](figure/Q341.png) ![plot of chunk Q34](figure/Q342.png) ![plot of chunk Q34](figure/Q343.png) ![plot of chunk Q34](figure/Q344.png) 

***

### Dimensión 4.1 - Infraestructura, equipamientos e insumos
![plot of chunk Q41](figure/Q411.png) ![plot of chunk Q41](figure/Q412.png) ![plot of chunk Q41](figure/Q413.png) ![plot of chunk Q41](figure/Q414.png) ![plot of chunk Q41](figure/Q415.png) ![plot of chunk Q41](figure/Q416.png) ![plot of chunk Q41](figure/Q417.png) ![plot of chunk Q41](figure/Q418.png) ![plot of chunk Q41](figure/Q419.png) ![plot of chunk Q41](figure/Q4110.png) ![plot of chunk Q41](figure/Q4111.png) ![plot of chunk Q41](figure/Q4112.png) ![plot of chunk Q41](figure/Q4113.png) ![plot of chunk Q41](figure/Q4114.png) ![plot of chunk Q41](figure/Q4115.png) ![plot of chunk Q41](figure/Q4116.png) ![plot of chunk Q41](figure/Q4117.png) ![plot of chunk Q41](figure/Q4118.png) ![plot of chunk Q41](figure/Q4119.png) ![plot of chunk Q41](figure/Q4120.png) ![plot of chunk Q41](figure/Q4121.png) ![plot of chunk Q41](figure/Q4122.png) ![plot of chunk Q41](figure/Q4123.png) 

***
