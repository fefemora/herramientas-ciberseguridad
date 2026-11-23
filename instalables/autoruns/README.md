# Autoruns

<p align="center"><img src="../../assets/instalables.svg" alt="" width="100%"></p>

[Volver al catálogo de instalables](../README.md) · [Descargar desde Microsoft Sysinternals](https://learn.microsoft.com/en-us/sysinternals/downloads/autoruns)

<p align="center">
  <a href="../README.md"><img src="https://img.shields.io/badge/Portable%20para%20Windows-14283F?style=flat-square" alt="Portable para Windows"></a>
  <a href="#identificar-qué-aplicación-se-abre-al-iniciar-sesión"><img src="https://img.shields.io/badge/Inicio%20autom%C3%A1tico-065F46?style=flat-square" alt="Inicio automático"></a>
</p>

Autoruns muestra qué programas, tareas programadas y servicios están configurados para iniciarse automáticamente en Windows. Descarga y extrae el ZIP de Microsoft. En un equipo x64, ejecuta `Autoruns64.exe`.

## Identificar qué aplicación se abre al iniciar sesión

Una persona dice que, desde que instaló el software de una impresora, aparece una ventana de actualización cada vez que entra a Windows. Quieres identificar qué la abre antes de cambiar la configuración.

1. Abre **Logon** y busca el nombre del fabricante o de la aplicación. Si no aparece ahí, revisa **Scheduled Tasks**.
2. Comprueba **Publisher** e **Image Path**. La ruta te ayuda a identificar el programa y a distinguirlo de otras entradas con nombres parecidos. Con **Jump to Entry** puedes ver dónde está configurada.
3. Si confirmas que es un componente opcional y acuerdas desactivarlo, desmarca solo esa entrada. Cierra sesión, vuelve a entrar y comprueba que la ventana ya no aparece y que puedes seguir imprimiendo. Si hay un efecto inesperado, vuelve a marcarla.

Si identificas el actualizador, pero no sabes qué depende de él, revisa las preferencias de la aplicación o la documentación del fabricante antes de cambiar la entrada.

[Documentación oficial de Autoruns](https://learn.microsoft.com/en-us/sysinternals/downloads/autoruns)
