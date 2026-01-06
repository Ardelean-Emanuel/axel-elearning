# Axel eLearning Website Build Tasks

Build a mobile-first static website for "Axel eLearning" (Moodle™ development specialists for ANY Moodle version) using Tailwind CSS (CDN is ok) and minimal vanilla JS (menu toggle + smooth scroll).

## Deliverables

- `index.html`
- `portfolio.html`
- optional `styles.css` for background atmosphere (noise/pattern/glow)

---

## Brand/Positioning

Axel eLearning provides Moodle custom development & support across any Moodle version (legacy to latest). We build upgrade-safe plugins, integrations, reports, and themes; we also help with upgrades and rescue/refactors for legacy sites.

---

## Design Inspiration

Premium cinematic dark theme with warm orange/copper accents, layered gradients, subtle noise, glass panels. Strong hero typography.

---

## Shared Header/Footer

Shared header/footer across both pages.

### Nav Items (exact order):
- How We Work
- Services
- Showcase
- About Us
- Contact

### Right Side:
- Phone placeholder
- Primary CTA: "Request a Proposal"

### Nav Behavior:
- Links to anchors on `index.html`
- Showcase links to `portfolio.html`
- Mobile: hamburger menu with accessible interactions

---

## index.html Sections (in order)

### 1) Hero

- **H1:** "Custom Moodle Development & Support"
- **Subhead:** "Axel eLearning — Moodle specialists for any version."
- **Transparent paragraph:**
  - Fixed-price proposals + clear plan
  - Upgrade-safe approach (no core hacks where possible)
  - We work across legacy and modern Moodle; we can modernize and upgrade
- **Buttons:**
  - "Learn More" (scroll to How We Work)
  - "Request a Proposal" (scroll to Contact)
- **Mock dashboard:** Premium glass card with metrics (SVG/HTML), no external images

### 2) Stats Strip (4 items)

- "Any Moodle version"
- "Upgrade-safe plugins"
- "Fixed-price proposals"
- "Clear handover docs"

Use bold numerals or strong labels, but keep claims honest.

### 3) "Smooth Sailing Assurance" Panel

- **Transparent proposals:** scope, milestones, estimate, deliverables
- **Change control:** written approval + updated estimate
- **Communication cadence:** weekly updates + demo checkpoints

### 4) "Custom Craftsmanship" List

- Themes
- Activity modules, blocks, reports
- Local/admin plugins
- Integrations (SSO/CRM/HRIS/Payments via web services)
- Performance & stability fixes
- Legacy rescue + refactor

### 5) Services (3 pillars)

Each pillar includes what's included and what's excluded (transparency).

**A) Custom Development (Enterprise)**

**B) Maintenance & Support (SMB)**

**C) Upgrades & Legacy Modernization (any Moodle version)**

### 6) How We Work (4–5 steps with outputs)

1. **Discovery & audit** → Output: written scope + risks
2. **Proposal** → Output: fixed-price estimate + timeline
3. **Build** → Output: code + progress demos
4. **QA & review** → Output: test notes + acceptance criteria checklist
5. **Launch & handover** → Output: docs + training + support options

### 7) Mini "Showcase Preview" Section

Links to `portfolio.html`

### 8) Testimonials (3 quotes)

With realistic roles (no real brands)

### 9) FAQ

- How pricing works (fixed price + re-scope)
- Timelines
- NDA
- Support response time (provide a transparent range like "same/next business day", not guarantees)
- How you handle old Moodle versions
- Do you modify core? (answer: avoid; if unavoidable, disclose clearly)

### 10) Contact Section

- Phone placeholder
- **Short form fields:**
  - Name
  - Email
  - Moodle version (select: "Not sure / 1.9–2.x / 3.x / 4.x / Latest")
  - Message
  - NDA checkbox
- Privacy microcopy (GDPR-friendly)

### 11) Footer

- Company name: Axel eLearning
- Address placeholder
- Email + phone placeholder
- **Links:** How We Work / Services / Showcase / About / Contact
- **Moodle trademark disclaimer:**
  > "Moodle and associated Moodle logos are trademarks of Moodle Pty Ltd or its related affiliates."
- Privacy/terms placeholders

---

## portfolio.html Sections (in order)

### 1) Page Hero

- **Title:** "Projects Showcase"
- **Subhead:** "Unlocking Your Vision: Axel eLearning Portfolio"
- Transparent intro + CTA button linking to `index.html#contact`

### 2) Project List (4 projects)

Mark as "Example projects" if needed.

#### Project A: ICM — Implementing Complex Educational & Marketing Needs in Moodle
- Context
- What we built (bullets)
- Version/constraints (e.g., "Moodle 3.9 legacy → upgraded path", etc.)
- Outcome (clearly labeled placeholder metrics if unknown)
- Deliverables (code + docs + handover)

#### Project B: Roche Diagnostics — Streamlined User Management in Moodle
- Context
- What we built (bullets)
- Version/constraints
- Outcome
- Deliverables

#### Project C: Horizon Flight Academy — Moodle Plugin Rescue & Enhancement
- Context
- What we built (bullets)
- Version/constraints
- Outcome
- Deliverables

#### Project D: Ultimaker — Innovating 3D Printing Education with Moodle Customization
- Context
- What we built (bullets)
- Version/constraints
- Outcome
- Deliverables

### 3) "Portfolio Excellence" Copy Block (3 subsections)

Adapted to Axel eLearning:

- **Tailored Themes:** Branding → Functionality
- **Dynamic Learning Modules:** Curriculum → Delivery
- **Custom Plugins:** Tailored functionality + inline comments + external docs (transparency)

### 4) Final CTA Block

- "Ready to start?"
- Phone + button to `index.html#contact`

---

## Technical Requirements

- Extremely mobile friendly
- Visually premium
- Accessible (semantic HTML, labels, focus-visible styles)
- Touch targets >= 44px
- No horizontal scrolling
- Responsive typography (clamp) for hero headings
