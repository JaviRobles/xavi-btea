#Secuencia del Gen del _Homo sapiens_

***por Javier Robles***

---
 



*A continuacion se muestra una pagina web con todo el procedimiento en Jupyter de lo que hicimos para crear el blast con un gen de interes de homo sapiens vs la base de datos del geoduck*



#Proceso:

###Nos ubicamos en el folder que vamos a trabajar


![foto1](1-pwd.png)
---

###Enlistamos los archivos que tenemos en nuestro folder query dos directorios arriba del que estamos trabajando 
por eso ponemos (../..) para subir.
####En este directorio tenemos nuestro gen de interés o problema a analizar.

![foto2](2-lista-de-archivos.png)
---

###Muestra el encabezado de nuestra secuencia problema o de interés.
Es para asegurarnos que tenemos la correcta.
*Nótese que es un archivo .fasta*

![foto3](3-encabezado-de-tu-secuencia.png)
---

###Enlista las bases de datos con las que vamos a comparar nuestra muestra problema. 
Seleccionaremos la "Geo_male"


![foto4](4-enlista-bases-datos.png)
---
###Blastea y genera un archivo de salida en la carpeta "out" del folder "blast"

![foto5](5-blast-secuencia-out.png)
---
###Muestra todo tu archivo .out generado

![foto6](6-muestra-out.png)
---

###Selecciona una secuencia de interés para analizarla individualmente
![foto7](7-selecciona-secuencia.png)
---
###grep nos permite agarrar/mostrar solamente las primeras 6 lineas del archivo .out
comando (-A6)

![foto8](8-agarra.png)
---
