# Modelado de datos y datos sintéticos

## Modelo conceptual
Glosario, entidades candidatas, relaciones, cardinalidades por validar, eventos y preguntas. Sin tipos SQL ni índices.

## Modelo lógico
Entidades, atributos, identificadores, claves, cardinalidades, opcionalidad, dominios, restricciones, estados, temporalidad, historial y trazabilidad.

## Modelo físico
Motor objetivo, tablas o colecciones, nombres, tipos, PK/FK, constraints, índices, particionamiento, auditoría, migraciones y rollback. Toda decisión se traza a consulta, RNF o restricción.

## Datos sintéticos

1. No usar PII real.
2. Mantener coherencia referencial.
3. Usar semilla reproducible.
4. Documentar distribuciones.
5. Incluir happy paths, errores, excepciones, nulos, reintentos y carga.
6. Separar reglas evidenciadas de reglas ficticias de generación.

Datasets sugeridos:

- `seed_reference_data`
- `happy_path`
- `manual_review`
- `business_exceptions`
- `integration_failures`
- `duplicate_retries`
- `security_negative_cases`
- `performance_volume`

## Validaciones
Unicidad, FK, dominios, estados, temporalidad, ausencia de PII real, reproducibilidad y cobertura de criterios.
