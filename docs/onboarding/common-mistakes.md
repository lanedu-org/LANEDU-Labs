# Errores comunes al empezar en GitHub

Cometer errores es parte normal del aprendizaje.  
Este documento existe para ayudarte a **reconocerlos y evitarlos**.

---

## Trabajar directamente en `main`

**Qué pasa:**  
Modificar directamente la rama `main`.

**Por qué es un problema:**  
`main` representa el estado estable del proyecto.  
Cambiarla sin revisión puede romper el flujo de trabajo.

**Cómo evitarlo:**  
Crea siempre una rama nueva desde `main` para cada cambio.

---

## No crear una Issue antes de trabajar

**Qué pasa:**  
Hacer cambios sin explicar primero el problema o la mejora.

**Por qué es un problema:**  
La Issue ordena ideas y evita duplicar trabajo.

**Cómo evitarlo:**  
Crea una Issue antes de comenzar, incluso si el cambio es pequeño.

---

## Commits sin mensaje claro

**Qué pasa:**  
Usar mensajes como:
- `cambios`
- `update`
- `fix`

**Por qué es un problema:**  
El historial pierde sentido y dificulta entender qué se hizo.

**Cómo evitarlo:**  
Escribe mensajes que expliquen **qué cambiaste** y **para qué**.

---

## Cambios demasiado grandes en un solo PR

**Qué pasa:**  
Un Pull Request con muchos cambios distintos.

**Por qué es un problema:**  
Es difícil de revisar y corregir.

**Cómo evitarlo:**  
Divide el trabajo en cambios pequeños y enfocados.

---

## Miedo a equivocarse

**Qué pasa:**  
No aportar por miedo a hacerlo mal.

**Por qué es un problema:**  
El aprendizaje se detiene.

**Cómo evitarlo:**  
Este repositorio es un entorno seguro.  
Aquí equivocarse es parte del proceso.

---

## ¿Encontraste un error nuevo?

Si detectas un error común que no esté listado aquí:

1. Crea una **Issue**
2. Describe el error y por qué ocurre
3. Propón cómo evitarlo
4. (Opcional) Envía un Pull Request para agregarlo a este archivo

Así ayudas a quienes vienen después.
