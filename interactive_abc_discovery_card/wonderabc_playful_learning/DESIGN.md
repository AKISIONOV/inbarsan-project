---
name: WonderABC Playful Learning
colors:
  surface: '#f9f9ff'
  surface-dim: '#cbdafc'
  surface-bright: '#f9f9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f1f3ff'
  surface-container: '#e8eeff'
  surface-container-high: '#dfe8ff'
  surface-container-highest: '#d7e3ff'
  on-surface: '#0b1b35'
  on-surface-variant: '#3e4850'
  inverse-surface: '#21304b'
  inverse-on-surface: '#ecf0ff'
  outline: '#6e7881'
  outline-variant: '#bdc8d2'
  surface-tint: '#006590'
  primary: '#006590'
  on-primary: '#ffffff'
  primary-container: '#2bb8ff'
  on-primary-container: '#004665'
  inverse-primary: '#88ceff'
  secondary: '#7c5800'
  on-secondary: '#ffffff'
  secondary-container: '#feb700'
  on-secondary-container: '#6b4b00'
  tertiary: '#b2196c'
  on-tertiary: '#ffffff'
  tertiary-container: '#ff87b8'
  on-tertiary-container: '#83004c'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#c8e6ff'
  primary-fixed-dim: '#88ceff'
  on-primary-fixed: '#001e2e'
  on-primary-fixed-variant: '#004c6e'
  secondary-fixed: '#ffdea8'
  secondary-fixed-dim: '#ffba20'
  on-secondary-fixed: '#271900'
  on-secondary-fixed-variant: '#5e4200'
  tertiary-fixed: '#ffd9e4'
  tertiary-fixed-dim: '#ffb0cd'
  on-tertiary-fixed: '#3e0021'
  on-tertiary-fixed-variant: '#8d0052'
  background: '#f9f9ff'
  on-background: '#0b1b35'
  surface-variant: '#d7e3ff'
typography:
  display-hero:
    fontFamily: Comfortaa
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
  display-hero-mobile:
    fontFamily: Comfortaa
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
  headline-lg:
    fontFamily: Comfortaa
    fontSize: 36px
    fontWeight: '700'
    lineHeight: 44px
  headline-lg-mobile:
    fontFamily: Comfortaa
    fontSize: 26px
    fontWeight: '700'
    lineHeight: 34px
  headline-md:
    fontFamily: Comfortaa
    fontSize: 24px
    fontWeight: '700'
    lineHeight: 32px
  headline-sm:
    fontFamily: Comfortaa
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
  body-lg:
    fontFamily: Quicksand
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 30px
    letterSpacing: 0.02em
  body-md:
    fontFamily: Quicksand
    fontSize: 18px
    fontWeight: '500'
    lineHeight: 26px
    letterSpacing: 0.01em
  body-sm:
    fontFamily: Quicksand
    fontSize: 15px
    fontWeight: '600'
    lineHeight: 22px
  phonics-callout:
    fontFamily: Comfortaa
    fontSize: 40px
    fontWeight: '700'
    lineHeight: 48px
    letterSpacing: 0.08em
  label-lg:
    fontFamily: Quicksand
    fontSize: 16px
    fontWeight: '700'
    lineHeight: 22px
    letterSpacing: 0.03em
  label-md:
    fontFamily: Quicksand
    fontSize: 14px
    fontWeight: '700'
    lineHeight: 18px
    letterSpacing: 0.02em
  label-sm:
    fontFamily: Quicksand
    fontSize: 12px
    fontWeight: '700'
    lineHeight: 16px
rounded:
  sm: 0.5rem
  DEFAULT: 1rem
  md: 1.5rem
  lg: 2rem
  xl: 3rem
  full: 9999px
spacing:
  touch-min: 3.5rem
  touch-lg: 4.5rem
  space-2xs: 0.25rem
  space-xs: 0.5rem
  space-sm: 0.75rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2rem
  space-2xl: 3rem
  gutter-mobile: 1rem
  gutter-tablet: 1.5rem
  gutter-desktop: 2rem
  margin-mobile: 1rem
  margin-tablet: 2rem
  margin-desktop: 3rem
---

## Brand & Style

This design system is crafted specifically for early-stage learners aged 6 to 10. The brand experience embodies curiosity, joy, empowerment, and gentle guidance. Every interaction should feel like opening an illustrated storybook or exploring an interactive toy chest: tactile, responsive, and delightfully animated.

The visual direction leans into a **Playful Tactile & Toy-like Neo-Skeuomorphic** style. Rather than relying on flat digital abstraction, elements feature soft pillowy extrusions, candy-coated depth, plump borders, and dimensional drop-shadows that invite immediate physical touch. The UI prioritizes cognitive clarity for developing readers by reducing visual noise, using explicit visual cues, high-contrast text layers, and celebratory micro-interactions.

## Colors

The palette is candy-toned, optimistic, and saturated without inducing fatigue. Contrast ratios adhere strictly to WCAG AA/AAA standards across all educational reading surfaces.

- **Primary (`#2BB8FF` - Sky Blue):** The dominant exploration color. Used for primary navigation paths, lesson maps, character dialog boxes, and interactive water elements.
- **Secondary (`#FFB800` - Sunshine Yellow):** The celebratory currency color. Applied to stars, reward points, active streaks, and primary positive reinforcement triggers. Pair with deep plum or navy text for legibility.
- **Tertiary (`#FF5CA8` - Bubblegum Pink):** The high-delight accent. Used for interactive discovery buttons, unlocked stickers, and phonics emphasis markers.
- **Quaternary Accents:**
  - *Lime Mint Green (`#1DD38D`):* Correct answers, mastery badges, audio pronunciation active states.
  - *Electric Violet (`#8B5CF6`):* Magic moments, bonus levels, grammar tooltips.
  - *Tangerine Orange (`#FF7828`):* High-energy action buttons, audio speaker triggers, urgent challenges.
- **Neutrals:**
  - *Background Canvas (`#F4F9FF`):* Soft tinted cloud white to reduce glare during prolonged screen time.
  - *Surface White (`#FFFFFF`):* Crisp card foregrounds to maximize child illustration visibility.
  - *Ink Navy (`#2B3A55`):* Deep rounded navy for all text, avoiding harsh true blacks.
  - *Muted Slate (`#7E8FA8`):* Subordinate instructional hints and inactive states.

## Typography

Typography prioritizes letterform differentiation for emerging readers. **Comfortaa** provides open, rounded geometric display headlines that feel non-intimidating and warm. **Quicksand** delivers clear baseline clarity and distinct ascenders/descenders, preventing character confusion (such as lowercase 'l', uppercase 'I', and digit '1').

- **Tracking & Spacing:** Body copy uses slightly enlarged letter spacing (`0.01em` to `0.02em`) to aid dyslexic readers and early decoders.
- **Phonics Callout:** Dedicated style with loose tracking (`0.08em`) specifically crafted for spelling modules, sound blending, and syllabic breaking.
- **All Caps Usage:** Prohibited in long instructions; restricted solely to single-word badges or initial alphabet recognition tiles.

## Layout & Spacing

Younger children interact via rough motor control, two-handed thumb grips on tablets, or imprecise finger taps. Layouts emphasize spacious tap-targets and physical safety margins.

- **Touch Target Floor:** The absolute minimum interactive target is `3.5rem` (56px), with preferred button sizes reaching `4.5rem` (72px) for critical progress buttons.
- **Grid Structure:**
  - **Mobile (portrait, <768px):** 4-column fluid layout, single main interactive card per viewport to maintain undivided attention.
  - **Tablet (portrait & landscape, 768px - 1024px):** 8-column layout. Optimal zone for learning games, featuring a permanent left or bottom audio/progress shelf.
  - **Desktop / Web Interactive Whiteboards (>1024px):** 12-column layout constrained to a maximum content width of 1200px to maintain accessible focal focus.
- **Spacing Rhythm:** Built on an `8px` baseline rhythm. Spacing between interactive tiles must never drop below `1rem` (16px) to avoid accidental mis-taps.

## Elevation & Depth

To provide immediate physical understanding of pressable objects, this design system uses **Tactile 3D "Push-Down" Drop Elevations** rather than ethereal blurred shadows.

- **Base Interactive Elevation (Level 1):** Solid unblurred directional drop (`0px 6px 0px`) tinted 25% darker than the component's base hue. When pressed or clicked, the element physically offsets `translateY(4px)` and the shadow shrinks to `0px 2px 0px`, simulating an arcade push button.
- **Floating Island Elevation (Level 2):** Applied to challenge cards, dialog bubbles, and modal quests. Uses a combination of a colored grounding shelf (`0px 8px 0px #E1ECF8`) paired with an ambient soft glow (`0px 16px 32px rgba(43, 58, 85, 0.08)`).
- **Celebratory Pop Elevation (Level 3):** Reserved for newly unlocked badges, floating audio prompts, and level rewards. Employs an ambient aura matched to the element's primary color (e.g., `#FFB800` star utilizes `0px 12px 28px rgba(255, 184, 0, 0.45)`).
- **Inner Rim Lighting:** All cards and interactive tiles utilize an inset 2px high-opacity white border (`inset 0px 2px 0px rgba(255, 255, 255, 0.65)`) to produce a glossy, candy-like bevel.

## Shapes

The design system uses high-radius **Pill-shaped (Level 3)** geometry. Sharp edges and acute angles are entirely eliminated to foster an emotionally safe, approachable, and friendly atmosphere.

- Standard buttons and navigation chips are rendered with full pill radiuses (`9999px` or `2rem`).
- Cards, challenge containers, and dialog panels use smooth `1.5rem` to `2rem` outer radii.
- Progress bars, input wells, and slider tracks feature rounded caps with hemispherical ends.
- Visual badges, counters, and avatar rings maintain strict circular or squircle proportions.

## Components

### Buttons
- **Hero "Chunky Action" Button:** Full pill shape, height 64px–72px. Background in Tangerine Orange (`#FF7828`) or Lime Mint (`#1DD38D`) with a 6px solid bottom lip in a matching deep shadow tone. Text is white, heavy-weight Quicksand with an optional tactile push-down bounce animation on click.
- **Audio Cue Button:** Circular floating button (minimum 64px) in Sky Blue (`#2BB8FF`) housing a high-contrast white speaker icon with animated concentric soundwaves during speech playback. Includes tactile haptic visual state (`scale(1.08)`).

### Interactive Phonics & Flash Cards
- Rendered on a pure white surface with a 3px border tinted `#E4F0FB`.
- Features an illustration area, oversized letter callout, and an embedded pronunciation audio badge in the top-right corner.
- Tapping triggers a playful 3D rotation flip or a bounce squish that reveals the phonics phonetic breakdown.

### Chips & Tags
- Pill-shaped labels with soft tinted backgrounds (15% color opacity) and deep colored text. Used to categorize lessons ("Vowels", "Sight Words", "Animal Phonics").
- Inactive tags have a subtle dashed outline; active tags become saturated with a solid bottom lip.

### Checkboxes & Choice Selectors
- Replaced by large selectable "Bouncy Blocks" instead of standard tiny form controls.
- Correct selection illuminates with Lime Mint Green and a popping checkmark badge; incorrect selections shake gently with a non-punitive cloud-grey outline.

### Input Fields
- Generously padded (`18px 24px`), large rounded borders (20px radius), pale blue background (`#F4F9FF`), and deep Navy ink.
- Focus state expands a 4px sunshine-yellow outer glow without harsh black borders.

### Interactive Reward Stars & Progress Trackers
- **Star Counter:** Squircle-shaped sunshine badge with a continuous gentle float keyframe. Each earned star triggers an explosion of confetti particles and an ascending chime sound.
- **Progress Trackers:** Styled as a winding gameboard path across whimsical terrain (clouds, islands, tree canopies) using thick pill segments that fill with animated gradient liquid upon completion.

### Dialogue & Helper Companions
- Soft conversational speech bubbles with a bottom-curved tail pointing to the on-screen animated mascot.
- Accompanied by integrated speed control and replay audio buttons directly attached to the bubble border.