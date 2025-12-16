

# Git

**Resumen en 1 línea:**  
Git es un sistema de control de versiones que permite registrar, organizar y colaborar sobre cambios en archivos de un proyecto.

---

## 1) ¿Qué es?

Git es un **sistema de control de versiones distribuido**.

Sirve para:
- Registrar cambios en archivos
- Volver a estados anteriores
- Trabajar en equipo sin sobrescribir trabajo ajeno

Git **no es GitHub**.  
Git funciona localmente; GitHub es una plataforma que usa Git.

---

## 2) ¿Para qué se usa en el mundo real?

Git se usa para:

- Desarrollo de software en equipo
- Documentación técnica colaborativa
- Control de versiones en proyectos personales
- Auditoría de cambios (quién cambió qué y cuándo)
- Trabajo remoto y open-source

En LANEDU Labs, Git se usa para **documentar, aprender y colaborar**.

---

## 3) ¿Cuándo usarlo y cuándo NO?

### ✅ Úsalo cuando:
- Varias personas trabajan en el mismo proyecto
- Necesitas historial de cambios
- Quieres experimentar sin romper el proyecto
- El proyecto evoluciona en el tiempo

### ❌ Evítalo cuando:
- El proyecto es desechable y de un solo uso
- No necesitas historial ni colaboración
- Los archivos no requieren control de cambios

---

## 4) Conceptos clave (mínimo necesario)

- **Repositorio:** proyecto controlado por Git
- **Commit:** registro de un cambio
- **Rama (branch):** línea de trabajo independiente
- **Merge:** integración de cambios
- **Estado (status):** archivos modificados o no

📘 Ver glosario general:  
`docs/onboarding/glossary.md`

---

## 5) Instalación / Requisitos

### Verificar si Git está instalado:
```bash
git --version
```

Instalar en sistemas basados en Linux:
```bash
sudo apt install git
```

En otros sistemas:
👉 Usa la documentación oficial.

---

## 6) Ejemplo mínimo (Hello World)

Inicializar un repositorio Git:
```bash
git init
```

Ver el estado del repositorio:
```bash
git status
```

Qué demuestra este ejemplo:
Muestra cómo iniciar Git y verificar el estado del proyecto.

---

## 7) Flujo típico de uso

Un flujo común con Git es:

1. Crear o clonar un repositorio
2. Crear una rama para trabajar
3. Modificar archivos
4. Crear commits
5. Enviar cambios al repositorio remoto
6. Integrar cambios (merge)

En LANEDU Labs, este flujo se combina con Issues y Pull Requests.

---

## 8) Errores comunes (para principiantes)

**Error:** Trabajar directamente en main  
**Cómo evitarlo:** Crear siempre una rama nueva

**Error:** Commits muy grandes  
**Cómo evitarlo:** Hacer commits pequeños y frecuentes

**Error:** Mensajes de commit poco claros  
**Cómo evitarlo:** Explicar qué hiciste en una frase corta

**Error:** No revisar el estado antes de commit  
**Cómo evitarlo:** Usar git status siempre

---

## 9) Buenas prácticas

✅ Un commit = un cambio  
✅ Usar ramas descriptivas  
✅ Mensajes de commit claros  
✅ Revisar cambios antes de commit  

❌ Commits genéricos ("update", "fix")  
❌ Trabajar sin rama  
❌ Forzar cambios sin revisión

---

## 10) Glosario rápido (opcional)

**Commit:** registro permanente de un cambio

**Branch:** línea de trabajo independiente

**Merge:** unión de cambios entre ramas

**Repositorio:** contenedor del proyecto

📌 Si falta un término:
- Crear Issue para el glosario global
- Archivo: docs/onboarding/glossary.md

---

## 11) Recursos confiables

### Oficiales
- https://git-scm.com/
- https://git-scm.com/docs

### Recomendados
- https://learngitbranching.js.org/
- https://www.atlassian.com/git/tutorials

---

## 12) Estado del documento

**Nivel:** Básico  
**Última revisión:** 2025-12-15  
**Mantención:** Comunidad LANEDU Labs