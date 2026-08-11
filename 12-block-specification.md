# DMC Application Specification — 12 bloques

## 1. Identidad
Nombre, industria, propósito, versión, estado, fuentes, stakeholders y fecha. No inventar responsables.

## 2. Contexto
Situación actual, problema, dolores, causas, impacto, evidencia y limitaciones. No mezclar problema con solución.

## 3. Objetivos
Resultados esperados, métricas, línea base, meta y ventana. Si faltan cifras, crear preguntas.

## 4. Alcance
Separar MVP, incluido, excluido, futuro, dependencias, restricciones y supuestos.

## 5. Actores
Actores humanos, áreas, roles, sistemas, automatizaciones y agentes; responsabilidades y límites.

## 6. Procesos
Flujo principal, entradas, salidas, eventos, estados, decisiones, alternativas, excepciones y fallas.

## 7. Historias

```text
HU-XXX
Como <actor>,
quiero <capacidad>,
para <valor>.
```

Agregar épica, prioridad sustentada, fuente, reglas, preguntas y estado.

## 8. Requisitos funcionales
ID, comportamiento observable, actor, condición, resultado, historia, fuente, estado y dependencia.

## 9. Requisitos no funcionales
Seguridad, privacidad, rendimiento, disponibilidad, escalabilidad, resiliencia, accesibilidad, trazabilidad, auditoría, idempotencia, observabilidad, explicabilidad y gobierno de IA. Todo RNF debe tener métrica o pregunta.

## 10. Reglas
Condición, resultado, excepción, responsable, fuente y estado. No confundir con validaciones de pantalla.

## 11. Criterios de aceptación

```text
CA-XXX
Dado <contexto>,
cuando <acción>,
entonces <resultado observable>.
```

Relacionar con historias y requisitos.

## 12. Preguntas y validaciones
ID, categoría, pregunta, responsable, impacto, artefactos afectados, prioridad y estado.

## Reglas de calidad

- Toda historia tiene fuente.
- Todo RF tiene historia o proceso.
- Toda regla tiene evidencia o está pendiente.
- Todo criterio es observable.
- Todo RNF tiene métrica o pregunta.
- Toda contradicción permanece visible.
