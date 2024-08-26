# Obtener dispositivos

En este paso la PC no tiene un dispositivo al mandarle datos (Esto puede ser por que perdio la conexion o no la tuvo en primer lugar), entonces obtiene y le manda bytes especificos para obtener la version del dispositivo y luego manda los datos (creados por el programa) del dispositivo con el protocolo AOA (Android Open Accesory, para colocar el dispositivo en modo accesorio), si recive una respuesta positiva, va a conectarse y a empezar a mandar [frames](enviar-frames.md).
