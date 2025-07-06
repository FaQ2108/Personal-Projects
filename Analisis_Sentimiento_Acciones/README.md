# 📈 Análisis de Sentimiento de Noticias Financieras

Proyecto para analizar el sentimiento de noticias relacionadas con acciones bursátiles utilizando NLP (Procesamiento de Lenguaje Natural).

## 🔍 Descripción
Este sistema:
- Recupera noticias financieras en tiempo real usando NewsAPI
- Traduce y analiza su sentimiento con VADER
- Clasifica noticias como:
  - 🟢 Positivas
  - 🔴 Negativas
  - ⚪ Neutrales
- Genera visualizaciones de tendencias temporales

## ⚙️ Requisitos
```
pip install newsapi-python pandas numpy matplotlib googletrans==4.0.0-rc1 vaderSentiment
```
🚀 Instrucciones de ejecución
1. Clonar el repositorio:

```
git clone https://github.com/FaQ2108/Proyectos-Personales.git
cd Proyectos-Personales/Analisis_Sentimiento_Acciones
```
2. Instalar dependencias:
```
pip install -r requirements.txt
```
3. Ejecutar el notebook:
```
jupyter notebook Analisis_de_Sentimientos_Acciones.ipynb
```
4. Insertar tu API key de NewsAPI cuando el notebook lo solicite
