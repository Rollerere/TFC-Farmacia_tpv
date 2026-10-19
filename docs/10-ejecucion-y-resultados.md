# 10. Ejecución y resultados

## Cómo registrar una ejecución

Registra fecha, versión probada, entorno, identificador de la prueba, resultado obtenido y evidencia. Una prueba pendiente no es una prueba superada. Si una prueba falla, registra la incidencia y vuelve a ejecutarla tras la corrección.

## Plantilla de sesión de pruebas

- **ID de sesión:** [SES-XXX]
- **Fecha:** [AAAA-MM-DD]
- **Versión o commit:** [Identificador]
- **Entorno:** [Navegador, sistema operativo y versión]
- **Ejecutado por:** [Persona]
- **Objetivo:** [Qué se comprueba]

| Caso | Resultado esperado | Resultado real | Estado | Evidencia/Incidencia |
|---|---|---|---|---|
| CP-XXX | [Esperado] | [Real] | [Pendiente/Superada/Fallida/Bloqueada] | [Referencia] |

## Registro de incidencias

| ID | Descripción | Pasos para reproducir | Severidad | Estado | Prueba relacionada |
|---|---|---|---|---|---|
| INC-XXX | [Problema] | [Pasos] | [Baja/Media/Alta] | [Abierta/Corregida/Cerrada] | [CP-XXX] |

## Ejemplo ficticio

- **ID de sesión:** SES-EJEMPLO.
- **Fecha:** No ejecutada.
- **Entorno:** No definido.
- **Resultado:** no hay resultados reales disponibles.

Este ejemplo muestra el formato de registro, no una ejecución.

## Lista de comprobación

- [ ] Se registra la versión probada.
- [ ] Los resultados reales proceden de una ejecución.
- [ ] Las evidencias son accesibles y están identificadas.
- [ ] Los fallos están relacionados con incidencias.
- [ ] Las correcciones se vuelven a probar.
