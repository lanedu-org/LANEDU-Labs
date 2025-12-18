# Arquitectura

LANEDU Labs está diseñado con una arquitectura simple, transparente y escalable.

La plataforma **no almacena entregas**, **no ejecuta código** y **no modifica repositorios**.  
Todo el trabajo ocurre en GitHub.

---

## GitHub como fuente de verdad

GitHub es el núcleo del sistema.

- Cada Lab es un repositorio
- Cada entrega es un Pull Request
- Cada validación se basa en información pública de GitHub

LANEDU Labs solo **lee y valida**.

---

## Repositorios inmutables

Los repositorios base de los Labs **no se modifican**.

- Los alumnos trabajan desde forks
- Los Pull Requests nunca se mergean
- El historial del Lab permanece limpio

Esto permite que cientos de personas trabajen en el mismo Lab sin conflictos.

---

## Validación automática

Cada Lab define reglas de validación claras.

La plataforma:
- Detecta Pull Requests abiertos
- Verifica títulos y ramas
- Revisa archivos modificados
- Aplica reglas específicas del Lab

Si las reglas se cumplen, el Lab se marca como completado.

No hay revisión manual.

---

## Separación de responsabilidades

La arquitectura separa claramente cada rol:

- **GitHub**: trabajo, evidencia, historial
- **Repos del Lab**: problema y reglas
- **Plataforma**: visualización, estado y validación

Esto reduce complejidad y puntos de fallo.

---

## Escalabilidad por diseño

La arquitectura permite escalar sin reescribir el sistema:

- Más Labs → más repositorios
- Más usuarios → más forks
- Más validaciones → mismas reglas

No existe un cuello de botella central.

---

## Seguridad y transparencia

LANEDU Labs:
- No solicita acceso de escritura a repositorios
- No ejecuta código de los usuarios
- No almacena información sensible

Todo es público, auditable y verificable.

---

## En resumen

LANEDU Labs es una capa ligera sobre GitHub.

No reemplaza herramientas existentes.  
Las utiliza como se usan en la vida real.

---

**LANEDU Labs**  
Arquitectura simple. Evidencia real. Escala natural.
