# 🛡️ Auditoría de Seguridad y Superficie de Ataque: Sistema de Recuperación de Datos Climáticos

![Security Audit](https://img.shields.io/badge/Security-Audit-red)
![Academic Project](https://img.shields.io/badge/UNL-Computaci%C3%B3n-blue)
![Cycle](https://img.shields.io/badge/Ciclo-8%C2%BA%20A-green)

Este repositorio contiene la **línea base de seguridad y el análisis de superficie de ataque** aplicado al **Sistema de Recuperación de Datos Climáticos** (proyecto desarrollado en 6.º ciclo)[cite: 1, 2]. El trabajo se desarrolla en el marco del componente Práctico-Experimental de la asignatura **Software Security** de la Carrera de Computación de la Universidad Nacional de Loja, ciclo 8vo Octavo [cite: 1].

---

## 📌 Información General

* **Institución:** Universidad Nacional de Loja (UNL)[cite: 1]
* **Facultad:** FEIRNNR — Carrera de Computación[cite: 1]
* **Asignatura:** Software Security (Ciclo 8 A)[cite: 1]
* **Docente:** Mgtr. Valeria Herrera Salazar[cite: 1]
* **Período Académico:** Octubre 2026 – Febrero 2027[cite: 1]
* **Integrantes / Autores:**
  * Estudiante 1: Gabriel Espinoza
  * Estudiante 2: Leonardo Peralta
  * Estudiante 3: Dalton Maza

---

## 🌡️ Descripción del Sistema Objeto de Auditoría

El **Sistema de Recuperación de Datos Climáticos** es una aplicación orientada a la recolección, almacenamiento y visualización de variables meteorológicas (temperatura, humedad, precipitación, etc.)[cite: 1, 2]. 

* **Funcionalidades Clave:**
  * Autenticación y gestión de usuarios (Administrador, Analista, Usuario Público).
  * Consulta y exportación de historial de datos climáticos.
  * Carga e ingesta de archivos/módulos de recolección de datos[cite: 2, 4].
* **Stack Tecnológico:**
  * **Backend:** Node.js
  * **Frontend:** JavaScript
  * **Base de Datos:** MongoDB
  * **Entorno:** Ejecución local controlada[cite: 2].

---

## 🎯 Objetivo del Proyecto de Seguridad

Evaluar y delimitar la superficie de ataque del sistema climático, identificar activos de información, analizar la gestión de errores y clasificar vulnerabilidades frente a los estándares de **OWASP Top 10**, con el fin de priorizar los hallazgos para posteriores auditorías técnicas y correcciones[cite: 1].

---

## 📂 Estructura del Repositorio

El proyecto se organiza conforme a las 4 fases de la **Guía Práctica APE 001**[cite: 1, 2]:

```text
.
├── README.md
├── docs/
│   ├── Ficha_del_Proyecto.pdf
│   └── Informe_Consolidado_APE01.pdf
├── fase1_superficie_ataque/
│   ├── inventario_superficie_ataque.xlsx
│   └── evidencias_capturas/
├── fase2_triada_cia/
│   ├── matriz_activos_y_amenazas.xlsx
│   └── informe_fase2.pdf
├── fase3_gestion_errores/
│   ├── registro_errores_fugas.xlsx
│   ├── parches_codigo/
│   └── evidencias_fugas/
└── fase4_owasp_top10/
    ├── lista_cotejo_owasp.xlsx
    └── matriz_priorizacion_hallazgos.xlsx