# Int1-Practica02-250917
----
En esta practica aprenderas a utilizar las heramientas Git y GitHub para el control de   versiones de proyectos d desarrollo de software, aplixando principios de buenas practicas de Documentacion, Desarrollo Claborativo y Respañldo de la Nube del Proyecto Integrador. 

Elaborado por: *Dulce Marbella Tolentino García*
Materia: **Proyecto Integrador**
Docente: **M.T.I Marco Antonio Ramirez Hernandez**
Periodo: *Mayo - Agosto 2026* 

## Comandos basicos para Maquetado de la Documentacióm utilizando el estandar de Markdown (.md) 
---
Markdown es el estandar utilizado por Git y GitHub, para estilizar (maquetar) la documentación de proyectos, lo que permite a usuarios y colaboradores del proyecto enterder el contexto y operacion del mismo. 

### 1. Encabezado o Títulos (HEADERS)
Para realizar una buena documentacion del proyecto debemos distribuir correctamente los contenidos, para poder dellimitar ohacer enfasis (entatizar), es decir resaltar las seciones mas impotantes, podremos utlizar lo siguiente: 

**Ejemplos**

#Encabezado nivel 1
## Encabezado nivel 2
### Encabezado nivel 3
#### Encabezado nivel 4
##### Enzabezado nivel 5
###### Encabezado nivel 6 
####### Encabezado nivel 7 - *El estandar solo permite 6 niveles para títulos, a partir del septimo seran presentado como texto plano (sin estilo)*

### 2. Separadores (SEPARATORS)  
Si se desea marcar una separacfion visual de los contenidos podemos utilizsar una linea horizontal indicando tres caracteres - contionuemos, en el maquetado

**Ejemplo**

### Titulo de la seccion 
---
Texto despues del separador

### 3. Parrafos (PARAGRAPHS)
Son titulos para prsentar grandes seciones que describenm detalladamente el contenido de las secciones de la documentacion, detallan procesos, explican codigo o contexto teorico. 

**Ejmplo**

Parrafo 1: este stexto es del parrafo 1 este texto es del parrafo 1 este texto es del parrafo 1este texto es del parrafo 1este texto es del parrafo 1 este texto es del parrafo 1 este texto es del parrafo 1 este texto es del parrafo 1 este texto es del parrafo 1 este texto es del parrafo 1 este texto es del parrafo 1 este texto es del parrafo 1 este texto es del parrafo 1 este texto es del parrafo 1 este texto es del parrafo 1 este texto es del parrafo 1 este texto es del parrafo 1 este texto es del parrafo 1 este texto es del 

Parrafo 2: Este texto es del parrafo 2 este texto es del parrafo 2 este texto es del parrafo 2 este texto es del parrafo 2 este texto es del parrafo 2 este texto es del parrafo 2 este texto es del parrafo 2 este texto es del parrafo 2 este texto es del parrafo 2 este texto es del parrafo 2 este texto es del parrafo 2 este texto es del parrafo 2 este texto es del parrafo 2 este texto es del parrafo 2 este texto es del parrafo 2 este texto es del parrafo 2 este texto es del parrafo 2 este texto es del parrafo 2 este texto es del parrafo 2 este texto es del parrafo 2 este texto es del parrafo 2 este texto es del parrafo 2 este texto es del parrafo 2 

En caso de que necesitemos alinear el parrafo a **izquierda**, **derecha**, **centrado** o **justificado**. deberemos utilizar una etiqueta ´´´ <p> ´´´ con la propiedad aling y la direccion deseada. 

<p align="left"> Parrafo alineado a la izquierda parrafo alineado a la izquierda parrafo alineado a la izquierda parrafo alineado a la izquierda parrafo alineado a la izquierda parrafo alineado a la izquierda parrafo alineado a la izquierda parrafo alineado a la izquierda parrafo alineado a la izquierda parrafo alineado a la izquierda parrafo alineado a la izquierda parrafo alineado a la izquierda parrafo alineado a la izquierda parrafo alineado a la izquierda 

<p align="center"> parrafo alineado al centro parrafo alineado al centrov parrafo alineado al centro v v v parrafo alineado al centro parrafo alineado al centro parrafo alineado al centro v parrafo alineado al centro parrafo alineado al centro parrafo alineado al centro parrafo alineado al centro parrafo alineado al centro parrafo alineado al centro parrafo alineado al centro parrafo alineado al centro parrafo alineado al centro parrafo alineado al centro

<p align="right"> parrafo alineado ala derecha parrafo alineado ala derecha parrafo alineado ala derecha parrafo alineado ala derecha parrafo alineado ala derecha parrafo alineado ala derecha parrafo alineado ala derecha parrafo alineado ala derecha parrafo alineado ala derecha parrafo alineado ala derecha parrafo alineado ala derecha parrafo alineado ala derecha parrafo alineado ala derecha parrafo alineado ala derecha parrafo alineado ala derecha parrafo alineado ala derechaparrafo alineado ala derecha 

<p align="justify"> parrafo justificado parrafo justificado parrafo justificado parrafo justificado parrafo justificado parrafo justificado parrafo justificado parrafo justificado parrafo justificado parrafo justificado parrafo justificado parrafo justificado parrafo justificado parrafo justificado parrafo justificado parrafo justificado parrafo justificado parrafo justificado parrafo justificado parrafo justificado parrafo justificado parrafo justificado 

### 4. Enfatizado de texto

- Texto en Negritas: Para resaltar texto importante que no sea un titulo por que esta puesto inicialmente estan en negrita, deberemos enecerrar el texto deseado entren dobles asteriscos (**)

Ejemplo: Este texto esta en **negrita**.

- Texto en cursiva (italico): Para hacer referencia a texto utilizando el formato inclinado o italico bastara cone encerrar el texto deseado entre dos arteriscos simple (*).

Ejemplo: Este *texto estara inclinado*.

- Texto en cursiva y negrita: para lograr esta estilizacion en la documentacion basta con juntar ambas configuraciones, es decir encerremos el texto en un triple asterisco (***).

Ejemplo: ***este ejemplo esta escrito en negrito e italico***.

- Texto Tachado: en algunas ocaciones es necesario dar formato al texto con un efecto de como es incorrecrto, generalmente esta ide see transmite porque el texto esta tachado, es decir con una linea que lo marca por la mitad. Para lograr este efecto tendremos que encerrar el texto entre una doble tilde de (~).

Ejemplo: se dice haya no  ~~haiga~~. 

- Texto subrayado: En est3e tipo de fromato el texto queda sobre una lilnea inferior para denotar su relevenacia, este formato no tiene una version rapida en el estandar MARDOWN<, pero dado su similaridad a HTML podemos utilizar las etiquetas ´´´<u>´´´y´´´</u>.

Ejemplo: El <u>texto</u>  debe estar <u>subrayado</u>. 

- Texto en suoper indice: En lagunas ocaciones se erequieere dar formato  a formulas estadisticas que requiere potencias entre otras aplicaciones, podemos utilizar el tag en HTML ```<sup>```y```<sup>``` para delimitar el formato.

Ejemplo: para elevar x al cuadrado tendriamos lo siguiente: x<sup>2</sup>.

- Texto en Subiondice: Ehn el caso de quimica se utilizan subindices para representar formulas, para ello podemos utilizar el formato de textocon la etiqueta HTML ```<sub>```y```</sub>```. 

Ejemplo: La formula del Agua es H<sub>2</sub>0. 

### 5. Listas.

Cuando realizamos documentacion utilizando el estandar de MARDOWN, comun que tengamos que listar elemnetos, requisitos de harware, requisitos de software o ennumerar pasos de como el software debe seer instalado paso a paso, por eso debemos saber como crear listas de las cuales hay de 3 tipos: **Ordenadas (Numeros)**, **Desordenadas(viñetas)** y **Mixtas(viñetas y numeros)**. 

1. Listas ordendas.

Estas deberan estar ennumeradas con un numero seguido por un punto y un espacio en blanco  para comenza con el listado. 

1. PC. 
2. Teclado.
3. Wifi.
4. Modem.
6. Tablet. 
5. Smart TV. 

Para reinicar el contenido se debe de poner una linea sin texto sin numerarla. 

2. Listas Desordenadas. 

Estas listas no llevan un numero,  si no una viñeta (simbolo), y suelen en listar elementos que no requieren un orden especifico. 

- Pan 
- Leche
- Huevo
- Arroz

3. Listas Mixtaas. 

Son aquellas que mezcla ambos elemenetos

- 3° A DSM
  1. Juan
  2. Pedro
  3. Aleandra
- 3° B DSM
  1. Romina
  2. Daniel
- 3° C DSM
  1. Les
  2. Pao
  3. Uriel
  4. Jeovany 

### 6. Bloques de Codigo (CODE BLOCKS) o Citas (BLOCK QUOTES)

Estos estilos de texto se utilizan para llama4r la atencion del lector, en pasos que son importantes, realizar algun a reseña o segmentar lineas den codigo que se debran ingresar en una terminal de comandos o lienas de ejecucion. 

- Cuadro de citas (Block Quotes)
Son cajas estilizadas en colores frisees por defecto con un marfen mas claro.

Ejemplo: 

Para listar las carpetas y archivos de una terminal de comandos del sistema operativo de Windows debemos usar el comando: 

>C:/dir

Despues oprimimos la tecla *enter*.

Tambien podemos usar texto multilinea.

**Ejemplo**

Pasos para instalar MySQL:

> - Descargar el archivo instaladro desde lña pagina oficialn www..myqsl.com
> - Instalar el servidor de base de datos.
> - Defirnir le puerto y contraseña pra el usuario **root**.
> - Inicializar el servidor de base de datos. 
> - Conectarnos a la abse de datos para verificar que se instalo correctamente. 

- Bloques de codigo 







