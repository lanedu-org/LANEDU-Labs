# rules.json

El archivo `rules.json` define **cómo se valida automáticamente un Lab** en LANEDU Labs.

Este archivo es leído por la plataforma para verificar si un Pull Request cumple con los requisitos del desafío.

---

## ¿Qué es rules.json?

`rules.json` es un archivo de configuración que describe:

- Qué se espera del Pull Request
- Qué archivos deben existir o cambiar
- Qué acciones están permitidas o prohibidas

No contiene lógica de negocio ni código ejecutable.  
Solo define **reglas claras y objetivas**.

---

## Ubicación

El archivo debe estar ubicado en:

```text
.lanedu/rules.json
Si el archivo no existe, el Lab no puede ser validado.

Estructura básica
Ejemplo de estructura mínima:

json
Copiar código
{
  "pr": {
    "title": {
      "pattern": "^LAB-01: .*"
    }
  }
}
Reglas comunes
Validación del Pull Request
Permite definir reglas sobre el Pull Request:

json
Copiar código
{
  "pr": {
    "title": {
      "pattern": "^LAB-01: .*"
    },
    "base_branch": "main"
  }
}
Ejemplos:

Formato obligatorio del título

Rama base esperada

Archivos requeridos
Permite exigir que existan ciertos archivos:

json
Copiar código
{
  "files": {
    "required": [
      "backup.sh",
      "README.md"
    ]
  }
}
Archivos prohibidos
Permite evitar modificaciones no deseadas:

json
Copiar código
{
  "files": {
    "forbidden": [
      ".lanedu/rules.json"
    ]
  }
}
Rutas específicas
Permite limitar los cambios a ciertas rutas:

json
Copiar código
{
  "files": {
    "allowed_paths": [
      "scripts/",
      "src/"
    ]
  }
}
Buenas prácticas
Mantén las reglas simples

Evita validaciones ambiguas

Documenta las reglas en el README del Lab

No cambies las reglas una vez publicado el Lab

Errores comunes
No incluir rules.json

Usar reglas demasiado restrictivas

Cambiar reglas después de que usuarios comenzaron el Lab

En resumen
rules.json permite:

Validar Labs automáticamente

Mantener criterios objetivos

Escalar sin revisiones manuales

Garantizar equidad entre usuarios