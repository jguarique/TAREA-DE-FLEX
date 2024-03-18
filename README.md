# TAREA-DE-FLEX

#1 Que es el modelo de caja en flexbox?

En flex box el modelo de caja es flexible, es una opción mas eficiente
para crear diseños en los que nuestro tamaño y orden sea más dinámico y permitiendo una alineación
de elementos mucho más ampliada.

2# Propiedades que definen el modelo de caja en flexbox.

Principalmente las propiedades que definen el modelo de caja en flexbox son:

Flex-direction: el cual se le pueden aplicar cuatro valores que definen el orden posicional
de nuestros elementos. 

row

row-reverse

column

column-reverse

3# Como se diferencia el modelo de caja de flexbox con el modelo de caja de CSS Tradicional?

En el modelo de caja de CSS tradicional podemos editar unicamente los margenes y rellenos que disponen nuestros elementos, mientras
que en flexbox podemos alinear, separar, y ordenar según nuestra necesidad.

4# Que es el overflow en flexbox?

El  overflow es cuando hay demasiado contenido en una caja, y no cabe cómoda o completamente dentro de ella.

5# Como se puede controlar el overflow en flexbox?

En este caso lo que podriamos hacer es modificar la propiedad "overflow" que por defecto tiene el valor visible y colocar
un valor de "hidden", de esta manera ese contenido que está sobrando en la caja se ocultará automaticamente.

6# Qué diferencia hay entre "overflow" y "text-overflow"?

Overflow se encarga de ocultar el contenido que sobra, text-overflow es una propiedad que ayuda al usuario
a saber en que punto se encuentra ese corte de contenido colocando por ejemplo un elipsis "...". 

7#Qué propiedades de posición se pueden utilizar en flexbox?

En flexbox tenemos por defecto la posicion "static", tambien podemos utilizar "absolute" "fixed" 
"relative y "sticky"

8# Cómo se puede centrar un elemento con position: absolute en Flexbox?

Para centrar un elemento con position lo mas sencillo es despues de aplicar la position en "absolute" es
agregarle un "inset" de 0 a nuestro elemento.

9# En qué se diferencian position: absolute, relative y fixed en Flexbox?

La position absolute no está dentro del flujo de la página, toma como referencia la ventana del elemento
posicionado, relative es un valor que está dentro del flujo de la página, es decir, su posición será con referencia
a su posición por defecto y fixed toma como referencia la ventana del navegador y no respetan el tener un contenedor padre que esté posicionado. Además, al hacer scroll en la página, el elemento que esté posicionado seguirá en la misma posición respecto a la ventana del navegador aunque el scroll haya desplazado la página hacia abajo.

10# Qué es el z-index en flexbox? 

El z-index es el orden de apilamiento, quiere decir el orden uno detras del otro o capas en las que se conforma nuestro proyecto.

11# Como usar Z-index?

Usamos z-index: "valor de la capa"

12# Que hay que tener en cuenta para usar z-index?

Principalmente hay que fijarse que el contendor al que vayamos a aplicar z-index no tenga una position "static", y también es recomendable no usar en exceso esta propiedad y ayudarse con otras técnicas de maquetación.











