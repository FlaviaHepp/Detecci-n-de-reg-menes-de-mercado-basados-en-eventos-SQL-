# 📊Detección de regímenes de mercado basados ​​en eventos (SQL)

## 📌Descripción

Este proyecto presenta un conjunto de análisis cuantitativos orientados a la detección de regímenes de mercado, desarrollados en SQL, combinando indicadores técnicos extremos con eventos informativos (noticias).

El objetivo es identificar zonas de alta probabilidad de estrés, reversión o aceleración del mercado, donde confluyen señales técnicas y eventos exógenos.

## 🎯Objetivos del Proyecto

- Detectar extremos técnicos relevantes en los activos
- Analizar la coincidencia temporal entre señales técnicas y noticias
- Medir el impacto de eventos informativos sobre volatilidad y tendencia
- Identificar regímenes de riesgo y posibles puntos de inflexión
- Aplicar SQL a problemas reales de market analytics

## 🧠Enfoque Analítico

El proyecto integra:
- Indicadores técnicos (ADX, volatilidad, métricas extremas)
- Eventos y noticias como shocks exógenos
- Análisis pre y post evento
- Clasificación de escenarios de mercado
- Agregación a nivel activo, industria y sector

Las preguntas que guía el análisis son:
- ¿Cuándo una señal técnica extrema deja de ser ruido?
- ¿Qué sucede cuando coincide con una noticia relevante?
- ¿El mercado entra en estrés, reversión o continuación?

## 🗂️Contenido del Repositorio

📁 Insights Principales

- Clasificación de Tickers por Robustez de la Tendencia (ADX)
- Clasificación de Eventos por Volatilidad Post-Evento
- Cobertura de la Volatilidad Sectorial por Eventos
- Cobertura de Noticias y Volatilidad Implícita (Kurtosis)
- Coincidencia de Eventos Negativos en la Industria
- Coincidencia de Extremos Técnicos y Noticias

Cada insight está implementado como un query SQL independiente, enfocado en una hipótesis concreta sobre el comportamiento del mercado.

## 🧮Tecnologías Utilizadas

- SQL
- Bases de datos relacionales
- Compatible con PostgreSQL / MySQL / BigQuery

## 🗃️Modelo de Datos (conceptual)

- tickers
- ticker_id
- nombre_empresa
- sector
- industria
- indicadores_tecnicos
- ticker_id
- fecha
- ADX, volatilidad, métricas extremas
- eventos / noticias
- ticker_id
- fecha_evento
- tipo_evento
- sentimiento / severidad
- volatilidad_implicita
- ticker_id
- fecha
- métricas implícitas

## 📈Casos de Uso

- Identificación de regímenes de estrés
- Análisis de puntos de inflexión
- Research cuantitativo basado en eventos
- Apoyo a estrategias event-driven
- Evaluación de riesgo sistémico

## ⚠️Consideraciones

- La coincidencia no implica causalidad
- Las señales técnicas extremas requieren contexto

Recomendado complementar con:
- gestión de riesgo
- validación histórica
- análisis macroeconómico

## 🚀Posibles Extensiones

- Score de estrés por activo / sector
- Backtesting de señales combinadas
- Alertas por confluencia de señales
- Visualización de regímenes de mercado

## 👤Autor

Flavia Hepp
Market Regime Detection · Event-Driven Analytics · SQL
