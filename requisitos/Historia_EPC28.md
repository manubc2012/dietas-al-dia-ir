# HIST-EPC28 — Historia de usuario EPC 28

**ID:** HIST-EPC28 · **Versión:** v1.0 · **Estado final:** Aprobado
**Autor / revisor:** Oscar Sánchez García (autor del caso) / [Nombre del estudiante] (analista)
**Fecha de cierre:** 2026-09-13
**Artefactos relacionados:** REQ-EPC28-CA1 a REQ-EPC28-CA4, PROTO-001, DOC-VAL-001

## Historia de usuario

Como médico del Departamento de Nutrición quiero consultar las dietas compatibles con el
diagnóstico de un paciente, señalando explícitamente si alguna dieta contiene alimentos
incompatibles con sus alergias registradas, para elegir con seguridad un tratamiento sin
cruzar manualmente la historia clínica con el catálogo de dietas.

## Criterios de aceptación

- **CA1** — Dado un paciente con una enfermedad registrada, el sistema muestra las dietas
  asociadas en un único paso.
- **CA2** — Si una dieta recomendada incluye un alimento alérgeno o incompatible del
  paciente, el sistema lo señala de forma inequívoca antes de confirmar.
- **CA3** — El médico accede a la ficha técnica completa de la dieta sin perder el
  contexto del paciente.
- **CA4** — Un usuario nuevo elige una dieta segura en menos de 90 segundos sin pasar por
  alto ninguna alerta.
