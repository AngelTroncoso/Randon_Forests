# 🌲🌲Predicción de Rendimiento Agrícola con Bosques Aleatorios🌾
![siembra](https://image.lexica.art/full_webp/b7a85875-316d-408e-9170-ee85004ec7a0)

¡Bienvenido al repositorio de modelos predictivos para agricultura de precisión! Este proyecto utiliza **Bosques Aleatorios (Random Forests)** para estimar el rendimiento de cultivos basado en condiciones ambientales y prácticas agrícolas. Ideal para agronomía, gestión de cultivos y optimización de recursos.

## 📋 Tabla de Contenidos
1. [Requisitos](#🔧-requisitos)
2. [Instalación](#⚙️-instalación)
3. [Uso](#🚀-uso)
4. [Estructura del Proyecto](#📂-estructura-del-proyecto)
5. [Datos](#📊-datos)
6. [Resultados](#📈-resultados)
7. [Contribución](#🤝-contribución)
8. [Licencia](#📜-licencia)
9. [Contacto](#📧-contacto)

---

## 🔧 Requisitos
- Python 3.8+
- Bibliotecas: `scikit-learn`, `pandas`, `numpy`, `matplotlib`, `seaborn`, `joblib`
- Memoria: 8GB+ RAM (para grandes conjuntos de datos)

## ⚙️ Instalación
```bash
# Clonar repositorio
git clone https://github.com/tuusuario/random-forest-agricultura.git

# Instalar dependencias
pip install -r requirements.txt
```
## 📂 Estructura del Proyecto

├── data/  
│   ├── rendimiento_cultivos.csv     # Dataset principal  
│   └── generador_datos_agricolas.py # Generador de datos sintéticos  
├── modelos/  
│   ├── entrenamiento_rf.py          # Entrenamiento del bosque aleatorio  
│   ├── optimizacion_hiperparametros.py  # Búsqueda de mejores parámetros  
│   └── prediccion_rendimiento.py    # Script para nuevas predicciones  
├── notebooks/  
│   ├── analisis_exploratorio.ipynb  # EDA interactivo  
│   └── visualizacion_importancia.ipynb  # Importancia de variables  
├── resultados/  
│   ├── mejor_modelo.joblib          # Modelo serializado  
│   ├ importancia_caracteristicas.png# Gráfico de importancia  
│   ├── metricas_evaluacion.txt        
│   └── predicciones_ejemplo.csv     # Predicciones de muestra  
└── requirements.txt  

## 📊 Datos

- Variables del dataset ficticio (generado sintéticamente):

- lluvia_mm (Precipitación acumulada en mm)

- temp_promedio (°C promedio durante temporada de crecimiento)

- tipo_suelo (Categórico: Arenoso, Arcilloso, Franco)

- fertilizante_kg (Kg de fertilizante por hectárea aplicado)

- densidad_siembra (Plantas por m²)

- horas_sol (Horas de sol diarias promedio)
  
## 🤝 Contribución
¡Aportes son bienvenidos! Sigue este proceso:

- Revisa los issues existentes o crea uno nuevo

- Haz fork del repositorio

- Crea tu rama: git checkout -b feature/mejora-modelo

- Realiza tus modificaciones

- Ejecuta pruebas con pytest tests/

- Haz push y abre un Pull Request

## 📜 Licencia  
- Distribuido bajo licencia GNU GPLv3. Ver LICENSE para detalles.
- Target: rendimiento_ton_ha (Toneladas por hectárea)

  ¡Dame una estrella si te parecio interesante! 🌟
