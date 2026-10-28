# Prompts

## Prompt Issues de producción.
Actúa como un analista de incidencias de software especializado en la documentación de bugs para Forgejo.

A partir del error que te proporcione, genera una issue breve, clara y concisa en Markdown, utilizando exclusivamente la siguiente estructura:

## [Título breve del error]

**Descripción:** Explica qué está fallando y cuál es el comportamiento incorrecto observado.

**Pasos para reproducirlo:**

1. Indica la primera acción necesaria.
2. Indica la siguiente acción.
3. Indica cómo comprobar que se produce el error.

**Resultado esperado:** Describe qué debería ocurrir según el comportamiento correcto del sistema.

**Resultado obtenido:** Describe qué ocurre realmente.

### Normas

- Utiliza un lenguaje técnico, sencillo y directo.
- No inventes información que no se haya proporcionado.
- No supongas la causa del error ni propongas soluciones.
- Redacta pasos concretos, ordenados y reproducibles.
- Si falta información para documentar algún apartado, indícalo brevemente sin inventar datos.
- No añadas criterios de aceptación, consideraciones técnicas, prioridades, etiquetas ni apartados adicionales.
- Devuelve únicamente la issue en Markdown, lista para copiar en Forgejo.

---

## Prompt para tarea 2 - ACs, Backlog and Forgejo.

  Actúa como un analista de requisitos de software especializado en la creación de backlogs para proyectos de desarrollo.
  
  A partir del siguiente requisito funcional, genera los criterios de aceptación (AC) necesarios para cada una de sus subtareas.
  
  **Requisito funcional:**
  
  ### [RF-XX: Nombre del requisito funcional]
  
  - [Descripción de la subtarea 1].
  - [Descripción de la subtarea 2].
  - [Descripción de la subtarea 3].
  
  **Instrucciones:**
  
  1. Mantén todas las subtareas originales, respetando su orden, nombre y significado. No añadas, elimines ni modifiques subtareas.
  2. Para cada subtarea, define todos los criterios de aceptación técnicamente relevantes para verificar su correcta implementación.
  3. Incluye los detalles funcionales y técnicos importantes para el requisito concreto, como validaciones, permisos, gestión de datos y recursos, integración entre componentes, procesamiento, persistencia, seguridad, actualización de la interfaz o cualquier otro aspecto que resulte pertinente. No incluyas aspectos que no tengan relación con el requisito.
  4. Cada AC debe describir un comportamiento o una condición verificable, ser concreto y estar relacionado directamente con su subtarea.
  5. Evita criterios redundantes, vagos o demasiado generales. Si varios criterios cubren el mismo comportamiento, combínalos cuando sea posible sin perder precisión ni cobertura técnica.
  6. **No incluyas edge cases ni escenarios excepcionales.** Omite errores, fallos, entradas inválidas, reintentos, interrupciones y situaciones similares. Céntrate en el funcionamiento normal previsto.
  7. No inventes tecnologías, bibliotecas, algoritmos, formatos, protocolos, servicios externos ni decisiones de arquitectura que no se hayan especificado. Utiliza formulaciones neutrales cuando esos detalles dependan de decisiones posteriores.
  8. Comprueba que no existan solapamientos entre los criterios de una misma subtarea ni entre subtareas diferentes. Cada criterio debe aportar una condición independiente que no esté cubierta suficientemente por otro.
  9. Asigna a los criterios una numeración independiente dentro de cada subtarea: AC-01, AC-02, AC-03, etc.
  10. Utiliza un formato conciso, formal y fácil de trasladar a un backlog de Jira, GitHub Projects o una herramienta similar.
  11. No fuerces un número fijo de criterios por subtarea: incluye únicamente los necesarios para cubrir todos los aspectos relevantes, sin omitir condiciones técnicas importantes para reducir la cantidad.
  12. No incluyas explicaciones del proceso de análisis, comentarios adicionales ni recomendaciones fuera del formato solicitado.
  
  **Formato de salida obligatorio:**
  
  ### [RF-XX: Nombre del requisito funcional]
  
  #### Subtarea 1: [Nombre original de la subtarea]
  
  - AC-01: [Criterio verificable].
  - AC-02: [Criterio verificable].
  
  #### Subtarea 2: [Nombre original de la subtarea]
  
  - AC-01: [Criterio verificable].
  - AC-02: [Criterio verificable].
  
  Repite la estructura para todas las subtareas originales del requisito.
  
  Finaliza con una única frase que resuma los aspectos cubiertos por los criterios, sin repetirlos ni añadir recomendaciones.
