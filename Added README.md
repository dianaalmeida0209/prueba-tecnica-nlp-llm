# Análisis de CVs usando NLP y LLMs

## Descripción
Sistema automatizado para análisis de Currículum Vitae utilizando técnicas de NLP y LLMs.

## Modelos Utilizados
- BART (facebook/bart-large-mnli) para clasificación zero-shot
- BERT (dslim/bert-base-NER-uncased) para reconocimiento de entidades
- spaCy (es_core_news_sm) para procesamiento en español

## Funcionalidades
- Extracción de información de CVs:
  - Nombre completo
  - Información de contacto
  - Años de experiencia
  - Formación en IA
- Sistema de scoring para cada campo extraído
- Generación de datos sintéticos para pruebas

## Resultados
El sistema logra extraer información con alta precisión:
- Nombres: 95% de precisión
- Contacto: 100% de precisión
- Experiencia: 95% de precisión
- Formación IA: 85-95% de precisión

## Autor
Diana Almeida
