# Dietas al Día — Ingeniería de Requisitos

Repositorio del proyecto académico **Dietas al Día**, curso *Ingeniería de Requisitos*
(Universidad Pontificia Bolivariana). Documenta el ciclo completo de un requisito
priorizado — **EPC 28: Asignación de tratamiento nutricional** — desde su especificación
hasta su prototipado, validación, control de cambios y trazabilidad.

> **Criterio de éxito de este repositorio:** alguien que no participó en el proyecto debe
> poder entender el contexto completo leyendo únicamente esta carpeta.

## Contexto del proyecto

El caso "Dietas al Día" modela un servicio de apoyo a la decisión nutricional para
médicos del Departamento de Nutrición. El requisito EPC 28 permite a un médico consultar
las dietas compatibles con el diagnóstico de un paciente, señalando explícitamente
cualquier alimento incompatible con sus alergias registradas.

## Estructura del repositorio

```
dietas-al-dia-ir/
├── README.md
├── requisitos/
│   └── Historia_EPC28.md            → Historia de usuario EPC 28 + criterios de aceptación (HIST-EPC28)
├── prototipo/
│   ├── Prototipo_DietasAlDia_EPC28.html   → Prototipo funcional de alta fidelidad (PROTO-001)
│   └── Descripcion_Prototipo_DietasAlDia.pdf → Descripción funcional del prototipo
├── validacion/
│   └── Validacion_CCB_DietasAlDia.docx    → Checklist IEEE, defectos, acta del CCB (DOC-VAL-001)
└── trazabilidad/
    ├── Matriz_Trazabilidad_DietasAlDia.xlsx   → Matriz de trazabilidad (MTX-001)
    └── Auditoria_Trazabilidad_DietasAlDia.pdf → Auditoría end-to-end (AUD-001)
```

## Línea de tiempo de las actividades

| Actividad | Artefactos generados |
|---|---|
| U3A2 — Prototipado | Historia EPC 28, prototipo funcional, checklist IEEE, registro de defectos, acta del CCB |
| U4A1 — Trazabilidad de un requisito | Matriz de trazabilidad, auditoría end-to-end |

## Metadatos de los artefactos

Cada artefacto de este repositorio está identificado en el **Catálogo de artefactos**
(hoja de `Matriz_Trazabilidad_DietasAlDia.xlsx`) con: ID único, versión, estado final,
autor o revisor, fecha de cierre y artefactos relacionados.

## Convención de versionado

Los commits de este repositorio siguen el orden cronológico real en que se produjo cada
artefacto (ver historial de commits), de modo que el historial de Git funciona como
evidencia adicional de control de versiones para la actividad U4A1.

## Autoría

Proyecto desarrollado por [Nombre del estudiante] para el curso Ingeniería de Requisitos,
profesor Oscar Eduardo Sánchez García, Universidad Pontificia Bolivariana.
