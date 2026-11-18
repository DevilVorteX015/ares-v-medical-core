# ARES-V // Edge-AI Medical Core

Simulador de monitoreo biomédico autónomo para misiones de larga duración basado en estándares **NASA LSAH / HRP**.

## Archivos principales

* `index.html`: Interfaz táctil y motor de diagnóstico Edge-AI con asistente virtual **ARES**, persistencia de sesión, ranuras de memoria independientes por tripulante (`SLOT A`–`SLOT E` hasta 10,000 registros) y exportación de informes clínicos `.TXT` ordenados cronológicamente.

* `ares_mission_config.txt`: Archivo editable con parámetros de misión, tripulación (`slotKey` a–e), umbrales clínicos e instrucciones médicas.

* `netlify.toml`: Configuración de actualización instantánea sin caché en Netlify.