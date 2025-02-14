# climateBERT-analysis

# Análisis de la Calidad de Reportes Ambientales en España (2015-2022)

Este repositorio contiene el código y los datos asociados al paper:  
**"Evaluación de la Regulación en la Calidad de la Divulgación Ambiental: Un Análisis con Transformers Fine-Tuned"**.

## 📌 Resumen
Investigamos cómo la regulación afecta la calidad de los reportes ambientales de empresas españolas entre 2015-2022.  
Para ello, utilizamos técnicas avanzadas de NLP, como **ClimateBERT** y una versión fine-tuned en **ClimaText**, para analizar 729 reportes corporativos.

Nuestros hallazgos sugieren que la regulación ha mejorado la especificidad y el compromiso en los reportes, especialmente en textos relacionados con riesgos.

## 📂 Estructura del repositorio
- `notebooks/` – Jupyter Notebooks con análisis de datos, entrenamiento de modelos y evaluación.
- `src/` – Código estructurado en Python para preprocesamiento y análisis.
- `data/` – (Opcional) Datos utilizados o instrucciones para obtenerlos.
- `results/` – Tablas y visualizaciones clave obtenidas.
- `requirements.txt` – Lista de dependencias.
- `Reproducibility.md` – Guía para reproducir el estudio.
- `Paper.pdf` – Versión en PDF del artículo.

## 🚀 Instalación
Clona este repositorio e instala las dependencias:

```bash
git clone https://github.com/usuario/nlp-climate-disclosure.git
cd nlp-climate-disclosure
pip install -r requirements.txt
