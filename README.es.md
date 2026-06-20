# Audio Device Switcher

Herramienta portable para Windows creada por MPTech Tools para cambiar rÃ¡pidamente el dispositivo de salida de audio predeterminado.

## Vista previa

![audio-switcher - Audio-Devie-Switcher](docs/screenshots/Audio-Devie-Switcher.png)

## QuÃ© hace

Audio Device Switcher permite cambiar entre dispositivos de salida de audio de Windows sin abrir la configuraciÃ³n de sonido.

EstÃ¡ pensada para usuarios que cambian a menudo entre altavoces, monitores, auriculares, dispositivos Bluetooth o interfaces de audio.

## Funciones

- Detecta dispositivos de salida de audio activos en Windows.
- Muestra el dispositivo de salida predeterminado actual.
- Permite establecer cualquier dispositivo detectado como predeterminado.
- Permite cambiar al siguiente dispositivo.
- Atajo global de teclado configurable.
- Permite excluir dispositivos del ciclo del atajo.
- Modo segundo plano/bandeja.
- Al cerrar la ventana, la app sigue funcionando en la bandeja.
- MenÃº de bandeja con Abrir app y Cerrar app.
- OpciÃ³n de iniciar con Windows.
- OpciÃ³n de iniciar minimizada.
- Interfaz en espaÃ±ol, inglÃ©s y portuguÃ©s.

## Release

Ejecutable portable:

../../releases/audio-device-switcher/audio-device-switcher.exe

Checksum:

../../releases/audio-device-switcher/checksums.txt

## Uso

1. Abre audio-device-switcher.exe.
2. Selecciona el dispositivo de salida de audio que quieras.
3. Pulsa Predeterminar.
4. Configura un atajo global si lo necesitas.
5. Cierra la ventana para dejar la app funcionando en la bandeja.
6. Usa el icono de la bandeja para abrir o cerrar completamente la app.

## Comportamiento del atajo

El atajo alterna entre los dispositivos incluidos.

Los dispositivos excluidos se ignoran en el ciclo del atajo, pero no se deshabilitan en Windows.

Esto permite mantener un dispositivo disponible manualmente, pero evitar que el atajo cambie a Ã©l.

## Inicio con Windows

La app puede iniciarse con Windows sin permisos de administrador.

Escribe una entrada en el registro del usuario actual:

HKCU\Software\Microsoft\Windows\CurrentVersion\Run

Si mueves el ejecutable portable despuÃ©s de activar el inicio con Windows, desactiva y activa de nuevo la opciÃ³n para que Windows guarde la nueva ruta.

## Notas

Windows SmartScreen puede mostrar un aviso porque el ejecutable todavÃ­a no estÃ¡ firmado con certificado.

Esta herramienta no usa cuentas, nube, tracking, servidores ni APIs externas.