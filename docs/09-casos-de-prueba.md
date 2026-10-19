# 09. Casos de prueba

## Cómo elaborar cada prueba

Cada caso debe ser reproducible y comprobar un resultado concreto. Incluye los datos de entrada, las precondiciones, los pasos y el resultado esperado. El resultado real y el estado solo se completan después de la ejecución.

## Plantilla vacía

### CP-XXX — [Nombre de la prueba]
- **Requisito relacionado:** [RF/RNF]
- **Tipo:** [Manual / Automatizada]
- **Prioridad:** [Alta / Media / Baja]
- **Precondiciones:** [Estado inicial]
- **Datos de entrada:** [Datos utilizados]

**Pasos**
1. [Acción]
2. [Acción]
3. [Comprobación]

**Resultado esperado:** [Resultado definido antes de ejecutar]

**Resultado real:** Pendiente de ejecución.

**Estado:** Pendiente.

**Evidencia:** [Ruta o enlace, cuando exista]

**Incidencia:** [ID o No aplica]

## Ejemplos ficticios

### CP-001 — Formulario vacío
- **Requisito relacionado:** RF-001.
- **Tipo:** Manual.
- **Precondiciones:** formulario disponible.
- **Datos de entrada:** todos los campos obligatorios vacíos.

**Pasos**
1. Abrir la página.
2. Dejar los campos vacíos.
3. Pulsar «Enviar».
4. Comprobar los mensajes y que no se acepta el formulario.

**Resultado esperado:** el envío se bloquea y se identifican los campos que deben corregirse.

**Resultado real:** Pendiente de ejecución.

**Estado:** Pendiente.

### CP-002 — Correo con formato inválido
- **Requisito relacionado:** RF-001.
- **Tipo:** Manual.
- **Datos de entrada:** `correo-no-valido`.

**Pasos**
1. Introducir el valor en el campo de correo.
2. Completar los demás campos.
3. Intentar enviar.
4. Comprobar la validación.

**Resultado esperado:** el sistema indica que el correo no tiene un formato aceptado y no continúa con el envío.

**Resultado real:** Pendiente de ejecución.

**Estado:** Pendiente.

## Pruebas automatizadas

Cuando se escriban pruebas automatizadas, documenta para cada conjunto:
- Herramienta y versión.
- Comando para ejecutarlo.
- Requisitos o funciones cubiertos.
- Resultado del comando.
- Enlace al informe generado.

No añadas código automatizado que no corresponda a la implementación real.

## Lista de comprobación

- [ ] Los pasos se pueden reproducir.
- [ ] El resultado esperado es concreto.
- [ ] Cada prueba se relaciona con un requisito.
- [ ] Los estados reflejan ejecuciones reales.
