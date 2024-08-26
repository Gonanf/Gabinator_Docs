---
description: Como funciona Gabinator_Desktop TCP
---

# Como funciona

## Gabinator\_Desktop utiliza:

WinAPI -> Para obtener el frame.

TCP -> Para iniciar una conexion como server y mandar los datos a un cliente.

TurboJPEG -> Para comprimir el frame a JPG.



### Funcionamiento

Gabinator\_Desktop empieza a escuchar por TCP (LAN o WLAN) como un servidor, si algun dispositivo se intenta conectar, este acepta y le empieza a mandar los datos de imagen
