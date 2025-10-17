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

## 🧩 Fase 4 – Generación de Datos Simulados

Se generó el archivo `pacientes.csv` con 3000 registros aleatorios, incluyendo:

- Campos nulos y valores “NA” en sexo, distrito y servicio
- Fechas aleatorias entre 2020 y 2025
- Montos entre S/ 50 y S/ 500

Este archivo alimentará el proceso ETL en la siguiente fase.

## 🧩 Fase 5 – Proceso ETL

Se procesó el archivo `pacientes.csv` para:

- Reemplazar valores nulos y “NA” en sexo, servicio y distrito
- Validar formato de fechas
- Eliminar duplicados y registros incompletos

Resultado: `pacientes_clean.csv` listo para ser cargado en MongoDB.
