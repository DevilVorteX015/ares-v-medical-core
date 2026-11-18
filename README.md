# ARES-V // Edge-AI Medical Core

Simulador de monitoreo biomédico autónomo para misiones de larga duración basado en estándares **NASA LSAH / HRP**, adaptado tanto para consola de escritorio/laptop como para dispositivos móviles.

## Archivos principales

* `index.html`: Interfaz táctil responsiva (PC/Laptop + Móvil) y motor de diagnóstico Edge-AI con asistente virtual **ARES**, KPIs calculados dinámicamente desde los 12 indicadores fisiológicos, mapa interplanetario Tierra–Marte con 10 posiciones de tránsito seleccionables en tiempo real, persistencia de sesión, ranuras de memoria independientes por tripulante (`SLOT A`–`SLOT E` hasta 10,000 registros) y exportación de informes clínicos `.TXT` ordenados cronológicamente.

* `ares_mission_config.txt`: Archivo editable con parámetros de misión, velocidad de la nave (`shipSpeedKmPerSec`), tripulación (`slotKey` a–e), umbrales clínicos e instrucciones médicas.

* `netlify.toml`: Configuración de actualización instantánea sin caché en Netlify.