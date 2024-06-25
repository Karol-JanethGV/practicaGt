# practicaGt
Esta práctica sirve para conocer los comandos basicos del maquetado bajo el estandar de MARKDOWN (.md), que nos servira para crear la documentacion de nuestros proyectos de software durante nuestra formacion profesional.

## 1.Títulos (HEADERS)

Si para la documentacion deseamos ubicar secciones de algun tema o contenido podremos utilizar estos elementos para poner textos resaltados como encabezados. Estos son muy similares a las etiquetas /<H1>..../<H6> en HTML.

**EJEMPLO:**
# Título Principal (Nivel 1)
## Subtitulo de Nivel 2
### Subtitulo de Nivel 3
#### Subtitulo de Nivel 4
##### Subtitulo de Nivel 5
###### Subtitulo de Nivel 6
####### El estándar solo te permite hasta 6 posibles titulos, a partir del septimo omitira la instruccion del maquetado

## 2. Separadores (SEPARATORS)
Esta instruccion coloca una linea vertical entre las secciones del documento permitido organizar y distribuir mejor el contenido, y puede ser maquetado utilizando 3 guines medios (-) continuos del párrafo deseado.

**EJEMPLO**
Párrafo 1 Párrafo 1 Párrafo 1 Párrafo 1 Párrafo 1 Párrafo 1 Párrafo 1 Párrafo 1 Párrafo 1 Párrafo 1
---
Párrafo 2 Párrafo 2 Párrafo 2 Párrafo 2 Párrafo 2 Párrafo 2 Párrafo 2 Párrafo 2 Párrafo 2 Párrafo 2
## 3. Párrafos (PARAGRAPHS)
Son utilizados para presentar texto descriptivo de la documentacion de los proyectos, en el cual podremos utilizar la propiedad de 'aligh' de HTML para poder controlar la alineacion del texto.
**EJEMPLO**
Párrafo 1 en caso de no definir la alineacion estara por defecto a la izquierda Párrafo 1 en caso de no definir la alineacion estara por defecto a la izquierda Párrafo 1 en caso de no definir la alineacion estara por defecto a la izquierda Párrafo 1 en caso de no definir la alineacion estara por defecto a la izquierda Párrafo 1 en caso de no definir la alineacion estara por defecto a la izquierda Párrafo 1 en caso de no definir la alineacion estara por defecto a la izquierda Párrafo 1 en caso de no definir la alineacion estara por defecto a la izquierda Párrafo 1 en caso de no definir la alineacion estara por defecto a la izquierda Párrafo 1 en caso de no definir la alineacion estara por defecto a la izquierda Párrafo 1 en caso de no definir la alineacion estara por defecto a la izquierda 
<p align="right"> Párrafo 2 al utilizar la etiqueta p y la propiedad de alineacio align con el valor right, este estara alineado na la derecha  Párrafo 2 al utilizar la etiqueta p y la propiedad de alineacio align con el valor right, este estara alineado na la derecha  Párrafo 2 al utilizar la etiqueta p y la propiedad de alineacio align con el valor right, este estara alineado na la derecha  Párrafo 2 al utilizar la etiqueta p y la propiedad de alineacio align con el valor right, este estara alineado na la derecha </p>

<p align="center"> Párrafo 3 estara centrado Párrafo 3 estara centrado Párrafo 3 estara centrado Párrafo 3 estara centrado Párrafo 3 estara centrado Párrafo 3 estara centrado Párrafo 3 estara centrado </p>
<p align="justify"> Algunas veces desearemos justificar el texto para presentar el texto de una manera mas organizada Párrafo 4 Algunas veces desearemos justificar el texto para presentar el texto de una manera mas organizada Párrafo 4 Algunas veces desearemos justificar el texto para presentar el texto de una manera mas organizada Párrafo 4 Algunas veces desearemos justificar el texto para presentar el texto de una manera mas organizada Párrafo 4 Algunas veces desearemos justificar el texto para presentar el texto de una manera mas organizada Párrafo 4 Algunas veces desearemos justificar el texto para presentar el texto de una manera mas organizada Párrafo 4 justificado</p>
## 4. Texto Enfatizado (BOLD,ITALIC/BOLD Y UNDERLINE)
Tambien es posible resaltar algunas palabras importantes utilizando las estilizacion de **Letras Negritas**, paran la que colocaremos dos * antes y despues de la palabra a resaltar, *Letras Cursivas* para que solo ponemos un  * antes y despues de las pabras, ***Letras Cursivas y Negritas*** colocamos 3 * y por ultimo <ins> texto subrayado <ins>texto subrayado</ins> <ins>texto subrayado</ins> <ins>texto subrayado</ins> <ins>texto subrayado</ins> <ins>texto subrayado</ins>y la etiqueta de cierre  </ins>

## 5.Cuadros de Codigo o Reseñas (BLOCKQUOTES)
Estos elementos utilizados para resaltar instrucciones especificas para la instalacion, configuracion y/o inicializacion del proyecto, para mostrar secciones de codigos fuente, y se maqueta utilizando el simbolode mayor  que (>) antes del texto.
**EJEMPLO**
Para listar carpetas y archivos desde una terminal de comandos en el sistema operativo de windows debemos usar el comando:
> C:/dir
 Despues oprimimos la tecla 'enter'.
 Tambien podemos poner texto multilinea
 **Ejemplo**
> - Descargar el archivo instalador desde la pagina oficial www.mysql.com
> - Instalar el servidor de Bases de Datos
> - Definir el puerto y contraseña para el usuario **root**
> - Inicializar el serviro de bases de datos
> - Conectamos a la base para verificar que se instalo correctamente.

## 6. Listas Ordenadas y No Ordenadas
si en nuestra documentacion necesitamos incluir informacion en modo de lista, es decir un elemento, tras otro podremos hacerlo utilizando las listas ya sea usando viñetas o numeracion definida.

Para el uso de viñetas solo es necesario agregar un (-) antes del texto.

**EJEMPLO**
Mi tipo favorito de musica es:
- Balada
- Rock
- Electro House
- pop
  Para enlistar elementos  en órden numerico solo basta con anteponer un numero antes del texto con un (.)
  **EJEMPLO**

  1. Crear una cuenta de GitHub
  2. Logearme con mi cuenta de GitHub
  3. Ir a la página Principal de mi perfil (Home)
  4. En el menu lateral buscar el boton que dice  **Nuevo Repositorio**
  5. Asignarle un nombre
  6. Definir un nombre
     - **Publico:** Cualquier persona podra ver y consultar el contenido de mi proyecto
     - **Privado:** Solo aquella persona que yo autorice podran visualizar y modificar el contenido de mi proyecto.
  7. Agregar un primer archivo documento1 *README:md*
  8. Aprobar la creacion del repositorio.

     ## 7. Ligas e Hipervinculos (LINKS)
   Estas son utilizados para redirigir a archivos, secciones dentro o fuera de nuestro repositorio. se maquetan utilizando corchertes /[/], inmediantamente de parentesis con la url destino /(/).

  **EJEMPLO**
  Mi buscador favorito es: [Google.(https://www.google.com).
  Esta documentacion fue creada por: ***Alumna Karol Janeth Gonzalez Vargas***
  <230323@utxicotepec.edu.mx

  ## 8. Tablas (TABLES)
  Si la documentacion requiere podemos presentar informacion en formato de tablas con filas y columnas, para maquetarlas podemos utilizar el caracter | para delificar las columnas y - para delimitar las filas

  **EJEMPLO**
  ---------------------------------------
  |Encabezado 1|Encabezado 2|Encabezado 3| Encabezado4|
  |-------------|-----------|------------|------------|
  |Fila 1 celda 1|Fila 1 celda 2|Fila 1 celda 3|Fila 1 celda 4|
  |Fila 2 celda 1|Fila 2 celda 2|Fila 2 celda 3|Fila 2 celda 4|
  |Fila 3 celda 1|Fila 3 celda 2|Fila 3 celda 3|Fila 3 celda 4|
  |Fila 4 celda 1|Fila 4 celda 2|Fila 4 celda 3|Fila 4 celda 4|
## 9. Imagenes
para la visualizacion de imagebes debemos cargar los archivos en nuestro repositorios y vincularlos
|[lugia] (https://github.com/KarlaIvon15/practicaGt/blob/main/descarga.jpg).
          
