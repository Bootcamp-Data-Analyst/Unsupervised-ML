# Mushroom Intel: Clasificación Avanzada de Hongos

![Mushroom Intel Banner](docs/mushroom_banner.png)

## Visión General
Este proyecto implementa una solución completa de Machine Learning para la clasificación de hongos entre comestibles y venenosos. Utiliza técnicas de vanguardia como la imputación por vecinos más cercanos (KNN) y modelos de ensamble para garantizar la máxima seguridad en la predicción.

### Puntos Clave
*   **🧠 Inteligencia Predictiva**: Pipeline avanzado con `KNNImputer` y `OrdinalEncoder` para un manejo preciso de datos faltantes.
*   **📊 Dashboard de Alta Gama**: Interfaz interactiva con navegación lateral y visualizaciones dinámicas de Plotly.
*   **✨ Fácil e Intuitivo**: Los menús ahora muestran descripciones claras en español (ej. "Almendra", "Bosque") en lugar de códigos técnicos (ej. "a", "d").
*   **🎨 Branding Completo**: Experiencia visual profesional con banner transparente, logo oficial y favicon personalizado.

## Tecnologías Utilizadas

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=Streamlit&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-%23F37626.svg?style=for-the-badge&logo=jupyter&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![Plotly](https://img.shields.io/badge/Plotly-%233F4F75.svg?style=for-the-badge&logo=plotly&logoColor=white)
![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)

---

## Estructura del Proyecto
```text
Unsupervised-ML/
├── data/                       # Dataset original y procesado
│   └── agaricus-lepiota.data
├── notebooks/                  # Análisis exploratorio y prototipado
│   └── mushroom.ipynb
├── docs/                       # Documentación adicional e imágenes
├── app.py                      # Aplicación principal (Streamlit)
├── requirements.txt            # Dependencias del proyecto
├── .gitignore                  # Configuración de archivos excluidos
└── README.md                   # Documentación principal
```

## Características de la Aplicación
- **Preprocesamiento Inteligente**: Uso de `KNNImputer` (k=5) para una imputación de datos coherente con el análisis científico.
- **Interfaz Humana**: Selectores optimizados con etiquetas descriptivas en lugar de códigos alfanuméricos crípticos.
- **Seguridad en la Predicción**: Modelo entrenado con `RandomForest` alcanzando altos niveles de precisión y confianza.
- **Visualización Progresiva**: Gráficos de distribución global y perfil de características para una exploración EDA profunda.

## Instalación y Uso

1.  **Clonar el repositorio**:
    ```bash
    git clone https://github.com/Bootcamp-Data-Analyst/Unsupervised-ML.git
    cd Unsupervised-ML
    ```

2.  **Instalar dependencias**:
    ```bash
    pip install -r requirements.txt
    ```

3.  **Ejecutar la aplicación**:
    ```bash
    streamlit run app.py
    ```

---
*Desarrollado como parte del proyecto de análisis de aprendizaje no supervisado y clasificación.*

## 🧪 Análisis Realizado

El núcleo analítico se basa en el notebook `mushroom.ipynb`, siguiendo estas etapas:

1.  **Limpieza y Preprocesamiento**: Manejo de valores nulos, eliminación de columnas constantes (`veil-type`) y codificación de variables categóricas (One-Hot & Label Encoding).
2.  **EDA Avanzado**: Análisis de distribuciones y relaciones entre variables como el olor y la clase.
3.  **Matriz de Cramér's V**: Medición de la asociación entre características categóricas.

## 🛠️ Requisitos

Para asegurar el correcto funcionamiento, se requieren:
*   `streamlit`
*   `pandas`
*   `numpy`
*   `plotly`
*   `scikit-learn`
*   `matplotlib` / `seaborn`

---

## 📝 Uso del Notebook

1.  Asegúrate de tener instaladas las dependencias.
2.  Abre `notebooks/mushroom.ipynb` en Jupyter o Google Colab para revisar el análisis estadístico detallado.
