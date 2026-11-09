# Contributing to Documentacion general

Este documento define las reglas para contribuir al repositorio **Documentacion general**.

## Estructura general

- Documentacion administrativa/ → Informes, manuales y decisiones
- Electronics/ → Esquemas y PCBs
- hardware/ → Componentes físicos de la prótesis
- mechanical/ → Archivos CAD, STL y STEP
- firmware/ → Código embebido (ESP32) 
    - [CIMA3D-Prosthesis](https://github.com/CIMA-3D/CIMA3D-Prosthesis.git)
- Machin learning/ → Modelos y datasets
    - [CIMA3D-Prosthesis](https://github.com/CIMA-3D/CIMA3D-Prosthesis.git)


## Versionado de piezas 3D (STL / STEP)

En impresión 3D se generan múltiples iteraciones de una misma pieza.
Para evitar confusión, se deben seguir estrictamente las siguientes normas:

Todas las piezas deben subirse siguiendo el sistema de versiones:

/mechanical/socket/v1/
/mechanical/socket/v2/
/mechanical/socket/prototype_YYYY_MM/

No se deben sobrescribir archivos antiguos.

Cada versión debe incluir:
- STL
- STEP (si existe)
- CHANGELOG.md

Consultar CONTRIBUTING.md para más detalles.

### 📦 Contenido obligatorio por versión
Cada carpeta de versión debe contener como mínimo:

- Archivo STL
- Archivo STEP (si existe)
- Archivo CHANGELOG.md describiendo los cambios

Ejemplo de estructura:

/mechanical/socket/v2/
- socket_v2.stl
- socket_v2.step
- CHANGELOG.md (en su defecto un comentaro al momento de hacer comit)

### 📝 CHANGELOG.md
El archivo CHANGELOG.md debe describir brevemente:

- Qué se ha modificado
- Por qué se ha modificado
- Fecha
- Autor/a
