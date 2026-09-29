# Tema 1: Introducción a las Estructuras de Datos

Material didáctico completo y listo para publicar en **GitHub Pages** correspondiente al **Tema 1** de la asignatura **Estructura de Datos (AED-1026)** del Tecnológico Nacional de México.

## Contenido

| Página | Descripción |
|--------|-------------|
| [index.html](index.html) | Portada, objetivos y navegación del tema |
| [clasificacion.html](clasificacion.html) | 1.1 Clasificación de las estructuras de datos |
| [tda.html](tda.html) | 1.2 Tipos de Datos Abstractos y 1.3 Ejemplos |
| [memoria.html](memoria.html) | 1.4 Manejo de memoria (estática y dinámica) |
| [analisis.html](analisis.html) | 1.5 Análisis de algoritmos (Big-O, tiempo y espacio) |
| [practica.html](practica.html) | Guía de la parte práctica |
| [notebooks/practica_tema1.ipynb](notebooks/practica_tema1.ipynb) | Jupyter Notebook con ejercicios |

## Cómo ver el sitio localmente

Abre `index.html` en tu navegador, o sirve la carpeta con un servidor local:

```bash
# Python 3
python -m http.server 8000

# Luego visita http://localhost:8000
```

## Publicar en GitHub Pages

1. Crea un repositorio nuevo en GitHub (por ejemplo `estructura-datos-tema1`).
2. Sube todos los archivos de esta carpeta a la rama `main` (o `master`).
3. Ve a **Settings → Pages**.
4. En **Source** selecciona la rama `main` y la carpeta `/ (root)`.
5. Guarda. En uno o dos minutos el sitio estará disponible en:

   `https://<tu-usuario>.github.io/estructura-datos-tema1/`

### Opción con GitHub CLI

```bash
# Desde esta carpeta
git init
git add .
git commit -m "Tema 1: Introducción a las Estructuras de Datos"
gh repo create estructura-datos-tema1 --public --source=. --push
# Luego activa Pages en la configuración del repositorio
```

## Jupyter Notebook

El notebook incluye 5 ejercicios:

1. Clasificación de estructuras  
2. Implementación del TDA Pila + verificación de paréntesis  
3. Memoria estática vs dinámica  
4. Análisis de complejidad (búsqueda lineal vs binaria + medición de tiempos)  
5. Reto: implementar el TDA Cola  

```bash
pip install jupyter pandas
jupyter notebook notebooks/practica_tema1.ipynb
```

También puedes subirlo a [Google Colab](https://colab.research.google.com/).

## Competencia del tema

> Conoce y comprende las diferentes estructuras de datos, su clasificación y forma de manipularlas para buscar la manera más eficiente de resolver problemas.

## Estructura del proyecto

```
estructura-datos-tema1/
├── index.html
├── clasificacion.html
├── tda.html
├── memoria.html
├── analisis.html
├── practica.html
├── css/
│   └── styles.css
├── js/
│   └── main.js
├── notebooks/
│   └── practica_tema1.ipynb
└── README.md
```

## Licencia

Material didáctico de uso educativo. Basado en el programa de estudios de Estructura de Datos (AED-1026) del TecNM (mayo 2016).
