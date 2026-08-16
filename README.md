# Proceso de desarrollo — AcopioLeche

## Modelo de proceso elegido

**Incremental con prácticas ágiles (Scrum ligero)**

## Justificación

Elegimos un modelo incremental porque nuestro proyecto se construye por unidades a lo largo del semestre (Unidad I: fundamentos, Unidad II: CRUD y backend con JWT, Unidad III: proyecto integrador completo), lo que encaja naturalmente con entregas por incrementos funcionales en vez de una sola entrega final tipo cascada. En AcopioLeche, cada incremento agrega una capacidad concreta: primero el registro básico del Acopio, luego el manejo offline-first con sincronización, y después el cálculo de pagos según calidad. Además, como equipo aún estamos aprendiendo Kotlin Multiplatform y Compose Multiplatform sobre la marcha, necesitamos flexibilidad para ajustar el alcance semana a semana — algo que el modelo cascada no permite bien, al exigir requisitos cerrados desde el inicio. Tomamos de Scrum las prácticas de reuniones breves de equipo y entregables por sesión, sin implementar el marco completo (no usamos Sprint Planning formal ni un Product Owner externo), ya que el tamaño del equipo (4 personas) y el contexto académico no lo requieren en su totalidad.

## Riesgos o limitaciones previstas

1. **Falta de un rol formal de priorización (Product Owner):** al no tener a alguien externo que priorice el backlog, el equipo podría dedicar tiempo a funcionalidades secundarias (como notificaciones o reportes) antes que a la entidad principal del CRUD (Acopio), retrasando lo que sí es evaluado en cada unidad.

2. **Los roles rotan cada semana**, lo que da flexibilidad pero también riesgo de pérdida de continuidad: quien lidera "Lógica y datos" una semana puede no estar disponible para resolver dudas sobre esa parte cuando ya rotó a otro rol.

3. **Sin un documento único de requisitos cerrado desde el inicio**, si el docente entrega criterios más detallados en semanas posteriores (por ejemplo, sobre autenticación JWT en la Unidad III), el equipo podría tener que rehacer trabajo ya avanzado en incrementos anteriores.

---
**Integrantes que participaron:** Alicia Vizcarra Ramos, Dayron Apaza Rodríguez, Jorge Luis Riveros Larico, Deysi Yaneth Mamani Jinez
