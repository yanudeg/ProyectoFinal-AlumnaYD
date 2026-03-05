# Instagram Lite - Proyecto QA

## Integrante
- Yanina Alexandra Degorgue

## Objetivo del testing
Validar el funcionamiento principal de una app tipo “Instagram Lite” (login, feed, interacción, búsqueda, perfil, settings y publicación), documentando casos, ejecución y defectos con evidencia.

## Alcance y entorno de prueba
- **Alcance:** Autenticación, Feed, Likes/Comentarios, Búsqueda, Perfil, Privacidad, Publicación, Manejo de errores básicos.
- **Entorno:** Mobile (iOS/Android), build demo 1.0.0 (simulada), red WiFi/4G (simulada), evidencias por capturas/logs.

## Conclusión general
El producto **no está listo para producción** hasta resolver defectos core (persistencia de like y privacidad, validación de comentarios) y re-ejecutar el smoke principal.

## Estructura del repositorio (mínima)
- /historias_usuario/historias_usuario.txt
- /casos_de_prueba/matriz_pruebas.xlsx
- /bugs/reporte_bugs.xlsx
- /api_testing/casos_api.xlsx
- /api_testing/api_resultados.txt
- /documentos/informe_final.txt
- README.md
