# Herramientas de ciberseguridad y diagnóstico TI

<p align="center"><img src="assets/portada.svg" alt="" width="100%"></p>

Catálogo en español de herramientas web y utilidades para Windows. Encuentra guías breves para investigar incidentes, verificar información pública y resolver fallas de soporte TI.

<p align="center">
  <a href="web/README.md"><img src="https://img.shields.io/badge/Herramientas%20web-14283F?style=flat-square" alt="Herramientas web"></a>
  <a href="instalables/README.md"><img src="https://img.shields.io/badge/Herramientas%20para%20Windows-065F46?style=flat-square" alt="Herramientas para Windows"></a>
</p>

<a name="qué-necesitas-resolver"></a>

## Índice por área

[OSINT](#osint) · [Ciberseguridad](#ciberseguridad) · [Soporte y diagnóstico TI](#soporte-y-diagnóstico-ti)

### OSINT

Verificación de metadatos e información geográfica. [Catálogo OSINT para Windows](instalables/README.md#osint).

| Herramienta | Aplicación práctica | Formato |
| --- | --- | --- |
| <img src="https://www.google.com/s2/favicons?domain=exiftool.org&amp;sz=32" width="16" height="16" alt=""> [ExifTool y ExifToolGUI](https://github.com/FrankBijnen/ExifToolGui/releases) | Comparación de metadatos de imágenes. | Windows |
| <img src="https://www.google.com/s2/favicons?domain=qgis.org&amp;sz=32" width="16" height="16" alt=""> [QGIS](https://qgis.org/download/) | Verificación de coordenadas con cartografía pública. | Windows |
| <img src="https://www.google.com/s2/favicons?domain=google.com&amp;sz=32" width="16" height="16" alt=""> [Google Earth Pro](https://support.google.com/earth/answer/21955?hl=es) | Comparación de imágenes satelitales históricas. | Windows |

### Ciberseguridad

Análisis de archivos y enlaces, reputación y actividad en Windows. [Catálogo de seguridad web](web/README.md#archivos-sospechosos-filtraciones-y-reputación) · [Catálogo de seguridad para Windows](instalables/README.md#ciberseguridad).

| Herramienta | Aplicación práctica | Formato |
| --- | --- | --- |
| <img src="https://www.google.com/s2/favicons?domain=virustotal.com&amp;sz=32" width="16" height="16" alt=""> [VirusTotal](web/virustotal/README.md#revisar-un-archivo-sospechoso-por-sha-256) | Consulta de archivos sospechosos por SHA-256. | Web |
| <img src="https://www.google.com/s2/favicons?domain=haveibeenpwned.com&amp;sz=32" width="16" height="16" alt=""> [Have I Been Pwned](web/have-i-been-pwned/README.md#revisar-si-un-correo-aparece-en-una-filtración) | Comprobación de correos en filtraciones conocidas. | Web |
| <img src="https://www.google.com/s2/favicons?domain=urlscan.io&amp;sz=32" width="16" height="16" alt=""> [urlscan.io](web/urlscan/README.md#revisar-un-enlace-sospechoso-con-un-informe-existente) | Revisión de informes existentes sobre enlaces sospechosos. | Web |
| <img src="https://www.google.com/s2/favicons?domain=urlhaus.abuse.ch&amp;sz=32" width="16" height="16" alt=""> [URLhaus](web/urlhaus/README.md#comprobar-si-un-enlace-está-asociado-a-malware) | Consulta de enlaces asociados a la distribución de malware. | Web |
| <img src="https://www.google.com/s2/favicons?domain=abuseipdb.com&amp;sz=32" width="16" height="16" alt=""> [AbuseIPDB](web/abuseipdb/README.md#revisar-reportes-de-abuso-sobre-una-ip) | Consulta de reportes de abuso por dirección IP. | Web |
| <img src="https://www.google.com/s2/favicons?domain=gchq.github.io&amp;sz=32" width="16" height="16" alt=""> [CyberChef](web/cyberchef/README.md#decodificar-un-campo-base64-de-un-registro) | Decodificación de datos Base64 en registros. | Web |
| <img src="https://www.google.com/s2/favicons?domain=nomoreransom.org&amp;sz=32" width="16" height="16" alt=""> [No More Ransom](web/no-more-ransom/README.md#buscar-un-descifrador-para-archivos-afectados-por-ransomware) | Búsqueda de descifradores para archivos afectados por ransomware. | Web |
| <img src="https://www.google.com/s2/favicons?domain=microsoft.com&amp;sz=32" width="16" height="16" alt=""> [Autoruns](instalables/autoruns/README.md#identificar-qué-aplicación-se-abre-al-iniciar-sesión) | Revisión de aplicaciones y tareas de inicio automático. | Windows |

### Soporte y diagnóstico TI

Diagnóstico de DNS, correo, HTTPS y aplicaciones. [Catálogo de diagnóstico web](web/README.md#dns-correo-y-sitios-web) · [Catálogo de diagnóstico para Windows](instalables/README.md#soporte-y-diagnóstico-ti).

| Herramienta | Aplicación práctica | Formato |
| --- | --- | --- |
| <img src="https://www.google.com/s2/favicons?domain=dnschecker.org&amp;sz=32" width="16" height="16" alt=""> [DNSChecker](web/dnschecker/README.md#comprobar-un-cambio-de-registro-a) | Seguimiento de cambios de DNS en distintos resolvedores. | Web |
| <img src="https://www.google.com/s2/favicons?domain=google.com&amp;sz=32" width="16" height="16" alt=""> [Google Admin Toolbox Dig](web/google-admin-toolbox-dig/README.md#revisar-los-registros-mx-después-de-una-migración-de-correo) | Verificación de registros MX tras una migración de correo. | Web |
| <img src="https://www.google.com/s2/favicons?domain=mxtoolbox.com&amp;sz=32" width="16" height="16" alt=""> [MXToolbox SuperTool](web/mxtoolbox/README.md#investigar-un-rechazo-de-correo-por-reputación-de-ip) | Diagnóstico de rechazos de correo por reputación de IP. | Web |
| <img src="https://www.google.com/s2/favicons?domain=ssllabs.com&amp;sz=32" width="16" height="16" alt=""> [Qualys SSL Labs](web/qualys-ssl-labs/README.md#diagnosticar-una-advertencia-de-certificado-https) | Diagnóstico de advertencias de certificado HTTPS. | Web |
| <img src="https://www.google.com/s2/favicons?domain=securityheaders.com&amp;sz=32" width="16" height="16" alt=""> [SecurityHeaders](web/securityheaders/README.md#comprobar-cabeceras-http-después-de-un-cambio) | Comprobación de cabeceras HTTP de seguridad. | Web |
| <img src="https://www.google.com/s2/favicons?domain=internet.nl&amp;sz=32" width="16" height="16" alt=""> [Internet.nl](web/internet-nl/README.md#verificar-la-seguridad-del-correo-de-un-dominio) | Revisión de la configuración de seguridad del correo. | Web |
| <img src="https://www.google.com/s2/favicons?domain=microsoft.com&amp;sz=32" width="16" height="16" alt=""> [Process Explorer](instalables/process-explorer/README.md#averiguar-qué-programa-tiene-abierto-un-archivo) | Identificación del proceso que mantiene un archivo abierto. | Windows |
