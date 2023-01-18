# LEARNING SASS

    sass es una extension, que permite escribir hojas de estilo con las caracteristicas propias de un lenguaje
    de programacion, permitiendo utilizar:

### INHERITANCE/EXTEND

### VARIABLES

### NESTING

### PARTIAL

### MODULES

### MIXINS

    funciona como un compilador, es decir, lo que escribimos en sass lo "traduce" a lenguaje css.

## Ventajas respecto al css:

    	- Reduce el tiempo para crear y mantener el CSS
    	- Permite tener una organización modular de los estilos
    	- Proporciona estructuras avanzadas propias de los lenguajes de programación,
    		como variables, listas, funciones y estructuras de control.
    	- Permite vigilar los ficheros, de tal manera que, si ha habido un cambio en la hoja de estilos,
    		se regenera automáticamente (modo watch).
    	- Existen muchas herramientas asociadas, muchas librerías hechas con Sass y una comunidad muy
    		importante de usuarios.

## Desventajas:

    	- Hay que aprender a utilizar una nueva herramienta
    	- Tiene una sintaxis más compleja que CSS.
    	- Hay un tiempo de consumo en el proceso de generación o compilación del CSS (minimo)

## Instalacion

    1º insertamos el comando en la terminal


    	``` npm i -d sass ```


    2º creamos las carpetas css y sass


    3º Añadimos el script en package.json para que identifique las carpetas y se quede watching


    	``` "sass":"sass sass:css --watch" ```

    4º lanzamos el comando en la terminal que lanza el script


    	```npm run sass```

## INHERITANCE

    - @EXTEND
