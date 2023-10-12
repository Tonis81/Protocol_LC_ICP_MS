[toc]

# PROCEDIMIENTO DE ANÁLISIS DE ESPECIES ARSENICALES MEDIANTE  HPLC-ICP-MS

<span  style="color:red">**IMPORTANTE: SEGUIR ESTAS INSTRUCCIONES RIGUROSAMENTE**</span>

1-   Encendemos el ICP-MS como habitualmente. Es decir, abrimos el argón tanto fuera como en el laboratorio, activamos el automuestreador y le quitamos la tapa, comprobamos que la botella de HNO3 1% está llena, abrimos el He, encendemos el cooling water, encendemos el aire acondicionado, activamos la campana extractora.

<img src="Apertura de gases.png" style="zoom:50%;" />





2-   Conectamos el capilar procedente del HPLC al nebulizador del ICP-MS.

3-   Encendemos el HPLC, encendiendo en último lugar la bomba A, puesto que esta cuenta con el controlador del equipo. Por el mismo motivo, cuando apaguemos el HPLC, la bomba A será el primer componente que apagaremos.

4-   Encendemos el PC y cargamos el programa indicado para controlar el HPLC-ICP-MS (Lab Solutions TRM – Analysis – Cargamos un método, Type 1 o 2 según las características deseadas para nuestro análisis. En este caso abrimos “Tipo 2 270923”) y comprobamos que el tubo que conduce el HNO3 al ICP-MS está correctamente conectado (comprobamos el flujo activando la bomba peristáltica).

5-   Colocamos la columna que nos convenga en función del método empleado. Para ello, sacaremos tubo por los peaks (como medio cm) para que al acoplar los peaks a la columna notemos que el tubo es introducido hasta hacer tope. Después enroscaremos el peak sujetándolo firmemente a la columna para no dejar ningún volumen muerto que pueda afectar nuestro análisis. 

6-   Clicamos en Method - LC Measurement conditions, y revisamos que las condiciones sean las indicadas en el método que nos proporcionó Shimadzu (no haremos cambios, e principio estará todo bien).

7-   Clicamos en Method - Analysis and mass registration, y comprobamos que en el caso del arsénico está seleccionado: Cuantitativo.

8-   Clicamos en Method - Compound registration, y comprobamos que tenemos incluidas las especies arsenicales de nuestro interés (posteriormente ajustaremos los tiempos de retención de los compuestos para que el equipo integre los picos detectados correctamente; nos indicará que detecta intensidad, pero en realidad es área). Normalmente, en la integración se trabaja con porcentaje (Window).

9-   Clicamos en Method - Standard registration, y debemos tener, en este caso, 3 patrones que incluyen las especies de interés, a las siguientes concentraciones: 12,5, 25 y 50 ppb.

10- Encendemos el plasma

11- Cambiamos el agua ultrapura tipo I de las bombas A y B (ese agua es de lavado, sirve para limpiar las bombas de vez en cuando), limpiándolas previamente con agua ultrapura tipo I. Realizamos el cambio de agua de las botellas para evitar que crezcan algas. 

12- Cambiamos el agua de las botellas pyrex que contienen agua ultrapura tipo I como fase móvil para evitar que crezcan algas.

13- Ponemos la fase móvil indicada en la bomba que corresponda, en este caso ácido fórmico al 1% (+ otros componentes) en la bomba A.

14- Clicamos en Analysis – LC StartUp y cargamos el método StartUp indicado, que debería cebar las bombas. En este caso, seleccionamos el Tipo 2 (en el botón Select) y clicamos run para que comience (si no está en hora el método, lo ajustaremos).

15- Clicamos en View - LC Monitor, y vemos que está Waiting for oven y que los tres ítems presentan un recuadro azul alrededor, ya que esto indica que están activos y que el método de StartUp está adquiriendo las condiciones iniciales. La válvula está en 0, lo que quiere decir que está tomando HNO3 1% de la botella correspondiente e introduciéndolo en el ICP-MS, mientras que lo que sale de la columna está yendo a deshechos. Cuando alcanza condiciones de temperatura, empieza a hacer la purga de la bomba A (podemos ver Purging A en LC Monitor).

16- Cuando en LC Monitor observamos que el equipo está Ready tras haber realizado las purgas de las bombas, introducimos el capilar de HPLC, que se encontraba en la botella de HNO3 1%, en la solución Tuning A y probamos a pasar la calibración interna, concretamente los ítems Torch position y P/A Calibration.

17- Una vez que hemos pasado la calibración interna del equipo, sacamos el capilar que habíamos introducido en la solución Tuning A, lo limpiamos con un papel y lo volvemos a introducir en la botella de HNO3 1%.

18- Introducimos en el rack los patrones (especies aisladas) que vamos a medir, poniéndole a los tubos de muestra la tapa para que el automuestreador los reconozca. Pasamos los patrones como muestras desconocidas para comprobar los tiempos de retención de cada una de las especies arsenicales.

19- Para analizar los patrones como muestras desconocidas clicamos Sample registration y metemos, en este caso, las 4 muestras desconocidas (una para cada especie). El rack 1 es el de las muestras y el rack 0 es el de los patrones (cuando te sale posición 1:2, por ejemplo, hace referencia al rack 1 y a la posición 2). Volvemos a introducir el rack 1 en su lugar dentro del automuestreador del HPLC al fondo, hasta notar un click.

20- Tras indicarle al equipo que comience a medir, nos notificará un mensaje advirtiéndonos de que no hemos realizado el análisis de la recta de calibrado. Aceptamos, puesto que no nos interesa realizarla aún, ya que necesitaremos para ello los tiempos de retención de las distintas especies. 

21- Tras comenzar la medida de las muestras, en LC Monitor observamos el mensaje “Pretreatment” mientras introduce la muestra, y “Running” mientras realiza el cromatograma. 

*Observamos que la presión de la columna está en torno a 65 bares, estos valores son normales, por lo que debemos prestar atención a si este valor aumenta o disminuye.

22- Tras haber medido los patrones de especies aisladas, cambiamos al menú Profile, concretamente a Profile selection, indicamos Select all, tanto en los elementos como en las muestras y podremos ver todos los picos de los cromatogramas. En este menú registraremos los tiempos de retención de cada uno de los picos y los apuntaremos.

23- Clicamos Method - Compound registration, y cambiamos los tiempos de retención de las distintas especies arsenicales según los tiempos que hemos ido obteniendo en nuestros resultados. Si algún pico sale mal, le pondremos de tiempo de retención 0.001 min.

24- Podemos cambiar la integración de los picos seleccionando el que nos interese en el menú Profile – Profile selection, y abajo a la derecha observamos el menú Integration. Aquí es interesante aumentar el slope, que es la inclinación del pico, si lo aumentas, el software integrará únicamente los picos que tienen una inclinación mayor, descartando de este modo los picos pequeños.

25- Cuando hemos terminado de medir las muestras de interés, clicamos Analysis – LC Shutdown settings, seleccionamos en este caso el de tipo 2, desmarcamos que haga el shutdown al apagar el plasma. En LC Monitor apagamos el Column oven, apagamos la bomba en el ítem “Binary gradient” clicando el icono de arriba a la izquierda, cambiamos la alcachofa de la bomba A a agua ultrapura tipo I y le volvemos a clicar al ítem “Binary gradient” para poner de nuevo en funcionamiento la bomba A, limpiando de este modo el equipo HPLC por dentro. Mantenemos la válvula del HPLC en la posición 0 para que vaya pasando el HNO3 1% al ICP-MS, mientras que la fase móvil que ha pasado a través de los conductos del HPLC y de la columna es descartada al bidón de residuos. 

26- Tras 10 minutos introduciendo HNO3 1% al ICP-MS, antes de apagar el plasma, le ponemos agua MQ durante otros 10 minutos. Para ello, cambiamos el capilar que se encuentra en la botella del HNO3 a un tubo Falcon con agua MQ. Transcurridos 10 minutos, apagamos el plasma.

27- Debido a que habíamos cargado el método Shutdown previamente, al apagar el plasma tras haber realizado la limpieza de los equipos, esta secuencia comienza. Tiene una duración de 10 minutos y lo que hace principalmente es apagar la bomba del HPLC lentamente. Aprovechamos estos 10 minutos para ir apagando el ICP-MS; es decir, cerramos el argón tanto fuera como en el laboratorio, desactivamos el automuestreador y le ponemos la tapa, cerramos el He, apagamos el cooling water, apagamos el aire acondicionado y desactivamos la campana extractora.

28- Guardamos los resultados con “Save”, cerramos el software y apagamos el ordenador. Seguidamente, apagamos el HPLC, apagando primero la bomba A que tiene el controlador del HPLC, tras ello apagamos los otros 3 componentes en el orden de nuestra preferencia (es indiferente).
