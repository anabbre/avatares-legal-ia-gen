# Memoria del Proyecto — Avatares Digitales (Sector Legal)

> **Demo IA Gen** con 3 “avatares” (Laboral, Compliance, Onboarding) para comunicación interna clara y consistente.  
> Guiones con GPT, voz con ElevenLabs, vídeos de animación simple, landing en Lovable.  
> **Disclaimer:** Demostración educativa. No constituye asesoramiento legal.

---

## 1) Escenario y objetivo
- **Escenario elegido:** Servicio de avatares digitales para un bufete (Escenario 3).
- **Título del proyecto:** *Galería de Avatares Legales*.
- **Objetivo de la demo:** Mostrar 3 perfiles con tono/estilo diferenciado capaces de explicar un tema y responder micro-FAQs, con **máximo uso de IA generativa** en el flujo (texto → audio → vídeo → web).

---

## 2) Equipo y roles
| Persona | Rol principal | Responsabilidades | Backup |
|---|---|---|---|
| Ana | **Guiones & Copy** | Guiones de 3 avatares (≤130 palabras + 2 Q&A c/u), copy de landing | Amalia |
| Carlos | **Audio TTS** | Generación de 3 locuciones en ElevenLabs + `audio/metadata.json` | Ana |
| Juan | **Vídeo/Animación** | 3 clips MP4 (1080p) con lower-third + subtítulos si aplica | Carlos |
| Amalia | **Web + Master + Slides** | Integración en **Lovable**, `master.mp4` + `master.srt`, slides y promptbook | Juan |

---

## 3) Planificación (hitos)
- **H1 – Contenidos**: guiones (`/scripts`) + copy web (`/brand/copy_web.md`).  
- **H2 – Audio**: `audio/{lucia,inigo,carmen}.wav` + `audio/metadata.json`.  
- **H3 – Vídeo**: `video/01_lucia.mp4`, `02_inigo.mp4`, `03_carmen.mp4`.  
- **H4 – Integración**: landing en **Lovable** (3 modales) + `video/master.mp4` + `master.srt` + slides.  
- **H5 – Ensayo**: *dry run* 15’ + 5’, checklist final.

> **Fechas**:  
> H1: TODO | H2: TODO | H3: TODO | H4: TODO | H5: TODO

---

## 4) Proceso y estadios intermedios
**E1 – Guiones & Copy (GPT)**  
- Prompt base (resumen): “Guion corporativo 120–130 palabras + 2 Q&A, tono [cercano/formal/didáctico], sin asesoría legal.”  
- Artefactos: `scripts/guion_lucia.md`, `guion_inigo.md`, `guion_carmen.md`, `brand/copy_web.md`.  
- Capturas: **TODO** (añadir en `/prompts/promptbook.md`).

**E2 – Audio (ElevenLabs)**  
- Parámetros por clip (ejemplo): estabilidad 0.60, style 0.40, speed 1.03 (Lucía).  
- Artefactos: `audio/*.wav`, `audio/metadata.json`.  
- Notas: nivelado de volumen, micro-pausas antes de Q&A.

**E3 – Vídeo/Animación (CapCut/Clipchamp/Slides→MP4)**  
- Enfoque: “logo/imagen parlante” con *breathing* (zoom 98–102%), lower-third y subtítulos opcionales.  
- Artefactos: `video/01_lucia.mp4`, `02_inigo.mp4`, `03_carmen.mp4` (1080p, ≤30–50 MB).

**E4 – Web + Master + Slides (Lovable / Editor vídeo / Gamma/SlidesAI)**  
- Landing: 3 tarjetas con botón **Reproducir demo** → modal con MP4.  
- Master: Intro 5 s + 3×~30 s + Cierre 10 s con CTA y **disclaimer**.  
- Artefactos: `video/master.mp4`, `video/master.srt`, `slides/presentacion.pptx|pdf`.

---

## 5) Producto final (enlaces y capturas)
- **Landing (Lovable):** [URL TODO]  
- **Vídeo master (1–2 min):** `video/master.mp4` (con `video/master.srt`).  
- **Capturas:** frames de cada avatar y pantallas de Lovable (añadir en `/slides` y aquí mini-mosaico).  
- **QR al repo o master:** TODO

---

## 6) Herramientas y experiencia de uso
- **Texto/guiones:** ChatGPT → rapidez para iterar tono y duración; cuidado con *hallucinations* (solución: límites y disclaimers).  
- **Voz:** ElevenLabs → control de timbre/velocidad; reto: prosodia en listas (solución: comas/puntos y micro-pausas).  
- **Vídeo:** CapCut/Clipchamp/Slides→MP4 → suficiente para “avatar” sin coste extra; reto: peso de archivo (solución: bitrate medio).  
- **Web:** Lovable → modales rápidos con MP4; revisar **mobile** y rendimiento.  
- **Slides:** Gamma/SlidesAI → estructuración automática; reto: uniformidad de estilo (solución: paleta y tipografía definidas).

---

## 7) Ética y límites
- **Transparencia:** voces sintéticas; sin suplantación de personas reales.  
- **Contenido legal:** mensajes informativos; **no** asesoría legal.  
- **Privacidad:** sin PII ni marcas reales.  
- **Derechos:** imágenes/íconos libres o generados; créditos en slides/README.

---

## 8) Lecciones aprendidas


---

## 9) Próximos pasos
- Multilingüe (TTS EN/PT) y selector de idioma en Lovable.  
- Métricas (tiempo de visionado/click en CTA).  
- Variantes de avatar (más roles: Protección de Datos, Seguridad).

---

## 10) Anexos
- **Promptbook:** `/prompts/promptbook.md` (prompts y capturas “antes/después”).  
- **Guiones:** `/scripts/*.md`  
- **Parámetros de voz:** `/audio/metadata.json`  
- **Especificaciones de vídeo:** resolución, fps, bitrate usados (añadir aquí cuando se cierre E3/E4).
