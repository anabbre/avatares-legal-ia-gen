# Avatares Legales – Demo IA Gen

Demo de comunicación legal con **3 avatares**:
**Operativo (Lucía)**, **Mentoría (Iñigo)** y **Especialista/Litigación (Adolfo)**.
Contenidos generados con **GPT** (guiones/copy) y **ElevenLabs** (voz).  
Vídeos de **animación simple** (logo/imagen parlante) y **landing** montada en **Lovable**.  
> *Demostración educativa. No constituye asesoramiento legal.*

---

## 🔗 Demo
- **Landing (Lovable)**: https://preview--ai-legal-showcase.lovable.app/ *(puede no estar pública por falta de permisos)*  

---

## 👥 Roles y pipeline (fases)
- **E1 – Guiones & copy** → **Ana** (backup Amalia)  
- **E2 – Audio TTS** → **Carlos** (backup Ana)  
- **E3 – Vídeo/animación (3 MP4)** → **Juan** (backup Carlos)  
- **E4 – Web Lovable + Slides** → **Amalia** (backup Juan)

**Handoff**: cada etapa entrega artefactos en el repo y menciona al siguiente owner en su issue.

---

## 🗺️ Planificación (hitos)
- H1: guiones + copy (`/scripts`, `/brand/copy_web.md`)  
- H2: audios ElevenLabs + `audio/metadata.json`  
- H3: `video/01_lucia.mp4` (**Operativo**), `02_inigo.mp4` (**Mentoría**), `03_adolfo.mp4` (**Especialista/Litigación**)
- H4: Lovable integrado (3 modales) + slides  
- H5: **Dry run** 15’+5’ y cierre

---

## ✅ Definition of Done
**E1**: 3 guiones ≤130 palabras + 2 Q&A; copy web coherente.  
**E2**: 3 WAV/MP3 nivelados (44.1 kHz) + `metadata.json` con `voice, stability, style, speed`.  
**E3**: 3 MP4 1080p, rótulo *lower-third*, ≤30–50 MB c/u.  
**E4**: Lovable con 3 botones “Reproducir demo” → modal correcto; footer con **disclaimer**; slides PDF.

---

## 📁 Estructura
```
.
├─ audio/
│  └─ metadata.json
├─ brand/
│  ├─ copy_web.md
│  └─ paleta.md
├─ prompts/
│  ├─ promptbook.md
│  ├─ prompt_slides.md
│  └─ prompt_web.md
├─ scripts/
│  ├─ guion_lucia.md
│  ├─ guion_inigo.md
│  └─ guion_adolfo.md
├─ slides/
│  └─ Digital Counsel_ Avatares Legales con IA.pdf
├─ video/
│  ├─ lucia.mp4
│  ├─ inigo.mp4
│  ├─ adolfo.mp4
│  ├─ Portada_comunicacion.png
│  ├─ Portada_ejecutivo.png
│  └─ Portada_especialista.png
├─ web/
│  ├─ Page1.png
│  ├─ Page2.png
│  ├─ Page3.png
│  └─ Page4.png
├─ MEMORIA.md
├─ README.md
└─ .gitignore
```

---

## 🧰 Herramientas
- **Texto/guiones**: ChatGPT
- **Voz**: ElevenLabs  
- **Vídeo**: CapCut / Clipchamp / (Slides→MP4)  
- **Web**: Lovable (modales con MP4)  
- **Slides**: Copilot + SlidesAI

---

## 📌 Entregables
- Landing en Lovable con **3 demos** embebidas  
- Slides (PDF)  
- Repo con guiones, audios, vídeos, **promptbook** y **memoria**

---

## 📝 Notas
- Nombres sin espacios/acentos: `01_lucia.mp4`, `lucia.wav`, etc.  
- Mantener volumen homogéneo y contraste de textos.  
- Sin datos reales ni marcas: todo es **ficticio**.
