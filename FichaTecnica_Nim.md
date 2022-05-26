Propósito: Nim es un lenguaje de programación de sistemas compilados tipificados estáticamente. Combina conceptos exitosos de lenguajes maduros como Python, Ada y Modula.

Paradigma: Statically typed compiled.

Fortalezas:

Nim genera ejecutables nativos sin dependencias, que no dependen de una máquina virtual, que son pequeños y permiten una fácil redistribución.

El compilador de Nim y los ejecutables generados son compatibles con todas las plataformas principales, como Windows, Linux, BSD y macOS.

La gestión de memoria de Nim es determinista y personalizable con destructores y semántica de movimiento, inspirada en C++ y Rust.

Es muy adecuado para sistemas embebidos en tiempo real.
Conceptos modernos como iteradores sin sobrecarga y evaluación en tiempo de compilación de funciones definidas por el usuario, en combinación con la preferencia de tipos de datos basados ​​en valores asignados en la pila, conducen a un código extremadamente eficaz.
 
Debilidades:

Los subprocesos/concurrencia siguen siendo difíciles de usar. No imposible solo difícil. Los subprocesos de Java/Go se sintieron realmente fáciles. Después de usar hilos en nim todavía no me gustan. Async/await se siente un poco demasiado detallado, me gusta el modelo de concurrencia gevent/scheme donde todo es concurrente sin marcas adicionales.
Vec3/vec3 .. No puedo tener un proceso de construcción con el mismo nombre que el tipo. Extraña limitación.
Extrañeza en torno a los nombres y la semántica de Enum. Tengo que nombrar mis cosas como aLeft y kLeft para alignLeft y keyLeft, ¿por qué no puedo simplemente usar Left? Sabe qué enumeración cabría, pero se niega a usarla.
gestión de dependencia ágil, es molesto tener que ir a github para etiquetar lanzamientos todo el tiempo, solo para hacer feliz a ágil.
Implementación: Compatibilidad con varios backends: compila en C, C++ o JavaScript para que Nim se pueda usar para todas las necesidades de backend y frontend.
Runtime / Maquina Virtual.

Plataformas soportadas: Windows, Unix.

Usuarios notables: CCP Games,
Status.im,
Fivnex,
State of the DApps,
cvebase.

Historia: El desarrollo inicial de Nim se inició en 2005 por Andreas Rumpf. Originalmente se llamó Nimrod cuando el proyecto se hizo público en 2008. La primera versión del compilador Nim se escribió en Pascal utilizando el compilador Free Pascal. En 2008, se lanzó una versión del compilador escrita en Nim. El compilador es un software gratuito y de código abierto, y está siendo desarrollado por una comunidad de voluntarios que trabajan con Andreas Rumpf. El lenguaje pasó a llamarse oficialmente de Nimrod a Nim con el lanzamiento de la versión 0.10.2 en diciembre de 2014. El 23 de septiembre de 2019, se lanzó la versión 1.0.0 de Nim, lo que significa la madurez del lenguaje y su cadena de herramientas.
Estado: Activo.
