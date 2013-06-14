GameOfLife
==========
Tengo dos versiones de Juego.
La primera versión es sencilla y funciona.

La segunda versión es más complicada y no funciona.
Tengo problemas para pasar valores de variables de una clase a otra.
La clase para iniciar el juego es Inicio, que llamará a la clase Seleccion.
Y ahí es donde empiezan los problemas.
Los botones de la clase Seleccion, llaman a la clase Ventana2. Y dependiendo 
de que boton pulses usa un constructor u otro. A la clase Ventana2 le paso los
valores de alto y ancho seleccionados en Seleccion. Y luego estos datos los usará 
la clase Panel1 para poder construir el EspacioCelular que nos los pide en el constructor.
Ahora mismo estoy atascada con eso. Creo que el problema tiene que estar en como
paso los valores de alto y ancho.
