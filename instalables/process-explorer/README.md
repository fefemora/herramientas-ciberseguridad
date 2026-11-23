# Process Explorer

<p align="center"><img src="../../assets/instalables.svg" alt="" width="100%"></p>

[Volver al catálogo de instalables](../README.md) · [Descargar desde Microsoft Sysinternals](https://learn.microsoft.com/en-us/sysinternals/downloads/process-explorer)

<p align="center">
  <a href="../README.md"><img src="https://img.shields.io/badge/Portable%20para%20Windows-14283F?style=flat-square" alt="Portable para Windows"></a>
  <a href="#averiguar-qué-programa-tiene-abierto-un-archivo"><img src="https://img.shields.io/badge/Diagn%C3%B3stico%20de%20procesos-065F46?style=flat-square" alt="Diagnóstico de procesos"></a>
</p>

Process Explorer muestra los procesos activos y permite buscar qué programa tiene abierto un archivo. Descarga y extrae el ZIP de Microsoft. En un equipo x64, ejecuta `procexp64.exe`. Microsoft indica Windows 11 o posterior para la versión actual en equipos cliente.

## Averiguar qué programa tiene abierto un archivo

Windows avisa que un archivo está en uso al intentar renombrar `inventario.xlsx`. Aunque hayas cerrado la ventana desde la que trabajabas, puede quedar abierto en otra instancia de la aplicación.

1. En Process Explorer, pulsa **Ctrl + F** o ve a **Find → Find Handle or DLL**. Busca `inventario.xlsx`.
2. Si aparecen varios resultados, compara la ruta para identificar la copia correcta. Revisa el nombre del proceso que la tiene abierta y su **PID**, el identificador de esa instancia.
3. Si el resultado apunta a Excel, guarda el trabajo pendiente y cierra el libro desde la aplicación. Intenta renombrarlo de nuevo. Si sigue en uso, repite la búsqueda para revisar qué proceso conserva acceso al archivo.

Empieza por cerrar el archivo desde la aplicación. Así puedes guardar los cambios antes de liberar el archivo.

[Documentación oficial de Process Explorer](https://learn.microsoft.com/en-us/sysinternals/downloads/process-explorer)
