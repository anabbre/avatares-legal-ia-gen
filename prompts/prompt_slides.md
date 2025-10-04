# Presentación del Proyecto: Galería de Avatares Legales

Quiero generar una presentación en base a una web de la que te paso capturas. La presentación debe recoger la estética de la página web, manteniendo la coherencia visual y su misma paleta de colores. Con base en el escenario 3 (Servicio de Avatares Digitales para el sector legal) del pdf que te adjunto y el contenido estructurado por diapositivas que te adjunto (**contenido obtenido de un prompt anterior en Copilot adjuntando el enunciado del proyecto y el README del repositorio).

## 🧭 Slide 1: Escenario y Título del Proyecto

**Título:** Galería de Avatares Legales  

**Escenario elegido:** Servicio de avatares digitales para un bufete de abogados  
**Objetivo:**  
Demostrar cómo tres avatares generados con IA pueden comunicar temas legales internos de forma clara, diferenciada y personalizada, usando un flujo completo de IA generativa: texto → audio → vídeo → web.

---

## 👥 Slide 2: Equipo y Roles

**Estructura del equipo multidisciplinar:**

| Persona | Rol Principal         | Responsabilidades                                 | Backup  |
|--------|------------------------|---------------------------------------------------|---------|
| Ana    | Guiones & Copy         | Guiones de los avatares + copy de la landing      | Amalia  |
| Carlos | Audio TTS              | Locuciones con ElevenLabs + metadata              | Ana     |
| Juan   | Vídeo/Animación        | Clips MP4 con subtítulos y diseño visual          | Carlos  |
| Amalia | Web + Master + Slides  | Landing en Lovable, video master, presentación    | Juan    |

---

## 📅 Slide 3: Planificación del Proyecto

**Hitos principales:**

- **H1:** Guiones y copy web (`/scripts`, `/brand/copy_web.md`)
- **H2:** Audios generados (`audio/*.wav`, `metadata.json`)
- **H3:** Vídeos individuales (`video/01_lucia.mp4`, etc.)
- **H4:** Integración en landing + video master + slides
- **H5:** Ensayo final (15’ presentación + 5’ preguntas)

**Fechas:** aún por definir (TODO)

---

## 🔄 Slide 4: Proceso y Estadios Intermedios

### E1 – Guiones & Copy (GPT)
- Prompt base: guion corporativo (120–130 palabras) + 2 Q&A, tono adaptado (cercano, formal, didáctico).
- Artefactos: `guion_lucia.md`, `guion_inigo.md`, `guion_carmen.md`.

### E2 – Audio (ElevenLabs)
- Parámetros personalizados por avatar (ej. Lucía: estabilidad 0.60, style 0.40).
- Notas: nivelado de volumen, micro-pausas antes de Q&A.

### E3 – Vídeo/Animación
- Formato “imagen parlante” con zoom sutil, subtítulos opcionales, lower-third.
- Herramientas: CapCut, Clipchamp, Slides→MP4.

### E4 – Web + Master + Slides
- Landing con 3 tarjetas y modales.
- Video master: intro + 3 clips + cierre con CTA y disclaimer.

---

## 🎬 Slide 5: Producto Final

**Landing (Lovable):**
- 3 tarjetas con botón “Reproducir demo”
- Modal con video MP4 por avatar

**Video master (1–2 min):**
- Intro 5 s  
- 3 avatares (~30 s cada uno)  
- Cierre 10 s con CTA y disclaimer

**Capturas:**
- Frames de cada avatar  
- Pantallas de la landing  
- QR al repositorio (pendiente)

---

## 🧰 Slide 6: Herramientas Utilizadas y Experiencia

- **Texto/Guiones:** ChatGPT → rápido, versátil; cuidado con hallucinations (solución: límites y disclaimers)
- **Voz:** ElevenLabs → control de timbre/velocidad; reto: prosodia en listas (solución: puntuación y pausas)
- **Vídeo:** CapCut/Clipchamp → suficiente para demo; reto: peso del archivo (solución: bitrate medio)
- **Web:** Lovable → modales rápidos; revisar rendimiento móvil
- **Slides:** Gamma/SlidesAI → estructuración automática; reto: estilo uniforme (solución: paleta definida)

---

## ⚖️ Slide 7: Ética y Límites

- **Transparencia:** voces sintéticas, sin suplantación  
- **Contenido legal:** informativo, no asesoría  
- **Privacidad:** sin datos personales ni marcas reales  
- **Derechos:** imágenes libres o generadas, créditos incluidos

---

## 📚 Slide 8: Lecciones Aprendidas

- La IA permite prototipar rápido, pero requiere supervisión humana  
- La coordinación entre roles técnicos y creativos fue clave  
- La integración web fue más sencilla gracias a herramientas low-code

