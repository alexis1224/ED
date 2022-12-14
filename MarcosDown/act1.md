# MARKDOWN 

Markdown es un lenguaje de marcado ligero, una forma de agregar formatos como encabezados, negritas, cursivas, listas... a un texto sin formato utilizando un editor de texto simple.Es decir, una forma rápida de coger apuntes con ordenador y pasarlos a limpio en un solo paso.

    - Elementos de bloque
       - Párrafos
       - Saltos de línea
       - Encabezados
       - Citas
       - Códigos de bloque
       - Líneas horizontales
    - Elementos de línea
       - Énfasis
       - Links o enlaces
       - Código
       - Imágenes
    - Otro elementos
       - Links automáticos
       - Omitir Markdown
       - Símbolos matemáticos

# Saltos de bloque (=Párrafos) 

Para generar un nuevo párrafo en Markdown simplemente separa el texto mediante una línea en blanco (pulsando dos veces INTRO). `Ejemplo:`

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut sem viverra aliquet eget sit amet. Morbi quis commodo odio aenean sed adipiscing.


Para generar 


# Slatos de línea (=lineas de texto)

Para realizar un salto de línea y empezar una frase en una línea siguiente dentro del mismo párrafo, tendrás que pulsar **dos veces** la barra espaciadora antes de pulsar una vez INTRO.    `Ejemplo:`

Nombre:  
Apellido:  
Dirección:  

# Encabezados

Las almohadillas o hastag `#` es el método utilizado en Markdown para cerar encabezados. Debes usarlos añadiendo uno por cada nivel y dejando un espacio en blanco. `Ejemplo:`

## Encabezado 2

### Encabezado 3

#### Encabezado 4

##### Encabezado 5

###### Encabezado 6

# Enfatizar: negritas y/o cursivas

Para poner cursivas encierra entre 1 asterisco. Para poner negritas encierra entre 2 asteriscos. Para poner negritas y cursiva encierra entre 3 asteriscos. `Ejemplo:`

Tortor *vitae purus* faucibus **ornare** suspendisse sed. Pulvinar mattis ***nunc sed blandit.*** Ut pharetra sit amet aliquam id

# Líneas horizontales

Para crearlas, en una línea en blanco deberás incluir `tres` de los siguientes elementos: 3 asteriscos, 3 guiones, o 3 guiones bajos. `Ejemplo:`

***

# Citas

Las citas se generan utilizando el carácter mayor que `>` al comienzo del bloque de texto. `Ejemplo:`

>Non pulvinar neque laoreet suspendisse interdum consectetur libero id faucibus. Egestas diam in arcu cursus euismod quis viverra nibh.

# Listas

Para crear listas desordenadas podemos utilizar 3 tipos de simbolos por cada item de la lista: Un asterisco `*`, un guión `-` o un símbolo más `+`. `Ejemplo: `

* Ítem 1
* Ítem 1
* Ítem 1

Para crear listas ordenadas debes utilizar la sintaxis de tipo: `1. `

1. Ítem 1
2. Ítem 1
3. Ítem 1

Para generar listas anidadas (desordenadas u ordenadas) dentro de otras, simplemente tendrás que añadir `dos (o cuatro) espacios en blanco. Ejemplo: `

* Ítem 1
    * Ítem 12
        * Ítem 121
* Ítem 2
  
1. Ítem

# Links o enlaces

Se crean escribiendo la palabra o texto enlazada entre `[]` corchetes, y el link en cuestión entre `()` paréntesis.

Sin texto enlazado escribe la URL entre ángulos `< URL >` Enlace de ejemplo como referencia: [3con14](https://markdown.es/sintaxis-markdown/), y al final del texto escribir la etiqueta seguida de dos puntos.

# Imágenes

Insertar una imagen con Markdown se realiza de una manera idéntica a insertar links. En este caso, debes añadir un simbolo de `!` exclamación al principio y el enlace que es la ubicación de la imagen.

    ![Texto alternativo](ruta/imagen.jpg "Título alternativo")

`Ejemplo:`

![Plato mondongo](foto1.jpg "Mondongo") 
![Mondongo meme](foto2.jpeg "Mondongo")

# Tablas

Markdown permite dibujar tablas mediante plecas `|`. Cada celda está separada por uno de estos caracteres. Para crear encabezados que se distingan visualmente del resto del contenido, se subrayan las celda correcpondientes con guiones `-` . `Ejemplo: `

| **Columna 1** | **Columna 2** |
|--|--|
| uno | dos |  
|tres | cuatro |
| cinco | seis |

# Línea de Código

Encerrando el código entre acentos graves `<html lang="es">`

# Bloque de Código

Para crear un bloque entero que contenga código lo único que tiene que hacer es encerrar dicho párrafo entre dos líneas formadas por tres `~` virgulillas o tres acentos grave. La otra manera de añadir código en Markdown es comenzar el párrafo con `cuatro espacios en blanco. Ejemplo: `

```html
<head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE-edge" />
    <title>Document</title>
</head>
```

# Omitir Markdown

Cómo escribir ciertos símbolos como * o #, sin que Markdown los interprete para convertirlos en negritas...  
Escribiendo justo delante del símbolo la barra invertida `\`. `Ejemplo:` Esto es una asterisco *

# Escritura matemática

En línea encerrando la fórmula entre signos de `$`. En párrafos centrados, encerrando las fórmula entre dos signos de `$$`

* Fórmulas en línea: $a²-b²=a²+b²+2ab$
* Fórmulas centradas: 
$$ a²-b²=a²+b²+2ab $$
* Radicales:
$$\sqrt {a²-b²}$$
* Fracciones: 
$$x=\frac{-b\pm\sqrt{b²-4ac}}{2a}$$
* Parentesis grandes
$$\left (\sqrt{X²} \right)²$$
* Colores
$$\color{yellow}{A}\color{black}{aBb123}$$
