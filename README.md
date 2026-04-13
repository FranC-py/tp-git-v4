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

