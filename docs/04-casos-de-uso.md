# 04. Casos de uso

## Cómo elaborarlos

1. Identifica los actores que interactúan con el sistema.
2. Define qué objetivo persigue cada actor.
3. Asocia cada caso de uso con los requisitos correspondientes.
4. Documenta precondiciones, flujo principal, alternativas y resultado.
5. Dibuja un diagrama general que muestre actores y casos de uso.

## Plantilla vacía de caso de uso

### CU-XXX — [Nombre]
- **Actor principal:** [Actor]
- **Objetivo:** [Resultado que busca]
- **Requisitos relacionados:** [RF-XXX]
- **Precondiciones:** [Condiciones previas]
- **Disparador:** [Acción que inicia el caso]

**Flujo principal**
1. [Acción del actor]
2. [Respuesta del sistema]
3. [Resultado]

**Flujos alternativos y excepciones**
- [Condición]: [Comportamiento esperado]

**Postcondiciones:** [Estado final]

**Pruebas relacionadas:** [CP-XXX]

## Actores y casos de uso

- **Actor:** [Nombre y responsabilidad]
- **Caso de uso:** [Objetivo del actor]

## Ejemplo ficticio

### CU-001 — Consultar actividades
- **Actor principal:** visitante.
- **Objetivo:** consultar las actividades publicadas.
- **Requisitos relacionados:** RF-002.
- **Precondiciones:** la web está disponible.
- **Disparador:** el visitante abre la sección de actividades.

**Flujo principal**
1. El visitante selecciona «Actividades».
2. El sistema muestra la lista disponible.
3. El visitante abre una actividad.
4. El sistema muestra sus detalles.

**Alternativa:** si no hay actividades, se muestra un mensaje informativo.

**Postcondiciones:** el visitante ha consultado la información o ha recibido un mensaje indicando que no hay contenido.

**Estado:** ejemplo ficticio, no validado contra una aplicación real.

## Diagrama de casos de uso

Dibuja el sistema como un límite, coloca los actores fuera y los casos de uso dentro. Si se utiliza Mermaid, el diagrama puede ser orientativo; para UML formal, puede ser preferible una herramienta específica de UML.

[Insertar diagrama o enlace al archivo de diagrama.]

## Lista de comprobación

- [ ] Los actores tienen objetivos claros.
- [ ] Cada caso de uso está descrito.
- [ ] Los flujos alternativos importantes están documentados.
- [ ] Los casos de uso se relacionan con requisitos.
