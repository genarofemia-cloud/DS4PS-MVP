# DS4PS-MVP
MVP de dashboard web para predicción de precipitaciones agrícolas. Visualiza pronósticos, historial de lluvias y alertas por zona usando datos meteorológicos en tiempo real.

# 🌧️ Dashboard Predictor de Precipitaciones en Provincia de Santa Fe — MVP

Dashboard web orientado al sector agropecuario para visualizar y anticipar
eventos de lluvia, apoyando la toma de decisiones en siembra, riego y cosecha.

## 📌 Descripción

Este MVP permite a productores rurales y técnicos agropecuarios consultar
pronósticos de precipitaciones geolocalizados, con visualizaciones claras
del historial reciente y alertas configurables por umbral de lluvia.

Desarrollado como prueba de concepto para validar la utilidad de datos
meteorológicos accesibles en la gestión del campo.

## 🎯 Funcionalidades del MVP

- 📍 Selección de zona/parcela por coordenadas o nombre de localidad
- 📊 Gráfico de precipitaciones acumuladas (últimos 7 y 30 días)
- 🔮 Pronóstico a 5 días con probabilidad de lluvia y mm esperados
- 🚨 Alertas visuales por eventos de lluvia intensa o déficit hídrico
- 🗺️ Mapa de calor de precipitaciones por región (vista general)

## 🛠️ Stack Tecnológico

| Capa | Tecnología |
|------|------------|
| Frontend | React + Recharts / Chart.js |
| Backend | Python (FastAPI) |
| Datos meteorológicos | Open-Meteo API / API--SMN--IGN República Argentina |
| Mapas | Leaflet.js |
| Deploy | Vercel / Railway |

## 🚀 Cómo correr el proyecto localmente

```bash
# Clonar el repositorio
git clone https://github.com/tu-usuario/rain-forecast-dashboard.git
cd rain-forecast-dashboard

# Instalar dependencias
npm install       # Frontend
pip install -r requirements.txt  # Backend

# Levantar el servidor
npm run dev
```

## 📁 Estructura del proyecto
