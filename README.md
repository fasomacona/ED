# Estructura de Datos (AED-1026)

Curso web completo basado en el programa oficial del **Tecnológico Nacional de México**.

Material didáctico con:

- Una página por cada tema del temario
- Teoría detallada, tablas comparativas y diagramas conceptuales
- Ejemplos de código en **Python** listos para copiar a Jupyter
- Ejercicios propuestos en cada subtema
- **Práctica en Jupyter Notebook** al final de cada tema

## Temario

| # | Tema | Página | Notebook |
|---|------|--------|----------|
| 1 | Introducción a las estructuras de datos | [temas/01-introduccion.html](temas/01-introduccion.html) | [01_practica_introduccion.ipynb](notebooks/01_practica_introduccion.ipynb) |
| 2 | Recursividad | [temas/02-recursividad.html](temas/02-recursividad.html) | [02_practica_recursividad.ipynb](notebooks/02_practica_recursividad.ipynb) |
| 3 | Estructuras lineales (Pilas, Colas, Listas) | [temas/03-estructuras-lineales.html](temas/03-estructuras-lineales.html) | [03_practica_lineales.ipynb](notebooks/03_practica_lineales.ipynb) |
| 4 | Estructuras no lineales (Árboles, Grafos) | [temas/04-estructuras-no-lineales.html](temas/04-estructuras-no-lineales.html) | [04_practica_no_lineales.ipynb](notebooks/04_practica_no_lineales.ipynb) |
| 5 | Métodos de ordenamiento | [temas/05-ordenamiento.html](temas/05-ordenamiento.html) | [05_practica_ordenamiento.ipynb](notebooks/05_practica_ordenamiento.ipynb) |
| 6 | Métodos de búsqueda | [temas/06-busqueda.html](temas/06-busqueda.html) | [06_practica_busqueda.ipynb](notebooks/06_practica_busqueda.ipynb) |

## Cómo usar

### Opción 1 – GitHub Pages (recomendado)

1. Sube este repositorio a GitHub.
2. Ve a **Settings → Pages**.
3. Source: branch `main`, folder `/ (root)`.
4. La página quedará en `https://tu-usuario.github.io/nombre-repo/`.

### Opción 2 – Local

```bash
# Clonar
git clone https://github.com/tu-usuario/estructura-datos-web.git
cd estructura-datos-web

# Abrir el sitio
# Puedes usar cualquier servidor estático, por ejemplo:
python -m http.server 8000
# Luego abre http://localhost:8000
```

### Notebooks

```bash
cd notebooks
jupyter notebook
# o
jupyter lab
# o súbelos a Google Colab
```

## Estructura del proyecto

```
estructura-datos-web/
├── index.html              # Página principal
├── css/styles.css          # Estilos
├── temas/
│   ├── 01-introduccion.html
│   ├── 02-recursividad.html
│   ├── 03-estructuras-lineales.html
│   ├── 04-estructuras-no-lineales.html
│   ├── 05-ordenamiento.html
│   └── 06-busqueda.html
├── notebooks/
│   ├── 01_practica_introduccion.ipynb
│   ├── 02_practica_recursividad.ipynb
│   ├── 03_practica_lineales.ipynb
│   ├── 04_practica_no_lineales.ipynb
│   ├── 05_practica_ordenamiento.ipynb
│   └── 06_practica_busqueda.ipynb
└── README.md
```

## Competencia de la asignatura

> Conoce, comprende y aplica eficientemente estructuras de datos, métodos de ordenamiento y búsqueda para la optimización del rendimiento de soluciones a problemas del mundo real.

## Licencia

Material educativo basado en el programa oficial AED-1026 del TecNM (© 2016).  
Adaptado a Python + Jupyter para uso libre en docencia.
