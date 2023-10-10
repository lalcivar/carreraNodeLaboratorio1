# carreraNodeLaboratorio1
===========================Eslint==================================

1. max-len

Aplicar una longitud máxima de línea .- Líneas de código muy largas en cualquier idioma pueden resultar difíciles de leer. Para ayudar en la legibilidad y el mantenimiento, muchos codificadores han desarrollado una convención para limitar las líneas de código a un número X de caracteres (tradicionalmente 80 caracteres).

2. max-statements-per-line

Aplicar un número máximo de declaraciones permitidas por línea .- Una línea de código que contiene demasiadas declaraciones puede resultar difícil de leer. El código generalmente se lee de arriba hacia abajo, especialmente cuando se escanea, por lo que limitar la cantidad de declaraciones permitidas en una sola línea puede ser muy beneficioso para la legibilidad y el mantenimiento.

3. no-extra-parens

No permitir paréntesis innecesarios .- Esta regla restringe el uso de paréntesis sólo cuando sean necesarios.

===========================Prettier==================================

1. Range

Formatee solo un segmento de un archivo.

Estas dos opciones se pueden utilizar para formatear el código que comienza y termina en un desplazamiento de caracteres determinado (inclusivo y exclusivo, respectivamente). La gama se ampliará:

     Hacia atrás hasta el inicio de la primera línea que contiene la declaración seleccionada.
     Avanza hasta el final de la declaración seleccionada.

2. Embedded Language Formatting

Controle si Prettier da formato al código citado incrustado en el archivo.

3. End of Line

Por razones históricas, existen dos tipos comunes de finales de línea en archivos de texto. Es decir, \n (o LF para avance de línea) y \r\n (o CRLF para retorno de carro + avance de línea).

===========================TSConfig======================================

1. allowUnreachableCode

Estas advertencias se refieren únicamente al código que probablemente sea inalcanzable debido al uso de la sintaxis de JavaScript.

2. allowUnusedLabels

Las etiquetas son muy raras en JavaScript y normalmente indican un intento de escribir un objeto literal.

3. noImplicitOverride

Cuando se trabaja con clases que usan herencia, es posible que una subclase "no esté sincronizada" con las funciones que sobrecarga cuando se les cambia el nombre en la clase base.


===========================EditorConfig==================================

1. tab_width

Un número entero que define el número de columnas utilizadas para representar un carácter de tabulación. El valor predeterminado es el valor de indent_size y normalmente no es necesario especificarlo.

2. max_line_length

Fuerza el ajuste de línea después de la cantidad de caracteres especificada. off para desactivar esta función (use la configuración del editor).

===========================Nodemon==================================

1. Delaying restarting

La cifra de retraso es el número de segundos (o milisegundos, si se especifica) que se deben retrasar antes de reiniciar. Entonces, nodemon solo reiniciará su aplicación la cantidad de segundos especificada después del último cambio de archivo.

Si configura este valor en nodemon.json, el valor siempre se interpretará en milisegundos.
