# Auditoría inicial del repositorio
**Alcance:** portada README, listado raíz y ficha `00-ficha-del-concurso.md` accesibles públicamente el 21/11/2026. Sin acceso integral a subcarpetas ni al PDF binario.

## Confirmado en la raíz visible
`README.md`, `00-ficha-del-concurso.md`, `cargo aspirante.pdf`, `cargo-aspirante.txt`, `index.html`; carpetas `02-normas`, `03-temario`, `05-plan-estudio`, `06-banco-practica`, `07-pendientes`, `08-estudio-general`, `09-simulacros`.

## Alertas (no asumir que ausente en todas las ramas)
- README enumera `01-fuentes-oficiales` y `04-valoracion-antecedentes`, no visibles en lista raíz consultada.
- La ficha presenta la Resolución 243 como resolución principal de apertura. **La apertura fue la Resolución 076 del 24 de marzo de 2026**; la Resolución 243 del 2 de septiembre de 2026 es modificatoria.
- El art. 6 de la Resolución 243 incluye expresamente la convocatoria **288**: se debe cotejar la versión corregida antes de fijar número de plazas, requisitos y calendario.
- Inscripciones del 7 al 18 de septiembre consignadas en ficha: históricas, no asumir vigentes ni abiertas.
- Lista de normas incluye Ley 640/2001, Ley 734/2002 y Decreto 1075/2015 como base archivística: actualizar y contextualizar, ver matriz normativa.
- No se pudo auditar código HTML/JS, accesibilidad, integridad de enlaces internos ni calidad de todas las preguntas.

## Riesgos y prioridad
**P0** Actualización del empleo 288 y sus versiones; **P0** no estudiar normas derogadas como vigentes; **P1** verificar documentos oficiales y calendario; **P1** inventario de fuentes; **P2** preguntas con trazabilidad a norma y fecha; **P2** pruebas automatizadas para `index.html` si contiene funcionalidad.

## Procedimiento de verificación
Leer convocatoria vigente publicada por Procuraduría y comparar: cargo/código, número de vacantes, funciones, requisitos, inscripción, pruebas, puntajes, fechas y reclamaciones. Guardar una tabla de cambios con `dato anterior`, `dato vigente`, `documento`, `artículo/página`, `fecha revisión`.
