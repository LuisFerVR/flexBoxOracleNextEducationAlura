# Documentación curso de flexbox en OracleNextEducationAlura

## Tecnologías:
![Static Badge]( https://img.shields.io/badge/CSS-blue)
![Static Badge]( https://img.shields.io/badge/HTML-black)
![Static Badge]( https://img.shields.io/badge/JS-yellow)

## Descripción del proyecto:
Este proyecto tuvo como objetivo reforzar los conocimientos adquiridos medinate el curso de FlexBox a cargo de Alura Latam y Oracle One Next Education.
Aquí podrás encontrar el link de diseño en figma, link de proyecto raiz en github y link de la páina desplegada.
## Despliegue:

Podrás observar el trabajo realizado con flexbox en el siguiente enlace:

:rocket:[Abrir sitio web](https://luisfervr.github.io/flexBoxOracleNextEducationAlura/):rocket:

## Dev-Notes:

### FlexBox
            <p>.clase{
                    display: flex; Establece que el elemento usa Flexbox <br>
                    justify-content: property; Define la distribución del contenido <br>
                    align-item: center; alinea elemntos dentro del contenedor <br>
                    position:fixed; Define que sea estático el elemnto en la pantalla <br>
                    top:0%; define en donde se posicione.
                }
            </p>
### Media
` @media (break-point){Estilos a ejecutar a partir de que se cumpla}`
`display: flex `Hace que el contenedor se expanda ocupando todo el ancho del diseño (observa el fondo negro que ocupa todo el ancho disponible), de esta manera, los otros contenedores con el mismo valor de display se colocan uno debajo del otro, en dirección vertical. En cambio, `display: inline-flex` utiliza las mismas características de visualización que display: inline, mostrando los elementos en línea, en horizontal, sin ocupar todo el ancho del diseño.</p>
        
### Mobile first
Para acomodar un footer bajo esta técnica:

`flex-wrap:column wrap;`Acomoda primero en una columna todo y después va expandiendolas conforme a tamaño.
`white-space:nowrap;`Hace que le contenido del texto quede en una sola línea.
`overflow:scroll` Coloca una barra de deslizamiento.
`gap:15px`Asigna un espaciado entre elemntos en la misma fila.
`La propiedad align-self es una propiedad de flex-item.`Este tipo de propiedad se aplica a los elementos que deseas alinear, y no al elemento padre flex-container.
Lo primero que se debe hacer para utilizar esta herramienta es cambiar el valor del atributo display de un elemento a display: flex. De esta manera, convertimos ese elemento en un flex-container, y sus elementos hijos pasan a ser flex-item.
`flex-grow: 1;`Se utiliza para expandir elementos proporcionalmente según el espacio disponible en un contenedor,con 1 significa que todos deben estar proporcionales
`flex-wrap: wrap;` Define que los items  se puedan ajustar en diferentes filas y columnas
`flex-shrink`Es ideal para aplicar cuando queremos reducir el tamaño de los elementos a medida que su contenedor disminuye en anchura. Cuanto mayor sea el valor, más se reducirá este elemento en comparación con sus elementos hermanos.
