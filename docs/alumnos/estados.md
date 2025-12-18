# Estados de un Lab

Cada Lab en LANEDU Labs tiene un estado visible que indica su progreso.

Los estados se actualizan automáticamente según la actividad en GitHub.

---

## Pendiente

Estado inicial de un Lab.

Significa que:
- No existe ningún Pull Request válido asociado al Lab
- El usuario aún no ha entregado una solución

Acción recomendada:
- Forkear el repositorio
- Comenzar a trabajar en la solución

---

## PR detectado

La plataforma detectó un Pull Request relacionado con el Lab.

Significa que:
- Existe un Pull Request abierto
- El Pull Request aún no cumple todas las reglas
  **o**
- Está en proceso de validación

Acción recomendada:
- Revisar el Pull Request
- Corregir título, archivos o reglas si es necesario
- Actualizar el mismo Pull Request

---

## Completado

El Lab fue validado exitosamente.

Significa que:
- El Pull Request cumple todas las reglas
- La entrega es válida
- El Lab está finalizado

No se requieren acciones adicionales.

---

## Importante sobre los estados

- Los estados no se cambian manualmente
- El estado depende exclusivamente de GitHub
- Actualizar un Pull Request puede cambiar el estado automáticamente

La plataforma siempre refleja la información real.

---

## En resumen

Un Lab puede estar en:
- **Pendiente** → no hay entrega
- **PR detectado** → entrega en progreso
- **Completado** → entrega válida

---

**LANEDU Labs**  
Progreso claro. Validación automática.
