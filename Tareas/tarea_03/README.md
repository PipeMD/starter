# Bitácora Tarea 03
Lo primero que hice fue definir que es lo que quería colocar en este Currículum Vitae. Ya decidido, inicié Visual Studio Code para poder desarrollar esta página. 

Empecé haciendo un archivo llamado index.html, en el cual pude colocar todo lo necesario para construir la estructura de la página. 

Vale decir que todo lo que está escrito aquí es sin los signos mayor o menor, reemplazados por "__", ya que no se ve dentro del archivo.

### HTML
Para hacer el html, use los contenidos que vimos en clases, como el __!DOCTYPE html__, con el cual se generaban automáticamente el __head__, que contiene los metadatos y el __body__, en el que va el texto. 

Pero faltaban metadatos para empezar a trabajar, empecé colocando el __Favicon__, escribiendo en el index __link rel="shortcut icon"__, con esto ya podía tener un ícono al lado del nombre de mi documento (Currículum Vitae).
Pero faltaba otro que me sería de utilidad más tarde, el cual es el __style__, la función con la que podremos construir el css, por eso coloqué un último metadato escrito así: __link rel="stylesheet" href="style.css"/__
Después use lo que aprendimos en clases para seguir construyendo mi CV en el apartado de __body__, como el __p__ para separar todo en párrafos, el __a__ para hacer hipervínculos, el __h__ para destacar el texto que quería hacer más grande y con la font en negrita, el __img src__ para colocar una foto sobre mi (la cual tuve que achicar usando width y height), el __ol__ para hacer listas ordenadas y el __ul__ para hacer listas no ordenadas.

Pero también use el __header__ para hacer un encabezado en el cual puse mi nombre, además de un __footer__ con el que podía colocar ciertas cosas en la parte de abajo de la página.

En algunas partes coloqué __div__, con los que dividía ciertos segmentos del html para después editarlos en el archivo css. 

Ya listo con todo lo que quería tener en mi página en cuanto a estructura, comencé con el css.

### CSS
Con el css tuve que crear otro archivo llamado style.css. Con el metadato que incluí al inicio (__link rel="stylesheet" href="style.css"/__) vincule el index.html con este style.css, con el fin de no colocar las funciones dentro de mi index y que se viera un poco más ordenado.

En este archivo, cambié el color del fondo de la página y la tipografía, usando:

body {
     background-color: beige; 
     font-family: Arial, Helvetica;
}

Con esto, el fondo pasó a ser de color beige y la tipografía es de Arial y/o Helvética, dependiendo de las fuentes que se tengan instaladas.

Usando uno de los __div__ que puse, seleccione un segmento con __id__, en donde quería que mi header ocupe más tamaño del que tenía, por lo que escribí la siguiente función:

#container{
    max-width: 70%;
    margin: 0px auto; 
}

Con eso mi header ocupa un mayor ancho de la página.

Siguiendo lo anterior, quería que una parte de mi contenido que ya tenía dividido ocupara un mayor ancho y estuviera en la parte derecha de la pantalla, por lo que hice la selección del segmento con __class__ y escribí lo siguiente:

.content{
    width: 70%;
    margin: 0px auto;
    float: right;
}

Con esto, parte de mi contenido ocupa un mayor ancho en la pantalla y estará "flotando" en la derecha de la página.

Por último, el contenido que tenía dentro del __footer__ aparecía muy grande y al lado izquierdo de la página, lo cual me parecía feo, por lo que dentro del ccs escribí esto:

footer{
    font-size: small ;
    text-align: center;
}

Con esto, el tamaño de la tipografía será pequeño y el texto estará en el centro de la página.

### Creación Página
Aquí tuve problemas, ya que en un principio intente hacer todo en el mismo repositorio que he usado siempre, poniendo todo el contenido en una carpeta /docs. Lamentablemente, al momento de crear la página en github me daba un error, por lo que tuve que recurrir a otro método.

Otro problema menor que tuve fue el hecho de que no se veía ni el Favicon ni la foto que tenía dentro de la página, pero era porque estaba copiando mal la ruta. Así que subí la foto sola al lado del index y el style y ahora si se podían ver las fotos. 

Cree otro repositorio que se llama Currículum--Vitae, en donde volvi a subir los archivos pero sin usar una carpeta /docs. Aquí estaba buscando los archivos en el /root, lo cual me sirvió y pude crear la página.

La página se puede ver mejor desde un computador, ya que desde el celular el contenido dentro se corre hacia abajo y no queda como deseaba. 

https://pipemd.github.io/Curriculum--Vitae/
