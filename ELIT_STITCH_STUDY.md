# ELIT v10 — Deep Page Study for Google Stitch Mockup Generation

> Generate high-fidelity mockup images for each page/screen described below.
> Visual identity: Dark green (#020a05 background), neon green (#2ecc71) accents, DM Sans + Barlow Condensed fonts.
> Device: Mobile-first (375px), also generate desktop (1280px) variants.

---

## GLOBAL DESIGN TOKENS

```
Background:     #020a05 (near-black with green tint)
Card surface:   #0b1f17 (dark forest green)
Card hover:     #112b1f (slightly lighter)
Accent:         #2ecc71 (neon green — used for CTAs, highlights, data, progress)
Accent dark:    #1a7a43 (secondary green)
Accent glow:    0 0 18px rgba(46,204,113,0.25) — used on primary buttons and active states
Warning:        #f39c12 (amber)
Error:          #e74c3c (red)
Text primary:   #e8f5ee (near-white with green tint)
Text secondary: #8ab09a (muted sage green)
Text muted:     #4a7060 (dark sage)
Border:         rgba(46,204,113,0.12)
Border hover:   rgba(46,204,113,0.25)

Font display:   'Barlow Condensed', condensed sans-serif — UPPERCASE, bold 700-900, tight letter-spacing
Font body:      'DM Sans', sans-serif — clean, modern geometric sans
Border radius:  12px (cards), 8px (inputs/buttons), 100px (pills/badges)
```

### UI Patterns
- **Cards**: Dark green (#0b1f17) with 1px border, 12px radius, subtle green glow on hover
- **Buttons Primary**: Solid #2ecc71, black text, green glow shadow, 100px pill shape
- **Buttons Secondary**: Transparent with #2ecc71 border, green text
- **Badges/Pills**: Tiny uppercase labels with colored dot + text, rounded full
- **Progress bars**: Thin (4px) with gradient fill from #1a7a43 to #2ecc71
- **Icons**: Emoji-based (not icon font), large (1.3-2.5rem) as section headers
- **Scrollbar**: 4px wide, green thumb on dark track

---

## PAGE 1: LANDING (Hero)

### Layout
- Full viewport height, centered content
- Two decorative blurred circles in background (large radial gradients, green tint, mix-blend-multiply)
- Content stacked vertically, centered

### Elements (top to bottom)
1. **Badge pill**: Small rounded pill with pulsing green dot + text "Plataforma IA Deportiva · Tecnología de Élite" — uppercase, tiny font, green background rgba
2. **Logo**: "ELIT" — Barlow Condensed, 4.5rem, font-weight 900, letter-spacing 6px, neon green with text-shadow glow
3. **Tagline**: "Elite Level Intelligence Training" — 1rem, sage text, letter-spacing 3px, uppercase
4. **Slogan paragraph**: ~2 lines, mentions "Inteligencia Artificial", bold keywords, secondary text color
5. **Two buttons side by side**:
   - Primary: "▶ Comenzar Ahora" — green pill, black text, glow
   - Secondary: "Ver Demo →" — bordered pill, green text
6. **Stats row**: 4 columns evenly spaced
   - "2,400+" / Jugadores
   - "87%" / Mejora
   - "15K+" / Rutinas
   - "99%" / Precisión IA
   - Numbers: Barlow Condensed 1.4rem bold green; Labels: tiny sage text

### Mood
Premium, tech-forward, sports energy. Think Nike Training Club meets dark fintech dashboard.

---

## PAGE 2: QUIÉNES SOMOS (About Us)

### Layout
- Scrollable page with section header + multiple content blocks stacked vertically
- Max-width container (~600px mobile, ~900px desktop)

### Section Header
- Title: "Quiénes Somos" — split into green + white halves
- Subtitle: one line description in sage text

### Block 1: Hero Card
- Large card with green glow border
- Trophy emoji (2.5rem) + "ELIT" title (Barlow Condensed, green) + tagline
- Body paragraph in sage text

### Block 2: "Nuestro Propósito" (Purpose)
- Badge: "🎯 Nuestro Propósito" — green pill
- Title: "Democratizando el Alto Rendimiento" — Barlow Condensed, white, large
- Body: Paragraph with bold green highlights, sage text
- Left green accent border (3px solid green, left side)

### Block 3: "¿Por qué somos necesarios?" (Why)
- Same card pattern as Block 2
- Badge: "⚡ ¿Por qué somos necesarios?" — amber-tinted pill
- Title: "El Talento No Puede Perderse"
- Body with bold highlights

### Block 4: "Inspiración y Fortaleza Mental" (Inspiration)
- Badge: "✝️ Inspiración y Fortaleza Mental"
- Large decorative quote mark (") in green, 3rem
- Bible verse in italicized/styled blockquote with green left border
- Reference: "— 1 Corintios 9:24-25 (NVI)" in sage
- **Three pillars** in a row (grid):
  - 🏃 "Corre para Ganar" + short text
  - 🔥 "Disciplina de Élite" + short text
  - 👑 "La Corona Eterna" + short text
  - Each pillar: card with emoji, Barlow title, body text

### Block 5: Values Grid
- 4 cards in 2x2 grid (mobile: stack)
- Each: Large emoji icon → Title (green, bold) → Short description
- 🧬 Ciencia / 🤖 Inteligencia IA / 🌎 Acceso Universal / 📈 Resultados Reales

---

## PAGE 3: SUSCRIPCIÓN (Subscription & Pricing)

### Layout
- Section header + 3 pricing cards side-by-side (scroll horizontal on mobile)
- Payment methods card below

### Pricing Cards (3 columns)
1. **Gratuito** — $0 / siempre
   - 4 features list (checkmark-style)
   - "Comenzar Gratis" button (bordered green)
2. **Formativo** (FEATURED) — $4.99 USD/mes
   - "MÁS POPULAR" badge at top (green pill, pulsing)
   - Card has green border + subtle green glow
   - 5 features including "Videos YouTube integrados HD", "Scouting con IA"
   - "Suscribirme" primary green button
3. **Élite** — $9.99 USD/mes
   - 5 premium features
   - "Suscribirme" bordered button

### Card Design
- Dark card (#0b1f17), 16px radius
- Plan name: Barlow Condensed uppercase
- Price: Barlow Condensed, 2.5rem, green, bold
- Period: tiny sage text
- Features: checkmark dot + text list
- Featured card: scaled slightly larger, green border, elevated

### Payment Methods Card
- Title: "💳 Métodos de Pago"
- 5 payment method pills in a row: Visa, Mastercard, Amex, PayPal, PSE
- Each pill: dark background, colored left border (brand color), icon + name
- SSL notice box: lock emoji + "Transacciones protegidas" text, green-tinted card

---

## PAGE 4: AUTH (Login / Register)

### Layout
- Centered card (max 400px), dark background
- Decorative blurred green circles behind

### Card Content
1. **Header**: "ELIT — Tu Cuenta" with decorative green accent
2. **Subtitle**: "Regístrate o inicia sesión"
3. **Tab toggle**: Two tabs "🆕 Registrarse" / "🔑 Iniciar Sesión"
   - Active tab: green bottom border + green text
   - Inactive: sage text
4. **Register form** (default visible):
   - Nombre Completo (text input)
   - Correo (email input)
   - Contraseña (password input)
   - "Crear Cuenta Gratis →" primary button
5. **Login form** (hidden by default):
   - Correo + Contraseña
   - "Iniciar Sesión →" button
6. **Divider**: "o explora sin cuenta"
7. **Guest button**: "Explorar como Invitado" secondary button, full width

### Input Design
- Dark background (#071410), 1px green border, 10px radius
- Placeholder: muted sage
- Focus: green border + subtle green glow
- Labels: tiny uppercase, letter-spacing, sage color

---

## PAGE 5: PERFIL DEPORTIVO (Athletic Profile)

### Layout
- Section header + 4 cards in 2-column grid (mobile: stack)
- "Generar Plan con IA" CTA button at bottom center

### Card 1: Datos Básicos
- 👤 icon + "Datos Básicos" title
- Fields: Edad (number), País (text) — side by side
- Posición: 4 toggle buttons in grid → ⚡ Delantero / 🔄 Volante / 🛡️ Defensa / 🥅 Arquero
  - Selected: green background, green border, bold
  - Unselected: dark card, sage border
- Pie: dropdown (Derecho/Izquierdo/Ambidiestro)
- Nivel: dropdown (5 levels from Nacional to Recreativo)

### Card 2: Medidas
- 📏 icon + "Medidas"
- Altura/Peso side by side
- 30m speed / Resistencia side by side
- Unit toggle: KG / LB pill buttons
- Sentadilla / Banca / Muerto — 3 columns

### Card 3: Tiempos
- ⏱️ icon + "Tiempos"
- Horas/sem equipo + personal side by side
- Total display: large Barlow Condensed green number "15h" in a highlighted box
- Días ELIT/semana input

### Card 4: Mental
- 🧠 icon + "Mental"
- Textarea: "¿Por qué juegas?"
- Two text inputs: Meta corto/largo plazo
- Two range sliders (1-10):
  - Estrés en partido: "Tranquilo ←→ Muy estresado"
  - Motivación: "Baja ←→ Máxima"
  - Slider: green track, green thumb, value display

### CTA Button
- "🤖 Generar Plan con IA" — large green pill, center, glow effect

---

## PAGE 6: DASHBOARD

### Layout
- Section header + semaphore risk indicator + 2-column grid (AI score + chart) + log card

### Semaphore (Risk Indicator)
- Full-width card with colored left accent
- Three states: 🟢 Green (Óptimo) / 🟡 Yellow (Sobrecarga) / 🔴 Red (Riesgo Alto)
- Badge pill with colored dot + level text
- Large emoji float-left, level title (Barlow Condensed), recommendation text

### AI Evaluation Card (left column)
- Green glow border
- Circular score ring: large number (e.g., "74") / "/100" inside a circle with green border + glow
- "Potencial Atlético" label below
- 5 attribute bars:
  - Velocidad / Resistencia / Fuerza / Mental / Técnica
  - Each: label (70px) → thin progress bar (green gradient fill) → value number
  
### Progress Chart (right column)
- Chart.js line chart with two datasets
- Green lines on dark background
- X-axis: months (Ene-Ago)
- Y-axis: 50-100 range
- Datasets: "Velocidad" (bright green) + "Resistencia" (dark green)
- Filled area under bright green line

### Log Card (full width)
- Title: "✍️ Registrar Marca"
- Category dropdown + Value input side by side
- "Guardar" button
- Log entries list: each entry is a row with category, delta badge (green "+5% 💪" or amber "-3% ⚠️"), value, date

---

## PAGE 7: CALENDARIO & RUTINAS (Calendar — Main Training Hub)

### Layout
- Section header + weekly progress bar + week navigation + 7 day cards (accordion)

### Weekly Progress Bar
- Label: "Progreso Semanal" + percentage
- Thin green progress bar (full width)
- Note text below

### Week Navigator
- "◀ Semana 1 ▶" — left/right arrows + week label

### Day Cards (7 accordion items)
Each card is a collapsible row:

**Header (always visible)**:
- Left: Date number (large) + Day abbreviation (LUN/MAR/etc.)
- Center: Training scope title + subtitle
  - Monday: "⚡ VELOCIDAD PURA" / "Sprint · Aceleración · Frecuencia de zancada"
  - Wednesday: "💥 FUERZA EXPLOSIVA" / "Pliometría · Potencia · Cadena posterior"
  - Friday: "⚽ TÉCNICA INDIVIDUAL" / "Control · Conducción · Biomecánica"
  - Rest days: "🧘 RECUPERACIÓN ACTIVA"
- Right: Badge (HOY/✓ LISTO/PRÓXIMO/DESCANSO) + arrow toggle
- Today card: green left border accent
- Done card: muted, green checkmark badge

**Body (expanded — training day)**:
- Mini semaphore risk bar
- Session progress bar with percentage
- **Exercise cards** (2-4 per day depending on level):
  Each exercise card contains:
  - Header row: Number (01, 02...) + Exercise name + muscle group + series×reps + RPE
  - Expandable body with:
    - **YouTube video iframe** (16:9 aspect ratio, lazy loading)
    - Technical detail paragraph
    - RPE dots (10 dots, filled up to RPE value in green)
    - **Interactive timer**:
      - Preset buttons: 30s / 45s / 60s / 90s / 120s (pill toggles)
      - Large timer display: Barlow Condensed, 3rem, green (pulses red when done)
      - 3 action buttons: ▶ Start / ↺ Reset / ✓ Done
      - Alert text below timer
  - Done exercises get green "✓" badge and muted styling
- **Confirm button**: "✅ Confirmar Entrenamiento de Hoy" — green pill, full width
  - Only active for today's date
  - After confirm: changes to "✓ Entrenamiento Confirmado" (disabled, green)

**Body (expanded — rest day)**:
- Mini semaphore
- Rest tips list: foam rolling, mobility, hydration, visualization
- Calming emoji (🧘) + rest recommendations

---

## PAGE 8: NUTRICIÓN & BIOTIPO IA (Nutrition)

### Layout
- Section header + hero nutrition card + macros grid + day adjustment + note

### Hero Card (centered, green glow)
- 🥗 large emoji
- "Plan Nutricional · [Position]" — Barlow Condensed title
- Position-specific bio text
- Stats line: weight, height, age, TDEE in green

### Macros Grid (3 columns)
Each macro card:
- Emoji icon (🥩/🍚/🥑)
- Large value: Barlow Condensed, green, e.g., "140g"
- Unit: "g/día"
- Label: Proteínas/Carbohidratos/Grasas
- Thin progress bar showing percentage of total calories

### Day Adjustment Card
- 📅 icon + "Día de Entreno:" or "Día de Descanso:"
- Carb adjustment recommendation
- Green-tinted info card

### AI Note
- Green-bordered note: "🤖 Calculado con Mifflin-St Jeor × 1.725"

---

## PAGE 9: SCOUTING CON IA (AI Video Analysis)

### Layout
- Section header + upload zone + analysis results + reference videos

### Upload Zone (initial state)
- Large dashed border zone (2px dashed green)
- 📹 emoji + "Sube tu Video" title + "Arrastra o clic · MP4, MOV" subtitle
- On hover/dragover: green background tint, green glow

### Analysis State (after upload)
- Video placeholder card with film emoji
- Green progress bar animating left-to-right
- "🤖 IA procesando..." blinking text

### Results (after analysis)
- Green pulsing dot + "Análisis completado · 94.7%"
- **3 scout cards** in grid:
  Each card:
  - 📊 icon + category title (e.g., "Velocidad y Explosividad")
  - Large score: Barlow Condensed "82" / "/100"
  - 3 bullet points with green dots, analysis text
  - Some bullets have ✅ (good) or ⚠️ (needs work) indicators
- "Analizar otro video" secondary button

### Reference Videos Card
- 🎓 "Videos de Referencia" title
- 3 video cards in grid:
  Each: YouTube iframe embed (16:9) + label with emoji + category name
  - Position-specific: e.g., for Delantero: Sprint/Conducción/Definición
  - Videos play inline within the card

---

## OVERLAYS & MODALS

### Security Modal (post-login)
- Dark overlay with blur backdrop
- Card: lock emoji 🔐 + "Alerta de Seguridad"
- Simulated email format: From security@elit.app, timestamp
- Subject line, access detected badge (red-tinted)
- "Hola [Name], nuevo acceso desde este dispositivo"
- Device + time info
- Two buttons: "Era yo" (secondary) + "Cambiar Contraseña" (primary green)

### Celebration Modal (session complete)
- Dark overlay with heavy blur
- Card with green border, bouncy pop-in animation
- Sparkle particles (colored dots flying outward from center)
- 🏆 trophy emoji (3.6rem, pulsing)
- "¡Sesión de Élite Completada!" — Barlow Condensed, green, large
- Subtitle congratulation text
- "¡A por la siguiente! →" green button

### Toast Notification
- Bottom-right fixed position
- Small card: green background tint, green border
- Slides in from right
- Text like "✅ ¡Entrenamiento confirmado!"

---

## RESPONSIVE BEHAVIOR

### Mobile (< 480px)
- All grids collapse to single column
- Navigation becomes hamburger menu (☰) with slide-in drawer
- Stats row wraps to 2x2
- Timer display stays large and centered
- Video iframes maintain 16:9 aspect ratio
- Cards get tighter padding (12px vs 16px)

### Tablet (480-768px)
- 2-column grids maintained
- Navigation still in topbar
- Pricing cards may scroll horizontally

### Desktop (> 768px)
- Full navigation bar with all links visible
- Profile uses 2-column card grid
- Dashboard side-by-side (AI score + chart)
- Pricing cards all visible in row

---

## ANIMATION NOTES

- **Landing badge dot**: Continuous pulse (scale 1→1.5→1, opacity cycle)
- **Landing title**: Subtle text-shadow glow animation
- **Card hover**: Border color transition to green, subtle shadow
- **Progress bars**: Width transition 1.4s ease (animate on load)
- **Timer warn state**: Background pulse between normal and red
- **Celebration sparkles**: Particles fly outward from center with randomized angles and colors
- **Celebration card**: Pop-in with cubic-bezier overshoot (scale 0→1.1→1)
- **Toast**: Slide in from right (translateX), auto-dismiss after 3.3s
- **Accordion toggle**: Arrow rotates 90°, body slides open with max-height transition

---

## COLOR PALETTE SUMMARY FOR STITCH

| Token | Hex | Usage |
|-------|-----|-------|
| bg-darkest | #020a05 | Page background |
| bg-card | #0b1f17 | Card surfaces |
| bg-card-hover | #112b1f | Interactive card states |
| bg-input | #071410 | Form input backgrounds |
| accent | #2ecc71 | Primary CTAs, data, progress, highlights |
| accent-dark | #1a7a43 | Secondary accents, gradient starts |
| accent-glow | rgba(46,204,113,0.25) | Button/card glow shadows |
| accent-bg | rgba(46,204,113,0.06) | Subtle tinted backgrounds |
| warning | #f39c12 | Caution states, delta negative |
| error | #e74c3c | Danger, timer expired, risk |
| text-primary | #e8f5ee | Main readable text |
| text-secondary | #8ab09a | Supporting text, descriptions |
| text-muted | #4a7060 | Least important text, labels |
| border | rgba(46,204,113,0.12) | Default card/section borders |
| border-hover | rgba(46,204,113,0.25) | Hover state borders |
