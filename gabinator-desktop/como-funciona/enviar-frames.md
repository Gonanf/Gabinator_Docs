# Enviar Frames

En este paso la PC ya tiene un [dispositivo compatible ](obtener-dispositivos.md)conectado y listo para mandar frames, entonces va a obtener el Desktop Window con el WinAPI (No obtiene el cursor, eso se le agrega luego en el proceso) y luego lo va a comprimir a .jpg en la memoria con OpenCV, entonces va a mandar un paquete que contiene los bytes de la imagen comprimida a Gabinator\_Android y esperara a que reciva el paquete exitosamente para luego hacerlo otra vez, por siempre.
