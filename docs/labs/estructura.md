Estructura de un Lab

Cada Lab en LANEDU Labs sigue una estructura clara y consistente.

Esto permite que todos los Labs se entiendan, validen y escalen de la misma forma.

Un Lab es un repositorio GitHub

Cada Lab vive en su propio repositorio. Ese repositorio contiene todo lo necesario para:

Entender el problema

Conocer las reglas

Validar la entrega

El repositorio base no se modifica.

Estructura mínima del repositorio

Un Lab debe contener, como mínimo:

lab-xx-nombre-del-lab/
├── README.md
└── .lanedu/
    └── rules.json


README.md

El archivo README.md define el desafío. Debe incluir:

Historia (contexto del problema)

Objetivo claro

Reglas del Lab

Entregable esperado

El README explica qué se debe lograr, no cómo hacerlo.

Carpeta .lanedu

La carpeta .lanedu/ contiene la configuración del Lab. Aquí se define cómo la plataforma valida el desafío.

rules.json

El archivo rules.json define las reglas de validación del Lab.

Ejemplos de reglas:

Formato del título del Pull Request

Archivos que deben existir

Rutas que deben ser modificadas

Restricciones (no borrar archivos, etc.)

Este archivo es leído por la plataforma para validar automáticamente.

Archivos adicionales (opcional)

Un Lab puede incluir archivos adicionales si es necesario:

Ejemplos

Plantillas

Archivos base

Carpetas simuladas

Estos archivos sirven como contexto o punto de partida, no como solución.

Inmutabilidad del Lab

El repositorio base del Lab:

No recibe merges.

No se modifica con entregas.

No cambia su historia.

Toda la actividad ocurre en forks y Pull Requests.

En resumen

Un Lab bien definido tiene:

✅ Un repositorio claro

✅ Un README con contexto y reglas

✅ Un rules.json para validación

✅ Entregas mediante Pull Requests