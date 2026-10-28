## Ficha de datos para el TP6

- **Pregunta:** ¿Qué socios comerciales ganaron (y perdieron) participación en las importaciones argentinas desde 2024, en comparación con 2019–2023? ¿Cambió también la composición de los destinos de exportación?
- **Fuente (URL):** https://comex.indec.gob.ar/#/database (INDEC, Sistema de Consulta de Comercio Exterior de Bienes)
- **Método de obtención:** descarga directa de las bases (CSV) con `requests`, guardando los archivos crudos en el repositorio
- **Unidad de observación y período:** país socio × mes, exportaciones FOB e importaciones CIF en dólares, 2019–2026
- **Condiciones de uso o licencia:** datos públicos del INDEC; se citará la fuente y se revisarán los términos de uso del sitio
- **Cómo voy a verificar los datos:** comparar los totales anuales y los principales socios contra los informes de Intercambio Comercial Argentino (ICA) del INDEC, teniendo en cuenta que en el ICA China incluye a Hong Kong y en el sistema de consultas no; para 2019–2023, verificación cruzada con WITS (Banco Mundial)
