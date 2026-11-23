# Práctica Integradora — Programación Avanzada (GAB-2402)

**Carrera:** Ingeniería Informática  
**Especialidad:** Gestión y Analítica Avanzada de Datos  
**Institución:** Tecnológico de Estudios Superiores de Chalco  

**Diseñada por el Prof. Fabián Soberanes Martín**

---

## Qué es esta práctica

Proyecto único que **cubre los cinco temas** de la asignatura:

1. Fundamentos de programación avanzada y manipulación de datos  
2. Visualización avanzada de datos  
3. Análisis estadístico y modelado predictivo  
4. Gestión de bases de datos avanzada  
5. Aplicaciones de analítica de datos y proyecto práctico  

Está organizada en **cuatro entregables** (sin desglose de horas en el enunciado; el docente define el calendario de clase).

| Entregable | Enfoque | Temas principales |
|------------|---------|-------------------|
| **1** | Datos listos y persistidos | 1 y 4 |
| **2** | Exploración visual y evidencia estadística | 2 y 3.1 |
| **3** | Modelo predictivo validado | 3.2 y 3.3 |
| **4** | Aplicación de analítica y cierre | 5 (+ integración 1–4) |

---

## Sitio web de la práctica (GitHub Pages)

Este repositorio es publicable como sitio estático:

```bash
# vista local
python -m http.server 8000
```

En GitHub: **Settings → Pages → Deploy from branch `main` / root**.

Páginas:

- `index.html` — visión general y caso de negocio  
- `entregable-1.html` … `entregable-4.html` — alcance de cada entrega  
- `rubrica.html` — criterios de evaluación  

---

## Datos

- `data/empleados_analitica.csv` — dataset de trabajo con nulos, duplicados y un outlier extremo a propósito.

---

## Estructura sugerida del trabajo del estudiante

```
tu-repo-de-entrega/
├── data/
├── notebooks/
│   ├── 01_limpieza_y_bd.ipynb
│   ├── 02_eda_visual_estadistica.ipynb
│   └── 03_modelado.ipynb
├── sql/
├── models/
├── app/
├── docs/
└── README.md
```

---

## Competencia de la asignatura

*Desarrolla y aplica soluciones avanzadas de programación en Python para la gestión y análisis de datos.*

---

**Prof. Fabián Soberanes Martín**
