# 🌳 De Selva a Potrero — Guerrero (Terra)

**Equipo:** Dancing' Bros  
**Integrantes:** Oliver Sebastián Ortega García, David Alejandro Ortega García, Yazid Itzayana Rodríguez Rodríguez, Jaquelin de los Ángeles García Constantino, David Israel Ortega González  
**Fecha:** 4 de octubre de 2025  
**Organizador:** NASA Space Apps Challenge 2025
**Localización:** Atoyac de Alvarez - Guerrero

---

## 📂 Estructura del Proyecto
``` dir
/source      → Scripts de Google Earth Engine (GEE)  
/data        → Datos CSV crudos  
/outputs     → Tablas y figuras finales  
/figs        → Mapas y visualizaciones adicionales  
/video       → Video final y frames  
/docs        → Documentos del proyecto (en-US y es-MX)  
/site        → Backup del sitio del proyecto en formato MHTML
```

---

## 📊 Resultados Clave
- **Pérdida acumulada Guerrero (2001–2024):** 29,660 ha  
- **Pérdida acumulada Atoyac:** 1,567 ha (5.3%)  
- **Año con mayor pérdida Guerrero:** 2024 (2,242 ha)  
- **Año con mayor pérdida Atoyac:** 2014 (142 ha)  

> 🔍 *Insights:* La deforestación en Guerrero se aceleró en los últimos años; Atoyac sigue un patrón más estable pero con picos puntuales.  

---

## ⚙️ Cómo Reproducir el Análisis
1. Exporta las series anuales de **MCD12Q1** y **NDVI (MOD13Q1)** desde Google Earth Engine.  
2. Ejecuta los scripts de `/source` para generar todas las salidas en `/outputs`.  
3. *(Opcional)* Integra **MCD64A1 (fuego)** y **ASTER** para inspección antes/después.  

---

## 🧠 Declaración de Uso de IA
Se utilizó IA generativa únicamente para la **redacción y edición** del README.  
Todo el análisis geoespacial se realizó **100% con Google Earth Engine**.  

---

## 🚀 Tips y Extras
- Para comparar años fácilmente, revisa las visualizaciones en `/figs`.  
- Los frames en `/video` pueden usarse para crear animaciones del cambio de cobertura.  
- Todos los datos crudos están en `/data` para **reproducibilidad total**.

---
### ⚙️ Requisitos

* **Java Runtime Environment (JRE)**
* **Visual Studio Code (VSCode)**
* **Google Cloud SDK**
* **Google Earth Engine API**

### 🚀 Instalación y Uso

1. Clona el repositorio privado:

   ```cmd
   git clone <repo-privado>
   cd Repository-GEE-NASA
   ```
2. Abre el proyecto en VSCode.
3. Configura tu acceso a la API de Google Earth Engine con tu cuenta autorizada.
4. Ejecuta los scripts desde la terminal o en VSCode.

### 🌍 Objetivo del Proyecto

El objetivo es aprovechar los **datos satelitales de TERRA** y el poder de la **Google Earth Engine API** para generar soluciones innovadoras dentro del marco del **NASA Hackathon**.

Este repositorio funciona como el centro de colaboración del equipo **Dancing' Bros**.
