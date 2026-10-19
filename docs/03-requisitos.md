# 03. Requisitos funcionales y no funcionales

## Cómo elaborar este apartado

Redacta requisitos concretos, verificables y sin ambigüedad. Los requisitos funcionales describen qué hace el sistema. Los no funcionales describen cualidades o restricciones, como accesibilidad, compatibilidad o rendimiento. Asigna un identificador a cada requisito y define cómo comprobarlo.

## Plantilla vacía: requisito funcional

### RF-XXX — [Nombre]
- **Descripción:** [Qué debe hacer el sistema]
- **Justificación:** [Por qué es necesario]
- **Prioridad:** [Alta / Media / Baja]
- **Precondiciones:** [Condiciones previas]
- **Criterios de aceptación:**
  - [ ] [Criterio verificable]
- **Casos de uso relacionados:** [CU-XXX]
- **Pruebas relacionadas:** [CP-XXX]
- **Estado:** [Propuesto / Aprobado / Implementado / Verificado]

## Plantilla vacía: requisito no funcional

### RNF-XXX — [Nombre]
- **Categoría:** [Accesibilidad / Rendimiento / Seguridad / Compatibilidad / Usabilidad / Otra]
- **Descripción:** [Cualidad o restricción]
- **Medida o criterio verificable:** [Cómo se evaluará]
- **Prioridad:** [Alta / Media / Baja]
- **Pruebas relacionadas:** [CP-XXX]
- **Estado:** [Propuesto / Aprobado / Implementado / Verificado]

## Ejemplo ficticio

### RF-001 — Validar formulario de contacto
- **Descripción:** el navegador comprobará que los campos obligatorios estén completos y que el correo tenga un formato aceptado.
- **Prioridad:** Alta.
- **Criterios de aceptación:**
  - [ ] Los campos obligatorios no pueden quedar vacíos.
  - [ ] Los datos inválidos generan mensajes comprensibles.
- **Casos de uso relacionados:** CU-001.
- **Pruebas relacionadas:** CP-001, CP-002.
- **Estado:** Ejemplo; no verificado.

### RNF-001 — Diseño adaptable
- **Categoría:** Compatibilidad y usabilidad.
- **Descripción:** el contenido debe poder consultarse en pantallas pequeñas y grandes sin desplazamiento horizontal innecesario.
- **Medida:** revisión en los tamaños de pantalla definidos para el proyecto.
- **Prioridad:** Media.
- **Pruebas relacionadas:** CP-010.
- **Estado:** Ejemplo; no verificado.

## Tabla de requisitos

| ID | Tipo | Descripción breve | Prioridad | Estado |
|---|---|---|---|---|
| RF-XXX | Funcional | [Descripción] | [Alta/Media/Baja] | [Estado] |
| RNF-XXX | No funcional | [Descripción] | [Alta/Media/Baja] | [Estado] |

## Lista de comprobación

- [ ] Cada requisito tiene un identificador único.
- [ ] Cada requisito puede comprobarse.
- [ ] Los requisitos no se contradicen.
- [ ] Los criterios de aceptación son claros.
