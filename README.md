# Monitor-Autom-tico-de-Puertos-y-Cambios-en-la-Red-Local

Este proyecto consiste en un script en Bash que escanea automáticamente la red local, detecta cambios en puertos abiertos y servicios, y envía alertas por correo electrónico usando Gmail SMTP seguro. Además, muestra notificaciones de escritorio cuando se detectan cambios.

Es ideal para pruebas de seguridad, monitoreo de red o para aprender automatización de tareas en Linux.

Características

Escaneo automático de la red local cada 12 horas usando Nmap.

Detección de cambios en hosts y puertos abiertos comparando con el último escaneo.

Envío de correo resumido a Gmail con los cambios detectados usando msmtp.

Notificaciones de escritorio (notify-send) al detectar cambios.

Registro histórico de escaneos y diferencias en la carpeta scan_reports.

Tecnologías y Herramientas

Bash: Scripting y automatización

Linux / Ubuntu / Debian

Nmap: Escaneo de puertos y detección de servicios

Cron: Programación de tareas automáticas

msmtp: Envío de correo a Gmail vía SMTP seguro

notify-send: Notificaciones en escritorio
