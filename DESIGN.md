---
name: Landing EPS Dolor Crónico · CS Entrevías
description: Programa grupal gratuito de educación para la salud sobre dolor crónico — calidez de barrio con respaldo sanitario
colors:
  azul-saludmadrid: "#0067A0"
  azul-profundo: "#004B73"
  azul-bruma: "#E8F2F8"
  terracota-paincafe: "#C2410C"
  terracota-bruma: "#FBEFE7"
  verde-movimiento: "#0D8A7A"
  verde-bruma: "#E6F5F2"
  crema-calida: "#FAF7F2"
  blanco: "#FFFFFF"
  arena: "#EFE9E1"
  tinta: "#1C1917"
  tinta-suave: "#44403C"
  ambar-resalte: "#FFE08A"
  teal-paincorp: "#0DB1A4"
  teal-oscuro-paincorp: "#004A59"
  violeta-etapa: "#7C3AED"
typography:
  display:
    fontFamily: "Georgia, Cambria, 'Times New Roman', serif"
    fontSize: "clamp(1.9rem, 6vw, 2.6rem)"
    fontWeight: 700
    lineHeight: 1.2
  headline:
    fontFamily: "Georgia, Cambria, 'Times New Roman', serif"
    fontSize: "clamp(1.5rem, 5vw, 2rem)"
    fontWeight: 700
    lineHeight: 1.2
  title:
    fontFamily: "system-ui, -apple-system, 'Segoe UI', Roboto, sans-serif"
    fontSize: "1.05rem"
    fontWeight: 700
    lineHeight: 1.3
  body:
    fontFamily: "system-ui, -apple-system, 'Segoe UI', Roboto, sans-serif"
    fontSize: "18px"
    fontWeight: 400
    lineHeight: 1.65
  label:
    fontFamily: "system-ui, -apple-system, 'Segoe UI', Roboto, sans-serif"
    fontSize: "0.78rem"
    fontWeight: 700
    letterSpacing: "0.4px"
rounded:
  sm: "8px"
  md: "14px"
  pill: "20px"
  tag: "4px"
spacing:
  gap: "0.85rem"
  card: "1.1rem"
  section: "2.25rem"
  container: "720px"
  touch: "56px"
components:
  card-benefit:
    backgroundColor: "{colors.blanco}"
    textColor: "{colors.tinta-suave}"
    rounded: "{rounded.md}"
    padding: "1.1rem"
  eyebrow-pill:
    backgroundColor: "{colors.verde-movimiento}"
    textColor: "{colors.blanco}"
    rounded: "{rounded.pill}"
    padding: "0.35rem 0.9rem"
  accordion-button:
    backgroundColor: "{colors.blanco}"
    textColor: "{colors.azul-profundo}"
    typography: "{typography.title}"
    height: "56px"
  cta-panel:
    backgroundColor: "{colors.azul-profundo}"
    textColor: "{colors.blanco}"
    rounded: "{rounded.md}"
    padding: "0.9rem 1rem"
---

# Design System: Landing EPS Dolor Crónico · CS Entrevías

## 1. Overview

**Creative North Star: "El PainCafé del barrio"**

El sistema visual imita el gesto que define al programa: sentarse a una mesa, tomar un café y hablar de igual a igual, sin batas ni camillas — pero dentro de un centro de salud público que da confianza. Es **cálido primero, institucional de fondo**. La estructura es de página única, generosa y de lectura pausada: fondo crema (nunca blanco clínico), tipografía grande (18px), tarjetas con esquinas suaves, chips de icono tintados y puntos de color que guían la vista sin gritar. Cada bloque empuja a la persona del miedo a la acción, coherente con una marca **empoderadora, activa y motivadora**.

El sistema rechaza de forma explícita cuatro registros: el **folleto clínico frío** (estética aséptica, jerga, listados burocráticos), el **look pharma/corporativo** (stock photos, marketing de producto), la **estética startup/SaaS** (gradientes de moda, andamiaje de "eyebrows" y numeración 01/02/03 en cada sección, aire de app impersonal) y el **wellness espiritual** (tonos místicos, promesas de "sanación"). El punto dulce es la proximidad de Vallecas con respaldo sanitario serio.

La paleta es tricolor con propósito clínico-narrativo: azul = confianza sanitaria, terracota = acogida del PainCafé, verde = movimiento y salud activa. El azul manda como cimiento; la terracota y el verde marcan la calidez y la acción.

**Key Characteristics:**
- Fondo crema cálido, jamás blanco quirúrgico.
- Tipografía serif para titulares (voz humana) + sans del sistema para lectura (rendimiento y familiaridad).
- Tarjetas planas; la codificación va por chip de icono tintado y punto de color, no por franjas laterales ni sombras dramáticas (las franjas border-left/top son un tell de IA y están prohibidas).
- Tres colores con significado fijo (azul/terracota/verde), no decoración.
- Accesibilidad AA como material de construcción: 18px base, touch 56px, foco ámbar de 4px, contrastes altos.

## 2. Colors

Paleta híbrida de confianza institucional y calidez de barrio, anclada en el azul de SaludMadrid.

### Primary
- **Azul SaludMadrid** (#0067A0): color institucional y de confianza. Enlaces, marcadores de sesión teórica, chips de icono, borde inferior de la cabecera, eyebrow de datos.
- **Azul Profundo** (#004B73): titulares (h1–h3), fondo del panel CTA oscuro, texto de refuerzo (`<strong>`).

### Secondary
- **Terracota PainCafé** (#C2410C): calidez y acogida. Marca todo lo relativo al PainCafé (badge, borde, título), la tagline en cursiva del hero, el estado hover de enlaces y el anillo de foco.
- **Terracota Bruma** (#FBEFE7): fondo suave del bloque PainCafé.

### Tertiary
- **Verde Movimiento** (#0D8A7A): salud activa y acción. Ticks de la checklist, sesiones prácticas del cronograma, eyebrow "Gratuito", estado abierto del acordeón, nota de equidad.
- **Verde Bruma** (#E6F5F2): fondo de paneles abiertos y notas.

### Neutral
- **Crema Cálida** (#FAF7F2): fondo general de la página. El anti-blanco-clínico por defecto.
- **Blanco** (#FFFFFF): superficie de tarjetas y cabecera.
- **Arena** (#EFE9E1): bordes, separadores entre secciones, fondos de avatar.
- **Tinta** (#1C1917): texto principal (contraste >12:1).
- **Tinta Suave** (#44403C): texto secundario y descripciones (contraste >7:1).

### Acentos puntuales
- **Ámbar Resalte** (#FFE08A): único resalte legible sobre el azul profundo del CTA (mensaje clave, números de paso). No usar sobre fondos claros.
- **Violeta Etapa** (#7C3AED): exclusivo del Bloque D ("sostener el cambio") y su avatar. Uso mínimo y semántico.

### Named Rules
**La Regla de los Tres Significados.** Azul = confianza sanitaria, terracota = acogida/PainCafé, verde = movimiento/acción. Un color nunca se usa "porque queda bien": si no comunica uno de esos tres significados, se usa un neutro.

**La Regla del Fondo Cálido.** El fondo base es crema (#FAF7F2), nunca blanco puro a página completa. El blanco se reserva para superficies elevadas (tarjetas). Es lo que separa "centro de salud acogedor" de "consulta fría".

## 3. Typography

**Display Font:** Georgia (con Cambria, "Times New Roman", serif)
**Body Font:** system-ui (con -apple-system, Segoe UI, Roboto, sans-serif)
**Label/Mono Font:** system-ui (misma familia, en mayúsculas con tracking)

**Character:** Emparejamiento por eje de contraste (serif + sans), no dos sans parecidas. El serif da voz humana y editorial a los titulares y a la tagline en cursiva; el sans del sistema da lectura cómoda, familiar y rápida en cualquier móvil del barrio. Los subtítulos de tarjeta (`h3` de beneficios y bloques) rompen a sans deliberadamente para diferenciar "titular de sección" (serif) de "etiqueta de contenido" (sans).

### Hierarchy
- **Display / h1** (700, clamp(1.9rem, 6vw, 2.6rem), lh 1.2): título del hero. Serif, azul profundo.
- **Headline / h2** (700, clamp(1.5rem, 5vw, 2rem), lh 1.2): títulos de sección. Serif, azul profundo.
- **Title / h3** (700, 1.05–1.2rem, lh 1.3): subtítulos de tarjeta (beneficios, bloques, equipo) en **sans**; encabezados menores en serif.
- **Body** (400, 18px, lh 1.65): texto de lectura. Longitud de línea contenida (lead a 56ch; container 720px).
- **Label** (700, 0.72–0.82rem, tracking 0.3–0.5px, mayúsculas): eyebrows, roles del equipo, claves de datos, tags de mito/verdad.

### Named Rules
**La Regla de la Cursiva con Voz.** La cursiva serif solo aparece en la tagline emocional y en las preguntas del PainCafé (citas). Es la voz cercana del programa; no se usa como énfasis decorativo.

## 4. Elevation

Sistema **mayormente plano con codificación por color puntual**. La profundidad no se transmite con sombras dramáticas sino con: (1) fondo crema vs. superficie blanca, (2) una sombra ambiental única muy sutil, y (3) un chip de icono tintado o un punto de color que además clasifica el contenido. Esto mantiene el aire limpio y accesible y evita el look "app con capas".

### Shadow Vocabulary
- **Sombra ambiental** (`box-shadow: 0 4px 16px rgba(0, 47, 73, 0.08)`): única sombra del sistema, teñida de azul profundo. En tarjetas de datos, beneficios, bloques y pasos del CTA. Sugiere elevación suave, nunca drama.

### Named Rules
**La Regla del Color que Clasifica.** El color de una tarjeta no es adorno: codifica su naturaleza mediante su chip de icono o su punto de bloque (verde = datos/acción, azul = beneficio, color por bloque en las 4 etapas, terracota = PainCafé). Se codifica con chip o punto, **nunca con franjas laterales** (border-left/right >1px, tell de IA prohibido).

## 5. Components

### Buttons
- **Shape:** esquinas de 14px (`--radio`); pills de 20px para eyebrows/badges.
- **Botón acordeón (mito/verdad):** el único control real. Fondo blanco, texto azul profundo en sans 700, altura mínima 56px táctil, chevron azul que rota 180° al abrir; hover con fondo azul bruma; la tarjeta pasa a borde verde al estar abierta (`aria-expanded="true"`).
- **Focus:** anillo `outline: 4px solid #C2410C; outline-offset: 3px` en todo elemento enfocable (`:focus-visible`). El foco ámbar sobre cualquier fondo es la firma de accesibilidad.
- **CTA:** no hay botón de formulario. La llamada a la acción es humana ("habla con tu médico/a o fisio") con pasos numerados; el número usa ámbar sobre azul profundo.

### Cards / Containers
- **Corner Style:** 14px (tarjetas), 8px (paneles internos como photo-box).
- **Background:** blanco sobre fondo crema; paneles suaves en azul/verde/terracota bruma según sección.
- **Shadow Strategy:** sombra ambiental única (ver Elevation) o solo borde arena de 1px en tarjetas ligeras (checklist, mitos, equipo).
- **Border:** 1px arena por defecto. La codificación de color va por chip de icono o punto de color, nunca por franja lateral (ver Regla del Color que Clasifica).
- **Internal Padding:** ~1.1rem.

### Chips / Tags
- **Eyebrow pill:** fondo verde o terracota, texto blanco, mayúsculas 700, radio 20px.
- **Tag mito:** fondo #FDE7D9, texto #9A3412, radio 4px. **Truth/verdad:** fondo verde, texto blanco.
- **Tipo de sesión:** teórica = azul bruma/azul profundo; práctica = verde bruma/#0B6B5E.

### Signature Component — Cronograma "Sesión a sesión"
Timeline vertical con línea de conexión (3px arena), marcadores circulares numerados (azul = teórica, verde = práctica) con halo crema, y tarjeta por sesión con fecha, tipo y título. La sesión 1 (PainCafé) va destacada con borde y fondo terracota. Se genera por JS desde `SESIONES[]`. **Deuda de accesibilidad conocida:** hoy depende de JS (hay `<noscript>` de aviso, pero no fallback de contenido); ver Do's and Don'ts.

### Equidad / Nota comunitaria
Panel verde bruma con texto #0B6B5E y perspectiva de género/equidad explícita. Parte del sistema, no un añadido.

## 6. Do's and Don'ts

### Do:
- **Do** mantener el fondo base en crema (#FAF7F2) y reservar el blanco para tarjetas.
- **Do** usar cada color por su significado fijo: azul confianza, terracota acogida, verde movimiento.
- **Do** conservar 18px de base, touch de 56px, longitud de línea contenida (~56–75ch) y el foco ámbar de 4px: son requisitos AA, no estética negociable.
- **Do** emparejar serif (titulares/voz) con sans (lectura), nunca dos sans parecidas.
- **Do** garantizar que el contenido esencial y el CTA se entienden **sin JavaScript**.
- **Do** usar lenguaje inclusivo y sencillo (lectura fácil), una idea por bloque, metáforas concretas (la mochila, el detector de humo).

### Don't:
- **Don't** convertir esto en un **folleto clínico frío**: nada de estética aséptica, jerga médica ni listados burocráticos.
- **Don't** caer en **pharma/corporativo**: nada de stock photos genéricas ni tono de marketing de producto.
- **Don't** aplicar tells de **startup/SaaS**: gradientes de moda, "eyebrow" en mayúsculas sobre CADA sección por defecto, ni marcadores 01/02/03 como andamiaje (los números solo cuando el orden informa, como en el cronograma).
- **Don't** derivar a **wellness/espiritual**: nada de tonos místicos, "sanación" ni promesas mágicas que resten credibilidad clínica.
- **Don't** usar ámbar (#FFE08A) sobre fondos claros: solo funciona sobre el azul profundo del CTA.
- **Don't** usar franjas laterales de color (border-left/right >1px): la codificación va por chip de icono o punto de color, y siempre con significado.
- **Don't** prometer curación. La marca promete herramientas, movimiento seguro y compañía — "dolor no es daño".
