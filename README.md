# De selva a potrero — Guerrero (Terra)

Equipo: Dancing' Bros  
Integrantes: Oliver Sebastian Ortega García, David Alejandro Ortega García, Yazid Itzayana Rodríguez Rodríguez, Jaquelin de los Ángeles García Constantino, David Israel Ortega González  
Fecha: 4 de octubre del 2025

## Estructura
/src      (scripts GEE y QGIS)
/data     (metadatos, CSV)
/outputs  (tablas y figuras)
/figs     (mapas/figuras adicionales)
/video    (frames y animación)
README.md
LICENSE

## Resultados clave
- Pérdida acumulada Guerrero (2001–2024): 29,660 ha
- Pérdida acumulada Atoyac: 1,567 ha (5.3%)
- Año pico Guerrero: 2024 (2,242 ha)
- Año pico Atoyac: 2014 (142 ha)

## Reproducibilidad
1) Exportar series anuales (MCD12Q1) y NDVI (MOD13Q1) desde GEE.  
2) Ejecutar el script de análisis para generar `/outputs`.  
3) (Opcional) Integrar MCD64A1 (fuego) y ASTER (lupas antes/después).

## Declaración de uso de IA
IA generativa usada solo para redacción/edición. El análisis geoespacial se realiza con GEE.
