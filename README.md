# TDR Aviation Fuel Simulator

**Treball de Recerca - Batxillerat**  
*High School Research Project on Sustainable Aviation Fuels*

---

## Overview

This is an interactive flight simulator developed as part of a high school research project (TDR). The tool allows users to compare the environmental and economic impact of traditional jet fuel (JET-A1) versus liquid hydrogen (LH2) on real flight routes across Europe.

The interface is in **Catalan** as it is a requirement for the school project.

---

## Features

- **9 aircraft models**:
  - Airbus A320, A330-300, A350-900, A380
  - Boeing 737-800, 777-300ER, 787-9, 747-8
  - Eurofighter Typhoon (military)

- **25+ airports** across:
  - Spain
  - United Kingdom
  - France
  - Germany

- **Real flight routes** with actual waypoints (SALAS, RAMON, RUBEO, CMA, etc.)

- **Interactive map** powered by Leaflet.js

- **CO₂ emissions comparison** between kerosene and hydrogen

- **Cost analysis** per flight route

- **Real-time flight data**:
  - Distance (great-circle route)
  - Flight time
  - Fuel consumption
  - CO₂ emissions
  - Total cost

---

## How It Works

The simulator calculates fuel consumption using a simplified Breguet equation:
