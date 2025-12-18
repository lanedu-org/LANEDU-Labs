# Estructura mínima del repositorio

Un Lab debe contener, como mínimo, la siguiente estructura de archivos:

```text
lab-xx-nombre-del-lab/
├── README.md
└── .lanedu/
    └── rules.json
```

---

##  README.md

El archivo `README.md` define el desafío del Lab.
Debe explicar **qué** se debe lograr, no **cómo** hacerlo.

Debe incluir claramente:

* **Historia:** contexto del problema.
* **Objetivo:** meta clara a alcanzar.
* **Reglas del Lab:** normas de participación.
* **Entregable esperado:** qué debe presentar el alumno.

---

##  Carpeta `.lanedu/`

La carpeta `.lanedu/` contiene la configuración interna del Lab.
Aquí se define cómo la plataforma valida automáticamente la entrega.

### `rules.json`

Este archivo define las reglas de validación técnica.
Es leído por la plataforma para evaluar el Lab sin intervención manual.

Ejemplos de reglas:

* Formato específico del título del Pull Request
* Verificación de existencia de archivos
* Rutas específicas que deben ser modificadas
* Restricciones (por ejemplo, prohibir el borrado de archivos base)

---

##  Archivos adicionales (opcional)

Un Lab puede incluir recursos extra si el contexto lo requiere:

* Ejemplos o plantillas
* Archivos base de código
* Estructuras de carpetas simuladas

> **Nota:** Estos archivos sirven como punto de partida, nunca como la solución al reto.

---

## Inmutabilidad del Lab

El repositorio base del Lab debe mantenerse íntegro:

* No recibe merges
* No se modifica con las entregas
* No cambia su historial

Toda la actividad de los alumnos ocurre exclusivamente en **forks** y **Pull Requests**.

---

## En resumen

Un Lab bien definido cuenta con:

*  Un repositorio con estructura clara
*  Un `README.md` con contexto y reglas
*  Un `rules.json` para validación automática
*  Un flujo de entregas basado en Pull Requests

