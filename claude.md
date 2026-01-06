<frontend_aesthetics>
Create a premium, distinctive landing page inspired by a cinematic dark/orange dev-studio design:
- Deep dark background with layered gradients, subtle noise, vignette edges
- Warm orange/copper accents, glassy panels, 1px borders, soft glow
- Dramatic typography hierarchy and confident spacing
Avoid generic "AI agency" visuals or purple gradients.
Avoid Inter/Roboto/system fonts. Pick two distinctive Google Fonts and use them consistently.
</frontend_aesthetics>

<mobile_first>
Mobile is not an afterthought. Design mobile-first:
- Sticky nav with hamburger menu (accessible)
- Touch targets >= 44px
- No horizontal scrolling
- Cards stack cleanly; spacing is comfortable
- Use responsive typography (clamp) for hero headings
</mobile_first>

<content_transparency>
Tone: transparent, specific, and trustworthy. Avoid vague claims.

Must explicitly explain:
- Supported Moodle versions: "any Moodle version" (legacy to latest) and how we handle upgrades
- Upgrade-safe approach: no core hacks; we extend via plugins/themes where possible
- Fixed-price proposals: what inputs are needed, what's included, what triggers re-scope
- QA: code review, testing approach (where applicable), acceptance criteria, handover
- Security/privacy: capability checks, secure coding, data handling; GDPR-friendly contact
If a claim is made, back it with a concrete mechanism or measurable statement.
</content_transparency>

<build_rules>
Build a static website using Tailwind CSS (CDN is ok) and minimal vanilla JS only for:
- mobile menu toggle
- smooth scrolling
Everything must be responsive and accessible:
- semantic HTML
- labels for inputs
- focus-visible styles
Deliver files:
- index.html
- portfolio.html
- optional styles.css for background/noise utilities
No external images required; use inline SVG icons and gradient mock panels.
</build_rules>
