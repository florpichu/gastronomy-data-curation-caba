# Curaduría de datos de gastronomía en CABA

Trabajo de la materia **Laboratorio de Datos** (FCEyN, UBA, 2025), realizado en conjunto con [Maximiliano Rodríguez Camps](https://github.com/).

## Objetivo

Trabajar con un dataset de **datos abiertos del Gobierno de la Ciudad de Buenos Aires** sobre establecimientos gastronómicos, aplicando un proceso completo de curaduría: desde datos crudos y con errores hasta un dataset limpio y confiable para análisis posterior.

## Proceso de curaduría

El dataset original presentaba varios problemas típicos de datos abiertos "del mundo real":

- **Errores de encoding**: caracteres especiales del español (como la ñ) codificados incorrectamente.
- **Datos faltantes**: campos incompletos que requirieron decisiones documentadas de imputación o exclusión.
- **Inconsistencias de formato**: variaciones en cómo se registraban ciertos campos (nombres, direcciones).

Cada decisión de limpieza se documentó explícitamente en el notebook, priorizando la trazabilidad del proceso por sobre "arreglar todo silenciosamente".

## Por qué importa este tipo de trabajo

La curaduría de datos —detectar y corregir errores de codificación, decidir cómo tratar datos faltantes, dejar el dataset en un estado utilizable y documentado— es una de las tareas más frecuentes y menos visibles del trabajo con datos reales. Un análisis o modelo, por más sofisticado que sea, es tan confiable como los datos que lo alimentan.

## Herramientas

Python · pandas · Jupyter Notebook

## Datos

Dataset de establecimientos gastronómicos de CABA, publicado en el portal de [datos abiertos del Gobierno de la Ciudad de Buenos Aires](https://data.buenosaires.gob.ar/).
