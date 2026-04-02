# Framework PROMPT
## Gestión de Productos de Inteligencia Artificial
### AD5018 — Inteligencia Artificial para Negocios | UTEC
#### Administración & Negocios Digitales | Malla 2024 — Nivel 9

---

> **¿Por qué PROMPT?**
> En IA Generativa, un *prompt* es la instrucción que activa la inteligencia del sistema.
> En este curso, el **Framework PROMPT** es la instrucción que activa la inteligencia del equipo.
> Cada letra es una fase. Cada fase es una decisión gerencial.

---

## Estructura General del Framework

```
P — Problema de negocio
R — Recursos de datos
O — Oportunidad de IA
M — Modelado y construcción
P — Performance y métricas
T — Transparencia y ética
```

El framework guía al equipo de 3 personas desde la identificación de un problema real hasta la construcción, evaluación y sustentación de un MVP funcional con IA. No es un proceso lineal rígido — las fases se retroalimentan. Sin embargo, **no se puede avanzar a la siguiente fase sin haber respondido honestamente las preguntas de la fase actual.**

---

## Mapa del Semestre

```
Semanas 1–3   →  Fases P + R        (Diagnóstico)
Semanas 4–5   →  Fase O             (Diseño)
Semana  6     →  ENTREGABLE 1       (Propuesta: fases P + R + O)
Semanas 7–11  →  Fase M             (Construcción del MVP)
Semanas 12–13 →  Fases P2 + T      (Evaluación y ética)
Semana  14    →  ENTREGABLE 2       (Sustentación: fases M + P2 + T)
```

---

---

# FASE P — Problema de Negocio

## Pregunta central
> *¿Qué decisión o proceso de negocio queremos mejorar con IA, y por qué la IA es la respuesta correcta y no otra solución?*

## Propósito de la fase
Esta es la fase más crítica del proyecto. Un problema mal definido garantiza un producto que nadie usa. El equipo debe resistir la tentación de hablar de tecnología y enfocarse exclusivamente en el problema humano. La mayoría de proyectos de IA fracasan aquí — no en la implementación técnica.

---

## 1. Identificación del problema

El equipo describe el problema usando el siguiente formato obligatorio:

> *"[Tipo de usuario] tiene dificultad para [acción específica] porque [causa raíz], lo que genera [consecuencia medible]."*

**Ejemplo correcto:**
> *"Los ejecutivos de ventas de una inmobiliaria pierden en promedio 2 horas diarias respondiendo consultas repetitivas de clientes por WhatsApp, lo que reduce su tiempo disponible para cierres comerciales en un 40%."*

**Ejemplo incorrecto:**
> *"Las empresas necesitan un chatbot con IA para mejorar su atención al cliente."*
> *(Este es el problema expresado como solución — el error más común en proyectos universitarios de IA.)*

---

## 2. Validación: ¿realmente necesitas IA?

Antes de continuar, el equipo responde este filtro de forma honesta:

| Pregunta | Interpretación |
|---|---|
| ¿Una hoja de cálculo o un formulario resuelve esto? | Si la respuesta es SÍ → no necesitas IA, replantea el problema |
| ¿El problema escala con el volumen de datos o usuarios? | Si la respuesta es SÍ → la IA puede ser la respuesta |
| ¿Hay un patrón repetitivo que un humano reconoce pero tarda en procesar? | Si la respuesta es SÍ → ML tradicional puede ayudar |
| ¿El problema requiere generar contenido, responder preguntas o razonar en lenguaje natural? | Si la respuesta es SÍ → IA Generativa puede ser la respuesta |
| ¿Necesitas tanto predecir como explicar, comunicar o actuar? | Si la respuesta es SÍ → considera una combinación |

---

## 3. Tipos de IA permitidos en el proyecto

El equipo elige uno de estos tres caminos y lo justifica en la propuesta:

### IA Generativa
Genera texto, respuestas, resúmenes, flujos conversacionales o contenido.

**Cuándo usarla:**
- El problema involucra lenguaje natural (preguntas, respuestas, redacción, traducción)
- Se necesita un asistente conversacional o chatbot
- Se quiere generar contenido personalizado a escala
- Se requiere resumir, clasificar o transformar documentos

**Ejemplos de aplicación en negocios:**
- Asistente de atención al cliente para una tienda online
- Generador automático de reportes de ventas en lenguaje natural
- Chatbot de onboarding para empleados nuevos
- Resumidor de contratos o documentos legales

---

### ML Tradicional (Supervisado / No Supervisado)
Aprende patrones en datos históricos para predecir, clasificar o segmentar.

**Cuándo usarlo:**
- Existen datos históricos con resultados conocidos
- Se quiere predecir un número o categoría futura
- Se necesita segmentar clientes, productos o comportamientos
- La decisión depende de patrones no visibles al ojo humano

**Tipos según los datos disponibles:**

```
¿Tienes datos históricos con etiquetas (resultado conocido)?
    SÍ → Aprendizaje Supervisado
         - Clasificación: ¿Este cliente se irá? ¿Este email es spam?
         - Regresión: ¿Cuánto venderemos? ¿Qué precio poner?
    NO → Aprendizaje No Supervisado
         - Clustering: ¿Qué segmentos de clientes tenemos?
         - Reducción de dimensionalidad: ¿Qué variables importan más?
```

**Ejemplos de aplicación en negocios:**
- Predicción de abandono de clientes (churn)
- Segmentación de base de clientes por comportamiento de compra
- Detección de transacciones fraudulentas
- Sistema de recomendación de productos

---

### Combinación GenAI + ML
El ML detecta patrones o predice; la GenAI comunica, explica o actúa sobre esos resultados.

**Cuándo usarla:**
- Se necesita predecir Y explicar el resultado en lenguaje natural
- Un modelo ML genera una alerta y un agente GenAI gestiona la respuesta
- Se quiere un dashboard inteligente que interprete sus propios datos

**Ejemplo de flujo combinado:**
```
Datos históricos → Modelo ML → Predicción de churn
                                      ↓
                              Prompt enriquecido
                                      ↓
                    Modelo GenAI → Email personalizado de retención
```

---

## Herramienta: Problem Statement Canvas

```
┌─────────────────────────────────────────────────────────────────┐
│  PROBLEM STATEMENT CANVAS — Fase P                             │
├──────────────────────┬──────────────────────────────────────────┤
│ Usuario afectado     │ ¿Quién sufre el problema?               │
├──────────────────────┼──────────────────────────────────────────┤
│ Problema específico  │ ¿Qué está pasando exactamente?          │
├──────────────────────┼──────────────────────────────────────────┤
│ Causa raíz           │ ¿Por qué ocurre?                        │
├──────────────────────┼──────────────────────────────────────────┤
│ Consecuencia medible │ ¿Qué pierde el usuario sin solución?    │
├──────────────────────┼──────────────────────────────────────────┤
│ Filtro IA            │ ¿Por qué la IA y no otra solución?      │
├──────────────────────┼──────────────────────────────────────────┤
│ Tipo de IA elegido   │ GenAI / ML Tradicional / Combinación    │
├──────────────────────┼──────────────────────────────────────────┤
│ Justificación        │ 2-3 líneas argumentando la elección     │
└──────────────────────┴──────────────────────────────────────────┘
```

---

## Error crítico de esta fase
> Definir el problema en función de la tecnología disponible en lugar del usuario.
> *"Vamos a hacer un chatbot con Claude"* no es un problema de negocio — es una solución sin problema asignado.

---

---

# FASE R — Recursos de Datos

## Pregunta central
> *¿Tenemos el combustible para que la IA funcione, de qué calidad es y qué haremos si no lo tenemos?*

## Propósito de la fase
Los datos son el insumo principal de cualquier sistema de IA. Esta fase obliga al equipo a ser honesto sobre lo que tiene antes de comprometerse con una solución. Un modelo brillante alimentado con datos malos produce resultados malos con mucha confianza — lo que es peor que no tener modelo.

> **Principio fundamental del campo:** *Garbage in, garbage out.* No hay excepción en ningún tipo de IA.

---

## Requerimientos de datos según el tipo de IA elegido

### Para IA Generativa

El trabajo principal no es entrenar un modelo — es preparar el **contexto** que la IA necesita para responder bien. El equipo debe entender la diferencia entre:

| Componente | Qué es | Ejemplo |
|---|---|---|
| **Modelo base** | Lo que la IA sabe por entrenamiento general | GPT-4o, Claude 3.5, Gemini |
| **Contexto inyectado** | Lo que el equipo agrega vía prompt o base de conocimiento | FAQs, manuales, políticas de la empresa |
| **Memoria de sesión** | Lo que el sistema recuerda dentro de una conversación | Historial del chat actual |

**Inventario de información necesaria:**

| Pregunta | El equipo debe responder |
|---|---|
| ¿Qué información necesita la IA para responder bien? | Documentos, FAQs, manuales, base de conocimiento |
| ¿Dónde está esa información actualmente? | PDFs, Notion, correos, base de datos, sitio web |
| ¿Está estructurada o dispersa? | Determina el esfuerzo de preparación |
| ¿Qué tan actualizada necesita estar? | Define frecuencia de mantenimiento |
| ¿Hay restricciones legales sobre esa información? | Privacidad, confidencialidad, derechos de autor |

---

### Para ML Tradicional

| Pregunta | El equipo debe responder |
|---|---|
| ¿Qué variable queremos predecir o clasificar? | La variable objetivo (target) |
| ¿Qué datos históricos existen? | Fuente, formato, volumen aproximado |
| ¿Los datos tienen etiquetas? | ¿Sabemos cuál fue el resultado en el pasado? |
| ¿Cuántos registros hay disponibles? | Mínimo referencial: 500 registros para empezar |
| ¿Hay datos faltantes, sesgados o desbalanceados? | Evaluar calidad antes de modelar |

---

### Para Combinación GenAI + ML

Cada componente tiene sus propios requerimientos — deben evaluarse por separado usando las dos tablas anteriores y luego mapear cómo se conectan los datos entre ambas capas.

---

## Herramienta: Data Readiness Checklist

El equipo evalúa cada dimensión con semáforo y documenta el plan de acción para los amarillos y rojos:

| Dimensión | 🟢 Listo | 🟡 Necesita trabajo | 🔴 Bloqueante |
|---|---|---|---|
| **Disponibilidad** | Los datos existen y son accesibles | Existen pero hay que extraerlos o solicitarlos | No existen o no hay acceso posible |
| **Volumen** | Suficiente para el tipo de IA elegido | Limitado, puede afectar calidad del resultado | Insuficiente para modelar o contextualizar |
| **Calidad** | Completos, consistentes, sin errores mayores | Algunos vacíos o inconsistencias manejables | Datos sucios, contradictorios o no confiables |
| **Relevancia** | Directamente relacionados con el problema | Parcialmente relacionados, requieren filtrado | No representan el problema definido en Fase P |
| **Legalidad** | Sin restricciones de uso | Requiere acuerdo, anonimización o consentimiento | Datos privados sin autorización de uso |

> **Regla del proyecto:** Si hay más de un 🔴 sin plan de resolución concreto, el equipo debe replantear el problema o la fuente de datos antes de avanzar a la Fase O. Un bloqueante no resuelto invalida todo lo que sigue.

---

## Error crítico de esta fase
> Asumir que los datos existen y son buenos sin verificarlo.
> El equipo que dice *"usaremos datos de la empresa X"* sin haber contactado a la empresa X está construyendo sobre arena.

---

---

# FASE O — Oportunidad de IA

## Pregunta central
> *¿Cómo se ve el producto, quién lo usa, qué hace la IA exactamente y cómo se construye?*

## Propósito de la fase
Aquí el equipo traduce el problema y los datos en un diseño concreto de producto. Esta fase conecta la estrategia con la construcción. El equipo debe definir el flujo completo del producto antes de escribir una sola línea de código o configurar cualquier herramienta.

---

## 1. Flujo del producto

El equipo traza el flujo completo en un diagrama antes de construir nada:

```
Usuario → [Interfaz] → [Lógica del producto] → [Motor de IA] → [Output] → Usuario
```

**Preguntas que guían el diseño del flujo:**
- ¿Qué hace el usuario para activar la IA? (escribe, sube archivo, hace clic, habla)
- ¿Qué procesa la IA en segundo plano?
- ¿Qué recibe el usuario como resultado? (texto, número, alerta, recomendación, imagen)
- ¿Hay un humano en el circuito que valida antes de que la IA actúe?
- ¿Qué pasa si la IA falla o no tiene respuesta?

---

## 2. Decisión estratégica: Build, Buy o Integrate

| Opción | Descripción | Cuándo usarla en el proyecto |
|---|---|---|
| **Buy** | Usar herramienta de IA existente sin modificar | Cuando el valor está en el flujo, no en el modelo. Ej: Custom GPT, Voiceflow |
| **Integrate** | Conectar API de IA a tu propio flujo o interfaz | Cuando se necesita control sobre la experiencia. Ej: Claude API + n8n |
| **Build** | Entrenar o ajustar un modelo propio con tus datos | Cuando los datos propios generan ventaja competitiva. Ej: Teachable Machine |

> **Para proyectos de pregrado:** *Integrate* es generalmente la opción más equilibrada. *Buy* es válido si el producto diferencia en el flujo. *Build* desde cero es raramente justificable en el tiempo disponible — a excepción de modelos visuales con Teachable Machine.

---

## 3. Diseño específico por tipo de IA

### Si es IA Generativa — Arquitectura del sistema de prompts

**System Prompt obligatorio — estructura mínima:**

```
ROL:         ¿Quién es la IA? (ej: asistente de ventas de empresa X)
CONTEXTO:    ¿Qué sabe sobre la empresa, el dominio o el usuario?
RESTRICCIONES: ¿Qué NO debe hacer nunca?
FORMATO:     ¿Cómo debe estructurar sus respuestas?
TONO:        ¿Formal, cercano, técnico, empático?
IDIOMA:      ¿En qué idioma responde siempre?
```

**Estrategia de contexto — el equipo elige una:**

| Estrategia | Descripción | Cuándo usarla |
|---|---|---|
| **Prompt simple** | Toda la información va en el system prompt | Base de conocimiento pequeña y estable |
| **RAG** (Retrieval Augmented Generation) | La IA consulta documentos externos antes de responder | Base de conocimiento grande o que cambia frecuentemente |
| **Memoria de sesión** | El sistema recuerda el historial de la conversación | Asistentes conversacionales con contexto acumulativo |

**Gestión de alucinaciones — plan obligatorio:**
- ¿Qué pasa si la IA inventa información que no está en la base de conocimiento?
- ¿El producto tiene mecanismo para que el usuario reporte errores?
- ¿Hay validación humana en decisiones críticas?

---

### Si es ML Tradicional — Selección del modelo

**Tipo de problema y modelo correspondiente:**

| Si quieres... | Tipo de modelo | Herramienta recomendada |
|---|---|---|
| Clasificar en categorías (sí/no, A/B/C) | Clasificación | Teachable Machine, BigML, AutoML |
| Predecir un número continuo | Regresión | BigML, Google AutoML Tables |
| Encontrar grupos similares sin etiquetas | Clustering | BigML, Orange Data Mining |
| Reconocer imágenes o gestos | Visión computacional | Teachable Machine |
| Reconocer audio o comandos de voz | Clasificación de audio | Teachable Machine |

**Métricas de evaluación del modelo — el equipo debe conocer y reportar:**

| Métrica | Qué mide | Cuándo es la más importante |
|---|---|---|
| **Accuracy** | % de predicciones correctas | Cuando los errores de ambos tipos cuestan igual |
| **Precision** | De los que predije positivos, ¿cuántos lo eran? | Cuando los falsos positivos son costosos |
| **Recall** | De los positivos reales, ¿cuántos detecté? | Cuando los falsos negativos son costosos |
| **F1 Score** | Promedio armónico de precision y recall | Cuando hay desbalance en las clases |
| **RMSE / MAE** | Error promedio en predicciones numéricas | Para modelos de regresión |

> **Para administradores:** No necesitan calcular estas métricas manualmente. Necesitan saber qué significan para interpretar si el modelo es confiable y tomar la decisión correcta.

---

## 4. Definición del MVP

**Un MVP válido para este curso es** la versión más simple del producto que demuestra que la IA resuelve el problema definido en la Fase P, sin que el equipo asista al usuario durante el uso.

**Un MVP válido puede ser:**
- Chatbot funcional que responde preguntas sobre un dominio específico
- Flujo automatizado en n8n que procesa datos y genera un reporte o acción
- Modelo de clasificación de imágenes funcional construido con Teachable Machine
- Interfaz simple conectada a una API de IA que resuelve el problema definido
- Agente de IA con herramientas que ejecuta tareas de negocio de forma autónoma

**Un MVP NO es:**
- Una presentación de lo que haría el producto
- Un prototipo de Figma sin funcionalidad real
- Un demo grabado y editado que oculta errores o intervención manual
- Un notebook de Python que solo corre en la computadora del equipo

> **Criterio de validación del MVP:** Un usuario que no pertenece al equipo puede usarlo y obtener valor sin instrucciones adicionales.

---

## Herramienta: AI Product Canvas

```
┌──────────────────────────────────────────────────────────────────┐
│  AI PRODUCT CANVAS — Fase O                                      │
├─────────────────────┬────────────────────────────────────────────┤
│ Problema resuelto   │ (1 línea — viene de Fase P)               │
├─────────────────────┼────────────────────────────────────────────┤
│ Usuario principal   │ ¿Quién lo usa directamente?               │
├─────────────────────┼────────────────────────────────────────────┤
│ Tipo de IA          │ GenAI / ML Tradicional / Combinación       │
├─────────────────────┼────────────────────────────────────────────┤
│ Motor de IA         │ Herramienta o API específica + versión     │
├─────────────────────┼────────────────────────────────────────────┤
│ Input del usuario   │ ¿Qué ingresa para activar la IA?          │
├─────────────────────┼────────────────────────────────────────────┤
│ Output de la IA     │ ¿Qué recibe como resultado?               │
├─────────────────────┼────────────────────────────────────────────┤
│ Flujo principal     │ Usuario → IA → Resultado (diagrama)       │
├─────────────────────┼────────────────────────────────────────────┤
│ Estrategia          │ Build / Buy / Integrate + justificación   │
├─────────────────────┼────────────────────────────────────────────┤
│ Humano en circuito  │ ¿En qué punto interviene un humano?       │
├─────────────────────┼────────────────────────────────────────────┤
│ Stack tecnológico   │ Herramientas específicas que usará el MVP │
├─────────────────────┼────────────────────────────────────────────┤
│ Alcance del MVP     │ ¿Qué incluye y qué NO incluye?            │
└─────────────────────┴────────────────────────────────────────────┘
```

---

## Error crítico de esta fase
> Construir el MVP antes de tener el canvas completo.
> El equipo que empieza a configurar herramientas sin haber definido el flujo termina construyendo algo que funciona técnicamente pero no resuelve el problema original.

---

---

# FASE M — Modelado y Construcción

## Pregunta central
> *¿Cómo construimos el MVP de forma iterativa, documentada y dentro del tiempo disponible?*

## Propósito de la fase
Esta es la fase de ejecución. El equipo construye el MVP usando el stack tecnológico definido en la Fase O. El proceso es iterativo: se construye, se prueba con usuarios reales (aunque sean compañeros), se corrige y se vuelve a probar.

---

## Ciclo de construcción recomendado

```
Semana 7  →  Configuración inicial del stack + primer prototipo
Semana 8  →  Primera prueba interna del equipo + correcciones
Semana 9  →  Segunda iteración + prueba con usuario externo al equipo
Semana 10 →  Tercera iteración + documentación técnica
Semana 11 →  MVP finalizado + preparación para evaluación
```

---

## Principios de construcción para equipos de administración

**1. Empieza por el flujo más simple posible**
El primer prototipo debe hacer una sola cosa bien — no todo lo que planificaste. Agrega complejidad solo después de que lo básico funcione.

**2. Documenta cada decisión técnica**
¿Por qué elegiste esa herramienta? ¿Por qué ese prompt? ¿Por qué esa fuente de datos? La sustentación evaluará el razonamiento, no solo el resultado.

**3. Prueba con usuarios desde la semana 8**
Un usuario externo al equipo que usa el MVP por primera vez revela problemas que el equipo ya no puede ver por estar demasiado cerca del producto.

**4. El error es parte del proceso**
Documentar qué salió mal y cómo se resolvió es tan valioso como el MVP final. Los jueces evalúan el proceso, no solo el producto.

---

## Stack Tecnológico del Curso

### Herramientas Primarias del Curso

#### Teachable Machine *(Google)*
**Tipo:** Herramienta no-code de ML visual
**URL:** teachablemachine.withgoogle.com
**Qué hace:** Permite entrenar modelos de clasificación de imágenes, sonido y poses usando los datos propios del equipo, sin escribir código. El modelo entrenado puede exportarse e integrarse en otras herramientas.
**Ideal para:**
- Clasificación de imágenes (productos defectuosos, tipos de documentos, gestos)
- Reconocimiento de sonidos o comandos de voz
- Detección de poses corporales
- Cualquier problema de clasificación visual o auditiva

**Limitaciones a conocer:**
- Solo hace clasificación (no regresión ni clustering)
- Requiere dataset de imágenes organizado por categorías
- La precisión depende directamente de la calidad y cantidad de ejemplos

---

#### n8n *(n8n GmbH)*
**Tipo:** Plataforma de automatización y orquestación de flujos con IA
**URL:** n8n.io (versión cloud o self-hosted)
**Qué hace:** Conecta herramientas, APIs y modelos de IA en flujos automatizados sin código. Permite crear agentes de IA, procesar datos, enviar notificaciones y construir pipelines completos de negocio.
**Ideal para:**
- Agentes de IA que ejecutan tareas de negocio de forma autónoma
- Automatización de flujos que involucran IA + otras herramientas (email, bases de datos, CRMs)
- Conexión entre modelos de ML y sistemas de comunicación
- Orquestación de múltiples herramientas de IA en un solo flujo

**Nodos clave para el proyecto:**
- AI Agent: para construir agentes con herramientas
- HTTP Request: para conectar cualquier API externa
- OpenAI / Anthropic: para llamadas directas a modelos de lenguaje
- Webhook: para recibir datos de otras aplicaciones
- Google Sheets / Airtable: para persistencia de datos simple

---

#### Claude (Anthropic) — vía API o claude.ai
**Tipo:** Modelo de lenguaje de IA Generativa
**URL:** claude.ai / api.anthropic.com
**Qué hace:** Modelo de lenguaje avanzado para generación de texto, razonamiento, análisis de documentos, código y conversación. Destaca en seguimiento de instrucciones complejas y razonamiento estructurado.
**Ideal para:**
- System prompts complejos con muchas restricciones y contexto
- Análisis y resumen de documentos largos
- Generación de respuestas estructuradas en formato JSON
- Tareas que requieren razonamiento paso a paso

**Formas de uso en el proyecto:**
- **claude.ai** (interfaz web): para prototipado rápido y pruebas de prompts
- **API de Anthropic**: para integración en n8n o aplicaciones propias
- **Claude Code**: para equipos que quieran construir con asistencia de IA en el desarrollo

---

### Herramientas Complementarias Recomendadas

#### OpenAI (GPT-4o / GPT-4o mini)
**Tipo:** Modelo de IA Generativa
**URL:** platform.openai.com
**Cuándo usarlo:** Cuando se necesita un modelo multimodal (texto + imagen), cuando se integra con n8n vía nodo nativo, o cuando el equipo ya tiene experiencia previa con ChatGPT.
**Ventaja sobre Claude para el proyecto:** Integración nativa en n8n sin configuración de HTTP Request personalizado.

---

#### Google Gemini
**Tipo:** Modelo de IA Generativa de Google
**URL:** ai.google.dev
**Cuándo usarlo:** Cuando el proyecto involucra integración con Google Workspace (Docs, Sheets, Gmail), o cuando se usa Vertex AI para ML en la nube.
**Ventaja para el proyecto:** Gratuito con Google AI Studio para prototipos, integración directa con Google Colab.

---

#### BigML
**Tipo:** Plataforma de ML visual sin código
**URL:** bigml.com
**Qué hace:** Permite entrenar modelos de clasificación, regresión y clustering sobre datos tabulares sin escribir código. Tiene interfaz visual para exploración de datos y evaluación de modelos.
**Ideal para:**
- Proyectos de ML tradicional con datos en Excel o CSV
- Cuando Teachable Machine no aplica (datos tabulares, no imágenes)
- Equipos que necesitan visualizar el proceso de ML completo

---

#### Voiceflow
**Tipo:** Plataforma no-code para agentes conversacionales
**URL:** voiceflow.com
**Qué hace:** Diseña flujos conversacionales con IA de forma visual, con integración a modelos de lenguaje como GPT o Claude.
**Ideal para:** Proyectos de chatbot donde la experiencia conversacional es el producto principal y se necesita control visual del flujo de diálogo.

---

#### Bubble
**Tipo:** Plataforma no-code para aplicaciones web
**URL:** bubble.io
**Qué hace:** Construye interfaces web completas sin código, con capacidad de conectar APIs externas de IA.
**Ideal para:** Proyectos que necesitan una interfaz propia (no solo un chatbot) donde el usuario interactúa con el producto a través de una web app.

---

#### Airtable / Google Sheets
**Tipo:** Base de datos simple / hoja de cálculo
**Cuándo usarlo:** Como capa de persistencia de datos para el MVP. Almacena logs de conversaciones, resultados de predicciones o datos de usuarios sin necesidad de base de datos formal.

---

#### Streamlit *(para equipos con Python básico)*
**Tipo:** Framework para crear interfaces web de ML en Python
**URL:** streamlit.io
**Qué hace:** Convierte scripts de Python en aplicaciones web interactivas en minutos.
**Ideal para:** Equipos que usen Google Colab o Jupyter Notebook y quieran mostrar su modelo ML con una interfaz real.

---

### Tabla resumen de herramientas por tipo de proyecto

| Tipo de proyecto | Herramientas recomendadas | Dificultad |
|---|---|---|
| Chatbot de atención al cliente | n8n + Claude/GPT API | 🟡 Media |
| Clasificador de imágenes | Teachable Machine + Bubble | 🟢 Baja |
| Agente de IA con tareas múltiples | n8n + Claude API + Google Sheets | 🟡 Media |
| Predictor con datos tabulares | BigML + Streamlit o Bubble | 🟡 Media |
| Asistente conversacional con conocimiento | Voiceflow + OpenAI / Claude | 🟢 Baja |
| Sistema de recomendación simple | BigML + n8n | 🟡 Media |
| Clasificador de audio o voz | Teachable Machine + n8n | 🟢 Baja |
| Combinación ML + GenAI | Teachable Machine + n8n + Claude | 🔴 Alta |

---

## Error crítico de esta fase
> Construir funcionalidades que no estaban en el alcance del MVP definido en la Fase O.
> El equipo que agrega características durante la construcción sin actualizar el canvas termina sin tiempo para probar lo que sí importa.

---

---

# FASE P2 — Performance y Métricas

## Pregunta central
> *¿Cómo sabemos que la IA funcionó y que el negocio mejoró gracias a ella?*

## Propósito de la fase
Un producto de IA sin métricas es un experimento sin conclusión. Esta fase obliga al equipo a pensar como gerentes — no como desarrolladores. El éxito no es que el modelo tenga alta accuracy: es que el negocio mejore en algo medible y que el usuario obtenga valor real.

---

## 1. Métricas de negocio

El equipo define al menos **2 métricas de negocio** que cambien si el producto funciona. Estas son las métricas que le importan al cliente, no al equipo técnico.

| Categoría | Ejemplos de métricas |
|---|---|
| **Eficiencia operativa** | Tiempo ahorrado por tarea, tickets resueltos por hora, costo por atención al cliente |
| **Calidad del servicio** | Tasa de error reducida, NPS (Net Promoter Score), satisfacción del usuario |
| **Crecimiento comercial** | Tasa de conversión, retención de clientes, nuevos usuarios atendidos por período |
| **Impacto financiero** | Ingresos incrementales estimados, costo evitado, ROI proyectado del MVP |

> **Regla:** Si el equipo no puede conectar el output de la IA con al menos una métrica de negocio, el producto no tiene justificación gerencial.

---

## 2. Métricas técnicas del modelo

Estas métricas evalúan qué tan bien funciona la IA internamente — pero siempre deben interpretarse en contexto de negocio.

### Para IA Generativa

| Métrica | Qué mide | Cómo evaluarla en el proyecto |
|---|---|---|
| **Relevancia** | ¿La respuesta responde la pregunta del usuario? | Evaluación manual con muestra de 20+ interacciones |
| **Coherencia** | ¿La respuesta tiene sentido interno? | Revisión de outputs por alguien externo al equipo |
| **Tasa de alucinación** | ¿Con qué frecuencia inventa información? | Comparar outputs con la fuente de verdad del equipo |
| **Tasa de rechazo** | ¿Cuántas veces la IA no puede responder? | Log de conversaciones con conteo de no-respuestas |
| **Tiempo de respuesta** | ¿Cuánto tarda en responder? | Relevante si la experiencia del usuario depende de la velocidad |

### Para ML Tradicional

| Métrica | Qué mide | Interpretación para administradores |
|---|---|---|
| **Accuracy** | % de predicciones correctas | Si es 70% → 3 de cada 10 predicciones están mal |
| **Precision** | De los positivos predichos, ¿cuántos eran reales? | Alta precision = pocas alarmas falsas |
| **Recall** | De los positivos reales, ¿cuántos detecté? | Alto recall = pocos casos perdidos |
| **F1 Score** | Balance entre precision y recall | Útil cuando hay desbalance en los datos |
| **Baseline comparison** | ¿El modelo es mejor que adivinar al azar? | Si no supera el baseline, el modelo no aporta valor |

---

## 3. Diseño de la evaluación del MVP

El equipo debe definir **antes de la sustentación** cómo va a demostrar que el MVP funciona:

| Elemento | Descripción |
|---|---|
| **Usuarios de prueba** | Mínimo 3 personas externas al equipo que usaron el MVP |
| **Escenario de prueba** | Tarea específica que el usuario debía completar con el producto |
| **Datos recolectados** | Qué midieron durante la prueba (tiempo, errores, satisfacción) |
| **Resultado vs. meta** | Comparación entre la métrica actual y la meta definida en esta fase |

---

## Herramienta: AI Impact Scorecard

```
┌──────────────────────────────────────────────────────────────────────┐
│  AI IMPACT SCORECARD — Fase P2                                       │
├───────────────────────────┬──────────────────┬───────────────────────┤
│ MÉTRICA DE NEGOCIO        │ VALOR ACTUAL     │ META CON EL MVP       │
├───────────────────────────┼──────────────────┼───────────────────────┤
│ [Métrica 1]               │                  │                       │
├───────────────────────────┼──────────────────┼───────────────────────┤
│ [Métrica 2]               │                  │                       │
├───────────────────────────┴──────────────────┴───────────────────────┤
│ MÉTRICA TÉCNICA           │ RESULTADO MVP    │ INTERPRETACIÓN        │
├───────────────────────────┼──────────────────┼───────────────────────┤
│ [Accuracy / Relevancia]   │                  │                       │
├───────────────────────────┼──────────────────┼───────────────────────┤
│ [Métrica 2]               │                  │                       │
├───────────────────────────┴──────────────────┴───────────────────────┤
│ EVALUACIÓN CON USUARIOS   │ N° usuarios: __  │ Escenario de prueba:  │
├───────────────────────────┼──────────────────┼───────────────────────┤
│ Resultado principal       │                  │                       │
└───────────────────────────┴──────────────────┴───────────────────────┘
```

---

## Error crítico de esta fase
> Medir solo que el modelo funciona técnicamente e ignorar si resuelve el problema real.
> Un chatbot que responde el 95% de preguntas correctamente pero que ningún usuario quiere usar es un fracaso de producto — no un éxito de ingeniería.

---

---

# FASE T — Transparencia y Ética

## Pregunta central
> *¿Quién asume el costo cuando la IA se equivoca, qué riesgos genera el producto y cómo los mitiga el equipo?*

## Propósito de la fase
Esta fase responde directamente al **Resultado de Aprendizaje RA2** del curso: identificar y mitigar riesgos éticos y legales en la implementación de IA. No es un capítulo final decorativo — es una dimensión que atraviesa todo el proyecto y que en la sustentación tiene peso propio en la rúbrica.

---

## 1. Riesgos técnicos de la IA

| Riesgo | Descripción | Cómo evaluarlo | Cómo mitigarlo |
|---|---|---|---|
| **Sesgo algorítmico** | El modelo discrimina un grupo sin intención | ¿Los datos de entrenamiento representan a todos los usuarios por igual? | Balancear el dataset, evaluar resultados por segmento |
| **Alucinaciones (GenAI)** | La IA genera información falsa con confianza | Tasa de alucinación medida en Fase P2 | Agregar fuentes verificadas, validación humana en decisiones críticas |
| **Overfitting (ML)** | El modelo funciona bien en entrenamiento pero falla en producción | Validar con datos que el modelo nunca vio | Separar dataset en entrenamiento y validación desde el inicio |
| **Dependencia tecnológica** | Si la API externa falla, el producto falla | ¿Qué pasa si Claude o OpenAI no está disponible? | Definir plan de contingencia o mensaje de fallback al usuario |
| **Deriva del modelo** | El modelo pierde precisión con el tiempo al cambiar los datos | ¿Cada cuánto se actualizan los datos de entrenamiento? | Definir protocolo de reentrenamiento o actualización de contexto |

---

## 2. Riesgos éticos y legales

| Dimensión | Preguntas que el equipo debe responder |
|---|---|
| **Privacidad** | ¿El producto maneja datos personales? ¿Los usuarios dieron consentimiento explícito? ¿Cómo se almacenan y protegen? |
| **Transparencia** | ¿El usuario sabe que está interactuando con IA y no con un humano? ¿Hay aviso visible? |
| **Responsabilidad** | Si la IA comete un error que daña a alguien (económico, reputacional, de salud), ¿quién responde legalmente? |
| **Equidad** | ¿El producto funciona igual de bien para todos los segmentos de usuarios? ¿Hay grupos que podrían ser perjudicados? |
| **Autonomía del usuario** | ¿El usuario puede rechazar la recomendación de la IA? ¿Tiene control sobre sus datos? |
| **Regulación aplicable** | ¿El sector tiene regulaciones específicas de IA? (salud, finanzas, educación, datos personales en Perú — Ley N° 29733) |

---

## 3. Marco regulatorio mínimo aplicable en Perú

El equipo debe conocer y mencionar en la sustentación la regulación aplicable a su proyecto:

| Regulación | Aplica cuando... |
|---|---|
| **Ley N° 29733** — Protección de Datos Personales (Perú) | El producto recopila, almacena o procesa cualquier dato personal de usuarios |
| **Reglamento de la Ley N° 29733** (D.S. 003-2013-JUS) | Se procesan datos sensibles (salud, finanzas, biometría) |
| **EU AI Act** *(referencial)* | El equipo quiere demostrar conocimiento de tendencias regulatorias internacionales |
| **Regulación sectorial** | Proyectos en salud (MINSA), finanzas (SBS), educación (MINEDU) tienen regulaciones adicionales |

---

## Herramienta: AI Risk Matrix

```
┌──────────────────────────────────────────────────────────────────────┐
│  AI RISK MATRIX — Fase T                                             │
├────────────────────────┬───────────┬──────────────┬──────────────────┤
│ RIESGO IDENTIFICADO    │ TIPO      │ NIVEL        │ MITIGACIÓN       │
│                        │           │ Alto/Med/Bajo│                  │
├────────────────────────┼───────────┼──────────────┼──────────────────┤
│ [Riesgo 1]             │ Técnico   │              │                  │
├────────────────────────┼───────────┼──────────────┼──────────────────┤
│ [Riesgo 2]             │ Ético     │              │                  │
├────────────────────────┼───────────┼──────────────┼──────────────────┤
│ [Riesgo 3]             │ Legal     │              │                  │
├────────────────────────┼───────────┼──────────────┼──────────────────┤
│ [Riesgo 4]             │ Técnico   │              │                  │
└────────────────────────┴───────────┴──────────────┴──────────────────┘

Regulación aplicable al proyecto: ________________________________
¿Los usuarios saben que interactúan con IA? SÍ / NO + cómo se comunica
¿Quién es responsable si la IA comete un error? ________________
```

---

## Error crítico de esta fase
> Tratar la ética como un anexo de última hora.
> Los riesgos que no se identifican en el diseño se convierten en crisis en producción. En la sustentación, el equipo que no puede responder *"¿qué pasa si la IA se equivoca?"* demuestra que nunca pensó en el usuario real.

---

---

# Entregable 1 — Propuesta del Proyecto
## Semana 6 | Fases P + R + O del Framework PROMPT

### Estructura del documento

| Sección | Basada en | Extensión |
|---|---|---|
| Carátula del equipo | — | 1 página |
| Resumen ejecutivo | Síntesis de P + R + O | 1 página |
| Problem Statement Canvas completo | Fase P | 1 página |
| Justificación del tipo de IA elegido | Fase P | 1 página |
| Inventario de datos disponibles | Fase R | 1 página |
| Data Readiness Checklist con semáforo | Fase R | 1 página |
| Plan de obtención de datos faltantes | Fase R | 1 página |
| AI Product Canvas completo | Fase O | 1 página |
| Diagrama de flujo del producto | Fase O | 1 página |
| Stack tecnológico seleccionado + justificación | Fase O | 1 página |
| Alcance del MVP — qué incluye y qué NO | Fase O | 1 página |
| Cronograma de construcción (Semanas 7–13) | Gestión | 1 página |

**Total:** 12–14 páginas + anexos opcionales

---

### Rúbrica Entregable 1 — 100 puntos

| Fase | Criterio de evaluación | Puntos |
|---|---|---|
| **P** | El problema está definido desde el usuario, no desde la tecnología | 10 |
| **P** | El filtro de validación IA está respondido honestamente con argumentos | 8 |
| **P** | La justificación del tipo de IA es coherente con el problema definido | 7 |
| **R** | El inventario de datos es específico (fuente, formato, volumen) | 10 |
| **R** | El Data Readiness Checklist es honesto — no todo puede ser verde | 8 |
| **R** | El plan para datos faltantes o amarillos/rojos es realista y concreto | 7 |
| **O** | El AI Product Canvas está completo y es consistente con P y R | 12 |
| **O** | El diagrama de flujo es claro, completo y técnicamente viable | 10 |
| **O** | El stack tecnológico está justificado en función del problema | 8 |
| **O** | El alcance del MVP es específico, realista y alcanzable en el tiempo | 10 |
| **O** | El cronograma es detallado y distribuye el trabajo en las semanas disponibles | 5 |
| **General** | Coherencia interna del documento — P, R y O cuentan la misma historia | 5 |
| **Total** | | **100** |

#### Escala de calificación Entregable 1

| Puntaje | Nivel | Descripción |
|---|---|---|
| 90–100 | Sobresaliente | El documento es una propuesta que podría presentarse a un inversionista real |
| 80–89 | Bueno | El documento es sólido con observaciones menores en coherencia o especificidad |
| 70–79 | Suficiente | El documento tiene la estructura correcta pero con debilidades en argumentación |
| 60–69 | En proceso | El documento tiene vacíos importantes en al menos dos fases |
| < 60 | Insuficiente | El problema está definido como solución o los datos no fueron verificados |

---

---

# Entregable 2 — Sustentación + MVP
## Semana 14 | Fases M + P2 + T del Framework PROMPT

### Componentes obligatorios

#### 1. Demo en vivo del MVP *(componente no negociable)*
- El MVP funciona en tiempo real durante la presentación
- Un evaluador externo al equipo (el profesor u otro grupo) lo usa durante la sustentación
- El equipo no puede intervenir ni asistir al evaluador durante el uso
- No se aceptan demos grabados como sustituto del producto funcional
- Los errores en vivo que el equipo sabe explicar son aceptables y valorados

#### 2. Presentación de resultados *(20 minutos)*
Estructura sugerida:

```
[3 min]  Recordatorio del problema (Fase P)
[3 min]  Decisiones clave tomadas durante la construcción (Fase M)
[5 min]  Demo en vivo del MVP
[4 min]  Resultados del AI Impact Scorecard con datos reales (Fase P2)
[3 min]  Análisis de riesgos y plan de mitigación (Fase T)
[2 min]  Lecciones aprendidas y próximos pasos
```

#### 3. Sesión de preguntas *(10 minutos)*
Cada integrante del equipo debe poder responder preguntas sobre cualquier fase del framework. La sustentación evalúa comprensión individual, no solo el producto grupal.

---

### Rúbrica Entregable 2 — 100 puntos

| Fase | Criterio de evaluación | Puntos |
|---|---|---|
| **M** | El MVP funciona en vivo sin asistencia del equipo al evaluador | 25 |
| **M** | El MVP resuelve el problema específico definido en la Fase P | 15 |
| **M** | El equipo documenta y explica las decisiones técnicas tomadas | 8 |
| **P2** | Las métricas de negocio están definidas con valores actuales y meta | 10 |
| **P2** | Los resultados técnicos están presentados e interpretados correctamente | 8 |
| **P2** | La evaluación con usuarios externos está documentada con datos reales | 7 |
| **T** | Al menos 3 riesgos identificados con nivel y mitigación concreta | 10 |
| **T** | El equipo conoce la regulación aplicable a su proyecto | 5 |
| **T** | El equipo responde con criterio la pregunta: ¿qué pasa si la IA se equivoca? | 5 |
| **General** | Claridad de la presentación y calidad de respuestas a preguntas | 7 |
| **Total** | | **100** |

#### Escala de calificación Entregable 2

| Puntaje | Nivel | Descripción |
|---|---|---|
| 90–100 | Sobresaliente | El MVP funciona, genera valor real y el equipo domina todas las fases |
| 80–89 | Bueno | El MVP funciona con limitaciones menores que el equipo sabe explicar |
| 70–79 | Suficiente | El MVP funciona pero la evaluación o el análisis de riesgos es débil |
| 60–69 | En proceso | El MVP funciona parcialmente o la sustentación tiene vacíos importantes |
| < 60 | Insuficiente | El MVP no funciona en vivo o el equipo no puede explicar sus decisiones |

---

---

# Preguntas Frecuentes del Proyecto

**¿Podemos cambiar el tipo de IA después de la Fase P?**
Sí, hasta antes de entregar la Propuesta (Semana 6). Después del Entregable 1 el tipo de IA queda fijo salvo justificación escrita aprobada por el profesor.

**¿El MVP tiene que ser perfecto?**
No. Tiene que ser funcional y demostrar que resuelve el problema central. Los errores menores son aceptables si el equipo los documenta y explica cómo los resolvería con más tiempo o recursos.

**¿Podemos usar una empresa real como caso?**
Sí, y es lo recomendado. Si usan datos reales de personas, deben tener autorización explícita y anonimizar información sensible antes de incluirla en documentos o demos.

**¿Qué pasa si en la Fase R descubrimos que no tenemos datos?**
Es una conclusión válida y valiosa — pero deben proponer una estrategia concreta de obtención de datos. No pueden continuar con un 🔴 en disponibilidad sin un plan de resolución aprobado.

**¿Pueden los tres integrantes dividirse las fases del proyecto?**
Para construir, sí. Para la sustentación, cada integrante debe poder explicar cualquier fase. El profesor puede dirigir preguntas a cualquier miembro del equipo sobre cualquier parte del proyecto.

**¿Pueden usar herramientas no listadas en el documento?**
Sí, con justificación. Cualquier herramienta adicional debe documentarse en el AI Product Canvas con la razón de su elección.

**¿El uso de IA para desarrollar el proyecto está permitido?**
Sí, y es coherente con el espíritu del curso. El equipo debe documentar cómo usó IA en el desarrollo (qué herramientas, para qué tareas) como parte de la sección de lecciones aprendidas en la sustentación.

---

# Alineación con Resultados de Aprendizaje del Sílabo

| Resultado de Aprendizaje | Fases PROMPT que lo evalúan | Evidencia requerida |
|---|---|---|
| **RA1:** Aplicar soluciones basadas en IA para optimizar procesos empresariales usando ML supervisado, no supervisado y/o por refuerzo | P + R + O + M + P2 | MVP funcional + AI Impact Scorecard con métricas de negocio |
| **RA2:** Identificar y mitigar riesgos éticos y legales en implementación de IA garantizando uso responsable y sostenible | T | AI Risk Matrix completa + conocimiento de regulación aplicable + plan de mitigación |

---

*Framework PROMPT — Versión 1.0*
*Diseñado por el Docente Alan Morante*
*Universidad de Ingeniería y Tecnología (UTEC)*
*Departamento de Administración & Negocios Digitales — Malla 2024*
