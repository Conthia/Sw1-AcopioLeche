# Proceso de desarrollo — AcopioLeche

## Modelo de proceso elegido

**Incremental con prácticas ágiles (Scrum ligero)**

## Justificación

Optamos por un modelo incremental debido a que nuestro proyecto se desarrolla en unidades a lo largo del semestre, cada una con sus propios entregables y aprendizajes. Esto se ajusta de manera natural a entregas por incrementos funcionales en lugar de una única entrega final en estilo cascada. En AcopioLeche, cada avance añade una capacidad específica: en primer lugar, el registro básico del acopio; después, la gestión offline-first con sincronización, y luego el cálculo de los pagos de acuerdo con la calidad. Además, como equipo todavía estamos aprendiendo Kotlin Multiplatform y Compose Multiplatform sobre la marcha; requerimos flexibilidad para modificar el alcance cada semana, algo que el modelo cascada no permite adecuadamente porque exige tener los requisitos definidos desde el principio. Adoptamos de Scrum las prácticas de reuniones cortas en equipo y entregables por sesión, sin aplicar el marco completo (no utilizamos un Product Owner externo ni la planificación formal del Sprint), porque ni el contexto académico ni la magnitud del equipo (cuatro personas) lo exigen completamente.

## Riesgos o limitaciones previstas

1. **Falta de un rol formal de priorización (Product Owner):** Si no hay una persona externa que dé prioridad al backlog, el equipo podría posponer lo que se evalúa en cada unidad y concentrarse primero en funciones secundarias (como reportes o notificaciones) antes de la entidad principal del CRUD (Acopio).

2. **Los roles rotan cada semana**, Lo que proporciona flexibilidad, pero a la vez conlleva el riesgo de perder continuidad: la persona que está al frente de "Lógica y datos" una semana puede no estar disponible para aclarar dudas sobre esa sección cuando ya se haya cambiado a otro rol.

3. **Sin un documento único de requisitos cerrado desde el inicio**, así que si el docente nos da más detalles en las próximas semanas (por ejemplo, sobre el tema de autenticación JWT en la Unidad III), es posible que tengamos que retocar o rehacer parte de lo que ya avanzamos en los primeros incrementos.
---
**Integrantes que participaron:** Alicia Vizcarra Ramos, Dayron Apaza Rodríguez, Jorge Luis Riveros Larico, Deysi Yaneth Mamani Jinez
