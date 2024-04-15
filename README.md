<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Documentación curso de flexbox en OracleNextEducationAlura</title>
</head>
<body>
    <div>
        <div>
            <h2>FlexBox</h2>
            <p>.clase{
                    display: flex; Establece que el elemento usa Flexbox <br>
                    justify-content: property; Define la distribución del contenido <br>
                    align-item: center; alinea elemntos dentro del contenedor <br>
                    position:fixed; Define que sea estático el elemnto en la pantalla <br>
                    top:0%; define en donde se posicione.
                }
            </p>
        </div>
        <br>
        <div>
            <h2>Media</h2>
            <p>@media (break-point){Estilos a ejecutar a partir de que se cumpla}</p>
        </div>
    </div>
    <div>
        <p><strong>display: flex </strong>hace que el contenedor se expanda ocupando todo el ancho del diseño (observa el fondo negro que ocupa todo el ancho disponible), de esta manera, los otros contenedores con el mismo valor de display se colocan uno debajo del otro, en dirección vertical. En cambio, <strong>display: inline-flex</strong> utiliza las mismas características de visualización que display: inline, mostrando los elementos en línea, en horizontal, sin ocupar todo el ancho del diseño.</p>
    </div>
    <div>
        <h1>mobile first</h1>
        <div>
            <p>para acomodar un footer bajo esta técnica:</p>
            <p><strong>flex-wrap:column wrap;</strong> Acomoda primero en una columna todo y después va expandiendolas conforme a tamaño.</p>
        </div>
        <div>
            <p><strong>white-space:nowrap;</strong> Hace que le contenido del texto quede en una sola línea.</p>
            <p><strong>overflow:scroll</strong> Coloca una barra de deslizamiento</p>
            <p><strong>gap:15px</strong>asigna un espaciado entre elemntos en la misma fila</p>
        </div>
        <div>
            <p>
                <stronge>La propiedad align-self es una propiedad de flex-item.</stronge>
                 Este tipo de propiedad se aplica a los elementos que deseas alinear, y no al elemento padre flex-container.
            </p>
            <br>
            <p>Lo primero que se debe hacer para utilizar esta herramienta es cambiar el valor del atributo display de un elemento a display: flex. De esta manera, convertimos ese elemento en un flex-container, y sus elementos hijos pasan a ser flex-item</p>
        </div>
        <div>
            <p>
                <stronge>flex-grow: 1;</stronge>
                Se utiliza para expandir elementos proporcionalmente según el espacio disponible en un contenedor,con 1 significa que todos deben estar proporcionales
            </p>
        </div>
        <div>
            <p>
                <stronge>flex-wrap: wrap;</stronge>
                Define que los items  se puedan ajustar en diferentes filas y columnas
            </p>
        </div>
        <div>
            <p>
                <stronge>flex-shrink</stronge>
                Es ideal para aplicar cuando queremos reducir el tamaño de los elementos a medida que su contenedor disminuye en anchura.
            </p>
            <p>cuanto mayor sea el valor, más se reducirá este elemento en comparación con sus elementos hermanos.</p>
        </div>
    </div>
</body>
</html>