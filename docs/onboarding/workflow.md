

# Flujo de trabajo en LANEDU Labs

Este documento define **cómo trabajamos en LANEDU Labs**.  
El objetivo no es complicar el proceso, sino **ordenarlo**.

Seguimos un flujo inspirado en proyectos open-source reales.

---

## 🎯 Objetivo del flujo

Este flujo existe para:

- Evitar cambios directos en producción
- Facilitar revisiones
- Mantener un historial claro
- Permitir que muchas personas colaboren sin conflictos

---

## 🌿 Ramas del proyecto

### `main`
- Rama principal del proyecto
- Contiene documentación estable
- **Nunca se trabaja directamente aquí**

> `main` representa el estado actual "publicado" del proyecto.

---

### Ramas de trabajo (feature branches)

Cada cambio se realiza en una **rama creada desde `main`**.

Formato recomendado:

```text
tipo/descripcion-corta
```

Ejemplos:
```text
docs/improve-github-basics
fix/typos-workflow
docs/add-python-errors
```

---

## 🧠 Tipos de cambios (convención)

Usamos una convención simple para nombrar ramas y commits:

| Tipo | Uso |
|------|-----|
| `docs/` | Cambios de documentación |
| `fix/` | Correcciones de errores |
| `chore/` | Ajustes menores / orden |

No es obligatorio, pero muy recomendado.

---

## 🔁 Flujo completo de trabajo

```text
Issue
  ↓
Fork
  ↓
Rama desde main
  ↓
Commit(s)
  ↓
Pull Request
  ↓
Revisión
  ↓
Merge a main
```

Este flujo es obligatorio para todos los aportes.

---

## 🐞 Paso 1: Crear una Issue

Antes de escribir código o documentación:

- Describe el problema o mejora
- Explica por qué es necesaria
- Indica el archivo involucrado

Ejemplo:
> "La sección de commits es confusa para principiantes"

---

## 🍴 Paso 2: Hacer un Fork

El fork crea una copia del repositorio en tu cuenta.
Ahí puedes trabajar con total libertad.

---

## 🌿 Paso 3: Crear una rama

Desde tu fork, crea una rama específica para el cambio.

✔ Un cambio = una rama  
❌ No mezclar varios temas en una sola rama

---

## 💾 Paso 4: Commits

Buenas prácticas:

- Commits pequeños
- Un commit = una idea
- Mensajes claros y descriptivos

Ejemplo de mensaje de commit:
```text
Improve explanation of Git workflow
```

---

## 🔁 Paso 5: Pull Request

El Pull Request es el espacio de conversación técnica.

Debe explicar:

- Qué cambiaste
- Por qué lo cambiaste
- A qué Issue responde

---

## ✅ Regla de oro

Si tu cambio es fácil de explicar,
probablemente está bien hecho.

---

## 📌 Importante

Este flujo no es negociable.
Es parte del aprendizaje.

Aprender a seguir procesos
es tan importante como el contenido técnico.

---

## 🧠 Si tienes dudas

Si no sabes cómo avanzar:

- Crea una Issue
- Pregunta antes de cambiar cosas
- Revisa ejemplos de PRs anteriores