# Plataforma DevSecOps de Gestión Financiera y Trading

## Registro de Decisiones y Avances
* **Decisión 1 (Infraestructura Local):** Se opta por desarrollar inicialmente sobre Windows utilizando Docker Desktop para orquestar los contenedores. Los volúmenes de Docker permitirán que el código editado en el IDE (Antigravity) se refleje en tiempo real dentro de los contenedores.
* **Decisión 2 (Aislamiento):** Se separan lógicamente los componentes en directorios (`infra/`, `bot/`, `ansible/`, `docs/`) para preparar una migración limpia hacia un servidor Linux nativo (Raspberry Pi 4 / SSD) en fases posteriores.
* **Avance Actual:** Inicialización del repositorio Git, definición de la estructura de directorios base y configuración del control de versiones.

## Siguientes Pasos
- [ ] Fase 1: Crear archivo `docker-compose.yml` para levantar la base de datos temporal (InfluxDB) y la herramienta de visualización (Grafana).