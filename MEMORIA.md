# Memoria del Proyecto — Avatares Digitales (Sector Legal)

> **Demo IA Gen** con 3 “avatares” (Operativo, Mentoría, Especialista/Litigación) para comunicación interna clara y consistente.
> Guiones con GPT, voz con ElevenLabs, vídeos de animación simple, landing en Lovable.  
> **Disclaimer:** Demostración educativa. No constituye asesoramiento legal.

---

## 1. Escenario y objetivo
- **Escenario elegido:** Servicio de avatares digitales para un bufete (Escenario 3).
- **Título del proyecto:** *Galería de Avatares Legales*.
- **Objetivo de la demo:** Mostrar 3 perfiles con tono/estilo diferenciado capaces de explicar un tema y responder micro-FAQs, con **máximo uso de IA generativa** en el flujo (texto → audio → vídeo → web).

### Perfiles de la demo
| Avatar | Enfoque | Resumen |
|---|---|---|
| Iñigo | **Ejecutivo** | Liderazgo y compliance: mensajes ejecutivos claros y alineados con políticas. |
| Lucía | **Especialista** | Formación legal dinámica: procedimientos y regulaciones del sector. |
| Adolfo | **Comunicación** | Resolución de dudas internas: respuestas cercanas y orientación rápida. |

---

## 2. Equipo y roles
| Persona | Rol principal | Responsabilidades | Backup |
|---|---|---|---|
| Ana | **Guiones & Copy** | Guiones de 3 avatares (≤130 palabras + 2 Q&A c/u), copy de landing | Amalia |
| Carlos | **Audio TTS** | Generación de 3 locuciones en ElevenLabs + `audio/metadata.json` | Ana |
| Juan | **Vídeo/Animación** | 3 clips MP4 (1080p) con lower-third + subtítulos si aplica | Carlos |
| Amalia | **Web + Slides** | Integración en **Lovable**, slides (SlidesAI/Copilot) y promptbook | Juan |

---

## 3. Planificación (hitos)
- **H1 – Contenidos**: guiones (`/scripts`) + copy web (`/brand/copy_web.md`).  
- **H2 – Audio**: `audio/{lucia,inigo,adolfo}.wav` + `audio/metadata.json`.  
- **H3 – Vídeo**: `video/01_lucia.mp4`, `02_inigo.mp4`, `03_adolfo.mp4`.  
- **H4 – Integración**: landing en **Lovable** (3 modales) + slides.  
- **H5 – Ensayo**: *dry run* 15’ + 5’, checklist final.
---

## 4. Proceso y estadios intermedios
**E1 – Guiones & Copy (GPT)**  
- Prompt base: “Guion corporativo 120–130 palabras + 2 Q&A, tono [cercano/formal/didáctico], sin asesoría legal.”
- Estilos definidos: **Ejecutivo (Iñigo)**, **Especialista (Lucía)** y **Comunicación (Adolfo)**.
- Prompt base: “Guion corporativo 120–130 palabras + 2 Q&A, tono [ejecutivo/didáctico/cercano], sin asesoría legal.”
- Artefactos: `scripts/guion_lucia.md`, `guion_inigo.md`, `guion_adolfo.md`, `brand/copy_web.md`.  
- Evidencias: `/prompts/promptbook.md` y capturas.

**E2 – Audio (ElevenLabs)**  
- Parámetros orientativos: estabilidad 0.55–0.65; style 0.30–0.40; speed 1.00–1.03.  
- Artefactos: `audio/*.wav`, `audio/metadata.json`.  
- Notas: nivelado de volumen, micro-pausas antes de Q&A.

**E3 – Vídeo/Animación (CapCut/Clipchamp/Slides→MP4)**  
- Enfoque: “logo/imagen parlante” (zoom 98–102%), lower-third y subtítulos opcionales.  
- Artefactos: `video/01_lucia.mp4`, `02_inigo.mp4`, `03_adolfo.mp4` (1080p, ≤30–50 MB).

**E4 – Web + Slides (Lovable / SlidesAI/Copilot)**  
- Landing: 3 tarjetas con botón **Reproducir demo** → modal con MP4.  
- Artefactos: `/web` (capturas), `slides/Digital Counsel_ Avatares Legales con IA.pdf`.

---

## 5. Producto final (enlaces y capturas)
- **Landing (Lovable):** https://preview--ai-legal-showcase.lovable.app/ *(puede requerir permisos)*
- **Vídeos:** `video/02_inigo.mp4` (**Ejecutivo**), `video/01_lucia.mp4` (**Especialista**), `video/03_adolfo.mp4` (**Comunicación**).
- **Slides:** `/slides/Digital Counsel_ Avatares Legales con IA.pdf`  
- **Capturas:** pantallas de Lovable en `/web`.

---

## 6. Herramientas y experiencia de uso
- **Texto/guiones:** ChatGPT → rapidez para iterar tono y duración; control con límites y disclaimers.  
- **Voz:** ElevenLabs → timbre/velocidad; prosodia resuelta con puntuación y pausas.  
- **Vídeo:** CapCut/Clipchamp/Slides→MP4 → suficiente para “avatar” sin coste extra; cuidar bitrate.  
- **Web:** Lovable → modales rápidos sin código; responsive; cambios ágiles.  
- **Slides:** Copilot y SlidesAI → plantillas + personalización de paleta/tipografía.

---

## 7. Ética y límites
- **Transparencia:** voces sintéticas; sin suplantación de personas reales.  
- **Contenido legal:** informativo; **no** asesoría legal.  
- **Privacidad:** sin PII ni marcas reales.  
- **Derechos:** imágenes/íconos libres o generados; créditos en slides/README.

---

## 8. Lecciones aprendidas
- La IA acelera prototipos, pero requiere revisión humana.  
- La coordinación entre roles fue clave para coherencia final.  
- Herramientas low-code aceleran integración y evitan “atascos” técnicos.

---

## 9. Próximos pasos
- Multilingüe (TTS EN/PT) y selector de idioma en Lovable.  
- Métricas (visionado/CTR en CTA).  
- Nuevos roles de avatar (Protección de Datos, Seguridad).

---

## 10. Anexos
- **Promptbook:** `/prompts/` (prompts y capturas).  
- **Guiones:** `/scripts/*.md`  
- **Parámetros de voz:** `/audio/metadata.json`  
- **Especificaciones de vídeo:** resolución, fps, bitrate (añadir al cerrar E3/E4).
