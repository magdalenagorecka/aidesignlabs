---
name: Aetheris Insight
colors:
  surface: '#f7f9fb'
  surface-dim: '#d8dadc'
  surface-bright: '#f7f9fb'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f2f4f6'
  surface-container: '#eceef0'
  surface-container-high: '#e6e8ea'
  surface-container-highest: '#e0e3e5'
  on-surface: '#191c1e'
  on-surface-variant: '#494454'
  inverse-surface: '#2d3133'
  inverse-on-surface: '#eff1f3'
  outline: '#7b7486'
  outline-variant: '#cbc3d7'
  surface-tint: '#6d3bd7'
  primary: '#6b38d4'
  on-primary: '#ffffff'
  primary-container: '#8455ef'
  on-primary-container: '#fffbff'
  inverse-primary: '#d0bcff'
  secondary: '#a43073'
  on-secondary: '#ffffff'
  secondary-container: '#fc79bd'
  on-secondary-container: '#76014e'
  tertiary: '#006947'
  on-tertiary: '#ffffff'
  tertiary-container: '#00855b'
  on-tertiary-container: '#f5fff6'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#e9ddff'
  primary-fixed-dim: '#d0bcff'
  on-primary-fixed: '#23005c'
  on-primary-fixed-variant: '#5516be'
  secondary-fixed: '#ffd8e7'
  secondary-fixed-dim: '#ffafd3'
  on-secondary-fixed: '#3d0026'
  on-secondary-fixed-variant: '#85145a'
  tertiary-fixed: '#6ffbbe'
  tertiary-fixed-dim: '#4edea3'
  on-tertiary-fixed: '#002113'
  on-tertiary-fixed-variant: '#005236'
  background: '#f7f9fb'
  on-background: '#191c1e'
  surface-variant: '#e0e3e5'
  lavender-aura: '#E0E7FF'
  soft-pink: '#FCE7F3'
  mint-glass: '#D1FAE5'
  solar-yellow: '#FDE68A'
  ai-disclosure: '#6366F1'
  agentic-action: '#F59E0B'
typography:
  display-lg:
    fontFamily: Manrope
    fontSize: 48px
    fontWeight: '800'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Manrope
    fontSize: 32px
    fontWeight: '700'
    lineHeight: '1.2'
  headline-lg-mobile:
    fontFamily: Manrope
    fontSize: 28px
    fontWeight: '700'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Manrope
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.3'
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.5'
  label-caps:
    fontFamily: JetBrains Mono
    fontSize: 12px
    fontWeight: '600'
    lineHeight: '1'
    letterSpacing: 0.1em
  conversational-text:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '500'
    lineHeight: '1.5'
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  base: 8px
  container-max: 1280px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 64px
  stack-sm: 12px
  stack-md: 32px
  stack-lg: 80px
---

## Brand & Style

This design system is built for the "Future AI Designer"—a professional who balances strategic intelligence with creative intuition. The aesthetic sits at the intersection of **Minimalism** and **Glassmorphism**, creating a digital environment that feels lightweight, breathable, and advanced.

The brand personality is **Visionary, Empathetic, and Academic**. It avoids the aggressive "tech-black" of contemporary SaaS in favor of a bright, optimistic "vibe-design" approach. The interface should feel like a clear headspace: high-clarity typography, soft tactile elements, and a sense of "Immersive Spatiality" that suggests the UI is floating in a clean, well-lit studio.

The emotional response should be one of **calm focus and discovery**. As users navigate the diagnostic quiz, the system uses vibrant accents to highlight growth areas, making the educational journey feel like a reward rather than a test.

## Colors

The palette is anchored in a "High-Luminance Foundation." We use a near-white neutral (`#F8FAFC`) for large surfaces to maximize the "airy" feel. 

- **Primary (Lavender):** Used for primary actions and "Conductor" level interactions. It represents the fusion of design and technology.
- **Secondary (Soft Pink):** Used for emotive feedback and human-centric touchpoints.
- **Tertiary (Mint):** Reserved for success states and "Safe AI" disclosures.
- **Solar Yellow:** Inspired by the reference infographic, this is used sparingly for "Learning Sparks" and highlighting system-level tags.

**Semantic Philosophy:** 
Color is not just decorative but functional. The `ai-disclosure` indigo is used strictly when the system is displaying machine-generated content, ensuring transparency. The `agentic-action` gold indicates autonomous AI suggestions versus manual human inputs.

## Typography

The typography strategy prioritizes **Explainability and Persona**. 

**Manrope** is used for headlines to provide a structured, professional, and slightly futuristic geometric feel. It anchors the layout with authority.

**Plus Jakarta Sans** is the workhorse for body and conversational text. Its softer, more rounded terminals make long-form educational content feel approachable and friendly.

**JetBrains Mono** is used for technical metadata, "Agentic" status labels, and system-level tags (e.g., "AI TRANSFORMATION"). This provides a "Design Technologist" aesthetic, bridging the gap between code and craft.

**Special Treatment:** 
- *Conversational Level:* Dialogue from the AI diagnostic assistant uses a medium weight with slightly increased line height to differentiate it from standard UI labels.
- *Explainability Level:* Micro-copy regarding data privacy and AI ethics uses the `label-caps` style to ensure high visibility without cluttering the spatial layout.

## Layout & Spacing

This system utilizes a **Fluid Adaptive System** where whitespace is treated as a core component rather than "empty" space. 

The grid is a 12-column fluid system on desktop, but the content is often centered in a "Focus Column" of 800px for the diagnostic quiz to prevent eye-strain and improve cognitive load. 

**Adaptive Rules:**
- **Mobile:** Single column with 16px margins. Elements use a "Stack" verticality.
- **Tablet:** 8-column grid with increased gutters (24px) to allow the "Glassmorphic" layers to breathe.
- **Desktop:** Full 12-column grid. We use "Safe Area" padding of 80px (`stack-lg`) between major sections (e.g., the Question and the Progress visualization) to maintain the "Airy" feel.

Layout logic is driven by "Systemic Orchestration"—components should grow and shrink fluidly based on the length of AI-generated responses, never being clipped or forcing horizontal scrolls.

## Elevation & Depth

Hierarchy is conveyed through **Tonal Layering** and **Glassmorphism** rather than heavy shadows.

- **Level 0 (Base):** Neutral white background (`#F8FAFC`).
- **Level 1 (Cards):** Soft white surfaces with a 1px border of 5% opacity black. These use a very diffused, large-radius shadow (24px blur, 4% opacity) to feel as if they are hovering slightly above the base.
- **Level 2 (Overlays/Modals):** Glassmorphism with a `backdrop-filter: blur(12px)`. This is used for AI disclosures and human-in-the-loop interventions, ensuring the user remains aware of the context beneath the intervention.
- **Tonal Tiers:** We use the pastel named colors (Lavender Aura, Mint Glass) to create "Surface-Container Tiers" that group related questions or insights without adding physical borders.

## Shapes

The shape language is **"Rounded and Friendly"** to offset the technical nature of AI diagnostics. 

- **Standard Components:** 0.5rem (8px) corner radius for input fields and small buttons.
- **Large Containers/Cards:** 1rem (16px) corner radius to create a soft, approachable frame for the content.
- **Interactive Tags/Chips:** Full pill-shape (`rounded-full`) to distinguish them as clickable, bite-sized pieces of data.
- **Progress Indicators:** Soft, rounded caps on all bar charts and progress rings to maintain the "Tactile" organic feel.

## Components

### Buttons
Primary buttons use a solid Lavender (`#8B5CF6`) with white text, featuring a subtle "squishy" press effect (scaling to 0.98 on active state). Secondary buttons are ghost-styled with a Lavender outline or a Soft Pink background for "Emotive" actions.

### Chips & Tags
Inspired by the "Future of UX" infographic, tags for skills (e.g., "AI FLUENCY") use the Solar Yellow (`#FDE68A`) background with dark mono-text. They have a 1px solid border to keep them crisp against light backgrounds.

### Diagnostic Cards
Quiz questions are housed in "Airy Cards" with 32px internal padding. They use a light-grey border (`#E2E8F0`) that transitions to a Primary Lavender glow when the question is "Active."

### Progress & Feedback
Visual indicators of the user's "AI Persona" development should use "Vibrant Gradients" (Lavender to Pink) within rounded tracks. 

### Input Fields
Clean, minimal fields with a focus on typography. The focus state does not just change border color but adds a soft "Mint Glass" glow to indicate a "Safe/Ready" state for user input.

### AI Disclosures
A specific "Informed Consent" component using the `ai-disclosure` indigo. It features a small "Sparkle" icon to denote generative logic, ensuring the user is always aware of the "Human-in-the-loop" status.