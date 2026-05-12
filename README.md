# 👋 Hola, soy Víctor Horcas

### Data Scientist | AI Engineer

Graduado en Economía y Máster en Data Science & AI, actualmente trabajando como **AI Engineer en Civica** (Granada). Apasionado por construir soluciones inteligentes que combinan Machine Learning, NLP y arquitecturas de datos modernas.

---

## 🚀 Sobre mí

- 🔭 **Actualmente:** AI Engineer en **Civica** — trabajando con Snowflake, DBT y Cortex Analyst
- 🎓 **Formación:** Máster en Data Science & IA | Graduado en Economía
- 🌱 **Aprendiendo:** Agentic AI, LangChain/LangGraph, arquitecturas RAG avanzadas
- 💼 **LinkedIn:** [Perfil de Linkedin](www.linkedin.com/in/victorhorcaspuertas)
- 📍 **Ubicación actual:** Granada, España

---

## 🛠️ Stack Técnico

### Lenguajes & Core
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)

### Machine Learning & Deep Learning
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-FF6600?style=for-the-badge&logo=xgboost&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![Transformers](https://img.shields.io/badge/🤗_Transformers-FFD21E?style=for-the-badge)

### NLP & Generative AI
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-FF4B4B?style=for-the-badge)
![Gemini](https://img.shields.io/badge/Google_Gemini-8E75B2?style=for-the-badge&logo=google&logoColor=white)

### Data Engineering & Databases
![Snowflake](https://img.shields.io/badge/Snowflake-29B5E8?style=for-the-badge&logo=snowflake&logoColor=white)
![DBT](https://img.shields.io/badge/DBT-FF694B?style=for-the-badge&logo=dbt&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)

### Tools & Frameworks
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

---

## 📊 Proyectos Destacados

### 🎵 [Predicción Musical - TFM](https://github.com/viictorhp/musical_predictor_PFM)
**Clasificación Multiclase | Feature Engineering | SHAP | LangChain**

Sistema de ML que predice el tier de sala de artistas de rap/urbano español (bajo/medio/alto) analizando 6 fuentes de datos: Spotify, Last.fm, YouTube, setlist.fm y tendencias. Incluye dashboard Streamlit con explicabilidad SHAP y agente conversacional con LangChain + Groq.

- 🎯 **67.5% accuracy** con XGBoost tuneado sobre 157 artistas
- 📈 32 features engineered combinando métricas de streaming, engagement y actividad en directo
- 🤖 Agente IA para explicación interpretable de predicciones
- 🧪 100% cobertura de tests unitarios

**Tech:** `Python` `XGBoost` `SHAP` `LangChain` `Streamlit` `pytest`

---

### 🤖 [Agente RAG - Industria Textil Española](https://github.com/viictorhp/gemini_agent)
**RAG | LangGraph | Vector Store | NLP**

Agente conversacional experto en la industria textil y moda española usando Retrieval-Augmented Generation. Implementa pipeline RAG completo con reformulación de queries, búsqueda semántica con MMR y generación contextual con memoria conversacional.

- 📚 Base de conocimiento: 4 PDFs (322 páginas) indexados en ChromaDB
- 🧠 **E5 multilingual embeddings** locales sin cuotas de API
- 🔄 **LangGraph** con 3 nodos secuenciales y memoria persistente
- 🌐 Desplegado en [Streamlit Cloud](https://geminiagent-z9tcmwt4mrmgarz4svyrjk.streamlit.app/)

**Tech:** `LangChain` `LangGraph` `ChromaDB` `Gemini 2.0` `Streamlit`

---

### 💬 [Análisis de Sentimiento - Trustpilot](https://github.com/viictorhp/deep_learning_project)
**Deep Learning | NLP | Topic Modeling**

Análisis de reputación online de dice.fm mediante 123K reseñas de Trustpilot. Combina análisis de sentimiento multilingüe con DistilBERT y topic modeling con TF-IDF + NMF para identificar fortalezas y debilidades versus competencia del sector.

- 📊 Análisis comparativo: dice.fm vs. sector Events & Entertainment
- 🎯 **DistilBERT multilingual** para clasificación de sentimiento (3 clases)
- 🔍 **NMF con 6 componentes** para extracción de topics interpretables
- 📉 Identificados gaps críticos: -37.2% en servicio al cliente, +23.8% en UX de compra

**Tech:** `Transformers` `DistilBERT` `scikit-learn` `NMF` `TF-IDF`

---

### 🛒 [Predicción de Recompra - E-commerce](https://github.com/viictorhp/MachineLearningProject)
**Binary Classification | Feature Engineering | RFM Analysis**

Sistema predictivo para identificar clientes con alta probabilidad de recompra usando el dataset Online Retail II (1M+ transacciones). Pipeline completo de ML con feature engineering RFM, validación temporal y optimización de hiperparámetros.

- 📈 **AUC 0.794** con XGBoost como mejor modelo
- 🎯 Features RFM (Recencia, Frecuencia, Revenue) + engineered variables
- ⚖️ Validación temporal para evitar data leakage
- 💡 Estrategia de negocio segmentada por probabilidad de recompra

**Tech:** `Python` `XGBoost` `scikit-learn` `Pandas` `GridSearchCV`

---

## 📈 GitHub Stats

<div align="center">
  
![](https://github-readme-stats.vercel.app/api?username=viictorhp&show_icons=true&theme=radical&hide_border=true&include_all_commits=true&count_private=true)

![](https://github-readme-stats.vercel.app/api/top-langs/?username=viictorhp&layout=compact&theme=radical&hide_border=true)

</div>

---

## 🎯 Enfoque Actual

Mis proyectos combinan rigor técnico con aplicabilidad práctica:

- ✅ **End-to-end ML pipelines** — desde ingesta de datos hasta deployment
- ✅ **Explicabilidad** — SHAP, feature importance, análisis de errores
- ✅ **Testing riguroso** — cobertura completa, fixtures, edge cases
- ✅ **Production-ready** — deployment en Streamlit Cloud, APIs, agentes conversacionales
- ✅ **Best practices** — Git, virtual environments, requirements.txt, documentación completa
