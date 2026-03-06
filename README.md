[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/rafabar78/Balance-H-Global/blob/main/Balance_Hidrico_Global.ipynb)

# Global Hydro-Intelligence Tool
Geospatial Engine for Multi-temporal Water Balance & Climate Metrics
Motor de análisis hidro-climático de alta precisión diseñado para la extracción y procesamiento de series temporales globales. La herramienta integra Google Earth Engine (GEE) y Python para la gestión avanzada de datos climáticos, permitiendo a consultores e investigadores obtener métricas hídricas robustas en cualquier coordenada geográfica.

🎯 Innovación en la Precisión Espacial
A diferencia de los análisis convencionales, este motor implementa un buffer circular de 5.5 km de diámetro (radio de 2,750 m). Esta dimensión está calibrada específicamente para:

Sincronización 1:1 con el Píxel: Coincidir con la resolución nominal de 0.05° de los sensores satelitales (como CHIRPS).

Integridad Estadística: Garantizar que los valores promediados (Precipitación, ETP) representen la unidad mínima de información sin sesgos por interpolación espacial.

Escalabilidad: Aplicable desde microcuencas hasta análisis regionales complejos.

  
*Precipitación: Fuente CHIRPS V2.0 - Descripción Técnica Resolución 0.05° (~5.5 km)*

*Temperatura/ETP - Fuente ERA5-Land - Descripción Técnica Resolución 0.1° (~11 km)*

*Buffer Espacial - Fuente Geometría Circular - Descripción Técnica Diámetro de 5.5 km para escala 1:1 con el píxel*
