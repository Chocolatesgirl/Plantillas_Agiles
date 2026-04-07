# 🛠️ Políticas WIP — Control del Flujo en Sistema Kanban

## 🎯 Objetivo

Definir políticas explícitas de Work In Progress (WIP) para controlar el flujo de trabajo, evitando sobrecarga del sistema y mejorando la capacidad de entrega.

Las políticas WIP permiten:

* Limitar el trabajo en curso
* Reducir multitarea
* Identificar cuellos de botella
* Mejorar la predictibilidad del sistema

---

## 🧩 Contexto del caso

Equipo desarrollando una:

👉 **Aplicación de aprendizaje de inglés para niños de 3 a 8 años**

### Problema inicial

* Desarrollo iniciaba múltiples tareas simultáneamente
* Testing acumulaba trabajo
* No existía control del flujo

👉 Resultado:

* WIP descontrolado
* Lead Time elevado
* Cycle Time altamente variable

---

## 🚨 Problema del sistema sin WIP

Sin límites de WIP:

* Se inicia más trabajo del que se termina
* Se acumulan tareas en etapas intermedias
* Se generan cuellos de botella
* El flujo pierde continuidad

👉 El sistema colapsa por sobrecarga.

---

## 🧠 Definición de políticas WIP

Se establecen límites explícitos por etapa:

| Etapa       | Límite WIP | Justificación                         |
| ----------- | ---------- | ------------------------------------- |
| Development | 3          | Evitar multitarea excesiva            |
| Code Review | 2          | Mantener flujo continuo de validación |
| Testing     | 2          | Proteger el cuello de botella         |
| QA          | 2          | Asegurar calidad sin acumulación      |

---

## ⚙️ Principios aplicados

### 1. Limitar inicio de trabajo

👉 No se permite iniciar nuevas tareas si el WIP está lleno

---

### 2. Priorizar finalización

👉 El foco cambia de “empezar” a “terminar”

---

### 3. Exponer problemas del sistema

👉 Cuando se alcanza el WIP:

* Se hace visible el cuello de botella
* Se obliga a tomar decisiones

---

### 4. Flujo pull, no push

👉 El trabajo se toma solo cuando hay capacidad disponible

---

## 🔄 Comportamiento del sistema con WIP

### Situación

* Testing alcanza su límite WIP
* Development tiene capacidad disponible

---

### Sin política WIP

* Development sigue iniciando tareas
* Aumenta acumulación

---

### Con política WIP

* Development detiene inicio de trabajo
* Apoya Testing

👉 Resultado:

* Reducción de cuello de botella
* Flujo más equilibrado

---

## 🛠️ Decisiones operativas

### 1. Detener inicio de nuevas tareas

Cuando WIP está lleno:

* No se permite mover nuevas historias
* Se prioriza trabajo en progreso

---

### 2. Gestión de bloqueos

* Tareas bloqueadas tienen prioridad máxima
* Se asignan recursos para desbloquear

---

### 3. Redistribución de capacidad

* Developers apoyan Testing o Code Review
* Se reduce especialización rígida

---

### 4. Revisión continua de límites

* WIP no es fijo
* Se ajusta según capacidad del equipo

---

## 📊 Impacto en métricas

| Métrica    | Antes    | Después      |
| ---------- | -------- | ------------ |
| WIP        | Alto     | Controlado   |
| Lead Time  | Alto     | Reducido     |
| Cycle Time | Variable | Estable      |
| Throughput | Bajo     | Incrementado |

---

## 📈 Interpretación

* Menos WIP → menor tiempo de entrega
* Flujo controlado → mayor predictibilidad
* Menos multitarea → mayor eficiencia

---

## 🔗 Conexión con el sistema Kanban

Las políticas WIP impactan directamente en:

* 🔄 `simulacion_flujo_trabajo_jira.md` → operación del sistema
* 📊 `metricas_flujo.md` → medición del impacto
* 📊 `cumulative_flow_explicado.md` → visualización del flujo

👉 WIP es el mecanismo central de control del sistema.

---

## 💼 Enfoque profesional

La gestión de WIP no es una regla operativa simple.

Es una herramienta de:

* Control del sistema
* Gestión de capacidad
* Toma de decisiones

👉 Permite transformar equipos reactivos en sistemas predecibles.

---

## 🔥 Insight clave

> El exceso de trabajo en progreso no acelera la entrega…
> la ralentiza.

---

## ✅ Conclusión

Las políticas WIP permiten:

* Controlar el flujo de trabajo
* Reducir la sobrecarga del sistema
* Mejorar la eficiencia del equipo

👉 Sin límites WIP, no hay Kanban efectivo.
