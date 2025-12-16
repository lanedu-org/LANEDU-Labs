

# Mantener tu fork actualizado (flujo profesional)

Cuando tu Pull Request es aceptado, el repositorio original avanza.
Tu fork **NO se actualiza automáticamente**.

Este documento explica cómo **sincronizar tu fork con el repositorio base**  
siguiendo prácticas reales de proyectos open-source.

---

## 🎯 Objetivo de este tutorial

Al terminar este documento sabrás:

- Qué significa `origin` y `upstream`
- Cómo actualizar tu fork local
- Cómo evitar conflictos comunes
- Cuándo crear una Issue antes de actualizar

---

## 🧠 Concepto clave (muy importante)

- **Repositorio base**: `lanedu-org/LANEDU-Labs`
- **Tu fork**: copia del repositorio en tu cuenta

GitHub **no sincroniza forks automáticamente**.  
Eso es responsabilidad del colaborador.

---

## 🌐 Paso 0: Entender los remotos

En Git existen "remotos", que son repositorios conectados.

- `origin` → tu fork
- `upstream` → repositorio original

Veamos esto en la práctica.

---

## 💻 Paso 1: Abrir tu entorno (Codespaces o local)

Abre tu proyecto en **Codespaces** o en tu máquina local.

Verifica los remotos configurados:

```bash
git remote -v
```

Resultado típico:

```
origin  https://github.com/tu-usuario/LANEDU-Labs.git (fetch)
origin  https://github.com/tu-usuario/LANEDU-Labs.git (push)
```

Si no ves upstream, debes agregarlo.

---

## 🔗 Paso 2: Agregar el repositorio original como upstream

Ejecuta:

```bash
git remote add upstream https://github.com/lanedu-org/LANEDU-Labs.git
```

Verifica nuevamente:

```bash
git remote -v
```

Ahora deberías ver:

```
origin    https://github.com/tu-usuario/LANEDU-Labs.git
upstream  https://github.com/lanedu-org/LANEDU-Labs.git
```

🎯 Esto se hace una sola vez por repositorio.

---

## 🔄 Paso 3: Traer los cambios del repositorio base

Antes de trabajar en algo nuevo, siempre sincroniza.

```bash
git fetch upstream
```

Esto descarga los cambios, pero no los aplica todavía.

---

## 🌿 Paso 4: Actualizar tu rama main

Cambia a tu rama main:

```bash
git checkout main
```

Integra los cambios del repositorio base:

```bash
git merge upstream/main
```

🎯 Resultado:
- Tu main ahora está actualizado
- Refleja el estado actual del proyecto

---

## 🚀 Paso 5: Enviar la actualización a tu fork

Ahora actualiza tu fork en GitHub:

```bash
git push origin main
```

Tu fork ya está sincronizado.

---

## 🧭 Flujo recomendado (resumen)

```
Fetch upstream
↓
Actualizar main
↓
Push a origin
↓
Crear nueva rama
↓
Trabajar
↓
Pull Request
```

---

## ⚠️ Buenas prácticas IMPORTANTES

### ✅ Siempre haz esto
- Sincroniza tu fork antes de empezar algo nuevo
- Crea ramas nuevas desde main actualizado
- Mantén tu main limpio (sin cambios directos)

### ❌ Evita esto
- Trabajar semanas sin sincronizar
- Hacer commits en main
- Resolver conflictos sin entenderlos
- Forzar pushes (--force) sin saber lo que haces

---

## 🧪 ¿Qué pasa si hay conflictos?

Si al hacer merge aparecen conflictos:

- No entres en pánico
- Lee qué archivos están en conflicto
- Resuelve uno por uno

Si no sabes cómo seguir:
- Detente
- Crea una Issue
- Pide ayuda

Los conflictos son normales en proyectos colaborativos.

---

## 📝 ¿Cuándo crear una Issue?

Crea una Issue si:
- No sabes cómo resolver un conflicto
- Algo se rompió tras actualizar
- El cambio del repositorio base afecta tu trabajo
- No estás seguro de cómo continuar

Preguntar también es contribuir.

---

## 🔑 Regla de oro

Un fork desactualizado es la principal causa de conflictos.

Mantener tu fork al día es parte del trabajo colaborativo.

---

## 🎉 Conclusión

Ahora sabes:
- Cómo sincronizar tu fork
- Cómo trabajar alineado al proyecto base
- Cómo evitar errores comunes

Este flujo es el mismo que se usa en proyectos open-source reales.