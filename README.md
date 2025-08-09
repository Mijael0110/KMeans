# Clasificación de zonas en California por ingresos medios con K-Means

Este proyecto aplica **Machine Learning no supervisado** para agrupar zonas de viviendas en el estado de California, utilizando el algoritmo **K-Means**.  
El objetivo es identificar **patrones socioeconómicos** basados en el **ingreso medio**, la **latitud** y la **longitud**.

---

## Dataset
El dataset contiene información de viviendas en California, incluyendo:
- `latitude` → Latitud de la zona.
- `longitude` → Longitud de la zona.
- `median_income` → Ingreso medio de los hogares.

---

## Metodología
1. **Preprocesamiento**
   - Selección de variables relevantes.
   - Escalado de características para evitar que una variable domine la métrica de distancia.
2. **Entrenamiento del modelo**
   - Uso de `KMeans` con `n_clusters=6` para segmentar zonas.
3. **Visualización**
   - Gráficos de distribución de grupos (`countplot`).
   - Mapa de clusters en el espacio geográfico.

---

## Objetivos del proyecto
- Clasificar las viviendas según ingresos medios.
- Analizar si existe relación entre ubicación geográfica e ingreso.
- Visualizar la segmentación en un mapa para interpretación intuitiva.

---

## Tecnologías utilizadas
- **Python 3**
- **Pandas** → Manejo y análisis de datos.
- **Scikit-learn** → Implementación de K-Means.
- **Matplotlib / Seaborn** → Visualización de datos.

---

## Ejecución
Clonar el repositorio y ejecutar el script principal:

```bash
git clone https://github.com/usuario/proyecto-california-kmeans.git
cd proyecto-california-kmeans
python main.py
