# 🏥 Proyecto Big Data – Análisis de Pacientes y Servicios Médicos

Este proyecto simula un caso real de análisis de datos en el sector salud, integrando herramientas como Python, MongoDB, Git y Jenkins.

## 📘 Fases del Proyecto

1. Preparación del entorno
2. Generación y limpieza de datos
3. Almacenamiento en MongoDB
4. Visualización de reportes
5. Versionamiento con GitHub
6. Integración continua con Jenkins

## 🧩 Fase 2 – Estructura de Carpetas

Se creó automáticamente la estructura base del proyecto usando `pathlib`:

- `data/`: contiene los archivos CSV originales
- `database/`: almacena los datos limpios
- `reports/`: gráficos y reportes tabulares
- `ci/`: evidencias de Jenkins
- `git/`: capturas de commits
- `scripts/`: notebooks del flujo

## 🧩 Fase 3 – Archivo base.csv

Se creó el archivo `base.csv` con la estructura de columnas:

- `id_paciente`
- `nombre`
- `edad`
- `sexo`
- `distrito`
- `servicio`
- `fecha_atencion`
- `monto`
