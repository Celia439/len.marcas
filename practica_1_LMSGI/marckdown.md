# Marckdown

## ¿Que es Marckdown?

Markdown es un lenguaje de marcado (_markup_) creado en 2004 por John Gruber y Aaron Swartz.

Markdown se basa en 3 principios:

1. inmediatez
2. compatibilidad
3. longevidad

### Inmediatez de Markdown

El objetivo de Gruber y Swartz era permitir la creación de contenidos formateados incluso a los usuarios menos experimentados, que no tuvieran conocimientos de diseño web o formateo.

_**Nota:** ¿qué es un contenido **formateado**? Un texto formateado es un texto que se muestra con un estilo determinado, por ejemplo, con partes en cursiva, **negrita**, ~~barrado~~, con enlaces o imágenes, títulos y subtítulos, citas y más._

Para crear contenidos con formato HTML el usuario debe utilizar una determinada sintaxis y un conjunto de más de 100 elementos (llamados tags).

En cambio, el formateo de texto en Markdown es mucho más sencillo. Un texto en Markdown es un archivo de _texto plano_ (plain text), en el que no cambia el tamaño de la letra, el color o la fuente, como ocurre en Microsoft Word, por ejemplo.

Diez minutos son suficientes para aprender la sintaxis básica.

Por ejemplo, para escribir un texto en negrita en HTML, es necesario teclear hasta 17 caracteres (los correspondientes a la etiqueta `strong`): la etiqueta de apertura va entre cuñas `(<…>)`, al igual que la etiqueta de cierre, que también lleva el indicador de barra oblicua para señalar que es una etiqueta de cierre (`</…>`).

`<strong>Texto en negrita</strong>`
Sin embargo, en Markdown sólo se requieren 4 caracteres, es decir, dos pares de asteriscos:
`**Texto en negrita**`

Con estas y otras sencillas medidas, Markdown simplifica enormemente la creación de documentos formateados.

Sin olvidar que en un archivo Markdown siempre es posible añadir partes de código HTML, que serán procesadas por Markdown como tal.

_Curiosidad: el nombre “Markdown” es un juego de palabras. En inglés “marcado” es “mark-up”, mientras que “markdown” es “rebaja”. Así que Markdown es una versión algo “rebajada” de un lenguaje de marcado._

### Compatibilidad de Markdown

Markdown tiene otra gran virtud: los archivos _.md o _.markdown pueden convertirse a HTML y a muchos otros formatos utilizando un procesador Markdown, es decir, un programa especial.
![Ejemplo Grafico.](/img/imagen.png)
Otra ventaja es que, dado que los archivos \*.md son archivos de texto plano, es decir, pueden abrirse con cualquier procesador de textos, no dependen de un software o aplicación concretos.

A diferencia de los archivos de texto creados por procesadores de texto propietarios, los archivos de texto escritos en Markdown pueden compartirse entre diferentes dispositivos y sistemas.

### Longevidad de Markdown

Dado que los archivos escritos en Markdown no se compilan, sino que son archivos de texto plano, es razonable suponer que serán legibles por los procesadores durante muchísimos años.

Incluso si todos los programas que utilizan Markdown dejaran de existir mañana (lo que es muy poco probable, dado su uso generalizado), un usuario podría seguir accediendo al contenido de estos archivos con cualquier editor de texto (como el bloc de notas de Windows, por ejemplo).

## Para qué se usa Markdown

Basándonos en lo antedicho, no es casualidad que Markdown se esté convirtiendo en el estándar de escritura para académicos, investigadores, redactores de contenidos y blogueros.

Algunos sitios web como GitHub, Reddit, Stack Exchange, OpenStreetMap o SourceForge han adoptado la sintaxis Markdown para los comentarios de los usuarios.

Markdown puede utilizarse en cualquier situación en la que sea necesario escribir un texto formateado.

A menudo se utiliza para formatear archivos README en proyectos de desarrollo de software, para escribir mensajes en los foros de discusión, para escribir documentación técnica y para crear artículos y páginas dentro de las herramientas de creación de sitios web, como Grav, el CMS con el que se creó el sitio web de Qabiria donde te encuentras ahora mismo.

Muchos programas de creación de notas y bases de conocimiento utilizan Markdown como formato estándar, por ejemplo, **Obsidian**.

## Las variantes de Markdown

Puede resultar sorprendente, pero no existe un estándar definido para Markdown, con la excepción del artículo original de John Gruber, que sin embargo describe el lenguaje dejando espacio para la ambigüedad y la interpretación.

Se crearon muchas variantes del lenguaje original, para corregir incoherencias o errores, o añadir funciones no previstas originalmente.

Además de las variantes propiamente dichas, también han surgido una serie de extensiones, es decir, otros lenguajes que añaden nuevas funciones a Markdown, como tablas, notas a pie de página, listas de definiciones, etc.

Algunos de estos lenguajes “extendidos” son:

* Markdown Extra
* GitHub Flavored Markdown (GFM)
* MultiMarkdown
* Maruku
* Kramdown
* Pandoc’s Markdown

#### En la web que está abajo contiene las sintaxis básica pero no contiene como se hace una tabla asi que lo añado.

### tablas
para crear tablas en marckdown debemos de utilizar los siguientes caracteres de la siguiente forma:

```
| columna izq   | columna drc   |
| ------------- |:-------------:|
| así           | quedaria      |
| dentro        | de            |
| marckdown     | ...           |
```
| columna izq   | columna drc   |
| ------------- |:-------------:|
| así           | quedaria      |
| fuera         | de            |
| marckdown     | ...           |

##### (La información a sido sacada de está pagina [Web](https://qabiria.com/es/recursos/blog/que-es-markdown-y-como-utilizarlo#).)