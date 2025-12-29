# 📊 Challenge Telecom X: análisis de evasión de clientes

## 📑 Tabla de Contenido
1. [Descripción del proyecto](#-descripción-del-proyecto)
2. [Tecnologías utilizadas](#️-tecnologías-utilizadas)
3. [Librerías utilizadas](#-librerías-utilizadas)
4. [Estructura del proyecto](#-estructura-del-proyecto)
5. [Análisis realizado](#-análisis-realizado)
6. [Principales resultados](#-principales-resultados)
7. [Conclusiones](#-conclusiones)
8. [Estado del proyecto](#-estado-del-proyecto)
9. [Posibles mejoras futuras](#-posibles-mejoras-futuras)


## 🧠 Descripción del proyecto
Este proyecto tiene como objetivo analizar los factores asociados a la cancelación de clientes (*churn*) en una empresa de telecomunicaciones, utilizando análisis exploratorio de datos (EDA) y visualizaciones para identificar patrones relevantes que expliquen por qué los clientes deciden cancelar el servicio.

El análisis se enfoca en variables demográficas, contractuales y económicas, comparando sistemáticamente clientes que cancelan frente a los que no.

---

### 💻 Lenguajes y herramientas principales

<p align="center">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width="60" height="60" alt="Python"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/pandas/pandas-original.svg" width="60" height="60" alt="Pandas"/>
  <img src="https://raw.githubusercontent.com/github/explore/master/topics/folium/folium.png" width="60" height="60" alt="Folium"/>
  <img src="https://upload.wikimedia.org/wikipedia/commons/d/d0/Google_Colaboratory_SVG_Logo.svg" width="60" height="60" alt="Google Colab"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/github/github-original.svg" width="60" height="60" alt="GitHub"/>
</p>

---

### 🧰 Librerías y entornos

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Google Colab](https://img.shields.io/badge/Google%20Colab-F9AB00?style=for-the-badge&logo=googlecolab&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge&logo=plotly&logoColor=white)


---

## 📁 Estructura del proyecto

- `challenge_telecom_x.ipynb` → Notebook con el análisis completo  
- `df_clean.csv` → Dataset limpio utilizado para el análisis  
- `README.md` → Descripción del proyecto  

---

## 🔍 Análisis realizado

El análisis se basa en la comparación entre clientes que **cancelan** y **no cancelan**, utilizando principalmente **porcentajes** para evitar sesgos por volumen.

Las variables analizadas incluyen:

- **Edad del cliente** (`Mayor_65`)
- **Tipo de contrato**
- **Antigüedad del cliente (meses de contrato)**
- **Cargos mensuales**

Para cada variable se seleccionó el tipo de gráfica más adecuado:
- Barras agrupadas para variables categóricas
- Boxplot para variables numéricas continuas

---

## 📈 Principales resultados

- Los clientes con **contratos mensuales** presentan la **mayor tasa de cancelación**.
- La cancelación es significativamente más alta durante los **primeros 12 meses** de relación con el cliente.
- Los clientes que cancelan muestran **cargos mensuales más elevados**, lo que sugiere sensibilidad al precio.
- Los clientes **mayores de 65 años** presentan una tasa de cancelación superior al resto de los clientes, aunque con menor impacto que las variables contractuales.

---

## 🧠 Conclusiones

La cancelación de clientes no ocurre de forma aleatoria, sino que está fuertemente asociada a factores contractuales y económicos. En particular, los contratos de corto plazo, la baja antigüedad y los cargos mensuales elevados incrementan significativamente la probabilidad de churn. Estos hallazgos indican que las estrategias de retención deben enfocarse principalmente en clientes nuevos y con contratos mensuales.

---

## 📌 Estado del proyecto

✅ **Finalizado**  
El análisis cumple con los objetivos planteados y responde de forma clara a la pregunta central del challenge:  
**¿Por qué están cancelando los clientes?**

---

## 🚀 Posibles mejoras futuras

- Construcción de un modelo predictivo de churn  
- Análisis de variables adicionales (servicios contratados, métodos de pago)  
- Creación de un dashboard interactivo  

---

## 👨‍💻 Autor

**Jonathan Caicedo**  
🎓 *Proyecto: Challenge Telecom X - Alura Latam*  
📅 2025  
