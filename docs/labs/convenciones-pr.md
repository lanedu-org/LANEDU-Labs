# Convenciones de Pull Requests

En LANEDU Labs, el **Pull Request (PR)** es la entrega oficial de cada Lab.  
Para que un Lab pueda ser validado automáticamente, el Pull Request debe cumplir ciertas convenciones.

Estas convenciones garantizan validación objetiva y consistente.

---

## El Pull Request es la entrega

No existen entregas fuera de GitHub.

- No se suben archivos a la plataforma
- No se envían enlaces externos
- No se adjuntan capturas por formularios

Si no existe un Pull Request válido, el Lab **no puede ser completado**.

---

## Título del Pull Request

El título del Pull Request debe seguir el formato definido por el Lab.

Ejemplo común:

```text
LAB-01: Backup de logs
El patrón exacto es validado mediante rules.json.

Pull Requests con títulos incorrectos no serán validados.

Rama de origen
El Pull Request debe cumplir:

Rama base: main

Rama de origen: fork del usuario

No se aceptan Pull Requests desde ramas internas del repositorio base.

Contenido del Pull Request
El Pull Request debe incluir:

Solo los archivos necesarios para la solución

Cambios relacionados exclusivamente al Lab

Commits claros y coherentes

Evita commits innecesarios o cambios no relacionados.

Descripción del Pull Request
La descripción del Pull Request es opcional, pero recomendada.

Puede incluir:

Breve explicación de la solución

Decisiones técnicas relevantes

Comandos utilizados

No afecta la validación automática.

Pull Requests que no se mergean
Los Pull Requests en LANEDU Labs no se mergean.

Sirven solo como evidencia

El repositorio base permanece intacto

El PR puede permanecer abierto o cerrarse sin merge

Un Pull Request por Lab
Cada Lab debe entregarse con un solo Pull Request.

Si necesitas corregir algo:

Actualiza el mismo Pull Request

No abras uno nuevo

Errores comunes
Título incorrecto

Pull Request contra la rama equivocada

Modificar archivos prohibidos

Abrir múltiples Pull Requests para el mismo Lab

Estos errores impedirán la validación.

En resumen
Un Pull Request válido debe:

Cumplir el formato de título

Apuntar a la rama correcta

Contener solo la solución

Respetar las reglas del Lab