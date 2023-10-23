[toc]

# PROCEDIMIENTO DE ANÁLISIS DE ESPECIES ARSENICALES MEDIANTE  HPLC-ICP-MS

<span  style="color:red">**IMPORTANTE: SEGUIR ESTAS INSTRUCCIONES RIGUROSAMENTE**</span>

1-   Encendemos el ICP-MS como habitualmente. Es decir, abrimos el argón tanto fuera como en el laboratorio, activamos el automuestreador y le quitamos la tapa, comprobamos que la botella de HNO3 1% está llena, abrimos el He, encendemos el cooling water, encendemos el aire acondicionado, activamos la campana extractora.

<img src="Apertura de gases.png" style="zoom:50%;" />

2-   Conectamos el capilar procedente del HPLC al nebulizador del ICP-MS, aunque se puede comenzar a trabajar con el método de HPLC en el ordenadors antes de cambiar el cableado. 

<img src="Capilar LC.png" style="zoom:50%;" />

3-   Encendemos el HPLC, encendiendo en último lugar la bomba A, puesto que esta cuenta con el controlador del equipo. Por el mismo motivo, cuando apaguemos el HPLC, la bomba A será el primer componente que apagaremos. Esto se realiza de esta forma para evitar errores de conexion entre el equipo y el ordenador. 

4-   Encendemos el PC y cargamos el programa indicado para controlar el HPLC-ICP-MS (Lab Solutions TRM – Analysis – Cargamos un método, Type 1 o 2 según las características deseadas para nuestro análisis. En este caso abrimos “Tipo 2 270923”) y comprobamos que el tubo que conduce el HNO3 al ICP-MS está correctamente conectado (comprobamos el flujo activando la bomba peristáltica). El tipo 2 es el método isocrático y por lo tanto solamente se utilizará un fase mobil. Ambos métodos, tipo 1 y tipo 2 se generación partiendo del método base acuosa sin colisión (water based mini torch LC). Parece que el método de colisión puede reducir la sensibilidad. Es importante recordar que para llevar a cabo los análisis de muestras además del métotodo tipo 1 (gradiente) y tipo 2 (isocrátrico) se van a utilizar los métodos de start up y shut down.

5-   Colocamos la columna que nos convenga en función del método empleado (ver recomendaciones de Shimadzu). Para ello, sacaremos tubo por los peaks (como medio cm) para que al acoplar los peaks a la columna notemos que el tubo es introducido hasta hacer tope. Después enroscaremos el peak sujetándolo firmemente a la columna para no dejar ningún volumen muerto que pueda afectar nuestro análisis. 

<img src="Cambio columna.png" style="zoom:50%;" />



6-   Clicamos en Method - LC Measurement conditions, y revisamos que las condiciones sean las indicadas en el método que nos proporcionó Shimadzu (no haremos cambios, e principio estará todo bien). En Méthods nos dice los elementos que están conectados para el análisis. La antorcha, cooling chamber, bomba peristaltica y el LC. El LC lo pone ya por defecto, pues es el program de especiación. También incluye los parámetros del plasma. 

7-   Clicamos en Method - Analysis and mass registration, y comprobamos que en el caso del arsénico está seleccionado: Cuantitativo. Seguimos en Método. LC messurement conditions. Aquí hay que meter los datos de métod tipo 2. Como este método solo tiene una bomba ponemos 100% bomba A. Presión máxima 125. Nota: hemos hecho un cambion en el tipo 1 - bomba A para soluciones acuosas (agua o phase mobil acuosa). La bomba B sería para las sales (es muy importante que después de utilizar sales se limpien bien todos los capilares pues puede haber precipitados que pueden generar problemas). En métodos hay varias pestañas (ej. temperatura del horno). Valvula inicialmente en 0 y solo cuando inyecte se ponga en 1 y pase por la columna. Para esto hemos generado un comando.  Esto significa una vez inyecta la muestras pasa por la coumna durante los 10 min que dura el método luego pasa a lavado. Seguimos con elementos de análisis. En este caso arsénico. Hay que seleccionar, cuantitativo y luego le ponemos a add. El ratio tiene que ver cuando hay varias masas. La masa mayoritario en relación a otras masas. Si añadidos patrón interno sería necesario el ratio. Estoy hay que verlo. No queda claro si necesitamos patrón interno. En principio dejeamos solamente As y las correcciones con la formula. Al final le damos OK.

8-   Clicamos en Method - Compound registration, y comprobamos que tenemos incluidas las especies arsenicales de nuestro interés (posteriormente ajustaremos los tiempos de retención de los compuestos para que el equipo integre los picos detectados correctamente; nos indicará que detecta intensidad, pero en realidad es área). Normalmente, en la integración se trabaja con porcentaje (Window). Registration compound. Para ello pichamos muestras desconocidas para ver donde caen los picos para saber los tiempos de retenciaión. Luego fijaremos los tiempo. Para ello primero hay que pasar los patrones como desconocidos para cada una de los patrones a analizar. En este apartado tambien hay que decirle cómo tiene que integrar los picos. El slope, window, ... dbl es el tiempo de doblaje. Le decimos al equipo como tiene que detectar los picos. De hecho hemos visto que al pasar estándares dice intensidad pero es área. Finalmente le decimes qué es cada pico. Los picos en cromatografía se puede mover y por la tante es importante como tiene que integrar el pico mas o menos. Se puede hace con porcenje o por bandas. Normalmente se trabaja en porcentaje o window. En nuestro caso solamente tenemos un compuesto pero con diferentes especies. Junto a los nombre se pondrían los tiempos de retención. 

9-   Clicamos en Method - Standard registration, y debemos tener, en este caso, 3 patrones que incluyen las especies de interés, a las siguientes concentraciones: 12,5, 25 y 50 ppb. Standard registration. Cuantos estándares. En la práctica tuvimos 3 patrones. En este caso sería bueno poner la mezcla pero tambien se podrían meter de forma individual. De todas formas recordar que yo en QUB soliamos hacer la curva de calibración para DMA. Una vez completo el método le damos a análisis sample registration para añadir la secuencia y patrones. Con las posiciones. El rack 0 que es el de patrones y el rack 1 es el de las muestras. El rack 1 es de 105. Se puede utilizar el rack 1 para todo patrones y muestras. Esta marcado en los racks si es 1 o 0.

> Nueva carpeta HPLC para meter el método. Para guardar el método hay que utilizar extract method. Save as es solo para las muestras. imtd (acabado en d es datos) esto con save as (método más resultados).  imtm (acabodo en m es método) extract method (salvamos en la estructura del método). Esto se refeiere a la extensión de los archivos. Lo imtd contiene el método y los datos con el imtm tiene solamente el método sin datos. 

10- Encendemos el plasma. Asegurarnos que todos los equipos estaán conectados con los capilares correspondientes. Antes de encender el plasma es importante que el capilar del HPLC esté conectado con el ICP-MS. Los otros dos capilar el IPC-MS se pueden quitar de la bomba peristaltica para que no saquen agua. Es posible que busque el automuestredos del ICP-MS, uanque no lo va a utilizar. 

11- Cambiamos el agua ultrapura tipo I de las bombas A y B (ese agua es de lavado, sirve para limpiar las bombas de vez en cuando), limpiándolas previamente con agua ultrapura tipo I. Realizamos el cambio de agua de las botellas para evitar que crezcan algas. 

<img src="Viales agua LC.png" style="zoom:50%;" />



12- Cambiamos el agua de las botellas pyrex que contienen agua ultrapura tipo I como fase móvil para evitar que crezcan algas.

13- Ponemos la fase móvil indicada en la bomba que corresponda, en este caso ácido fórmico al 1% (+ otros componentes) en la bomba A.

14- Clicamos en Analysis – LC StartUp y cargamos el método StartUp indicado, que debería cebar las bombas. En este caso, seleccionamos el Tipo 2 (en el botón Select) y clicamos run para que comience (si no está en hora el método, lo ajustaremos). En el caso que en las bombas lleven mucho tiempo paradas es posible que sea necesario realizar un purga manual. Para ello utilizaremos un jeringuilla y abriremos y cerraremos de forma manuel las válculas del HPLC. Hemos generado un método start up. Este método debería de hacer el cebado de la bomba y demás. Esto se hace en análisis. Es es como un método más que haga la autopurga y que ponga la concentración inicial. Este lo salvamos como start up tipo 2. En este solo está la bomba A en funcionamiento. Le damos a run para que comience. Esto se puede poner que lo ejecute en distinto tiempos. Este método hay que pasarlo para hacer el linkeado con el HPLC. Es necesario hacer el start up para que funcieno todo en unísono. Es importante que en este paso la fase mobil ya esté en posición cuando se inicia el startup. 

<img src="Purga manual.png" style="zoom:50%;" />

<img src="Purga manual 1.png" style="zoom:50%;" />

<img src="Purga manual 2.png" style="zoom:50%;" />

15- Clicamos en View - LC Monitor, y vemos que está Waiting for oven y que los tres ítems presentan un recuadro azul alrededor, ya que esto indica que están activos y que el método de StartUp está adquiriendo las condiciones iniciales. La válvula está en 0, lo que quiere decir que está tomando HNO3 1% de la botella correspondiente e introduciéndolo en el ICP-MS, mientras que lo que sale de la columna está yendo a deshechos. Cuando alcanza condiciones de temperatura, empieza a hacer la purga de la bomba A (podemos ver Purging A en LC Monitor).

16- Cuando en LC Monitor observamos que el equipo está Ready tras haber realizado las purgas de las bombas, introducimos el capilar de HPLC, que se encontraba en la botella de HNO3 1%, en la solución Tuning A y probamos a pasar la calibración interna, concretamente los ítems Torch position y P/A Calibration. Para la calibración/tuning se utilizar el capilar de HPLC. El que tenemos en la botella del HNO3 al 1%. Recordar que la valvula tiene que estar en 0. Para si está en 0 se puede ver en LC monitor. El LC monitor es muy útil para ver las condicones del HPLC.

17- Una vez que hemos pasado la calibración interna del equipo, sacamos el capilar que habíamos introducido en la solución Tuning A, lo limpiamos con un papel y lo volvemos a introducir en la botella de HNO3 1%. Instrument calibraction. Nos piede la posición R7 pero da un poco igual pues está aspirado por el capilar del HPLC. 

18- Introducimos en el rack los patrones (especies aisladas) que vamos a medir, poniéndole a los tubos de muestra la tapa para que el automuestreador los reconozca. Pasamos los patrones como muestras desconocidas para comprobar los tiempos de retención de cada una de las especies arsenicales.

19- Para analizar los patrones como muestras desconocidas clicamos Sample registration y metemos, en este caso, las 4 muestras desconocidas (una para cada especie). El rack 1 es el de las muestras y el rack 0 es el de los patrones (cuando te sale posición 1:2, por ejemplo, hace referencia al rack 1 y a la posición 2). Volvemos a introducir el rack 1 en su lugar dentro del automuestreador del HPLC al fondo, hasta notar un click. Ponemos las muestras en el rack 1 y seleccionamos las posiciones. El rack tiene una tapa que hay que quitar para poner bien los viales y luego. Recardar también que los viales tienes tapadera. La tapadera es importante, pues el autosampler lo va a buscar. La aguja tiene un enganche. La parte de arriba del rack 1 se puede quitar pero es recomendable ponerlo. Metemos en rack dentro y le damos al start de método de análisis. El rack tiene que estar bien puesta y hacer tope con la pestaña final bien colocada. 

20- Tras indicarle al equipo que comience a medir, nos notificará un mensaje advirtiéndonos de que no hemos realizado el análisis de la recta de calibrado. Aceptamos, puesto que no nos interesa realizarla aún, ya que necesitaremos para ello los tiempos de retención de las distintas especies (para ello pasamos patrones con las especies conocidas - unknown samples). Se puede ver los pasos que hace el HPLC en el LC monitor. 

21- Tras comenzar la medida de las muestras, en LC Monitor observamos el mensaje “Pretreatment” mientras introduce la muestra, y “Running” mientras realiza el cromatograma. Si se abre la compuesta del automuestreador se puede ver como se succiona la muestra. En este sentido va a apaciendo el cromatrograma. 

> Observamos que la presión de la columna está en torno a 65 bares, estos valores son normales, por lo que debemos prestar atención a si este valor aumenta o disminuye.

22- Tras haber medido los patrones de especies aisladas, cambiamos al menú Profile, concretamente a Profile selection, indicamos Select all, tanto en los elementos como en las muestras y podremos ver todos los picos de los cromatogramas. En este menú registraremos los tiempos de retención de cada uno de los picos y los apuntaremos.

23- Clicamos Method - Compound registration, y cambiamos los tiempos de retención de las distintas especies arsenicales según los tiempos que hemos ido obteniendo en nuestros resultados. Si algún pico sale mal, le pondremos de tiempo de retención 0.001 min.

24- Podemos cambiar la integración de los picos seleccionando el que nos interese en el menú Profile – Profile selection, y abajo a la derecha observamos el menú Integration. Aquí es interesante aumentar el slope, que es la inclinación del pico, si lo aumentas, el software integrará únicamente los picos que tienen una inclinación mayor, descartando de este modo los picos pequeños. Donde están los cromatrogramas se pueden modificar las condiciones de integración para ajustar las integraciones. Se puede aumentar el slope. Modificar las ingraciones de los picos. La integrar los picos hay que in a profile. 

25- Cuando hemos terminado de medir las muestras de interés, clicamos Analysis – LC Shutdown settings, seleccionamos en este caso el de tipo 2, desmarcamos que haga el shutdown al apagar el plasma. En LC Monitor apagamos el Column oven, apagamos la bomba en el ítem “Binary gradient” clicando el icono de arriba a la izquierda, cambiamos la alcachofa de la bomba A a agua ultrapura tipo I y le volvemos a clicar al ítem “Binary gradient” para poner de nuevo en funcionamiento la bomba A, limpiando de este modo el equipo HPLC por dentro. Mantenemos la válvula del HPLC en la posición 0 para que vaya pasando el HNO3 1% al ICP-MS, mientras que la fase móvil que ha pasado a través de los conductos del HPLC y de la columna es descartada al bidón de residuos. 

26- Tras 10 minutos introduciendo HNO3 1% al ICP-MS, antes de apagar el plasma, le ponemos agua MQ durante otros 10 minutos. Para ello, cambiamos el capilar que se encuentra en la botella del HNO3 a un tubo Falcon con agua MQ. Transcurridos 10 minutos, apagamos el plasma.

27- Debido a que habíamos cargado el método Shutdown previamente, al apagar el plasma tras haber realizado la limpieza de los equipos, esta secuencia comienza. Tiene una duración de 10 minutos y lo que hace principalmente es apagar la bomba del HPLC lentamente. Aprovechamos estos 10 minutos para ir apagando el ICP-MS; es decir, cerramos el argón tanto fuera como en el laboratorio, desactivamos el automuestreador y le ponemos la tapa, cerramos el He, apagamos el cooling water, apagamos el aire acondicionado y desactivamos la campana extractora.

28- Guardamos los resultados con “Save”, cerramos el software y apagamos el ordenador. Seguidamente, apagamos el HPLC, apagando primero la bomba A que tiene el controlador del HPLC, tras ello apagamos los otros 3 componentes en el orden de nuestra preferencia (es indiferente).



Tipo 1 (método de gradiente)

1. Generamos en método de análisis, start up y shutdown. La principal diferencia con el tipo 2 es el gradeite pues tenemos en marcha las dos bombas. La bomba B tiene las sales. Esto también es importante para el start up y shut down que deben de tener la purga de las dos bombas. 
2. Recordar colocar las fases mobiles. En B las de sales y en A las acuoasas.
3. Recorda que en shut down hay que poner las dos fases mobies en A la solución acuosa. Es importante que en toda la coducción que agua. Esto se puede cambiar de forma rápida. Eliminar todo el fosfato que pueda quedar en todas las conducciones. 
4. Para apagar donde está la columna hay que presional el boton.


