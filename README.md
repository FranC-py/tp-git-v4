# Proyecto Final

## Solución

El trabajo consiste en una pulsera que monitorea el pulso todo el tiempo y detecta caídas. Capaz le sumamos oxígeno en sangre, dependiendo del sensor que terminemos usando. Aparte de sensar eso, va a tener un botón físico de S.O.S.

Al detecta un problema (pulso anormal, caída o aprietan el S.O.S.), la pulsera manda un mensaje de emergencia a los familiares mediante un bot de Telegram. El mensaje te dice qué problema hubo, los niveles de pulso y las coordenadas exactas.

3 características:

- Botón de cancelación: Como al detectar una caída no tiene forma de saber si es real o una falsa alarma, le damos al usuario un margen de 10 segundos para apretar un botón y cancelar el envío del mensaje.

- Independiente del WiFi: Para que la puedan usar en cualquier lado, le ponemos un módulo con una tarjeta SIM (como las de Claro o Personal) y manda la info con sus propios datos.

- Cargador magnético: Para garantizar que el usuario no se saque la pulsera para cargarla (y se olvide de ponérsela), le hacemos un módulo de cargador portátil. Se pega de forma magnética encima de la pulsera y la carga puesta, garantizando que el monitoreo no se corte.

