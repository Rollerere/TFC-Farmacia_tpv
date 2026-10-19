# 08. Plan de testing

## Cómo elaborar este apartado

Define qué se probará, por qué, con qué herramientas, quién lo hará y qué condiciones se deben cumplir para finalizar. El plan describe la estrategia; los resultados se documentan después de ejecutar las pruebas.

## Alcance de las pruebas

- **Incluido:** [Funcionalidades y cualidades que se comprobarán]
- **Excluido:** [Aspectos fuera del alcance y justificación]
- **Entornos:** [Navegadores, dispositivos y versiones]
- **Responsables:** [Persona o equipo]

## Tipos de pruebas

| Tipo | Objetivo | Método o herramienta | Aplicable |
|---|---|---|---|
| Unitarias | Verificar funciones aisladas | [Vitest u otra] | [Sí/No] |
| Integración | Verificar interacción entre partes | [Herramienta o método] | [Sí/No] |
| Funcionales | Comprobar requisitos | [Manual/Playwright] | [Sí/No] |
| Aceptación | Verificar criterios acordados | [Manual] | [Sí/No] |
| Responsive | Comprobar distintas resoluciones | [Navegador/dispositivos] | [Sí/No] |
| Accesibilidad | Revisar barreras de uso | [Herramienta y revisión manual] | [Sí/No] |
| Rendimiento | Evaluar carga y respuesta | [Herramienta] | [Sí/No] |
| Regresión | Comprobar que cambios no rompen funciones | [Pruebas repetidas] | [Sí/No] |

## Estrategia de ejecución

1. Revisar requisitos y criterios de aceptación.
2. Preparar datos y entorno.
3. Ejecutar pruebas unitarias cuando existan funciones que lo justifiquen.
4. Ejecutar pruebas funcionales manuales y automatizadas.
5. Registrar resultados y evidencias.
6. Registrar incidencias y repetir las pruebas afectadas tras corregirlas.
7. Revisar la trazabilidad antes de cerrar el ciclo.

## Criterios de entrada
[Condiciones necesarias para comenzar.]

## Criterios de salida
[Condiciones para considerar terminado el ciclo de pruebas.]

## Riesgos
| Riesgo | Impacto | Mitigación |
|---|---|---|
| [Riesgo] | [Bajo/Medio/Alto] | [Acción] |

## Ejemplo ficticio

Para una web sencilla se propone validar funciones JavaScript con pruebas unitarias, comprobar navegación y formularios manualmente y automatizar recorridos principales con Playwright. La aplicabilidad final dependerá de la implementación.

**Importante:** no se declara ninguna prueba ejecutada en este ejemplo.

## Lista de comprobación

- [ ] El alcance está delimitado.
- [ ] Se han seleccionado herramientas adecuadas.
- [ ] Los criterios de entrada y salida son verificables.
- [ ] Se han considerado accesibilidad, compatibilidad y regresión.
