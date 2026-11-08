## Estructura general

- hardware/ → Componentes físicos de la prótesis
- mechanical/ → Archivos CAD, STL y STEP
- electronics/ → Esquemas y PCBs
- firmware/ → Código embebido (ESP32)
- ml/ → Modelos y datasets
- docs/ → Informes, manuales y decisiones

## Versionado de piezas

Todas las piezas deben subirse siguiendo el sistema de versiones:

/mechanical/socket/v1/
/mechanical/socket/v2/
/mechanical/socket/prototype_YYYY_MM/

Cada versión debe incluir:
- STL
- STEP (si existe)
- CHANGELOG.md

Consultar CONTRIBUTING.md para más detalles.