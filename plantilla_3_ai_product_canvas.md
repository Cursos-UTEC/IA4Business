# Plantilla 3 — AI Product Canvas
## Framework PROMPT | Fase O — Oportunidad de IA
### AD5018 Inteligencia Artificial para Negocios | UTEC

---

**Equipo:**
- Integrante 1: _______________________________________________
- Integrante 2: _______________________________________________
- Integrante 3: _______________________________________________

**Fecha de entrega:** _______________
**Versión del canvas:** _______________

---

> **Instrucción general:**
> Este canvas se completa DESPUÉS de tener aprobados el Problem Statement Canvas y el Data Readiness Checklist. Si el problema o los datos cambian, este canvas debe actualizarse. Las secciones deben ser consistentes entre sí — si hay contradicciones internas, el canvas no está listo.

---

## SECCIÓN 1 — Identidad del producto

### 1.1 Nombre del producto / MVP
```
Nombre:
```

### 1.2 Problema que resuelve
> *Copia exactamente la declaración del Problem Statement Canvas. No parafrasear.*

```
"[Usuario] tiene dificultad para [acción] porque [causa], lo que genera [consecuencia]."


```

### 1.3 Usuario principal
> *¿Quién usa el producto directamente? Sé específico — no "las empresas" sino el rol exacto.*

```
Escribe aquí:


```

### 1.4 Tipo de IA
- [ ] IA Generativa
- [ ] ML Tradicional — Clasificación
- [ ] ML Tradicional — Regresión
- [ ] ML Tradicional — Clustering
- [ ] Combinación GenAI + ML

---

## SECCIÓN 2 — Motor de IA

### 2.1 Herramienta o API principal

| Campo | Detalle |
|---|---|
| Herramienta / API | |
| Versión o modelo específico | *(ej: Claude 3.5 Sonnet, GPT-4o, Teachable Machine)* |
| Forma de acceso | *(API / interfaz web / SDK / no-code)* |
| Costo estimado para el MVP | *(gratuito / freemium / pago — especificar)* |

### 2.2 Herramientas de soporte

| Herramienta | Rol en el producto | ¿Por qué esta y no otra? |
|---|---|---|
| | | |
| | | |
| | | |

---

## SECCIÓN 3 — Experiencia del usuario

### 3.1 Input del usuario
> *¿Qué hace o ingresa el usuario para activar la IA?*

- [ ] Escribe texto en un chat o formulario
- [ ] Sube un archivo (imagen, PDF, CSV, audio)
- [ ] Hace clic en un botón o selecciona una opción
- [ ] Habla o graba un audio
- [ ] El sistema se activa automáticamente (sin acción del usuario)
- [ ] Otro: _______________

**Descripción detallada del input:**
```
Escribe aquí (2-3 líneas):


```

### 3.2 Output de la IA
> *¿Qué recibe el usuario como resultado de la interacción con la IA?*

- [ ] Texto / respuesta en lenguaje natural
- [ ] Número o predicción
- [ ] Clasificación o categoría
- [ ] Alerta o notificación
- [ ] Recomendación con opciones
- [ ] Imagen generada
- [ ] Acción ejecutada automáticamente (email enviado, registro guardado, etc.)
- [ ] Otro: _______________

**Descripción detallada del output:**
```
Escribe aquí (2-3 líneas):


```

---

## SECCIÓN 4 — Flujo del producto

### 4.1 Diagrama de flujo
> *Dibuja o describe el flujo completo paso a paso. Usa flechas (→) para conectar los pasos.*

```
Paso 1: Usuario →
Paso 2: →
Paso 3: →
Paso 4: →
Paso 5: → Usuario recibe:
```

**Versión visual (opcional pero recomendada):**
> *Pega aquí una imagen del diagrama o el link a la herramienta donde lo dibujaste (Miro, Lucidchart, draw.io, etc.)*

```
Link o imagen:
```

### 4.2 Humano en el circuito
> *¿En qué punto del flujo interviene un humano para validar o corregir antes de que la IA actúe?*

- [ ] No hay intervención humana — la IA actúa de forma autónoma
- [ ] El humano revisa el output antes de que llegue al usuario final
- [ ] El humano puede aprobar o rechazar la recomendación de la IA
- [ ] El humano interviene solo cuando la IA no tiene respuesta
- [ ] Otro: _______________

**Justificación de la decisión:**
```
Escribe aquí (2-3 líneas):


```

### 4.3 Plan de contingencia
> *¿Qué pasa si la IA falla, no tiene respuesta o la API no está disponible?*

```
Escribe aquí:


```

---

## SECCIÓN 5 — Decisión estratégica Build / Buy / Integrate

Marca con una X:

- [ ] **Buy** — usar herramienta existente sin modificar
- [ ] **Integrate** — conectar API de IA a flujo o interfaz propia
- [ ] **Build** — entrenar modelo propio con datos del equipo
- [ ] **Combinación** — especificar: _______________

**Justificación (obligatoria):**
> *¿Por qué esta estrategia y no las otras dos? Argumenta en función del problema y el tiempo disponible.*

```
Escribe aquí (4-5 líneas):


```

---

## SECCIÓN 6 — Diseño específico por tipo de IA

### Si es IA Generativa — System Prompt

> *Escribe el system prompt completo que usará el MVP. Debe seguir la estructura mínima obligatoria.*

```
ROL:
[Quién es la IA en este producto]

CONTEXTO:
[Qué sabe sobre la empresa, el dominio o el usuario]

RESTRICCIONES:
[Qué NO debe hacer nunca]

FORMATO DE RESPUESTA:
[Cómo debe estructurar sus respuestas]

TONO:
[Formal / cercano / técnico / empático]

IDIOMA:
[Idioma en el que responde siempre]
```

**Plan de gestión de alucinaciones:**
```
¿Qué pasa si la IA inventa información?

¿Hay validación humana en decisiones críticas?

¿El usuario puede reportar respuestas incorrectas?
```

---

### Si es ML Tradicional — Especificaciones del modelo

| Campo | Detalle |
|---|---|
| Tipo de modelo | *(clasificación / regresión / clustering)* |
| Herramienta de entrenamiento | *(Teachable Machine / BigML / AutoML / otra)* |
| Variable objetivo (target) | |
| Features principales | *(variables de entrada más importantes)* |
| Métrica de evaluación principal | *(accuracy / precision / recall / F1 / RMSE)* |
| Criterio mínimo de aceptación | *(ej: accuracy > 80% para considerar el modelo útil)* |

---

## SECCIÓN 7 — Alcance del MVP

### Lo que SÍ incluye el MVP
> *Lista las funcionalidades que estarán listas para la sustentación de la Semana 14.*

```
1.
2.
3.
4.
```

### Lo que NO incluye el MVP *(pero podría incluir una versión futura)*
> *Declarar esto explícitamente demuestra madurez en la gestión del proyecto.*

```
1.
2.
3.
```

### Criterio de éxito del MVP
> *¿Cómo sabrá el equipo que el MVP está listo para ser sustentado?*

```
"El MVP está listo cuando un usuario externo al equipo puede [acción específica]
sin instrucciones adicionales y obtiene [resultado específico]."


```

---

## SECCIÓN 8 — Autoevaluación del equipo

| Pregunta de control | Respuesta |
|---|---|
| ¿El problema en la Sección 1.2 es copia exacta del Problem Statement Canvas? | SÍ / NO |
| ¿El flujo de la Sección 4 es consistente con el tipo de IA elegido? | SÍ / NO |
| ¿El stack tecnológico fue verificado (cuentas creadas, accesos confirmados)? | SÍ / NO |
| ¿El alcance del MVP es realista para construir en 7 semanas? | SÍ / NO |
| ¿El system prompt fue probado al menos una vez antes de entregar? | SÍ / NO |
| ¿Todos los integrantes entienden cada sección de este canvas? | SÍ / NO |

> **Si alguna respuesta es NO → el canvas no está listo para entregar.**

---

*Framework PROMPT v1.0 — AD5018 UTEC | Plantilla 3 de 4*
