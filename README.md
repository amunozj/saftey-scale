# Saftey Scale 💜

A bilingual (English / Spanish) mental health distress scale and crisis line reference, designed as an installable web app (PWA) that works fully offline.

**Live app:** https://amunozj.github.io/saftey-scale

---

**[Para español haga click acá](#escala-saftey-)**

---

## Why this exists

I built this inspired by my daughter, who designed her own 1–10 distress scale as part of her safety plan after a mental health crisis. She wanted something she could open on her phone — fast, private, no login, no internet required — that would remind her what each level feels like and what to do. We also wanted to have a way of talking about emotional states with a single number so that we don't have to have lengthy Q&As.

I decided to expand the app to include crisis lines for all Spanish-speaking countries because our family is Colombian, and I wanted it to be useful for others like us who may be navigating this in Spanish, wherever they are.

**I am a scientist, not a mental health professional.** The scale content was written collaboratively with my daughter and reviewed carefully, but the crisis line numbers were researched from public sources and may contain errors. I will correct mistakes as soon as I become aware of them and as soon as I can.

---

## For parents and providers: how to use this with your child or patient

This app is designed to be used *together* — ideally introduced during a calm moment, not during a crisis. The goal is that the person using it eventually reaches the point where they can identify their own level and communicate it without needing to explain everything.

### Step 1 — Install it together

Sit down with your child or patient and install the app on their phone:

- **Android:** Open https://amunozj.github.io/saftey-scale in Chrome → tap the three-dot menu → "Add to Home Screen"
- **iPhone:** Open in Safari → tap the Share button → "Add to Home Screen"

Once installed, it works with no internet connection — including in moments of crisis when someone may not want to navigate a browser.

### Step 2 — Go through the levels together

Walk through each level from 1 to 10. Tap a number, read the description aloud, and ask: *"Does this sound like what that feels like for you? Is there anything you'd change?"*

Some conversations to have at each level:

| Level | What to discuss |
|-------|----------------|
| **1 — Living my best life** | What does a genuinely good day look like? What makes it feel that way? |
| **2 — This is me** | What does "normal" actually feel like day to day? What are the signs things are okay? |
| **3 — A little off** | What are the earliest signs something is off? What usually helps at this stage? |
| **4 — Struggling** | What coping strategies work here? Who are safe people to reach out to? |
| **5 — Really hard** | What does distress feel like in the body? What has worked before to interrupt it? |
| **6 — ⚠️ Danger zone** | **This is the most important level.** Agree on a signal. The default is: say "I'm at a 6." Agree that this phrase means: *I need you, right now, no questions asked.* |
| **7–8 — Crisis / Overwhelmed** | Who is physically present at home? What does getting help look like step by step? |
| **9 — Thoughts of suicide** | Discuss this directly and calmly. Establish that this is a medical emergency and agree on the path: ER, crisis line, or emergency services. |
| **10 — Active crisis** | Make sure the person knows they can show someone the screen if they can't speak. |

### Step 3 — Establish the shared vocabulary

The most important thing this app creates is a **shared shorthand**. Once you've gone through the levels together, the person can say "I'm at a 6" and you both know exactly what that means — without having to find words for something that may be very hard to describe.

Practice saying it out loud during the setup conversation. Ask: *"If you were at a 6 right now, what would you say to me?"*

### Step 4 — Edit it to fit

The app lets the user edit every field — descriptions, body sensations, thoughts, and action steps — to match their own experience. Encourage your child or patient to change the wording of any level that doesn't feel accurate. The descriptions in the defaults are starting points, not clinical definitions.

To edit: tap any level number, then tap the ✏️ edit button next to any field.

### Step 5 — Pin the right crisis line

Go to the **Crisis Lines** tab and pin the correct country. This ensures that levels 8, 9, and 10 show the right number for where you are. If you're in the US, 988 is already the default. If you're in Colombia, pin Colombia (106). If you're traveling, you can re-pin at any time.

### A note on level 6

Level 6 is intentionally the clinical centerpiece of this scale. It represents the threshold where urges to self-harm begin — before the thinking brain shuts down, and while the person still has the capacity to reach out. The entire point of the scale is to make it possible for someone to communicate *before* they're at 9 or 10.

The agreement is simple: **if they say "I'm at a 6," you respond — no matter what, no questions first, no judgment.** The explanation can come later.

---

## How to help

### Report a wrong or missing crisis line number
Open an [Issue](https://github.com/amunozj/saftey-scale/issues/new?template=wrong-number.md) and select the **"Wrong or missing crisis line"** template. Please include a source link if you have one.

### Suggest a correction to the scale text
Open an [Issue](https://github.com/amunozj/saftey-scale/issues/new?template=text-correction.md) and select the **"Text correction"** template.

### Submit a fix directly
Pull requests are welcome. The entire app is a single `index.html` file — find the `ALL_CRISIS_LINES` array near the top of the `<script>` block and edit the relevant entry. Please include a source for any number changes.

---

## Files

| File | Purpose |
|------|---------|
| `index.html` | The entire app — HTML, CSS, JS, and inlined fonts |
| `manifest.json` | PWA manifest (enables "Add to Home Screen") |
| `sw.js` | Service worker (enables full offline use) |

---

## Credits

Built using [Claude AI](https://claude.ai) by Andrés Muñoz-Jaramillo.  
Crisis line data sourced from official ministry websites.

---

*If you or someone you know is in crisis, please reach out to a crisis line. In the US: call or text **988**. In Colombia: call **106**.*

---
---

# Escala Saftey 💜

Una escala de bienestar en salud mental bilingüe (inglés / español) con líneas de ayuda en crisis, diseñada como una aplicación web instalable (PWA) que funciona completamente sin conexión a internet.

**Aplicación:** https://amunozj.github.io/saftey-scale

---

## Por qué existe

Creé esto inspirado en mi hija, quien diseñó su propia escala del 1 al 10 como parte de su plan de seguridad tras una crisis de salud mental. La idea es que ella tuviera algo que pudiera abrir en su teléfono — rápido, privado, sin inicio de sesión, sin necesidad de internet — que le recordara cómo se siente cada nivel y qué hacer.

Expandí la aplicación para incluir líneas de crisis de todos los países de habla hispana porque nuestra familia es colombiana, y quería que fuera útil para otros como nosotros que navegamos esto en español, donde sea que estén.

**Soy científico, no profesional de la salud mental.** El contenido de la escala fue escrito en colaboración con mi hija y revisado cuidadosamente, pero los números de las líneas de crisis fueron investigados a partir de fuentes públicas y pueden contener errores. Corregiré los errores tan pronto como los conozca y tan pronto como pueda.

---

## Para padres y proveedores: cómo usar esto con su hijo o paciente

Esta aplicación está diseñada para usarla *juntos* — idealmente negociada durante un momento tranquilo, no durante una crisis. El objetivo es que la persona que la usa llegue al punto en que pueda identificar su propio nivel y comunicarlo sin tener que explicar todo.

### Paso 1 — Instalarla juntos

Siéntense juntos e instalen la aplicación en el teléfono:

- **Android:** Abran https://amunozj.github.io/saftey-scale en Chrome → toquen el menú de tres puntos → "Agregar a pantalla de inicio"
- **iPhone:** Abran en Safari → toquen el botón de compartir → "Agregar a pantalla de inicio"

Una vez instalada, funciona sin conexión a internet — incluso en momentos de crisis cuando alguien puede no querer navegar un navegador.

### Paso 2 — Recorrer los niveles juntos

Recorran cada nivel del 1 al 10. Toquen un número, lean la descripción en voz alta y pregunten: *"¿Esto cuadra con lo que sientes? ¿Hay algo que cambiarías?"*

Algunas conversaciones para tener en cada nivel:

| Nivel | Qué discutir |
|-------|-------------|
| **1 — Mejor momento** | ¿Cómo es un día muy bueno? ¿Qué lo hace sentir así? |
| **2 — Un día normal** | ¿Cómo se siente un día "normal"? ¿Cuáles son las señales de que las cosas están bien? |
| **3 — Algo está mal** | ¿Cuáles son las primeras señales de que algo no está bien? ¿Qué suele ayudar en esta etapa? |
| **4 — Me está costando** | ¿Qué estrategias de afrontamiento funcionan aquí? ¿A quién se puede contactar? |
| **5 — Muy difícil** | ¿Cómo se siente el malestar en el cuerpo? ¿Qué ha funcionado antes para mejorarlo? |
| **6 — ⚠️ Zona de peligro** | **Este es el nivel más importante.** Acordar una señal. La predeterminada es: decir "Estoy en un 6." Acordar que esta frase significa: *Te necesito, ahora mismo, sin preguntas primero.* |
| **7–8 — Crisis / Abrumad@** | ¿Quién está físicamente presente en casa? ¿Cómo se ve pedir ayuda paso a paso? |
| **9 — Pensamientos de suicidio** | Hablar de esto directa y tranquilamente. Establecer que es una emergencia médica y acordar el camino: urgencias, línea de crisis, o número de emergencias. |
| **10 — Crisis activa** | Asegurarse de que la persona sepa que puede mostrarle la pantalla a alguien si no puede hablar. |

### Paso 3 — Establecer el vocabulario compartido

Lo más importante que crea esta aplicación es un **lenguaje común**. Una vez que hayan recorrido los niveles juntos, la persona puede decir "Estoy en un 6" y ambos saben exactamente lo que significa — sin tener que encontrar palabras para algo que puede ser muy difícil de describir.

Practiquen decirlo en voz alta durante la conversación de configuración. Pregunten: *"Si estuvieras en un 6 ahora mismo, ¿qué me dirías?"*

### Paso 4 — Editarla para que encaje

La aplicación permite editar cada campo — descripciones, sensaciones corporales, pensamientos y pasos de acción — para que coincida con la experiencia propia. Alienten a su hijo o paciente a cambiar la redacción de cualquier nivel que no se sienta preciso. Las descripciones predeterminadas son puntos de partida, no definiciones clínicas.

Para editar: toquen cualquier número de nivel, luego toquen el botón ✏️ editar junto a cualquier campo.

### Paso 5 — Fijar la línea de crisis correcta

Vayan a la pestaña **Líneas de Ayuda** y fijen el país correcto. Esto asegura que los niveles 8, 9 y 10 muestren el número correcto para donde están. Si están en Colombia, fijen Colombia (106). Si están viajando, pueden volver a fijar en cualquier momento.

### Una nota sobre el nivel 6

El nivel 6 es intencionalmente el centro clínico de esta escala. Representa el umbral donde comienzan los impulsos de autolesión — antes de que la parte racional deje de funcionar, y mientras la persona todavía tiene la capacidad de pedir ayuda. El objetivo completo de la escala es hacer posible que alguien se comunique *antes* de estar en un 9 o un 10.

El acuerdo es simple: **si dicen "Estoy en un 6," hay que responder — sin importar qué, sin preguntas primero, sin juicios.** La explicación puede venir después.

---

## Cómo ayudar

### Reportar un número incorrecto o faltante
Abre un [Issue](https://github.com/amunozj/saftey-scale/issues/new?template=wrong-number.md) y selecciona la plantilla **"Wrong or missing crisis line"**. Por favor incluye un enlace a una fuente si tienes uno.

### Sugerir una corrección al texto
Abre un [Issue](https://github.com/amunozj/saftey-scale/issues/new?template=text-correction.md) y selecciona la plantilla **"Text correction"**.

### Enviar una corrección directamente
Los pull requests son bienvenidos. Toda la aplicación es un único archivo `index.html` — busca el array `ALL_CRISIS_LINES` cerca del inicio del bloque `<script>` y edita la entrada correspondiente. Por favor incluye una fuente para cualquier cambio de número.

---

## Créditos

Creado con [Claude AI](https://claude.ai) por Andrés Muñoz-Jaramillo.  
Datos de líneas de crisis obtenidos de los sitios web oficiales de ministerios de salud.

---

*Si usted o alguien que conoce está en crisis, por favor comuníquese con una línea de ayuda. En Colombia: llame al **106**. En EE.UU.: llame o escriba al **988**.*
