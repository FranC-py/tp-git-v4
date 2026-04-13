# Proyecto Final

## Problema
¿Alguna vez te preocupaste de que tus abuelos o padres puedan sufrir un accidente y que no este enterado?, una encuesta realizada en el instituto técnico salesiano Villada nos mostro el como varios alumnos se preocupan por sus abuelos que viven solos o también profesores que se preocupan de sus padres ya ancianos.


Esto no es exageración, ya que puedan pasar muchas cosas y si uno no se entera a tiempo pueden derivar en situaciones como golpes fuertes, robos, o en situaciones mas graves hacia ser querido.

Estar informado es algo importante, así que proponemos la siguiente idea:

## Solución

El trabajo consiste en una pulsera que monitorea el pulso todo el tiempo y detecta caídas. Capaz le sumamos oxígeno en sangre, dependiendo del sensor que terminemos usando. Aparte de sensar eso, va a tener un botón físico de S.O.S.

Al detecta un problema (pulso anormal, caída o aprietan el S.O.S.), la pulsera manda un mensaje de emergencia a los familiares mediante un bot de Telegram. El mensaje te dice qué problema hubo, los niveles de pulso y las coordenadas exactas.

3 características:

- Botón de cancelación: Como al detectar una caída no tiene forma de saber si es real o una falsa alarma, le damos al usuario un margen de 10 segundos para apretar un botón y cancelar el envío del mensaje.

- Independiente del WiFi: Para que la puedan usar en cualquier lado, le ponemos un módulo con una tarjeta SIM (como las de Claro o Personal) y manda la info con sus propios datos.

- Cargador magnético: Para garantizar que el usuario no se saque la pulsera para cargarla (y se olvide de ponérsela), le hacemos un módulo de cargador portátil. Se pega de forma magnética encima de la pulsera y la carga puesta, garantizando que el monitoreo no se corte.


## Componentes a utilizar

Estos módulos a continuación son algunos de los que tenemos en mente para utilizar.

Placa: XIAO ESP32 S3 Sense
Microcontrolador compacto y potente con conectividad WiFi y Bluetooth integrada. Permite procesamiento de datos en tiempo real y tiene bajo consumo energético.

Giroscopio (para detectar caídas): MPU6050
Sensor utilizado en sistemas de detección de caídas por su buena precisión y tamaño reducido.

Sensor de pulsos y oxígeno en sangre: MAX30102
Módulo que mide la frecuencia cardíaca y la saturación de oxígeno mediante luz infrarroja. Se destaca por su bajo consumo.

Comunicación inalámbrica con internet (con tarjeta SIM): SIM800L
Módulo GPRS que permite enviar datos a través de la red móvil usando una tarjeta SIM. Ideal donde no hay acceso a WiFi y se necesita comunicación remota.:wq

## Autores 

- CASTILLO Franco
- CERRI Valentín
- SALATIN Francisco
- VIRGOLINI Santiago

<<<<<<< HEAD
Cambio 1: Castillo
Cambio 2: Castillo
Cambio 3: Castillo
Cambio 1: Cerri
Cambio 2: Cerri
Cambio 3: Cerri
cambios 1 - salatin
cambios 2 - salatin
cambios 3 - salatin
Cambio 1: Virgolini
Cambio 2: Virgolini
Cambio 3: Virgolini

## Respuestas de actividad 2.6

1. Guardar versiones manualmente es un método propenso al caos. Usar un sistema de control de versiones como Git ofrece ventajas estructurales y técnicas que hacen el trabajo mucho más profesional y seguro.

2. git add: Se usa para seleccionar los archivos o cambios que querés incluir en el próximo guardado. 

git commit: Sirve para guardar esos cambios de forma permanente en el historial del proyecto pero agregando un mensaje que explicque qué se hizo. Importante que sea claro el mensaje.

git pull: Se usa para traer a tu compu los cambios que están en el repositorio, así se agregan al proyecto actualizaciones que hicieron otros.

git push: permite subir tus cambios al repositorio, para que queden guardados y a disposición para los demás.

4. En un proyecto real, usamos ramas principalmente para trabajar tranquilos sin romper lo que ya funciona, ya que nos permiten separar cada tarea nueva o cada arreglo de errores en un espacio propio. Esto sirve para que varios compañeros puedan avanzar en distintas partes del código al mismo tiempo sin mezclarse ni borrarse cosas entre sí; además, funcionan como un campo de pruebas donde podemos experimentar cambios arriesgados con la seguridad de que, si algo sale mal, la versión principal del proyecto sigue intacta y operativa. Finalmente, las ramas son fundamentales para revisar el trabajo antes de darlo por terminado, asegurando que solo el código que realmente funciona se sume al resultado final.

5. El git rebase es una técnica que permite integrar cambios de una rama a otra manteniendo un historial lineal y limpio. A diferencia del merge tradicional, que crea un nuevo "commit de unión" conectando dos ramas, el rebase "vuelve a escribir" la historia: toma los commits de la rama de trabajo, los desplaza temporalmente y los vuelve a aplicar uno por uno justo después del último commit de la rama base. Esto elimina las ramificaciones innecesarias en el gráfico del repositorio, facilitando la lectura del progreso del proyecto como si todos los cambios se hubieran realizado en una única secuencia lógica y ordenada.
