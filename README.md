# Asix1M4UF1_A3Apuntes

Primer repositorio de ejemplo en ASIX 2024

###### Primer Capitulo: Markdown.

Este texto esta en *cursiva*

Este texto esta en _cursiva_
Este texto esta en **negrita**
Este texto esta en __cursiva__
Este texto esta en _**negrita y cursiva**_

1. Primera Opcion de menu
2. Segunda Opcion de menu
3. Tercera Opcion de menu

* Primera opcion de lista desordenada
* Segunda opcion de lista desordenada
- Tercera opcion de lista desordenada
    1. Primer submenu
    2. Segundo submenu
- Cuarta opcion de lista desordenada
    3. Tercer submenu
    4. Cuarto submenu
+ Quinta opcion de lista desordenada
+ Sexta opcion de lista desordenada





```
<html>
    <head>
    </head>
    <body>
        <p>Esto es un parrafo<p>
    </body>
</html>
```

[Esto es un enlace](https://joan23.fje.edu "Enlace a la web del cole")

![Esto es una imagen](https://github.com/CarlosMilanDiaz/Asix1M4UF1_A3Apuntes/blob/main/descarga%20(2).png "Titulo opcional de la imagen")
|Primera Col.|Segunda Col.|3 Col|
|---------------|:------------:|------------:|
|Col 2 es|Centrada|35€|
|Estilo Cebra|Gris|Blanco|
|Clase|ASIX|M4|

-[ ] Opcion A

-[X] Opcion B

-[ ] Opcion C

######Segundo Capitulo:HTML

En un lenguaje de marcas empieza con una etiqueta que se escribe entre <> y para marcar o decir que acaba se escribe la misma etiqueta pero con una barra delante </>.

La sintaxi basica es,  basicamente es , etiqueta atributo y información del atributo.
Aqui definimos el tipo de pagina que hacemos para decirselo al navegador <!DOCTYPE html>

Aqui definimos el idioma <html lang="en">

Justo aqui empieza el encabezado de datos  <head>

En la  linea indica el set de caracteres. <meta charset="UTF-8">
Esto es para el ancho y demas de la pagina <meta name="viewport" content="width=device-width, initial-scale=1.0">

En la linea de codigo es donde se pone el titulo que saldrá arriba en la pestaña de la pagina1 <title>Document</title>
y aqui acaba el encabezado como siempre acaban las etiquetas de una pagina con la barra"/" </head> justo aqui empieza el body, que es el cuerpo de la pagina  <body> estas etiquestas són las de un parrafo, el cual se abre sin / y se cierra con ella escrita. <p> </p>

El order list es una lista ordenada en el que abre con ol, y acaba con /ol, la cual cada elemento interno de la lista es un <li> y como dice su nombre esta ordenada con un numero al principio.

    <li>como este por ejemplo que abre con li, y como todas las etiquetas se cierran con /.</li>
    <li>aqui hay otro elemento de la lista</li>
    <li>y aqui el tercer elemento</li>    
</ol>y ya aqui cerramos el order list```
La parte de ol se puede hacer como Unorder list(ul) y en vez de ser numeros te lo ponen con puntos.
Por si se quiere hacer una lista dentro de otra lista seria lo mismo, haciendo un ol, con la otra lista añadida identada y aqui tenienes un ejemplo:
1
    1.1.Nivell1
    1.2.Nivell2
La etiqueta <br>: sirve para dar un salto o espaciado
La etiqueta <a>: sirve para crear un enlace a otras páginas web, archivos o ubicaciones dentro de la misma página. El atributo <href> se utiliza para especificar la URL de destino del enlace.El atributo <alt> sirve para canviar el nombre cuando te pones encima.
Aqui un ejemplo
<a href="google"alt="Esto es un enlace ">Texto de ejemplo</a>
<hr>sirve para poner una linea horizontal para hacer un cambio de seccion<hr>
Esta etiqueta es una cita, (esto es una cita) <blockquote></blockquote>
Para mostrar una imagen es , la etiqueta img, con la ruta de donde se saca la imagen, 
<img src="https://github.com/CarlosMilanDiaz/Asix1M4UF1_A3Apuntes/blob/main/nationalgeographic_1468962.jpg">
Para usar un icono de una web como por ejemplo fontawesome hay que linkear en el head el <script src="https://kit.fontawesome.com/06d159bd36.js" crossorigin="anonymous"></script> Escribimos este link/script que nos ha dado la pagina para poder enlazar nuestra pagina para enlaza y linkear cosas de esta, como poer ejemplo podriamos poner para poner un icono o una fuente lo siguiente:<i class="fa-solid fa-dog">codigo enlazado desde fontawesome</i>
Para poner una foto se pone <img src="(ubicacion de la foto)" alt="Imagen de planeta"> para ir a alguna parte dentro de la propia pagina añadir un id a la parte qu queramos ir a ver(el destino) añadimos por ejemplo un titulo que queremos que sirva como enlace para ir a ver el destino(origen)
    Si queremos poner una tabla ponemos los siguiente:
 <thead>
        <tr>
            <th>123</th>
            <th>234</th>
            <th>345</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <th>qwe</th>
            <th>wer</th>
            <th>ert</th>
        </tr>
    </tbody>
    <tfoot>

    </tfoot>
</table>```

Table es la etiqueta de la tabla general, tr son las filas en la que escribirmos th por cada columna que quieras poner con loa datoa a mostrar, si quieres puedes poner un thead o tfoot para hacer un encabezado o un pie de tabla, sino si solo se quiere hacer una tabla sin nada mas, se hace en el tbody.
</body>
</html>

######Tercer Capitulo:CSS

3 formas de insertar css

1. Insertar en la propia etiqueta
2. Añadir en el head de la pagina el link de enlace
3. Archivo externo

Si solo se quiere poner algo exclusivamente en una parte se puede hacer individualmente.

Las hojas css/ archivo externo, sirve para todas las paginas de todo el sitio web.


En una tabla, se pone el atributo style en la etiqueta, se compone por declaraciones:valor
ejemplo: style="text-align: center;color: red;"
esto hace que la tabla o la columna por ejemplo se ponga la letra de color rojo, y la alineación del texto en el centro.

Los colores es pueden poner con la combinacion en exadecimal y en rgb, que seria el siguiente formato(255,255,255), se pone como maximo de cada valor en 255, el minimo es 0, y para hacer los colores se combinan.
ejemplo, si queremos poner en rgb el azul puro se pone (0,0,255), o si queremos el rosa seria (255,0,255).


Para modificar un unico elemento como por ejemplo una fila, pero que no se me cambien todas las filas creamos en la fila un atributo que se llama "id" que es un identifiacador unico, y modificar ese id, por ejemplo si el id="PrimeraFila" , para nombrarla y editarla se escribe  #PrimeraFila{y aqui dentro los cambios que se quieran hacer}.

En caso que se quieran cambiar un grupo de partes de la pagina, se escribe en ved de "id", se escribe "class" que para hacer la referencia en vez de poner # como en id, se pone un "." delante del nombre de la clase.
class--> .clasetextoazul
id-->   #identificadorazul
Aui pongo un ejemplo de como seria:
```
.clasetextoazul{
    color:blue;
}
#identificadorazul{
    color:blue;
}
```

Para seleccionar a todo el documento se hace una edición total con el simbolo "*".
Por ejemplo:
```
*{
    color: blue;
}
```



Hijos y padre para dar formato:
Si solo quiero que afecte a hijos que son por ejemplo strong de un li.
Se pondria en el css asi:
```
li > strong{
    y lo que queramos editar.
}
```
Tambien si queremos afectar a dos clases
Por ejemplo:
```
h2 h1{
    color:red;
    text-align:center;
}
```
######Cuarto Capitulo : Responsive

El diseño web responsive o adaptativo es una técnica que busca la correcta visualización de una misma página en distintos dispositivos, desde ordenadores de escritorio hasta tablets y móviles
Redimensionamiento y colocación de elementos: El diseño responsive ajusta los elementos de una página para adaptarse al ancho de cada dispositivo, permitiendo una mejor experiencia de usuario. Los layouts y las imágenes son fluidos, y se utiliza código media queries de CSS para lograrlo.
Asegurate de que todos los elementos HTML tengan la box-sizing propiedad establecida en border-box.Sirve para asegura que el relleno y el borde estén incluidos en el ancho y alto total de los elementos.

