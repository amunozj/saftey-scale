# Saftey Scale 💜

A bilingual (English / Spanish) mental health distress scale and crisis line reference, designed as an installable web app (PWA) that works fully offline.

**Live app:** https://amunozj.github.io/saftey-scale

---

## Why this exists

I built this inspired by my daughter, who designed her own 1–10 distress scale as part of her safety plan after a mental health crisis. She wanted something she could open on her phone — fast, private, no login, no internet required — that would remind her what each level feels like and what to do.  We also wanted to have a way of talking about emotional states with a single number so that we don't have to have lengthy Q&As

I decided to expand the app to include crisis lines for all Spanish-speaking countries because our family is Colombian, and I wanted it to be useful for others like us who may be navigating this in Spanish, wherever they are.

**I am a scientist, not a mental health professional.** The scale content was written collaboratively with my daughter and reviewed carefully, but the crisis line numbers were researched from public sources and may contain errors. I will correct mistakes as soon as I become aware of them and as soon as I can.

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

## Installing on a phone

**Android:** Open the app in Chrome → tap the three-dot menu → "Add to Home Screen"  
**iPhone:** Open in Safari → tap Share → "Add to Home Screen"

Once installed, the app works with no internet connection.

---

## Credits

Built using [Claude AI](https://claude.ai) by Andrés Muñoz-Jaramillo.  
Crisis line data sourced from official ministry websites.

---

*If you or someone you know is in crisis, please reach out to a crisis line. In the US: call or text **988**. In Colombia: call **106**.*
