# MPi3
CAN-BUS enabled MP3 Player in Python (Running on Raspberry Pi)

Plays music stored in sqlite-DB based on the amount of before plays with possibility to delete song from playmode.
Controlls via Opel Astra H steering wheel buttons (UP+DOWN).
Writes data to Opel Astra H Graphic or Color display.

Uses MCP2515 and MCP2551 CAN-Transciever for Communication with vehicles midspeed-CAN-bus.
A working CAN-Setup is required.


# MPi3
Reproductor MP3 programado en Python via CAN-BUS (Corriendo en Raspberry Pi)

Reproduce música almacenada en una base de datos SQlite, con posibilidad de eliminar canciones del modo de reproducción
Controlado a través de los mandos del volante (Arriba + Abajo)
Muestra la información de las canciones en pantallas GID y CID, con CD70 NAVI y DVD90 NAVI con modo AUX.
En otras radios, no se garantiza el funcionamento.

Usa los transceptores CAN CP2515 y MCP2551 para comunicarse via CAN-BUS de velocidad media
Se requiere una configuración del modulo CAN funcional.

Can-BUS Astra :
Alta velocidad:   500Kbps (2 Cables)
Media velocidad:   95Kbps (2 Cables)
Baja velocidad:  33.3Kbps (1 Cable)
