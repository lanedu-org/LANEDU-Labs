

# Cómo crear un Pull Request (estilo profesional)

Un Pull Request (PR) es una **propuesta de cambio**.  
No es solo "enviar algo": es **explicar una idea y abrir una conversación técnica**.

Este documento define cómo crear Pull Requests en **LANEDU Labs**, siguiendo prácticas usadas en proyectos reales de código abierto.

---

## 🎯 ¿Qué es un buen Pull Request?

Un buen PR es:

- Pequeño
- Claro
- Fácil de revisar
- Fácil de entender

> Si un PR necesita mucha explicación verbal, probablemente es demasiado grande.

---

## 🧭 Antes de empezar

Antes de abrir un Pull Request, asegúrate de que:

- Existe una **Issue asociada**
- Tu cambio es **específico**
- Sabes exactamente **qué archivo vas a modificar**

---

## 🧪 Proceso paso a paso

### 1️⃣ Crear una Issue

Describe el problema o mejora que quieres realizar.

Ejemplo:
> "La explicación de commits es confusa para principiantes"

---

### 2️⃣ Hacer un Fork

Copia el repositorio de **LANEDU Labs** en tu cuenta de GitHub.  
Todo tu trabajo se realizará en tu fork.

---

### 3️⃣ Crear una rama

Desde `main`, crea una rama descriptiva.

Formato recomendado:

```text
tipo/descripcion-corta
```

Ejemplo:

```text
docs/improve-pr-guide
```

### 4️⃣ Realizar el cambio

- Modifica solo los archivos necesarios
- Mantén el cambio pequeño y enfocado
- Evita mezclar temas distintos en un mismo PR

### 5️⃣ Hacer commit

Usa mensajes claros y descriptivos.

Formato recomendado:

```text
<verbo en presente> <qué cambiaste>
```

Ejemplo:

```text
Improve PR documentation clarity
```

### 6️⃣ Abrir el Pull Request

Al crear el PR, completa la descripción con la siguiente estructura.

#### 📝 Descripción sugerida

```text
¿Qué cambia este PR?
- Mejora la explicación del flujo de trabajo

¿Por qué es necesario?
- Reduce confusión en alumnos nuevos

Issue relacionada:
- #12
```

Esto facilita enormemente la revisión.

---

## 🔍 Revisión del Pull Request

Durante la revisión:

- Escucha el feedback
- Ajusta el PR si es necesario
- No tomes los comentarios como algo personal

El objetivo no es "ganar", es mejorar el proyecto.

---

## ❌ Errores comunes en Pull Requests

Evita estos errores frecuentes:

- Cambios demasiado grandes
- No explicar el motivo del cambio
- Pull Requests sin Issue asociada
- Mensajes de commit poco claros

---

## ✅ Checklist antes de enviar

Antes de enviar tu PR, revisa:

- ✅ El PR tiene una Issue asociada
- ✅ El cambio es pequeño y claro
- ✅ El mensaje de commit es descriptivo
- ✅ El PR explica qué cambia y por qué

Si todo está marcado, vas por buen camino.✅


---

## 🚫 Qué NO hacer en un Pull Request

- No mezclar varios temas en un mismo PR
- No modificar archivos que no estén relacionados
- No abrir PRs sin Issue previa
- No trabajar directamente sobre `main`

Si tienes dudas, es mejor preguntar en una Issue antes de avanzar.

---

## 🧠 Idea final

> Un buen Pull Request no demuestra que sabes mucho.  
> Demuestra que sabes **colaborar bien**.
