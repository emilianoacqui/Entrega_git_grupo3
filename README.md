# Misión Git: Campus U1

Este repositorio simula la documentación inicial de un sistema académico universitario simple llamado **Campus U1**.
La actividad está pensada para aprender Git básico en equipo, con misiones cortas y progresivas.

## Reglas generales de trabajo

- Trabajen en equipos de 4 o 5 personas.
- Antes de editar, revisen el estado del repo (`git status`).
- Cada cambio relevante debe quedar en un commit claro y breve.
- Usen ramas para trabajo paralelo y luego integren con `merge`.
- Si aparece un conflicto, resuélvanlo en equipo y documenten la decisión.
- En los retos, eviten copiar y pegar comandos completos: construyan cada comando en equipo.

## Propuesta gamificada por equipos

### Roles sugeridos

- **Integrador/a**: crea y fusiona ramas, cuida el historial.
- **Auditor/a**: revisa `git status`, `git diff` y valida commits.
- **Desarrolladores/as** (2 o 3): editan archivos según cada misión.
- **Coordinador/a** (opcional): administra tiempos y reparto de tareas.

### Misiones y puntaje

- **Misión 1 (Reto 1)**: +10 puntos
- **Misión 2 (Reto 2)**: +15 puntos
- **Misión 3 (Reto 3)**: +20 puntos
- **Misión 4 (Reto 4)**: +30 puntos
- **Misión 5 (Reto 5)**: +15 puntos

**Total base:** 90 puntos

### Bonificaciones

- +5 por commits con mensajes claros y consistentes.
- +5 por resolver conflicto sin pedir intervención docente.
- +5 por explicar al finalizar qué comandos usaron y por qué.

### Penalizaciones suaves

- -3 por commit sin mensaje útil (ejemplo: "cambios").
- -3 por mezclar varias misiones en un único commit.
- -5 por fusionar una rama sin revisarla con `git status` y `git diff`.

## Nota breve para docente

Sugerencia de dinámica para 40-45 minutos prácticos:

1. Reto 1 (5 min)
2. Reto 2 (8 min)
3. Reto 3 (10 min)
4. Reto 4 (12 min)
5. Reto 5 (8 min)

Cierre sugerido: 5 minutos de puesta en común comparando estrategias de resolución de conflictos.

## Secuencia sugerida para demostración docente

Esta secuencia está preparada para mostrar tres momentos clave:

1. **Caso sin conflicto**: usar `docs/comandos.md` (edición por secciones distintas).
2. **Conflicto real de merge**: usar `app/version.txt` (misma línea en dos ramas).
3. **Corrección de error local**: usar `docs/flujo-trabajo.md` con `git restore`.

Guía paso a paso disponible en `docs/guia-docente-demo.md`.

## Uso de material docente

- Los archivos `docs/guia-docente-demo.md` y `docs/guia-comandos-docente.md` son para conducción de clase.
- Se recomienda que el docente los use como apoyo visual y no como plantilla para que estudiantes copien comandos.
