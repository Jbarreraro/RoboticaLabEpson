# RoboticaLabEpson
# Itegrantes: 
- Andres Hernandez
- Sebastian Daleman
- Andrés Barrera
- Daniel Segura
- Andrés Serna

# Observaciones:

El archivo 'PracticaEpson.txt' con tiene el codigo empleado para la solucion del problema planteado.

Desarrollo de la practica:

En la guia proporcionada por Epson, inicialmente se propusieron una serie de ejercicios basicos para empezar a conocer la sintaxis basica del lenguaje usado para la programacion del robot SCARA. Todo esto, para finalmente proponer una rutina que debia ejecutar el robot. 

Rutinas de movimiento:

Paletizado en Z: Esta es la primera rutina de movimiento que debia ejecutar se trataba de un paletizado que debia tener forma de Z, a continuacion una imagen desriptiva:

![image](https://github.com/Jbarreraro/RoboticaLabEpson/assets/70239708/936ac4d8-2645-4cf7-a530-2276da7357c6)

Para relizar esto, se definia un espacio de trabajo con forma de cuadricula 3x3. Luego el robot debia recorrer cada una de estas secciones de la cuadricula hasta completar la forma de Z. Esto se lograba definiendo los limites de la cuadricula y luego recorriendolos usando un ciclo for.

Paletizado en S:

Definiendo la cuadricula de la misma forma que en la rutina anterior, el unico cambio que se debe hacer en este caso es la forma en la que se usa el ciclo for para recorrer esta cuadricula ya que ahora la figura que debe seguir el robot es en forma de S como muestra la siguiente imagen.

![image](https://github.com/Jbarreraro/RoboticaLabEpson/assets/70239708/b0424709-d4c1-4757-bf63-26dcce5a1528)


# Video de Primeros Movimientos en Robot SCARA
En este primer video se muestra el ejercicio inicial, el cual consite en ir a 3 puntos previamente definidos mediante la operacion de enseñanza manual de aquellos puntos; donde se manipuló fisicamente de forma que se la herramienta se encontrara en los puntos deseados y se guardara aquella posicion en la memoria de robot. Se realizaron 3 movimientos distintos usando los comandos *move*, *go* y *jump*. El primero de estos comandos realiza un movimiento lineal desde el punto de origen hasta el punto de detino, el segundo realiza el movimineto de punto A a punto B de tal forma que lo hace usando un algortimo que no pide tantos recursos para operar y que no garantiza un movimento lineal pero si rapido. Por ultimo, el comando *jump* realiza un movimiento lineal de punto origen a  punto destino realizando un movimiento en la tercera articulacion llevando la herramienta a Z=0 y de regreso a su posicion inicial una vez ha llegado a su punto destino.
https://drive.google.com/file/d/1JvVPhqxk5jlifc67FBeYukoPVBREIzIJ/view?usp=sharing
# Video de Paletizado 
Este segund ovideo muestra las operaciones de paletizado en S y Z junto con un paletizado externo el cual permite alcanzar cada una de las concavidades del molde mostrado en el video.
https://drive.google.com/file/d/1K9kjpsfY8MNcmO08PnX7UPWOqlKnLlXd/view?usp=sharing



