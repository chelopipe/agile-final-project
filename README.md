# agile-final-project
PROYECTO FINAL
## Historia de Usuario

**Como** [tipo de usuario]  
**Necesito** [funcionalidad o acción deseada]  
**Para que** [beneficio o propósito]

## Criterios de aceptación

- [ ] Dado [contexto], Cuando [acción], Entonces [resultado esperado]
- [ ] Dado [otro contexto], Cuando [otra acción], Entonces [otro resultado esperado]

## Notas adicionales
[Observaciones, referencias o mockups]

## Etiquetas
[mejora, deuda técnica, prioridad, etc.]

# 🗒️ Proyecto: Gestor de Notas Minimalista (Kanban + Scrum)

Este proyecto simula un flujo completo de trabajo Scrum utilizando un tablero Kanban en GitHub. El producto es una aplicación sencilla para tomar, buscar y sincronizar notas con funcionalidades clave.

---

## 🎯 Objetivo del Proyecto

Crear una aplicación de notas que permita a los usuarios:
- Crear, editar y buscar notas rápidamente
- Sincronizarlas en la nube
- Agregar recordatorios
- Visualizar y administrar su contenido fácilmente

---

## 📋 Historias de Usuario (formato: Como… Necesito… Para que…)

1. **Crear nota rápida desde la pantalla principal**
   - Como usuario
   - Necesito crear una nota nueva desde la pantalla principal
   - Para que pueda capturar ideas rápidamente  
   - 🏷️ `mejora` – ⏳ 3 puntos  
   - 📜 **Criterios de aceptación (Gherkin)**  
     ```gherkin
     Dado que estoy en la pantalla principal  
     Cuando presiono el botón "nueva nota"  
     Entonces debería poder escribir y guardar una nota
     ```

2. **Buscar notas por palabra clave**  
   - Como usuario  
   - Necesito buscar notas usando una palabra clave  
   - Para que pueda encontrar rápidamente información previa  
   - 🏷️ `mejora` – ⏳ 5 puntos  
   - 📜  
     ```gherkin
     Dado que tengo varias notas guardadas  
     Cuando uso la barra de búsqueda  
     Entonces debería ver solo las notas que contienen la palabra clave
     ```

3. **Agregar recordatorios a notas**  
   - Como usuario  
   - Necesito configurar recordatorios en notas específicas  
   - Para que pueda recibir alertas en momentos determinados  
   - 🏷️ `mejora` – ⏳ 5 puntos  
   - 📜  
     ```gherkin
     Dado que estoy escribiendo una nota  
     Cuando configuro una fecha y hora de recordatorio  
     Entonces debería recibir una notificación en ese momento
     ```

4. **Sincronizar notas con la nube**  
   - Como usuario  
   - Necesito que mis notas se sincronicen automáticamente  
   - Para que no las pierda si cambio de dispositivo  
   - 🏷️ `mejora` – ⏳ 8 puntos  
   - 📜  
     ```gherkin
     Dado que tengo conexión a internet  
     Cuando guardo o edito una nota  
     Entonces debería sincronizarse automáticamente con la nube
     ```

5. **Editar notas existentes**  
   - Como usuario  
   - Necesito modificar notas previamente guardadas  
   - Para que pueda actualizar su contenido  
   - 🏷️ `mejora` – ⏳ 3 puntos  
   - 📜  
     ```gherkin
     Dado que tengo notas guardadas  
     Cuando elijo una nota  
     Entonces debería poder editar y volver a guardarla
     ```

6. **Eliminar notas antiguas**  
   - Como usuario  
   - Necesito eliminar notas que ya no necesito  
   - Para que pueda mantener mi espacio organizado  
   - 🏷️ `mejora` – ⏳ 2 puntos

7. **Dark Mode para la app**  
   - Como usuario  
   - Necesito activar un modo oscuro  
   - Para que me sea más cómodo usarla por la noche  
   - 🏷️ `mejora` – ⏳ 3 puntos  
   - 📦 **Icebox**

8. **Soporte para adjuntar imágenes**  
   - Como usuario  
   - Necesito subir imágenes en las notas  
   - Para que pueda guardar información visual  
   - 🏷️ `mejora` – ⏳ 8 puntos  
   - 📦 **Icebox**

9. **Corregir error al editar nota sincronizada**  
   - Como desarrollador  
   - Necesito resolver un fallo en la edición remota  
   - Para que no se pierdan cambios  
   - 🏷️ `deuda técnica` – ⏳ 5 puntos

10. **Optimizar tiempo de carga inicial**  
   - Como desarrollador  
   - Necesito mejorar el tiempo de arranque de la app  
   - Para que la experiencia de usuario sea fluida  
   - 🏷️ `deuda técnica` – ⏳ 5 puntos

---

## 🧊 Icebox

- Historia 7: Dark Mode  
- Historia 8: Adjuntar imágenes

---

## 📦 Product Backlog (Refinado)

1. Crear nota rápida desde la pantalla principal ✅  
2. Buscar notas por palabra clave ✅  
3. Agregar recordatorios a notas ✅  
4. Sincronizar notas con la nube ✅  
5. Editar notas existentes ✅  
6. Eliminar notas antiguas  
9. Corregir error al editar nota sincronizada 🛠️  
10. Optimizar tiempo de carga inicial 🛠️

---

## 🏁 Sprint: Sprint 1 (2 semanas)

**Historias incluidas:**
- Historia 1 (3 puntos)
- Historia 2 (5 puntos)
- Historia 3 (5 puntos)
- Historia 4 (8 puntos)

🧮 Total: 21 puntos

---

## 🌀 Simulación del Sprint

1. Asignar Historia 1 → `En progreso`  
2. Historia 1 → `Revisión/QA`  
3. Historia 2 → `En progreso`  
4. Historia 1 → `Hecho`  
5. Historia 2 → `Revisión/QA`  
6. Historia 3 → `En progreso`  
7. Historia 2 → `Hecho`  
8. Historia 3 → `Revisión/QA`  
9. Historia 4 → `En progreso`  
10. Historia 3 → `Hecho`

**Estado final del sprint:**  
- Historias 1, 2, 3 ✅ **Completadas**  
- Historia 4 ⏳ **En progreso**

---

## 📉 Burndown Chart (texto simulado)


---

## 🔗 Enlaces

- [🔗 Tablero Kanban (simulado)](https://github.com/usuario/fake-kanban-board)  
- [📁 Issues](https://github.com/usuario/fake-kanban-board/issues)  
- [📌 Sprint Milestone](https://github.com/usuario/fake-kanban-board/milestone/1)

---

## 🛠️ Etiquetas usadas

- `mejora`  
- `deuda técnica`  
- `icebox`  
- `en progreso`  
- `revisión`  
- `hecho`

---

## ✅ Lista de verificación Scrum

- [x] Backlog refinado  
- [x] Historias con Gherkin  
- [x] Etiquetas aplicadas  
- [x] Sprint creado  
- [x] Flujo de trabajo simulado  
- [x] Hito cerrado  



