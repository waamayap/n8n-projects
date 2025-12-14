# Proyecto de Web Scraping con Inteligencia Artificial

Este repositorio contiene un proyecto de web scraping diseñado para extraer,
procesar y almacenar información de sitios web de forma automatizada, utilizando
inteligencia artificial y flujos de trabajo escalables con n8n.

El proyecto se basa en un enfoque modular y por etapas, permitiendo manejar
sitios con estructuras cambiantes, protecciones anti-bot y distintos tipos de
datos (estructurados y no estructurados).

---

## 🎯 Objetivo del Proyecto

Diseñar y documentar un flujo de web scraping que:
- Extraiga información de sitios web de cursos u otras fuentes públicas.
- Utilice modelos de IA para interpretar el contenido de forma flexible.
- Procese el HTML crudo y lo transforme en texto limpio y estructurado.
- Almacene los resultados en herramientas adecuadas según el tipo de dato.
- Sea escalable, reutilizable y fácil de mantener.

---

## 🧠 Tecnologías Utilizadas

- **n8n**: Orquestación de flujos de trabajo automatizados.
- **Servicios de scraping especializados (ej. Firecrawl)**: Para interactuar con
  sitios web protegidos y evitar bloqueos comunes (403 Forbidden).
- **Inteligencia Artificial (OpenAI)**: Extracción semántica de información y
  refinamiento del contenido.
- **HTML → Markdown**: Preprocesamiento para mejorar la calidad del texto.
- **JSON estructurado**: Salida de datos lista para ser utilizada por otros nodos.
- **Google Sheets**: Almacenamiento de datos estructurados (URLs, nombres, precios, etc.).
- **Google Docs**: Almacenamiento de contenido extenso y semiestructurado.

---

## 🗂️ Estructura del Repositorio

```text
n8n-projects/
├── project-web-scraping/
│   ├── workflows/        # Flujos exportados desde n8n (.json)
│   ├── docs/             # Documentación adicional del proyecto
│   └── README.md         # Descripción específica del proyecto
└── README.md             # Este archivo
