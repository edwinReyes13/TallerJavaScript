<!--lenguaje markdown
objetivo: proporcionar una herramienta para documentar codigo, o aspectos tecnicoa para compartirlos o tenerlos de refenrecia en mi git hub o otra plataforma.

markdown es un lenguaje de marcado ligero 

el objetivo de su creador fue hacer quela gente pudiera escribir usando un formato de texto plano facil de leer
facil de escribir y con la posibilidad de convertir su documento en html valido.

la gran simpleza de su sintaxis hizo que tuviera una rapida adopcion y popularidad en la comunidad de desarrolladores.

actualmente aparte de permitir generar contenido html de forma dinamica, tambien se emplea (casi de forma estandar)
para la creacion de documentacion tecnica y con la proliferacion de la arquitectura JAM Stack para la creacion de sitios estaticos a traves de herramientas de tipo SSG(static site generator) y ssr (sergey side rendering) como hugo, gatsby, eleventy, next js, sergey

conocer sintaxis Markdown

1.-parrafos [parrafo 1...]
Lorem Ipsum es simplemente el texto de relleno de las imprentas y archivos de texto. Lorem Ipsum ha sido el texto de relleno estándar de las industrias desde el año 1500, cuando un impresor (N. del T. persona que se dedica a la imprenta) desconocido usó una galería de textos y los mezcló de tal manera que logró hacer un libro de textos especimen.-->

cursiva
*negrita*
tachado
*cursiva y negrita*
cursiva y tachado
*negrita y tachado*
*cursiva, negrita y tachado*


#     encabezado nivel 1
##    encabezado nivel 2
###   encabezado nivel 3
####  encabezado nivel 4
##### encabezado nivel 5
###### encabezado nivel 6

divisiones

un bloque de contenido
---
este es otro bloque de contenido

listas: podemos utilizar las listas ordenadas y desordenadas

1. html5
1. css
1. javascript
1. ajax
1. json

citas podemos dar formato de cita a un texto, anteponiendo a la linea de texto un caracter de mayor que (>).

la IA en el futuro reemplazara muchas profeciones de TI. -Ad Nasser

chatgpt debe potenciar mi aprendizaje, no suprimir mi estado autodidacta.

Ad Nasser

enlaces 
[youtube](https://www.youtube.com)
[enlace a google](https://www.google.com)

imagenes
![texto alternativo] (URLdelaimagen)

tablas
|columna 1 |columna 2|columna 3|
|----------|---------|---------|
|A         |B        |C        |
|D         |E        |F        |
|G         |H        |I        |

codigo
podemos dar formato de codigo aun texto para ello se usa el cento grave (`).

esto es`codigo` en linea.

en javascript  una variables se define asi:
let saludo = "Hola Mundo";

pero si queremos sacar un bloque completo de codigo utilizamos':
--- js
//Asi se utliza los comentarsios en javaScrip de una consola
console.log("bienbenido al miundo de la programcion frontend con javaScrip")

console.log("esta es otra linia  "+ "Y se concatena el +")

/*
este es un comentario de mas de una linia
*/

/*en javascrp*/

//AHORA vamoos a trabajar con decalaracion de varaibales:
let estudiante="Edwin reyes"
let edad=19
let isEstudiante=true
let calificacion=92.8



console.log("estudiante" + estudiante)
console.log("edad" + edad)
console.log("estudia" + isEstudiante)
console.log(typeof + calificacion)
console.log("el promedio global de estudiante es ${calificacion}")

let val1;
let val2;
    val1=prompt("ingresa un numero");
    val2=prompt("ingrasa el segundo numero");
let num1=parseInt(val1);
let num2=parseInt(val2);
   console.log("la suma es: " + (num1+num2));


/*javaScrip es deblimente  tioeado  esto significa que
no es estricto en la decalracion  de tipos de datos .Es decir no 
fuerza a que inicialmente digas el tipo de dato de la variable */


//estructura 
let Carp=200
----
--- js
// alert("eatamos en el archivo EstructuraCiclo .js")


//Estructura de control while
for(let i=0; i<=10;  i++){
    console.log("no interaccion" + i)
}

// 
let contador=1;

while(contador <10){
    console.log("no interaccion" + contador)
    contador++
}

//control do/while
let num=1;
do{
    console.log("d0/while no inetraccion" + num);
    num ++;
} while(num < 10)

    //for in 
    // bucle itera sobre las propiedades

let estudiante ={ nombre:"Edwin reyes" , edad:18, calificacion: 70}

for (let propiedad in estudiante){
    console.log(propiedad + ": " + estudiante[propiedad])
}
---




<!--esto es un comentario-->