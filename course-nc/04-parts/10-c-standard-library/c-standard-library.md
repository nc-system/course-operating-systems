
# C STANDAR LIBRARY

    - La biblioteca estándar de C, o libc (no confundir con stdlib.h); es una recopilación de archivos de cabecera y bibliotecas con rutinas, estandarizadas por un comité de la Organización Internacional para la Estandarización (ISO), que implementan operaciones comunes, tales como las de entrada y salida o el manejo de cadenas. A diferencia de otros lenguajes como COBOL, Fortran, o PL/1, C no incluye palabras clave para estas tareas, por lo que prácticamente todo programa implementado en C se basa en la biblioteca estándar para funcionar.


## Diseño

    - El nombre y las características de cada función, el prototipo, así como la definición de algunos tipos de datos y macros, se encuentran en un fichero denominado archivo de cabecera (con extensión ".h"), pero la implementación real de las funciones están separadas en un archivo de la biblioteca. La denominación y el ámbito de las cabeceras se han convertido en comunes, pero la organización de las bibliotecas sigue siendo diversa, ya que éstas suelen distribuirse con cada compilador. Dado que los compiladores de C, a menudo, ofrecen funcionalidades adicionales que no están especificados en el ANSI C, la biblioteca de un compilador no siempre es compatible con el estándar ni con las bibliotecas de otros compiladores.


## Calidad del diseño

    - Está demostrado que la mayor parte de la biblioteca estándar de C ha sido bien diseñada, aunque se ha comprobado que algunas partes también son fuente de errores; funciones para entrada de cadenas como gets() o scanf(), producen desbordamientos de buffer, y muchas guías de programación recomiendan evitar su uso. La función strtok() presenta otra singularidad, está diseñada para ser utilizada como un analizador léxico rudimentario, pero resulta difícil de utilizar además de ser muy frágil.