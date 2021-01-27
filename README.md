# Apuntes_UF2_1
## DISEÑO Y REALIZACIÓN DE PRUEBAS
### OBJETIVOS DE LAS PRUEBAS
- Una buena prueba debe centrarse en dos objetivos:
- 1. Probar si el software no hace lo que debe hacer
- 2. Probar si el software hace lo que no debe hacer.
- Existen distintos frameworks para la realización de pruebas.
### FRAMEWORK
- En general, un framework (marco de trabajo) está compuesto por:
  - un conjunto de las mejores prácticas y suposiciones
  - herramientas comunes
  - bibliotecas
- Permite unificar el proceso de desarrollo entre desarrolladores.
### Forma de las Pruebas
- **Pruebas dinámicas:** Requieren la ejecución de la aplicación. Permiten medir el comportamiento de la aplicación desarrollada.
- **Pruebas estáticas:** Se realizan sin ejecutar el código de la aplicación. Se examina el código fuente.
### Estrategias de Prueba
- **Caja negra:** Se estudia el sistema desde fuera. Son pruebas de funcionalidad.
- **Caja blanca:** Se examina el código fuente y su ejecución. Son pruebas estructurales.
### ESTRATEGIAS DE PRUEBA DE CAJA NEGRA
- Se estudia el sistema desde fuera.
- Se trabaja sobre la interfaz.
- No se tienen en cuenta los detalles internos de funcionamiento.
- Se proporcionan entradas y se estudian las salidas.
- Principales técnicas:
  - Particiones de equivalencia
  - Valores límite
### ESTRATEGIAS DE PRUEBA DE CAJA BLANCA
- Se examina el código fuente y su ejecución.
- Se comprueban los flujos de ejecución dentro de cada unidad (función, clase, módulo, etc.)
- También pueden comprobarse los flujos entre unidades durante la integración.
- E incluso entre subsistemas, durante las pruebas de sistema.
- Principales técnicas:
  - Cobertura de código
  - Prueba de bucles
### TIPOS DE PRUEBAS
- **Funcionales:** Evaluan el cumplimiento de los requisitos.
- **No funcionales:** Evaluan aspectos adicionales como rendimiento, seguridad, ...
### PRUEBAS FUNCIONALES
- Pruebas unitarias (o de unidad)
- Pruebas de regresión
- Pruebas de integración
- Pruebas de humo (smoke test)
- Pruebas del sistema
- Pruebas alfa y beta
- Pruebas de aceptación (validación por parte del cliente)
### PRUEBAS NO FUNCIONALES
- Pruebas de usabilidad
- Pruebas de rendimiento
- Pruebas de stress
- Pruebas de seguridad
- Pruebas de compatibilidad
- Pruebas de portabilidad
- ...
### MECANISMOS DE PRUEBA
- Manual
  - Mediante pruebas realizadas por personal de la empresa o externo.
- Automático
  - Mediante software que ejecuta código de forma automatizada y compara los resultados obtenidos y los resultados esperados.
### SOPORTE DEL DEPURADOR
- Puntos de ruptura
- Ejecución paso a paso
- Análisis de variables
### TDD 
- Desarrollo guiado por pruebas de software, o Test-Driven Development (TDD)
  - Escribir las pruebas primero (Test First Development).
  - Refactorización (Refactoring).
### Formas de integración
- Integración Big bang
- Integración Descendente
- Integración Ascendente
- Integración Continua (CI)
### SERVIDORES DE INTEGRACIÓN CONTINUA
- CI : Integración continua
- CD : Entrega continua
- Jenkins
- Bamboo
- TravisCI
- CircleCI







