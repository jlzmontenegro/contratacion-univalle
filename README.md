# Contratación Universidad del Valle 2024–2026

Tablero interactivo con los 8.821 contratos de la Universidad del Valle (NIT 890.399.010-6) de 2024 a octubre de 2026:
filtros por año, tipo de contrato, valor y contratista, gráficos que filtran al hacer clic y la tabla completa de
contratos (contratista, número, tipo, objeto completo, fechas y valor) con búsqueda, orden, paginación y columnas a elegir.

**Fuentes**
- 2024: documentos de contrato publicados por Univalle en SECOP II (órdenes contractuales, contratos, actas de inicio,
  registros presupuestales, actas de designación de supervisor), leídos automáticamente, con OCR para los escaneados.
- 2025 y 2026: reportes de ejecución de contratos del portal de Transparencia de Univalle.

Valor = valor inicial adjudicado, sin adiciones. Corte: 22 de octubre de 2026.

Los datos están en [`data/contratos.json`](data/contratos.json). La página no necesita compilación: es HTML estático con
[d3](https://d3js.org/) desde CDN.
