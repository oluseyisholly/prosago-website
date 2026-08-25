# Prosago Works — Repository Instructions

This repository represents **Prosago Works**, the parent technology company.

The approved Prosago Works Brand Guidelines are the single source of truth for corporate brand expression. When implementing UI, copy, layouts, assets, marketing pages, documentation, or other customer-facing surfaces, follow these instructions and the approved brand assets exactly.

If a task conflicts with the approved brand system, do not silently improvise. Preserve the brand system and flag the conflict.

---

## 1. Brand Positioning

Prosago Works is a B2B technology parent company that builds intelligent, dependable platforms for operationally intensive businesses.

Core idea:

> **Foundations for what's next.**

Supporting descriptor:

> Prosago Works builds intelligent, dependable technology for growing businesses.

Brand promise:

> Prosago Works builds technology that makes business easier to understand, manage and grow — never technology customers have to work around.

The company is intended to grow into a technology group spanning business software, AI, cloud services, infrastructure, and future products.

Do not position Prosago Works as a single-product startup.

---

## 2. Brand Personality

The brand should feel:

- Intelligent
- Dependable
- Ambitious
- Clear
- Human
- Precise
- Forward-looking

Maintain these tensions:

- Ambitious without arrogance
- Intelligent without coldness
- Dependable without becoming boring

Avoid communication or design that feels:

- Jargon-heavy
- Vague
- Boastful
- Corporate-stiff
- Gimmicky
- Hype-driven
- Trend-chasing

---

## 3. Brand Values

Product, engineering, UI, and copy decisions should support these principles:

- **Purposeful Innovation** — technology must solve a real problem and create measurable value.
- **Reliability** — systems should hold up under real operating conditions.
- **Simplicity** — absorb complexity rather than passing it to users.
- **Integrity** — never claim capabilities that do not exist.
- **Security & Responsibility** — protect customer data and access by design.
- **Customer Understanding** — decisions should reflect real operational experience.
- **Long-Term Thinking** — build for durability rather than short-term trends.
- **Progress** — products should move users measurably forward.

---

## 4. Brand Architecture

Prosago Works uses an **endorsed brand architecture**.

### Corporate-owned environments

Examples:

- Prosago Works corporate website
- Investor materials
- Recruitment
- Partnerships
- Media communications
- Company presentations
- Ecosystem overviews

In these environments:

1. **Prosago Works leads.**
2. Products appear as members of the portfolio.
3. Product brands must never visually compete with Prosago Works at equal weight.

### Product-owned environments

Examples:

- Product websites
- Product apps
- Product onboarding
- Product dashboards
- Product documentation
- Product marketing

In these environments:

1. The product identity leads.
2. Prosago Works appears only as a subtle endorsement.
3. Approved endorsement formats include:
   - `Product Name — by Prosago Works`
   - `Built by Prosago Works`
   - `Powered by Prosago Works` when technically appropriate

The endorsement must remain visually subordinate to the product identity.

### Critical rule

Do **not** force the Prosago Works corporate visual identity onto independent product brands.

Products may have their own colour palette, illustration style, iconography, photography, messaging, and interface language.

What products inherit from Prosago Works is quality, usability, accessibility, engineering excellence, customer-centred thinking, reliability, and long-term scalability — not identical visual branding.

---

## 5. Logo Rules

Always use official logo assets supplied by the brand designer.

Do not recreate the logo from screenshots, the PDF, text, CSS, SVG approximations, or hand-drawn paths when official assets are available.

Approved logo forms include:

- Logomark
- Logotype
- Full logo
- Horizontal logo
- Vertical logo
- Badge logo

### Preferred digital use

- Use the **horizontal logo** in wide website headers where appropriate.
- Use the **logomark** for favicons, compact navigation, social avatars, and other constrained spaces where the brand is already established.
- Use the full or vertical lockup only where the available space suits it.

### Minimum digital sizes

- Logomark: **50px minimum**
- Logotype: **150px minimum**
- Full logo: **150px minimum**

### Clearspace

Always preserve the protected clearspace defined in the approved logo system. Do not crowd the logo with navigation, text, buttons, imagery, or decorative elements.

### Never

- Stretch or skew the logo
- Rotate the logo
- Re-colour individual logo elements arbitrarily
- Add drop shadows or visual effects
- Add strokes
- Modify the geometry
- Rearrange lockup components
- Recreate a custom logo variation without approval

### Monochrome use

When a one-colour logo is required, use only:

- Base Black
- Pure White

Choose the version that provides sufficient contrast with the background.

---

## 6. Typography

### Primary typeface

**DM Sans**

Use DM Sans throughout the corporate web experience wherever possible.

### Supporting/substitute typeface

**Montserrat**

Use Montserrat only when DM Sans is unavailable or where the brand guidelines explicitly permit a secondary voice.

### Fallback stack

Use:

```css
font-family: "DM Sans", "Montserrat", "Helvetica Neue", Arial, "Segoe UI", sans-serif;
```

### Hierarchy

Use the following as the baseline web typography system:

- **H1** — DM Sans Bold 700 — 40–56px
- **H2** — DM Sans Medium/Semibold — 28–36px
- **H3** — DM Sans Medium 500 — 20–24px
- **Body** — DM Sans Regular 400 — 16px
- **Caption / Label** — DM Sans Regular/Medium — 12–13px
- **Data / Tabular** — DM Sans Regular/Medium — 14–16px with tabular numerals where appropriate

Digital interfaces should not use readable UI text below **13px**.

Use line-height of at least **1.4× font size** for interface text unless a specific approved design calls for a tighter display treatment.

Do not substitute unrelated typefaces for visual novelty.

---

## 7. Corporate Colour System

Use the approved colour palette only.

### Core accent

- **Reddish Orange** — `#FF481E`

Reddish Orange is the brand's distinctive high-energy accent. Use it deliberately and sparingly so it retains impact.

### Core neutrals

- **Deep Slate Blue** — `#132F3F`
- **Warm Sand** — `#D9B89C`
- **Platinum** — `#E2E2E0`
- **River Bed** — `#484D53`
- **Base Black** — `#000000`
- **Pure White** — `#FFFFFF`

Do not invent new primary brand colours without explicit approval.

### Light-mode mapping

Use this as the default corporate light theme:

- Page background → Pure White
- Surface/card background → Platinum
- Primary text → Base Black
- Secondary/muted text → River Bed
- Border/divider → Platinum, darkened 10–15% only if needed for visibility
- Accent/interactive → Reddish Orange

### Dark-mode mapping

Use this as the default corporate dark theme:

- Page background → Deep Slate Blue
- Surface/card background → River Bed
- Primary text → Pure White
- Secondary/muted text → Platinum
- Border/divider → River Bed, lightened 10–15% only if needed
- Accent/interactive → Reddish Orange

### Governing contrast rule

When **Reddish Orange** is used as a background, small body text should default to **Base Black** unless an approved design demonstrates sufficient contrast otherwise.

Accessibility and legibility take precedence over decorative colour usage.

### Product-brand restriction

Reddish Orange, Base Black, and Pure White are reserved for Prosago Works corporate identity and endorsement use.

Independent product brands must **not** adopt Reddish Orange as their own primary or hero colour.

---

## 8. UI and Layout Direction

The Prosago Works corporate interface should feel:

- Structured
- Clean
- Confident
- Modern
- Calm
- Highly legible
- Professional without feeling cold

Prefer:

- Strong whitespace
- Clear visual hierarchy
- Simple navigation
- Well-defined sections
- Restrained use of the orange accent
- Balanced neutral surfaces
- Layouts that feel intentionally engineered rather than decorative

Avoid:

- Excessive gradients
- Overuse of orange
- Busy SaaS-template patterns
- Decorative glassmorphism used only because it is fashionable
- Overly playful shapes that weaken the dependable B2B character
- Generic "startup" visual clichés
- Excessive animations

Motion, if used, should reinforce hierarchy, clarity, state changes, or system relationships rather than exist as decoration.

---

## 9. Photography Direction

Prosago Works photography should use:

- Cool, controlled lighting
- Structured compositions
- Real operational environments
- Genuine technology use
- People who appear competent, calm, and believable

Avoid:

- Warm/golden lifestyle filters
- Generic startup-office stock photography
- Overly staged corporate scenes
- Unrealistically polished workplace imagery
- Photos where Reddish Orange dominates the entire frame

Reddish Orange may appear as a deliberate accent inside photography but should not overwhelm the image.

---

## 10. Illustration Direction

Approved corporate illustration style:

- Hand-drawn monoline appearance
- Black linework
- Slight variation in line weight
- Semi-isometric perspective
- Loose construction/sketch lines may remain visible
- Dashed elliptical orbit motifs may be used to suggest connectivity, motion, and systems in progress
- Reddish Orange is limited to approximately 1–2 accent fills in an illustration

Do not fully recolour illustrations orange.

Do not introduce a radically different illustration family without approval.

---

## 11. Iconography

Corporate iconography should follow these rules:

- Base grid: **24×24px** or **48×48px at 2×**
- Use one consistent stroke weight across the icon set
- Corners should be rounded in a manner compatible with the logo geometry
- Default to outline icons
- Solid Reddish Orange may be used for one accent element only
- Do not mix outline, filled, and duotone icon systems within the same experience
- Minimum practical icon size: **16px**
- Simplify an icon instead of shrinking a complex icon below legibility

Prefer a single coherent icon library or custom icon set rather than mixing unrelated libraries.

---

## 12. Patterns and Supporting Graphics

Use only approved Prosago Works supporting patterns or faithfully reproduced approved assets.

The brand system includes repeating geometric patterns derived from the Prosago Works visual language, including logomark-based and rounded-grid motifs.

Use patterns as supporting texture, never as the primary source of visual hierarchy.

Do not place dense patterns directly behind important body copy unless readability remains excellent.

---

## 13. Brand Voice

Corporate copy must be:

- Clear and direct
- Confident
- Warm and human
- Precise
- Forward-looking

Use plain, concrete language over abstract technology buzzwords.

Use short, confident headlines and more explanatory body copy.

Never oversell a capability the company or product does not yet have.

Small, dry humour is acceptable when appropriate, but never at the customer's expense.

Use:

- **Second person** (`you`, `your business`) for customer-facing copy
- **First person plural** (`we`) for Prosago Works brand statements

Avoid:

- Empty superlatives
- "Revolutionary" / "game-changing" style hype without evidence
- Excessive AI buzzwords
- Dense technical jargon in customer-facing content
- Claims that cannot be supported

---

## 14. Messaging Pillars

Where appropriate, corporate website copy should reinforce these ideas:

1. **Built from understanding, not assumption** — products reflect how businesses actually operate.
2. **Dependable by design** — reliability, security, and responsible data handling are built in.
3. **Built to scale with you** — technology should grow with the organisation.
4. **Clarity over complexity** — powerful systems should remain easy to use.

---

## 15. Approved Messaging Library

Use these approved lines when they fit the context. Do not force them into every page.

### Corporate / parent brand

- Foundations for what's next.
- Built to grow with you.
- Technology that grows the way your business does.
- Intelligent systems. Real business.
- We build the foundations. You build what's next.
- Where operations become possibilities.

### Trust & reliability

- Dependable technology for demanding operations.
- Reliable systems. Confident businesses.
- Clarity, even when the day isn't.

### Ambition & growth

- From one product to a whole ecosystem.
- We're not building a product. We're building a foundation.
- Grow without outgrowing your tools.

### Approved CTA language

- Start Growing Today
- Book Your Demo
- Talk To Us
- Explore The Platform
- Get Early Access
- Join The Ecosystem
- See The Difference
- Take Back Control
- Grow With Confidence
- Meet Prosago Works

Do not invent louder or more aggressive CTAs unless a product requirement specifically calls for them.

---

## 16. Website Content Hierarchy

For the **Prosago Works corporate website**, the company should be presented as the primary identity.

The site should communicate:

- What Prosago Works is
- Why it exists
- Its long-term vision
- Its operating philosophy
- Its products and portfolio
- Its reliability and security mindset
- Its capability to build and scale technology businesses
- Its relationship with partners, investors, future hires, and customers

Products such as **BusBud** should be presented as portfolio companies/products created by Prosago Works, not as the identity of Prosago Works itself.

The corporate site should answer the credibility question:

> Is this a company built to last and capable of growing into something larger than what exists today?

---

## 17. UX Principles

Where the brand guidelines do not prescribe exact component behaviour, follow these implementation principles:

- Prefer clarity over cleverness.
- Keep navigation predictable.
- Reduce unnecessary user decisions.
- Use familiar interaction patterns.
- Make important actions visually obvious.
- Provide clear hover, focus, active, disabled, loading, empty, success, and error states.
- Maintain keyboard accessibility.
- Use semantic HTML.
- Provide visible focus states.
- Do not communicate state using colour alone.
- Ensure responsive behaviour from mobile through large desktop.
- Preserve readable line lengths for long-form text.

These are implementation defaults and should not override an approved visual design.

---

## 18. Responsive Design

Every page and component must be designed and tested for:

- Mobile
- Tablet
- Laptop
- Desktop
- Large desktop

Do not treat mobile as a compressed desktop layout.

On smaller screens:

- Preserve brand hierarchy
- Maintain logo clearspace
- Reduce decorative content before reducing readability
- Keep tap targets accessible
- Stack layouts logically
- Maintain readable typography

---

## 19. Accessibility

Accessibility is part of Prosago Works' design quality standard.

At minimum:

- Use semantic HTML
- Ensure keyboard navigation works
- Use descriptive alt text for meaningful imagery
- Mark decorative imagery appropriately
- Maintain sufficient colour contrast
- Associate labels with form fields
- Preserve visible focus indicators
- Avoid inaccessible hover-only interactions
- Respect reduced-motion preferences where animations exist

Do not use the brand palette in ways that make content unreadable.

---

## 20. Asset Handling

Use official supplied assets wherever possible.

Expected asset categories may include:

- Corporate logos
- Logomark
- Badge mark
- Approved patterns
- Illustrations
- Photography
- Icons

If the repository does not contain a required official asset:

1. Do not recreate it from the brand guideline PDF unless explicitly instructed.
2. Use a clearly marked placeholder only when necessary for implementation.
3. Flag the missing asset in the task summary.

Never embed screenshots of the brand guideline as production website assets.

---

## 21. CSS / Design Token Guidance

When implementing the corporate brand, define reusable tokens rather than scattering raw values across components.

A baseline token set should represent:

```css
--pw-orange: #FF481E;
--pw-slate: #132F3F;
--pw-sand: #D9B89C;
--pw-platinum: #E2E2E0;
--pw-river-bed: #484D53;
--pw-black: #000000;
--pw-white: #FFFFFF;
```

Prefer semantic aliases on top of these primitives, for example:

```css
--color-bg;
--color-surface;
--color-text;
--color-text-muted;
--color-border;
--color-accent;
```

Do not hard-code brand colours repeatedly inside individual components when a shared token can be used.

---

## 22. Component Rules

When a design system/component library exists in the repository:

- Reuse existing components before creating new ones.
- Extend existing variants instead of duplicating components.
- Preserve a consistent spacing and typography system.
- Avoid one-off inline styles unless technically necessary.
- Keep brand decisions in design tokens/theme configuration where possible.

For a new project, create reusable primitives for at least:

- Buttons
- Links
- Typography
- Containers
- Section layouts
- Cards
- Form controls
- Navigation
- Footer
- Badges/labels
- Modal/dialog patterns if required

Do not create a new visual language on a page-by-page basis.

---

## 23. Engineering Behaviour

Before making significant changes:

1. Inspect the existing repository structure.
2. Identify the current framework, package manager, styling system, and component conventions.
3. Reuse the existing architecture unless there is a clear reason to change it.
4. Avoid introducing major dependencies for trivial UI tasks.
5. Never hard-code secrets or API credentials.
6. Use environment variables for environment-specific configuration.
7. Preserve type safety where the project supports it.
8. Do not weaken linting, tests, or TypeScript settings merely to make a change pass.

If repository-specific engineering instructions exist in nested `AGENTS.md` files, follow the most specific applicable instructions.

---

## 24. Completion Checklist

Before considering a user-facing implementation complete:

- Verify the Prosago Works visual hierarchy is preserved.
- Verify only approved colours are used for the corporate identity.
- Verify DM Sans is used where expected.
- Verify logo proportions and clearspace are preserved.
- Verify Reddish Orange has not been overused.
- Verify copy matches the approved tone of voice.
- Verify no unsupported product or company claims were added.
- Verify responsive behaviour.
- Verify basic accessibility.
- Verify interactive states.
- Run the repository's lint/test/build commands where available.
- Fix issues introduced by the change before finishing.

---

## 25. Source of Truth

The approved **Prosago Works Brand Guidelines (August 2026)** govern the brand system.

This `AGENTS.md` is an implementation-oriented translation of those guidelines for coding agents. It does not replace the original brand guideline document.

When uncertain about a visual or verbal brand decision, consult the approved brand guideline and official design assets rather than inventing a new convention.
