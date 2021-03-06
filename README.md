# Como empezar con Arduino

Querido Santiago,

Aqui te dejamos algo de documentacion para que puedas disfrutar de tu regalo por tu decimo cumpleanyos. 
Esperamos que lo disfrutes, y no dudes en preguntarle a tu padre o escribir a Pablo si tienes preguntas.

## Mini-Guia rapida

Queria aprovechar para hablarte de un par de cosas que rodean al Arduino que pueden parecer complicadas al principio, pero veras que no hace falta ser un experto para poder hacer cosas chulas.

En dos palabras, el Arduino junta el mundo de la electricidad con el de la programacion, haciendo ambas mucho mas sencillas y divertidas.

### Electricidad 
Seguro que te has preguntado como funcionan las bombillas, el micro-ondas, un altavoz o un coche teledirigido. 
La electricidad te permite mover energia de un lado a otro, y convertir dicha energia en una forma u otra. 
Por ejemplo, la energia (quimica) almacenada en una pila se puede transportar por un cable para encender una bombilla (energia luminosa)

A mi me gusta pensar que una corriente electrica es como un rio: va de lo alto hacia el mar, y con un poco de ingenio podemos sacarle provecho (como mover un molino de agua). La electricidad en grandes cantidades puede ser peligrosa (ojo con los enchufes!!) pero la electricidad que hay en una pila no es peligrosa para ti. 
Eso si, si no tienes cuidado puedes quemar alguna de esas mini-bombillas (Diodo Led)... pero no te preocupes, que cuestan muy poquito. 

Tu padre es un genio de la electricidad. Preguntale!

### Programacion
Los programas le dicen al ordenador lo que tiene que hacer: son el alma de la informatica! Tu juego de ordenador favorito es un programa, lo que hace moverse la flechita cuando mueves el raton es un programa... el ordenador esta lleno de ellos!

A mi lo que mas me fascina de la informatica es la cantidad (y complejidad) de programas que se ejecutan en un momento. No exagero si te digo que cientos y cientos! 
Una cosa tan sencilla como ver un video de Youtube depende del esfuerzo de miles y miles de personas que han pasado muchos anyos programando para que sea posible. 
Uno puede pasar la vida programando y nunca llegar a ser un experto de verdad. Pero no desesperes: todos hemos empezado a programar sin tener ni idea, hay que ir paso a paso!

Yo a veces me imagino que programar es como jugar en un escritorio con muchos cajones. Cada cajon (se llaman "variables") contiene un numero que puedes combinar con otros (copiar, sumar, multiplicar...) y el programa define lo que haces con esos cajones. 
Por ejemplo: "mira esta variable, y si es un 7 haz esto, y si no haz esto otro"... o "repite esta operacion 10 veces"

Con Arduino, tu eres el que decide lo que el aparatejo tiene que hacer, por medio de un programa. El resultado suele ser que la electricidad se mueve de un sitio a otro, en funcion de lo que programes, encendiendo bombillitas, leyendo sensores de temperatura o tocando musica en un zumbador.
Cuando instales el IDE (el programa que sirve para programar Arduinos) veras que viene con algunos programas de ejemplo que solo tienes que darle a un boton para probarlos. Echale un ojo a dichos programas e intenta entender como funcionan. Veras que en seguida puedes hacer tus propias modificaciones y, con el tiempo, escribir programas desde cero.

### Primeros pasos

Lo primero es lo primero: el primer programa de prueba!

1. Descargate el IDE para tu ordenador (https://www.arduino.cc/en/Main/Software)
2. Arranca el IDE (deberias tener un icono nuevo en el escritorio)
3. Conecta el Arduino con el cable USB azul
4. En el menu Tools, elige Board Arduino/Genuino UNO
5. En el menu File -> Examples -> 01.Basic, elige el ejemplo "Blink"
6. Dale al iconito redondo con una flecha a la derecha para meter el programa en el Arduino
7. Observa como parpadea la luz.
8. Prueba a cambiar los tiempos de espera entre encendido y apagado (delay) y repite los pasos 6 y 7.

Y lo segundo... prueba a tocar algo de musica:

1. Descarga el fichero "marcha_imperial.ino" de esta pagina
2. Crea un directorio nuevo llamado "marcha_imperial" en MisDocumentos\Arduino\Sketches
3. Copia el fichero marcha_imperial.ino dentro del nuevo directorio
4. Cierra y vuelve a arrancar el IDE
5. En la seccion de File -> Sketchbook deberia aparecer el elemento marcha_imperial. Abrelo.
6. Pincha el zumbador negro en los PIN: GND y 11
7. Dale al iconito redondo con una flecha a la derecha para meter el programa en el Arduino

### Documentacion Online

Aqui termina la mini-introduccion al Arduino. Lo siguiente es que investigues por tu cuenta. Hay una serie de videos que pueden echarte una mano, lo mejor para empezar: https://www.youtube.com/watch?v=OSHJUkG8zW4

Este video va bastante en detalle sobre la programacion de Arduino. No te preocupes si no lo entiendes todo desde el principio! https://www.youtube.com/watch?v=3BnS59Kg9DE

Si quieres saber mas sobre programacion, puedes pedirle a tus padres que se miren este pagina y te cuenten: http://www.xataka.com/especiales/ninos-y-programacion-consejos-y-recursos-para-que-este-verano-se-inicien

La documentacion oficial del Arduino esta en ingles: https://www.arduino.cc/en/Guide/HomePage
 
Lo dicho, esperamos que lo disfrutes! Recuerda, experimenta por tu cuenta, pide ayuda cuando lo necesites, y recuerda que es un juguete y lo importante es pasarlo bien con el.

Con todo nuestro carinyo,
 Tus primos Esther y Pablo
 Y tus sobrinos Valeria y Erik
