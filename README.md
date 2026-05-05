# Propuesta de Autoridad Metropolitana de Movilidad — ZMVM

Análisis cuantitativo con Python para construir evidencia empírica sobre
la necesidad de una autoridad metropolitana de movilidad en la ZMVM.

##

## Pregunta de investigación

¿Cómo diseñar una propuesta institucional para una autoridad metropolitana
de movilidad en la ZMVM, con facultades vinculantes, capacidad de
coordinación presupuestal y legitimidad política?

## Enfoque

Cada materia del propedéutico produce un análisis cuantitativo que responde
una subpregunta de investigación:

* Economía urbana → distribución del gasto en movilidad
* Sociología urbana → desigualdad en tiempos de traslado
* Estadística social → validación de diferencias (significancia)
* Investigación metropolitana → análisis institucional comparado

**Hipótesis de trabajo:**
La fragmentación institucional en la ZMVM genera desigualdades medibles
en tiempos de traslado y acceso a recursos de movilidad.

## Estructura del repositorio

zmvm-movilidad-tesis/
├── economia_urbana/
├── sociologia_urbana/
├── estadistica_social/
├── investigacion_metropolitana/
├── integracion/
├── data_raw/          # datos originales
├── utils/             # funciones reutilizables
└── README.md

## Datos

| Fuente                        | Año                | Variables clave                     | Estado      | Acción                                |
| ----------------------------- | ------------------ | ----------------------------------- | ----------- | ------------------------------------- |
| INEGI - Censo                 | 2020               | Población, vivienda, ingreso proxy  | ⚪ Pendiente | Descargar y filtrar ZMVM              |
| Encuesta Origen-Destino (EOD) | 2017 (buscar 2023) | Tiempos, modos, motivos de traslado | ⚪ Pendiente | Descargar y limpiar variables clave   |
| Transparencia municipal       | 2019-2025          | Presupuesto en movilidad            | ⚪ Pendiente | Identificar fuentes y homologar datos |

## Primer análisis sugerido

📊 `estadistica_social/notebooks/01_tiempos_traslado.ipynb`

Este notebook:

* Calcula tiempos promedio de traslado por municipio
* Visualiza desigualdades territoriales
* Sirve como base para análisis posteriores

## Cómo usar este repositorio

1. Clona el repositorio o descarga los archivos
2. Abre los notebooks en Google Colab
3. Carga los datos desde `/data_raw`
4. Ejecuta los notebooks (.ipynb) en orden dentro de cada carpeta
5. Cada notebook genera visualizaciones y resultados interpretables

## Requisitos

* Python 3.10+
* Google Colab (recomendado)
* Librerías: pandas, matplotlib, numpy

## Estado del proyecto

🟡 En construcción — Propedéutico (mayo–junio 2026)

| Materia                     | Avance        | Próximo entregable                      |
| --------------------------- | ------------- | --------------------------------------- |
| Economía urbana             | ⚪ No iniciado | Análisis de presupuesto por municipio   |
| Sociología urbana           | ⚪ No iniciado | Correlación tiempo vs ingreso           |
| Estadística social          | ⚪ No iniciado | Validación estadística de desigualdades |
| Investigación metropolitana | ⚪ No iniciado | Benchmark de modelos institucionales    |

## Objetivo final

Construir una propuesta institucional basada en evidencia cuantitativa
sobre desigualdad y fragmentación metropolitana en la ZMVM, que sirva como:

* Proyecto final del propedéutico
* Anteproyecto de tesis de maestría
* Portafolio técnico para colaboraciones o consultoría

## Importante
Este repositorio forma parte de un proyecto académico en desarrollo.
Los análisis y conclusiones están sujetos a cambios.

*Última actualización: 5 de mayo de 2026*

---

*Última actualización: 5 de mayo de 2026*
