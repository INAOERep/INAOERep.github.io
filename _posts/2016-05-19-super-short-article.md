# Curvas de luz

Una de las cosas más importantes que podemos estudiar de los objetos que observamos en el cielo es su luz que nos llega, tanto si es producida por ellos mismos (como en el caso de las estrellas) o si es reflejada (como los asteroides). Un astrónomo es un experto en la detección y el estudio de la luz, en todo tipo de longitud de onda (la longitud de onda es la distancia entre dos crestas o valles consecutivos de una onda). Es decir, es capaz de detectar luz en radiofrecuencia (>1 m), microondas (1 m-10^-2 m), luz en infrarrojo (10^-3 m-2.5*10^-6 m), luz visible (780*10^-9 m-380*10^-9 m), ultravioleta (380*10^-9 m- 200*10^-9), luz en rayos X (200*10^-9 m-10*10^-9 m) hasta los rayos gamma (<10*10^-12).

Uno de los aspectos que es de gran interés es observar cómo cambia esta luz que nos llega de un objeto, como varía la luz que observamos con el tiempo. Por ejemplo, imagine que observamos un faro lejano de una playa. La luz del faro da vueltas, por lo que no siempre observaremos la misma cantidad de luz; si estamos en la zona que está iluminada observaremos muchísima luz, pero cuando da media vuelta la fuente, estaremos observando muy poca luz, casi nada. Algo similar ocurre con muchos objetos en el espacio.

Un caso similar se tiene cuando se mide la luz de un asteroide. Un asteroide es parte de lo que se conoce como un cuerpo menor del sistema solar. A diferencia de los planetas, por ejemplo, no tienen una forma regular o simétrica. Más bien, un asteroide es como una papa, tiene formas irregulares, con algunas caras más grandes que otras, algunos son más alargadas que otros, etc, etc. Además, un asteroide no emite luz propia, es más como un espejo que refleja la luz del Sol. Por eso, dependiendo que cara refleje luz del Sol hacia nosotros, notaremos que recibimos más o menos luz del asteroide. Así, si graficamos la luz reflejada conforme avanza el tiempo, notaremos un comportamiento curioso. La gráfica sube y baja de maneras distintas, hasta que después de un cierto tiempo se repiten estas mismas formas de subir y bajar. Ese tiempo en el que el comportamiento de la luz se repite se llama **periodo** del asteroide.

Determinar el **periodo** de un asteroide es de los aspectos más importantes que se pueden encontrar si se estudia su curva de luz. Pero ¿Qué es una curva de luz? Una **curva de luz** es una gráfica que muestra cómo cambia el brillo de un objeto al pasar el tiempo. Este brillo puede recibir un valor numérico el cual se denomina **magnitud**. Debido a la atmósfera, el campo de visión, el Sol, la distancia asteroide-Tierra y asteroide Sol, entre otros factores, esta magnitud será **aparente**, es decir, no es el brillo propio del objeto. Además, por otros factores como el instrumento que se usa para medir la magnitud, el clima, etc, cuando se tienen imágenes del objeto, éstas deben pasar por un proceso que elimine todos los efectos no deseados antes de ser estudiadas.

Cuando ya se tienen las imágenes finales, es necesario identificar el asteroide, pues en la imagen se ven muchos puntos brillantes y es difícil determinar cuál es el asteroide si el observador no recuerda exactamente cuál era. Se puede recurrir a una técnica sofisticada para saber cuál es el asteroide de un conjunto de imágenes. Dicha técnica se llama hacer un “GIF”. Como un asteroide está más cerca de nosotros que los demás objetos brillantes (estrellas, quizá planetas, etc.), su movimiento es más notable, por lo que al poner en secuencia las imágenes se podrá identificar a simple vista donde está e incluso que camino siguió durante la noche en que se observó. 

Mediante algún software se mide su magnitud en cada imagen y se puede graficar finalmente en función del tiempo. Una gráfica como estas se puede observar a continuación (note que la fecha está dada en formato Juliano).

<img src="https://github.com/Kevin22062000/Servicio-Social/blob/main/771_Libera.PNG" width="475px" alt="400px"/>

Como las observaciones que se hacen a un objeto pueden variar en tiempo por días, semanas, meses e incluso años, es conveniente poner los datos en “fase”. Es decir, todas las observaciones de cada fecha que coincidan con una de las caras que nos dé el asteroide corresponderán a un solo valor o estarán alrededor de un solo valor en el eje x. De esta forma, si se observó una cara del asteroide en un momento dado y meses después se observó de nuevo, ambos datos coincidirán alrededor de un punto. Cuando se llega a la última cara del asteroide no se tendrán datos más allá, pues se volvería a estar en la cara que se graficó al inicio. Es por esta razón que los valores en el eje x van desde 0 hasta 1, pues en este extremo final el asteroide habrá dado una vuelta, es decir, habrá completado un periodo de rotación.

Otro aspecto que señalar es que las observaciones en diferentes fechas tienen una diferencia pequeña en su magnitud entre ellas. Por ejemplo, en una noche se observó que la mayor magnitud que se recibió de un asteroide fue de 14 y otra noche fue de 14.5. Esto no supone mayor problema que restar o sumar valores a los datos de una u otra noche para hacerlos coincidir.

## Construcción de una curva de luz

A continuación, se presenta la traducción de una actividad en la que podrá realizar su propia curva de luz. La actividad original se puede encontrar en el siguiente enlace: [](https://lco.global/education/activities/plotting-an-asteroid-light-curve/)

### Graficando una Curva de Luz de un Asteroide

### Resumen

Una de las cosas que esperamos que aprenda a través de la observación de objetos cercanos a la Tierra es su periodo exacto de rotación. Podemos hacerlo tomando una serie de observaciones del objeto a lo largo del tiempo, y trazando el cambio en el brillo. Usando [Asteroid Tracker](https://asteroidtracker.lco.global/) puede ayudar a colectar observaciones de objetos NEO interesantes, luego trazar e interpretar sus datos para medir el periodo de rotación de un asteroide.

### Objetivos

Los estudiantes trazarán y analizarán datos observacionales colectados por miembros del público usando *Asteroid Tracker*, y tratarán de medir el periodo de rotación del asteroide.

**Objetivos de Aprendizaje**

- Familiarizarse con asteroides y objetos cercanos a la Tierra
- Participar en el proyecto de ciencia ciudadana *Asteroid Tracker* y contribuir a ampliar nuestra comprensión del Sistema Solar
- Trazar una curva fotométrica usando datos observacionales
-	Interpretar graficas y reconocer la periodicidad en un conjunto de datos
-	Entender como y por qué los astrónomos estudian el periodo de rotación de un asteroide

### Planeación

**Materiales**

- Una computadora con software de hoja de cálculo y acceso a Internet
- Datos observacionales de asteroides tomados usando Asteroid Tracker, por ejemplo [2002 KL6](https://s3.us-west-2.amazonaws.com/www.lco.global/documents/2002_kl6.txt?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIA6FT4CXR4ZJRYWHNN%2F20220419%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20220419T005107Z&X-Amz-Expires=3600&X-Amz-SignedHeaders=host&X-Amz-Signature=de6c5de397f96b983613d533f9e5e1920d237e2bdbf784d4dd53ee67b91c23b4)
- Opcional: [hoja de cálculo de actividades de 2002 KL6](https://drive.google.com/file/d/1yPsU6ZDOwSuAHSx5PZvicfp_vDXsvJ3d/view)

### Trasfondo

Los Asteroides son objetos rocosos que orbitan el Sol, pero que son muy pequeños para considerarlos planetas. De hecho, son comúnmente conocidos como “Planetas Menores”.

<img src="https://github.com/Kevin22062000/Servicio-Social/blob/main/asteroids-graphic-updatedlogo-01.width-500.png"/>

La mayoría de los asteroides en nuestro Sistema Solar están localizados en el cinturón de asteroides, entre Marte y Júpiter. Sin embargo, hay algunos que han dejado esta región influenciados por las fuerzas gravitacionales ejercidas por los planetas, y están en caminos que los llevan cerca de la Tierra. Si se aproximan a la Tierra a una distancia menor que 1.3 UA (1 UA es la distancia entre la Tierra y el Sol), son considerados como Objetos Cercanos a la Tierra, o NEOs (por sus siglas en inglés). Observaciones de objetos cercanos a la Tierra pueden revelar información acerca de su tamaño, forma, composición, camino orbital y rotación.

Como los asteroides son cuerpos tan pequeños que residen lejos de la Tierra, a menudo lucen justo como estrellas ordinarias (pequeños puntos de luz). La diferencia es, dado que los asteroides están orbitando alrededor del Sol parecen moverse con respecto a las estrellas fijas en el fondo – así es como detectamos a los asteroides. Podemos observarlos en detalle tomando una serie de observaciones de corta exposición. La trayectoria de un asteroide a través del cielo puede determinarse midiendo con precisión la posición del asteroide en tiempos diferentes. Esto permitiría la determinación de la órbita del asteroide alrededor del Sol, y por lo tanto su trayectoria en el cielo en subsecuentes días, meses o años.

Encuentra más con [Space Book](https://lco.global/spacebook/solar-system/asteroids/).

### Asteroid Tracker

El Observatorio Las Cumbres está realizando actualmente una campaña internacional para observar Objetos Cercanos a la Tierra (NEOs) llamado *Asteroid Tracker*. Los participantes simplemente introducen su dirección de correo electrónico y el Observatorio Las Cumbres programará observaciones de un NEO objetivo cuidadosamente seleccionado. Cada campaña dura alrededor de un mes, poco después de lo cual los datos estarán disponibles.

Una de las cosas que esperamos aprender a través de observaciones tomadas con *Asteroid Tracker* es el periodo exacto de rotación de los asteroides. Podemos hacer esto tomando muchas imágenes del asteroide conforme se mueve a través del cielo y midiendo el brillo a medida que cambia con el tiempo.

### Instrucciones

Si usted quiere trazar sus **propios** datos, visite el [sitio de Asteroid Tracker](https://asteroidtracker.lco.global/) para llevar a cabo sus observaciones con anticipación.

Algunos datos están disponibles desde el *Asteroid Tracker* para el asteroide 2002 KL6. Puede descargar los datos sin procesar como un [archivo de texto (.txt)](https://s3.us-west-2.amazonaws.com/www.lco.global/documents/2002_kl6.txt?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIA6FT4CXR4ZJRYWHNN%2F20220419%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20220419T005107Z&X-Amz-Expires=3600&X-Amz-SignedHeaders=host&X-Amz-Signature=de6c5de397f96b983613d533f9e5e1920d237e2bdbf784d4dd53ee67b91c23b4) o descargar los datos en una [hoja de cálculo de Excel](https://drive.google.com/file/d/1yPsU6ZDOwSuAHSx5PZvicfp_vDXsvJ3d/view) pre hecha.

1. Si descargó la hoja de cálculo de Excel, salte al **Paso 4**. Si descargó sus datos como un archivo de texto (.txt o .dat) necesitará abrirlos en su software de hoja de cálculo (esta guía está basada en Microsoft Excel) y separe los datos en columnas. Haga esto seleccionando **datos>texto a columnas>delimitado**

2. Los datos necesitarán ser separados en nueve columnas (A-I), etiquetadas como se muestra debajo:

    A:	**Neo designation** (varias longitudes, números y txt)

    B:	**Year** (año)

    C:	**Month** (mes)

    D:	**Date** (día y segundos)

    E:	**RA** (normalmente un número de 6 cifras con 2 decimales) 

    F:	**Dec** (normalmente +/- y un número de 6 cifras con 1 decimal)

    G:	 **Magnitude** (generalmente un número de 1 ó 2 cifras con varios decimales)

    H:	**Filter** (denotado por una letra como ‘V’ que significa ‘visible’)

    I:	**Telescope Code** (un código hecho de varios números de letras y números).

    <img src="https://github.com/Kevin22062000/Servicio-Social/blob/main/asteroid-rotation-scrn10-700x150.max-1000x1000.png"/>

3. Ordene su hoja de cálculo por el **Telescope Code**. Borre todas las filas que no tengan el telescope code ‘**Z21**’, esto nos dejará con datos colectados por un telescopio LCO de 0.4 metros en el Observatorio Teide.

4. En esta actividad estaremos trazando el cambio en la magnitud (brillo) de un asteroide con el tiempo. Para hacer esto, haga un diagrama de dispersión de **date** y **magnitude**. Puede resaltar ambas columnas presionando **CMD** en una Mac o **CTRL** en un dispositivo Windows, luego seleccione **Gráfico>Gráfico de dispersión marcado.**

      <img src="https://github.com/Kevin22062000/Servicio-Social/blob/main/screen_shot_2017-02-24_at_12.39.57-737x364.max-1000x1000.png"/>
        
      Notará que hay brechas en los datos, como los mostrados en la imagen de arriba, dándonos una serie de curvas de luz parciales. El siguiente paso es combinar los datos y crear una curva de luz completa, hágalo siguiendo los pasos siguientes.
    
5. Si está usando la hoja de cálculo pre hecha, vaya a la segunda hoja llamada ‘**2002_KL6 (2)**’. Si ha creado tu propia hoja de cálculo, abra una nueva hoja de Excel y copie sus propios datos en ella. Puede hacer esto dando click derecho en la pestaña de la hoja y seleccionando **Mover o Copiar** y luego marcando **Crear una copia**. \*\*No borre su primera hoja o curva de luz\*\*.

6. Ahora necesitamos introducir el periodo de rotación del asteroide. El periodo de rotación será introducido en una columna llamada ‘**Period**’. Si le gustaría saber el periodo de rotación, sombree el siguiente texto
    
    4.61 horas
    
    De otra manera, debe introducir un periodo de rotación aleatorio, después inferir con qué precisión se basa el valor en la curva de luz que se trazará en el Paso 10. Como punto de partida le diremos que el plazo para 2002 KL6 es de entre 4.5 horas y 5 horas. Si ingresa el periodo de rotación correcto, debería ver una serie de curvas de luz apiladas. Si el valor es incorrecto, los datos aparecerán confusos y aleatorios. Simplemente cambia la cifra en la columna Period hasta que esté satisfecho con la curva de luz.
    
7. Ahora necesita convertir su periodo de rotación en una fracción de un día. En una columna llamada **Rotation**, use la siguiente ecuación para introducir el valor correcto en cada fila:

    **Periodo(hrs)/24(hrs)**

    <img src="https://github.com/Kevin22062000/Servicio-Social/blob/main/asteroid-rotation-scrn11-855x150-2.max-1000x1000.png"/>

8. Ahora usaremos el periodo de rotación y la fecha, para calcular la **Fase**. En una columna llamada **Phase**, use la siguiente ecuación donde INT convertirá la segunda cantidad en un número entero.

    **(fecha/rotación)-INT(fecha/rotación)**

9. Complete la **Phase** de cada fila.

10. Ahora crearemos un nuevo gráfico de dispersión para mostrar la magnitud del asteroide cambiando con el tiempo. Esta vez realice el gráfico usando los valores de **Phase** y **Magnitude**. Debería notar que las curvas de luz ahora están apiladas y los espacios se han eliminado, creando una curva de luz más clara y completa. Si este no es el caso, intente jugar con el valor de **Period** hasta que obtenga algo similar al gráfico de abajo.

    <img src="https://github.com/Kevin22062000/Servicio-Social/blob/main/2002_KL6_light_curve_pt1.max-600x600.png"/>

11. Los valores de menor magnitud significan que un objeto es más brillante y los picos siguen claramente una pendiente descendente. Haga click en el eje de magnitud y seleccione **Valores en orden inverso** para mostrar esto claramente.

12. Ahora, revise la primera curva de luz que realizó. ¿Nota que el asteroide parece iluminarse con el tiempo? ¿Qué cree que causó este brillo? Resalte el siguiente texto para ver la respuesta:

    ¡El asteroide viajaba más cerca de la Tierra!

    Este brillo es la razón por la que su gráfico más reciente tiene varios picos apilados directamente uno encima del otro. Para superponer estos picos, tendremos que compensar el brillo cambiando nuestros valores de magnitud a ojo. Cree una nueva columna para las magnitudes revisadas y continúe leyendo.

**Como compensar el brillo del asteroide**

Mirando atrás a su vieja curva, notará que mientras el asteroide aumentó su brillo con el tiempo, algunos de los picos son de magnitud similar. En el ejemplo de debajo podrá ver los puntos de los datos pueden ser separados en tres grupos con otros picos de la misma magnitud. Llamémoslos Grupo 1, Grupo 2 y Grupo 3 (moviéndonos de izquierda a derecha).

Como hay más puntos de datos en el Grupo 2, reduciremos la magnitud del Grupo 1, e incrementaremos la magnitud del Grupo 3 para que coincida. Los puntos de datos en el Grupo 2 permanecerán sin cambios.

Mirando mi gráfica, puedo ver que los puntos de datos en el Grupo 1 caen entre el 8-10 de junio y el pico en 16 mag, +0.25 mag comparado con el Grupo 2. Para alinear estos picos, necesito bajar todos los puntos de datos entre el 8-10 de junio 0.25 mag. Esto puede hacerse calculando **=SUM(magnitude-0.25)**

El último pico parece tomar lugar alrededor del 22 de junio, y alcanza su máximo de -0.35 en comparación con los primeros picos. Esto significa que deberá agregar 0.35 a todos los valores alrededor del 22 de junio.

Copie la magnitud para el Grupo 2 directamente desde la columna magnitude y haga un nuevo gráfico de dispersión mostrando **Altered Magnitude** y **Phase**. Si es necesario, siga ajustando sus valores de esta manera, hasta que haya alineado los picos en su gráfica (vea imagen debajo).

### Conclusión

Usted debería tener ahora una curva de luz sólida que muestre el cambio en el brillo del asteroide a lo largo del tiempo. ¡Felicidades!

1. ¿Cuál es el periodo de rotación del asteroide?  _ _ _ _ _ _ _ _ _ _ horas

2. ¿Alguno de sus compañeros de clase uso un periodo diferente? Compare sus gráficas finales. ¿Quién piensa que estuvo más cerca de la respuesta correcta?

Ahora, responda las siguientes preguntas para demostrar su entendimiento de como los astrónomos miden los periodos de rotación de los asteroides.

1. ¿Qué nos muestra esta curva de luz?

2. ¿Qué causa que varíe el brillo del asteroide?

3. ¿Se vería igual la curva de luz si el asteroide fuera esférico?

4. ¿Cuánto tiempo le toma a su asteroide rotar usando solo su curva de luz final?

    a. ¿Cómo midió el periodo de rotación?

5. ¿La magnitud general creció progresivamente más alto o bajo con el tiempo?

    a. ¿Por qué podría suceder esto?
