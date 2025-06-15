<!-- README.md -->
# Técnicas Computacionales Avanzadas de Hidro/Aero-Dinámica en Ingeniería y Astrofísica
> Taller práctico dentro de **InspiraSTEM 2025**  
> **Instructor:** *Erick Urquilla*

![Banner del taller](docs/banner.png)

## Descripción del taller
En este curso práctico se discutirán técnicas modernas de modelado computacional de fluidos. Estas técnicas desempeñan un papel crucial tanto en la industria aeroespacial y mecánica como en la investigación científica de frontera, incluyendo la astrofísica.

Como proyecto de grupo, se abordará de forma pedagógica una implementación computacional en **Python** de la **ecuación de agua poco profunda (1-D)**.  
* La **discretización espacial** del fluido se realizará mediante **elementos finitos**.  
* La **discretización temporal** se llevará a cabo mediante **diferencias finitas**.

El curso proporcionará conocimientos fundamentales a los/las participantes, dotándolos de habilidades de vanguardia en la industria moderna.

---

## Objetivos de aprendizaje

- Comprender la formulación numérica de la ecuación de agua poco profunda.  
- Implementar un solver **Python + NumPy** con mallas de elementos finitos.  
- Analizar la estabilidad y precisión de esquemas de diferencias finitas en el tiempo.  
- Visualizar campos de velocidad y altura de agua con **Matplotlib**.  
- Discutir aplicaciones reales en ingeniería y astrofísica.

---

## Contenido del repositorio

| Carpeta / archivo | Descripción |
|-------------------|-------------|
| `notebooks/` | Cuadernos Jupyter paso a paso. |
| `src/` | Código Python modular del solver CFD. |
| `data/` | Datos de ejemplo y resultados de simulaciones. |
| `docs/` | Presentaciones, PDFs y la imagen de banner (`banner.png`). |
| `requirements.txt` | Lista mínima de dependencias (NumPy, Matplotlib, etc.). |

---

## Requisitos previos

| Conocimiento | Nivel |
|--------------|-------|
| Python (listas, funciones, clases) | Básico–intermedio |
| Cálculo vectorial y ecuaciones diferenciales | Intermedio |
| Métodos numéricos elementales | Deseable |

---

## Instalación rápida

```bash
# 1. Clonar el repositorio
git clone https://github.com/InspiraSTEM/taller-cfd-2025.git
cd taller-cfd-2025

# 2. Crear entorno virtual (opcional pero recomendado)
python -m venv .venv
source .venv/bin/activate        # Linux/Mac
# .venv\Scripts\activate.bat     # Windows

# 3. Instalar dependencias
pip install -r requirements.txt

# 4. Lanzar los notebooks
jupyter lab notebooks/
