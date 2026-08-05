## :rocket: API Testing - Urban Grocers

### :dart: Objetivo
Validar la calidad y estabilidad de los servicios back-end de Urban Grocers a partir de la documentación oficial en ApiDoc, asegurando el cumplimiento de los criterios de aceptación y la correcta implementación de los métodos REST.

### :gear: Proceso de Pruebas
1.  **Análisis de Requisitos:** Revisión de la documentación técnica en ApiDoc para definir el alcance, flujos críticos y reglas de negocio.
2.  **Diseño de Casos:** Creación de checklist y casos de prueba en Excel, contemplando escenarios positivos, negativos, de límites y manejo de errores.
3.  **Ejecución:** Validación de endpoints mediante colecciones en **Postman**, verificando los métodos `POST` para creación, `GET` para consulta y `PATCH` para actualización de usuarios.
4.  **Gestión de Defectos:** Reporte y seguimiento de incidencias en **Jira** con pasos reproducibles, evidencia, severidad y trazabilidad hacia el requisito.

### :chart_with_upwards_trend: Resultados
Se detectaron y documentaron **26 defectos**, concentrados principalmente en la validación de límites del método `GET`. Se logró optimizar los tiempos de ejecución mediante la automatización del flujo en colecciones de Postman, asegurando la calidad del servicio antes de su integración con el front-end.

### :bulb: Conclusiones
Este proyecto marcó mi transición de UI a Back-end Testing. Fortalecí mi entendimiento de métodos HTTP, códigos de estado y validación de contratos. Consolidó mi criterio para detectar defectos críticos que no son visibles en la interfaz y mejoró mi documentación técnica en Jira.

### :wrench: Herramientas
`Postman` | `Jira` | `Excel` | `ApiDoc`
