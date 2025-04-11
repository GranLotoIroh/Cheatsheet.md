# Editor de texto
## Encabezados
"# Nombre"
Cada "#" adicional creará un encabezado con menor importancia jerárquica siendo "#" El encabezado principal.
"Encabezados" es un título con jerarquía 2, mientas que "Editor de texto" ocupa el puesto de encabezado principal.
### Encabezado 3
#### Encabezado 4

Se pueden crear hasta encabezado 6, a partir de ahí deja de contar  como encabezado

## Modificadores de texto
**Negrita**: Dos asteriscos al empezar y acabar el texto **palabra**.

**Cursiva**: Un asterisco al empezar y acabar el texto *palabra*. También sirve encapsular el contenido entre barras bajas _palabra_

**Tachado**: Doble "~" al principio y al final ~~palabra~~.

**Subrayado**: Encapsular el contenido entre barras bajas _palabra_

**Resaltado**: Doble "=" al empezar y acabar el texto  ==palabra==.

**Línea divisoria**: Triple guión "---" en una linea en blanco. En caso de ponerlo justo debajo de una frase, resaltará esa frase en el editor de texto aunque cuando se exporte ésta mantendrá su tamaño original. 

---
## Modificadores de párrafo
#todo callouts
https://help.obsidian.md/Editing+and+formatting/Callouts

# Listas
"-" y espacio creará una lista desordenada
- Item 1
	- Para anidar solo aplicar tab
- Item 2

na lista ordenada
1. Item 1
	1. Anidado, no subdirecciona
2. Item 2
## Checkboxes
La sintaxis para esta función es igual que para crear una lista desordenada. Para convertir esta lista desordenada en un checkbox deberemos continuarlo con un "[]" y un espacio entre los corchetes.
- [ ] Item 1

Para que aparezca tachado se tendrá que poner una "x" entre los corchetes.
- [x] Item 2

# Links
## Archivos
Para referenciar otro documento se usa doble corchete "[[]]".
No hace falta que se cree en el momento el sitio al que enlaza, lo crea automáticamente vacío y se puede volver a él mas tarde.
Para que se muestre el enlace con otro nombre, por ejemplo, un archivo que está creado en "Ejemplo 1", pero lo queremos llamar "Enlace". Para ello se usará "[[Ejemplo 1 | Enlace]]"
En el caso que querer mostrar el contenido referenciado se le tendrá que añadir una exclamación delante. La sintaxis restante sería así "![[]]". Se pueden reescalar las imágenes si, tras el nombre se pone un barra vertical "|" y el número de píxeles que se quiera ocupar. 
Ej: "![[ejemplo|200]]"
### Encabezados
Se pueden referenciar encabezados de otros documentos y párrafos dentro de estos. La sintaxis para esto sería la misma que para enlazar un archivo y, sin espacios, seguirlo de un "#" y el nombre del párrafo.
[[Cheatsheet#Encabezados]]
### Párrafos
Si se quiere concretar más y poner un párrafo que esté anidado dentro de un encabezado se tendrá que usar la referencia al documento al que pertenece, usar "^" y escribir parte del párrafo, sin poner la referencia al encabezado, para que el buscador lo pueda encontrar y marcar con un identificador que podremos editar. 
![[Cheatsheet#^a612a3]]

Párrafo de prueba ^a612a3
## Páginas web
En caso de querer referenciar un enlace a una página web la sintaxis sería "\[Nombre para el enlace]" seguido de "(paginaweb)".
- [Google](https://www.google.com)
## Rutas de archivos
Otro caso puede ser enlazar a otra vault, para hacerlo la sintaxis sería la misma que para enlazar una página web. "[Nombre de referencia]" seguido de la ruta en la que se encuentre la nota entre paréntesis: "(ruta documento)" sin dejar un espacio entre medias del corchete y el paréntesis.
- [Vault multimedia](Z:\ObsidianVaults\Multimedia\PruebaLink.md)
# Carpetas
Para que una carpeta aparezca arriba del todo debe ser llamada con una barra baja antes del nombre, por ejemplo _carpeta

# Búsqueda
#todo busqueda

# Bookmarks
#todo bookmarks
# Properties
#todo properties
Para declarar las properties del documento, a.k.a metadatos, 
## Tags
Los tags sirven para marcar con metadatos a que categoría pertenece el archivo. 
Se crea un tag usando "#" seguido de la palabra a referenciar, por ejemplo #ejemplo
En cada archivo habrá diferentes marcadores donde se usan. 
- Linked mentions: Muestra los archivos en los que ha sido referenciado.
- Links: Recopila las referencias a otras notas que hayan sido enlazadas con "[[]]"
- Tags: Lista los tags que hayan sido creados entre todos los documentos. Se pueden anidar tags usando un "/" tras el tag principal y poniendo un nombre a continuación.
