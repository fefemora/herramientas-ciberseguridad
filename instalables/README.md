# Herramientas de escritorio

<p align="center"><img src="../assets/instalables.svg" alt="" width="100%"></p>

[Volver a la portada](../README.md) · [Ver herramientas web](../web/README.md)

<p align="center">
  <img src="https://img.shields.io/badge/Escritorio%20y%20portables-14283F?style=flat-square" alt="Escritorio y portables">
  <img src="https://img.shields.io/badge/L%C3%ADnea%20de%20comandos-065F46?style=flat-square" alt="Línea de comandos">
</p>

[OSINT](#osint) · [Ciberseguridad](#ciberseguridad) · [Soporte y diagnóstico TI](#soporte-y-diagnóstico-ti)

## OSINT

Herramientas para verificar metadatos, ubicaciones y cambios visibles en fuentes públicas.

| Herramienta | Formato en Windows | Caso de uso |
| --- | --- | --- |
| <img src="https://www.google.com/s2/favicons?domain=exiftool.org&amp;sz=32" width="16" height="16" alt=""> [ExifTool y ExifToolGUI](https://github.com/FrankBijnen/ExifToolGui/releases) | CLI y GUI opcional · instalable o portable | Compara los metadatos de una foto original y una copia para ver si se conservaron la fecha o las coordenadas. [Descargar ExifTool](https://exiftool.org/install.html). |
| <img src="https://www.google.com/s2/favicons?domain=qgis.org&amp;sz=32" width="16" height="16" alt=""> [QGIS](https://qgis.org/download/) | Instalable · GUI | Cruza coordenadas de una foto con un mapa público y deja documentada la ubicación analizada. |
| <img src="https://www.google.com/s2/favicons?domain=google.com&amp;sz=32" width="16" height="16" alt=""> [Google Earth Pro](https://support.google.com/earth/answer/21955?hl=es) | Instalable · GUI | Compara imágenes históricas de un lugar público para acotar cuándo cambió una carretera o un edificio. |

## Ciberseguridad

Herramientas para verificar archivos, proteger credenciales e investigar actividad en Windows.

| Herramienta | Formato en Windows | Caso de uso |
| --- | --- | --- |
| <img src="https://www.google.com/s2/favicons?domain=microsoft.com&amp;sz=32" width="16" height="16" alt=""> [Autoruns](autoruns/README.md) | Portable para Windows | Identifica qué programas y tareas se inician automáticamente. |
| <img src="https://www.google.com/s2/favicons?domain=keepassxc.org&amp;sz=32" width="16" height="16" alt=""> [KeePassXC](https://keepassxc.org/download/) | Escritorio y opción portable para Windows | Guarda credenciales en una base de datos local cifrada. |
| <img src="https://www.google.com/s2/favicons?domain=quickhash-gui.org&amp;sz=32" width="16" height="16" alt=""> [QuickHash GUI](https://github.com/tedsmith/quickhash) | Escritorio | Calcula hashes de archivos y permite compararlos con los que publica el proveedor. |
| <img src="https://www.google.com/s2/favicons?domain=microsoft.com&amp;sz=32" width="16" height="16" alt=""> [Sigcheck](https://learn.microsoft.com/en-us/sysinternals/downloads/sigcheck) | Portable · CLI | Verifica si un instalador está firmado, quién lo firmó y qué hash tiene. |
| <img src="https://www.google.com/s2/favicons?domain=microsoft.com&amp;sz=32" width="16" height="16" alt=""> [Sysmon](https://learn.microsoft.com/en-us/sysinternals/downloads/sysmon) | Servicio de Windows · instalación con CLI | Registra eventos como creación de procesos o conexiones de red, según la configuración. Sirve para investigar qué ocurrió en un equipo. |
| 📄 [evtx_dump](https://github.com/omerbenamram/evtx/releases) | Línea de comandos | Lee registros de eventos de Windows exportados en formato EVTX. |
| <img src="https://www.google.com/s2/favicons?domain=github.com&amp;sz=32" width="16" height="16" alt=""> [Hayabusa](https://github.com/Yamato-Security/hayabusa/releases) | Ejecutable descargable · CLI | Aplica reglas de detección a registros EVTX y genera una cronología para revisar eventos de interés. |
| <img src="https://www.google.com/s2/favicons?domain=ericzimmerman.github.io&amp;sz=32" width="16" height="16" alt=""> [Timeline Explorer](https://ericzimmerman.github.io/) | Descarga en ZIP · GUI | Abre una cronología exportada a CSV, por ejemplo desde Hayabusa, y filtra eventos por fecha o equipo. |
| <img src="https://www.google.com/s2/favicons?domain=autopsy.com&amp;sz=32" width="16" height="16" alt=""> [Autopsy](https://www.autopsy.com/download/) | Instalable · GUI | Examina una imagen de disco y ordena los archivos por sus marcas de tiempo durante una revisión forense. |

## Soporte y diagnóstico TI

Herramientas para diagnosticar problemas de aplicaciones, conectividad y registros.

| Herramienta | Formato en Windows | Caso de uso |
| --- | --- | --- |
| <img src="https://www.google.com/s2/favicons?domain=microsoft.com&amp;sz=32" width="16" height="16" alt=""> [Process Explorer](process-explorer/README.md) | Portable para Windows | Identifica qué proceso tiene abierto un archivo o ha cargado una DLL. |
| <img src="https://www.google.com/s2/favicons?domain=microsoft.com&amp;sz=32" width="16" height="16" alt=""> [Process Monitor](https://learn.microsoft.com/en-us/sysinternals/downloads/procmon) | Descarga en ZIP · GUI | Revisa qué archivo o clave del Registro intenta abrir una aplicación que falla al arrancar. |
| <img src="https://www.google.com/s2/favicons?domain=microsoft.com&amp;sz=32" width="16" height="16" alt=""> [TCPView](https://learn.microsoft.com/en-us/sysinternals/downloads/tcpview) | Portable · GUI | Identifica qué proceso local abrió una conexión TCP o qué aplicación usa un puerto. |
| <img src="https://www.google.com/s2/favicons?domain=wireshark.org&amp;sz=32" width="16" height="16" alt=""> [Wireshark y TShark](https://www.wireshark.org/download.html) | Escritorio y línea de comandos | Permiten examinar capturas de tráfico para diagnosticar problemas como consultas DNS sin respuesta. |
| <img src="https://www.google.com/s2/favicons?domain=curl.se&amp;sz=32" width="16" height="16" alt=""> [curl](https://curl.se/) | Línea de comandos | Sirve para diagnosticar conexiones HTTPS y revisar respuestas HTTP. |
| <img src="https://www.google.com/s2/favicons?domain=jqlang.org&amp;sz=32" width="16" height="16" alt=""> [jq](https://jqlang.org/download/) | Línea de comandos | Permite filtrar y transformar registros en formato JSON. |
