# Prompt for nano banana pro: Atomic Design Hierarchy Image

## Image Specifications

**Dimensions & Aspect Ratio:**
- Width: 1920px
- Height: 1080px
- Aspect Ratio: 16:9 (standard Slidev presentation format)
- DPI: 150+ for crisp display

## 3lectrify Design System

### Color Palette (MUST USE EXACTLY):

**Primary Colors:**
- Middle Green: `#88C0B1` (PRIMARY brand color - use for highlights, titles)
- Orange: `#D04227` (CTA color - use for accents, emphasis)
- Deep Blue: `#293645` (Main background color)
- Dark Blue: `#3C5067` (Card/component backgrounds)

**Secondary Colors:**
- Light Green: `#C5E0D7` (Light accents)
- Blue Grey: `#5F8299` (Borders, subtle elements)
- White: `#FFFFFF` (Text, light elements)
- Light Grey: `#C2C2C2` (Secondary text)

### Typography:
- Font Family: **Lato** (or similar modern sans-serif if unavailable)
- Font Weights: Light (300), Regular (400), Bold (700)
- Text should be clean, modern, readable

### Design Primitives & Component Style:

**Buttons:**
- Background: `#88C0B1` (middle green)
- Text: White or dark
- Border radius: 20px (rounded corners)
- Padding: Generous (16px vertical, 32px horizontal)
- Font: Bold Lato

**Cards:**
- Background: `#3C5067` (dark blue)
- Border radius: 20px
- Subtle shadow or border: `#5F8299`
- Padding: 24-32px

**Input Fields:**
- Background: Lighter than cards (`#5F8299` or white with transparency)
- Border: 2px solid `#88C0B1` or `#5F8299`
- Border radius: 12px
- Placeholder text: `#C2C2C2`

**Icons:**
- Style: Simple, modern, outlined or filled
- Color: `#88C0B1` (green) or `#D04227` (orange)
- Size: Consistent, proportional

**Overall Style:**
- Modern, clean, professional tech aesthetic
- Generous spacing and breathing room
- Subtle gradients acceptable (blue tones)
- No harsh shadows - keep it flat/modern

## Content & Layout Requirements

### Structure (Left to Right Flow):

Show 5 levels of Atomic Design hierarchy:

1. **ATOMS**
   - Icon: Simple atomic/circle symbol in `#88C0B1`
   - Example: Single button component, single input field, label, icon
   - Visual: Smallest, isolated elements
   - Background: `#3C5067` card

2. **MOLECULES**
   - Icon: Connected nodes/molecular structure in `#88C0B1`
   - Example: Search bar (input + button + icon combined)
   - Visual: 2-3 atoms combined into functional group
   - Background: `#3C5067` card
   - Show visual connection/combination from atoms

3. **ORGANISMS**
   - Icon: Network/organism symbol in `#D04227` (orange for emphasis)
   - Example: Navigation header OR Login form (multiple molecules combined)
   - Visual: Complex card with header, form fields, buttons
   - Background: `#3C5067` card
   - Show it's built from molecules + atoms

4. **TEMPLATES**
   - Icon: Wireframe/layout symbol in `#88C0B1`
   - Example: Page layout structure (header placeholder, content area, sidebar)
   - Visual: Wireframe-style page layout with organism placeholders
   - Background: `#293645` (slightly different to show it's a container)
   - Show grid/layout structure

5. **PAGES**
   - Icon: Document/page symbol in `#D04227`
   - Example: Complete page with real content (dashboard with data, filled forms)
   - Visual: Full, realistic page with actual content
   - Background: `#293645` with content in `#3C5067` cards
   - Show it's the template filled with real data

### Visual Flow & Arrows:

- Connect each level with RIGHT-POINTING ARROWS (`→`) in `#88C0B1`
- Arrows should be thick, clear, modern style
- Show progression: Atoms → Molecules → Organisms → Templates → Pages

### Labels:

- **Label Position:** Above or below each component/level
- **Label Style:**
  - Font: Lato Bold
  - Color: `#FFFFFF` (white)
  - Size: Large enough to read (18-24px equivalent)
- **Label Text:**
  - "ATOMS"
  - "MOLECULES"
  - "ORGANISMS"
  - "TEMPLATES"
  - "PAGES"

### Additional Visual Cues:

- Show **increasing complexity** from left to right (atoms small → pages large/complete)
- Use **consistent 3lectrify card style** (rounded corners, dark blue backgrounds)
- Add subtle **visual hierarchy**: earlier stages lighter/simpler, later stages more detailed
- Include small **code brackets** `{ }` or design symbols where appropriate
- Keep background clean: `#293645` (deep blue) with subtle texture acceptable

## Style Reference:

Think: **Modern SaaS design system illustration** meets **tech startup presentation**

**DO:**
- Use exact hex colors from 3lectrify palette
- Keep it clean, modern, professional
- Show clear visual progression
- Use generous spacing
- Make it visually scannable at a glance

**DON'T:**
- Use generic design system colors
- Make it too detailed/busy
- Use harsh shadows or gradients
- Use fonts other than Lato (or close sans-serif)
- Obscure the hierarchy

## Example Component Visuals to Include:

### Atoms (show 2-3):
- Green button: `#88C0B1` background, white text, 20px border radius
- Input field: White/transparent background, green border
- Small icon in green

### Molecules (show 1):
- Search bar: Input field + button + search icon, all combined seamlessly

### Organisms (show 1):
- Login form card:
  - Dark blue card background `#3C5067`
  - Heading: "Login" in white
  - 2 input fields (email, password)
  - Green button `#88C0B1` "Submit"
  - Border radius 20px on card

### Templates:
- Wireframe layout showing header, sidebar, content area
- Use lighter blue/grey outlines `#5F8299`

### Pages:
- Complete dashboard view with navigation, filled charts/content
- Use full color, realistic content

## Output Format:

- PNG format, transparent or `#293645` background
- High resolution (1920x1080px minimum)
- Optimized for web display
- Clean, crisp edges (no compression artifacts)

---

**Goal:** Create a visually stunning, brand-aligned representation of Atomic Design that clearly shows the building-block progression from smallest elements (atoms) to complete interfaces (pages), using the exact 3lectrify design system colors and style primitives.
