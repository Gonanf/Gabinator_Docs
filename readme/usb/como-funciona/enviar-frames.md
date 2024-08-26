# Enviar Frames

En este paso la PC ya tiene un [dispositivo compatible ](obtener-dispositivos.md)conectado y listo para mandar frames, entonces va a obtener el Desktop Window con el WinAPI (Por ahora no tiene  cursor) y luego lo va a comprimir a .jpg en la memoria con TurboJPEG, entonces va a mandar un paquete que contiene los bytes de la imagen comprimida a Gabinator\_Android y esperara a que reciva el paquete exitosamente para luego hacerlo otra vez, por siempre.
