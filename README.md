# educational-email-scraper-ecuador

Proyecto en Python orientado a la **recolección automatizada de correos electrónicos institucionales públicos** de centros educativos en Ecuador, mediante técnicas de **web scraping**, búsquedas automatizadas en Google y análisis de contenido HTML.

El sistema está diseñado para **fines académicos, investigativos y de análisis de datos**, utilizando exclusivamente información publicada de forma abierta en sitios web oficiales.

---

## 🎯 Objetivo del proyecto

Desarrollar una herramienta que permita:
- Identificar sitios web de instituciones educativas
- Extraer correos electrónicos institucionales visibles públicamente
- Normalizar nombres de instituciones
- Exportar resultados estructurados en formatos reutilizables (CSV / JSON)

---

## 🚀 Funcionalidades principales

### 🔍 Búsqueda automatizada
- Uso de múltiples consultas personalizadas en Google
- Enfoque en instituciones educativas de Ecuador
- Soporte multiversión del scraper (v0.0.1 → v0.0.4)

### 🌐 Web scraping
- Descarga y análisis de HTML con `requests`
- Parseo de contenido con `BeautifulSoup`
- Extracción de correos mediante expresiones regulares
- Manejo de timeouts y errores de red

### 🧹 Normalización de datos
- Limpieza automática de títulos HTML
- Eliminación de palabras irrelevantes (contacto, oficial, web, etc.)
- Capitalización correcta de nombres
- Unificación de resultados duplicados

### 📦 Exportación de datos
- CSV (versiones iniciales)
- JSON estructurado (versiones avanzadas)
- Descarga directa desde Google Colab

---

## 🧰 Tecnologías utilizadas

- Python 3
- Google Colab
- requests
- BeautifulSoup4
- googlesearch-python
- re (expresiones regulares)
- CSV / JSON

---

## 📁 Estructura del proyecto

