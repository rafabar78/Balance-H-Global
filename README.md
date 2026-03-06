[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/rafabar78/Balance-H-Global/blob/main/Balance_Hídrico_Global.ipynb)

# Global Hydro-Intelligence Tool
Herramienta de Hydro-Intelligence para balances hídricos globales. Usa Google Earth Engine (GEE) y Python para procesar series CHIRPS (0.05°) y ERA5-Land. Implementa un buffer de 5.5 km de diámetro para coincidir con la resolución nativa del píxel (Escala 1:1), garantizando precisión en el cálculo de P, ETP.

  
Precipitación - Fuente: CHIRPS V2.0 - Descripción Técnica: Resolución 0.05° (~5.5 km)
Temperatura/ETP - Fuente: ERA5-Land - Descripción Técnica: Resolución 0.1° (~11 km)
Buffer Espacial - Fuente: Geometría Circular - Descripción Técnica: Diámetro de 5.5 km para escala 1:1 con el píxel
