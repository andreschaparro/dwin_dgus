# Pantallas DWIN DGUS

La pantalla utilizada es la `DMG10600T070_A5WTC`.

## Kernel Firmware Upgrade

1. Formatear una tarjeta `microSD` en `FAT32`.

📝La tarjeta `microSD` debe ser de `16GB` o menos.

2. Crear una carpeta con el nombre `DWIN_SET` en la tarjeta `microSD`.
3. Descargar la última versión del `Kernel` del [foro](https://forums.dwin-global.com/index.php/forums/).
4. Descomprimir el archivo descargado.

📝El `Kernel` se compone de un archivo con extensión `.INI` y otro con `.BIN`.

5. Copiar los archivos del `Kernel` a la carpeta `DWIN_SET`.
6. Apagar la pantalla.
7. Insertar la tarjeta `microSD` en la pantalla.
8. Encender la pantalla.
9. Esperar a que finalice el proceso de actualización.
10. Apagar la pantalla.
11. Retirar la tarjeta `microSD` de la pantalla.

## OS Configuration (UART4 y UART5)

📝Por defecto solo funcionan las interfaces `UART2` y `CAN`.

1. Borrar el contenido de la carpeta `DWIN_SET` de la tarjeta `microSD`.
2. Descargar el archivo `C51_8283 protocol (full function, UART2, UART 4, UART 5 universal)` del [sitio web del fabricante](https://www.dwin-global.com/kernel-upgrade/).
3. Descomprimir el archivo descargado.
4. Copiar el archivo `T5L51.BIN` a la carpeta `DWIN_SET`.
5. Apagar la pantalla.
6. Insertar la tarjeta `microSD` en la pantalla.
7. Encender la pantalla.
8. Esperar a que finalice el proceso de configuración.
9. Apagar la pantalla.
10. Retirar la tarjeta `microSD` de la pantalla.

📝La `UART4` es la interfaz `RS485` y queda configurada a `115200 baudios 8N1`.
