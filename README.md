# Asistente de Ciberseguridad Interactivo con Gemini AI 🤖

## Descripción del Proyecto 📝
Este es un proyecto de **Jupyter Notebook** que utiliza la **API de Gemini** para crear un asistente interactivo de ciberseguridad.  
El objetivo principal es servir como una herramienta educativa, permitiendo a los usuarios aprender y explorar conceptos de ciberseguridad de manera práctica y dinámica.

El asistente tiene las siguientes capacidades clave:

- Generar escenarios de ataque detallados (por ejemplo, phishing, inyección SQL).
- Explicar técnicas de defensa y buenas prácticas de seguridad.
- Evaluar respuestas de los usuarios sobre temas de ciberseguridad, proporcionando retroalimentación constructiva.

## Requisitos 🛠️
Para ejecutar este proyecto, necesitas un entorno de Python con las siguientes dependencias instaladas:

- Python 3.8 o superior
- Jupyter Notebook
- Librería `google-generativeai`

Instalación rápida de la librería:

```bash
pip install -q -U google-generativeai
```

## Configuración de la API 🔑

Para utilizar el proyecto necesitas una **clave de API de Gemini**.

### Obtener la API Key
1. Visita [Google AI Studio](https://studio.google.com/).
2. Inicia sesión con tu cuenta de Google y genera una nueva clave de API.

### Configuración en el Notebook
1. Abre el archivo `POC_Ciberseguridad_Gemini.ipynb` en Jupyter Notebook.
2. Reemplaza `"TU_API_KEY_AQUI"` con tu clave real en el punto 2 (Configurar la API Key)

## Uso del Notebook 🚀

El notebook está diseñado para ser **intuitivo y fácil de usar**:

1. Ejecuta cada celda de código secuencialmente.  
2. Las primeras celdas realizan la configuración inicial y definen las funciones.  
3. En la sección **Llamados de cada función**, encontrarás llamadas a funciones con diferentes escenarios.  
4. La respuesta de la API se mostrará automáticamente debajo de la celda ejecutada.  
