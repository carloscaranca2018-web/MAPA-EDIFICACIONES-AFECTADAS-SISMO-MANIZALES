# Edificaciones Afectadas – Sismo Manizales

Mapa interactivo con la ubicación de las edificaciones afectadas por el sismo en el Área Metropolitana de Manizales (MEMAZ).

## 🗺️ Ver el mapa

- **Localmente:** abre `index.html` en cualquier navegador.
- **En línea (GitHub Pages):** una vez publicado el repositorio, actívalo en `Settings > Pages` (rama `main`, carpeta `/root`) y quedará disponible en:
  `https://<tu-usuario>.github.io/<nombre-del-repositorio>/`

## 📋 Contenido

- **Cuadrantes MEMAZ**: polígonos del Área Metropolitana de Manizales.
- **290 puntos georreferenciados**, cada uno con:
  - Barrio
  - Dirección
  - Nombre de la edificación
  - Uso predominante
  - Estado de habitabilidad (🔴 No habitable por riesgo / 🟢 Habitable post-intervención)
- **Buscador** por barrio, dirección o nombre.
- **Panel de resumen** con conteo total de puntos por categoría.

## 🛠️ Tecnología

Construido con [Leaflet.js](https://leafletjs.com/) y OpenStreetMap como capa base. Es un archivo HTML autocontenido: no requiere instalación ni backend.

## 📁 Estructura

```
├── index.html   # Mapa interactivo (todo el contenido embebido)
└── README.md    # Este archivo
```

## 📊 Fuente de datos

Los datos de georreferenciación provienen de la caracterización de zonas de afectación por el sismo en Manizales, Caldas.
