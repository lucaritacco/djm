# Product

## Register

brand

## Users

Two audiences share the same single-page site, in Bahía Blanca, Argentina:

- **Tradespeople / pro contractors** — albañiles, constructoras, instaladores. On the job, on a phone, often in the field on 4G. They want to know if DJM stocks the specific material (telgopor, dinteles RETAK, planchas, etc.), the hours, and how to get in touch fast — usually via WhatsApp.
- **Particulares / DIY buyers** — homeowners doing a small reform, picking up materials directly. Often older, less technical, arriving from an Instagram tap.

Both land mid-task, not browsing. The job to be done is identical for both: confirm DJM has what they need, confirm they're open / close, and start a conversation (WhatsApp, visit, call).

## Product Purpose

A one-page web presence for **DJM Materiales de Construcción** — a building-materials distributor and retailer on Donado 1020, Bahía Blanca. The site exists to do two things in equal weight:

1. **Drive enquiries** — push the visitor toward WhatsApp, Instagram, or a physical visit ("cómo llegar"). There is no online catalogue or checkout; the conversion is a conversation.
2. **Build local credibility** — show the 200+ product range, real hours, real address, real Instagram presence, so a first-time visitor referred via word-of-mouth or Instagram trusts DJM enough to walk in or message.

Success looks like: a contractor sees a material listed, taps WhatsApp, and gets a quote the same day. A particular sees the hours and shows up Saturday morning.

## Brand Personality

**Pro contractor, no-nonsense.** Speaks to tradespeople first; particulares are welcome but not the centre of gravity. Three-word personality: **direct, trade-grade, dependable**. Tone is Argentine Spanish, matter-of-fact, zero marketing fluff. No hyperbole, no "soluciones integrales", no "tu socio estratégico". Materials are named the way a tradesman names them.

Emotional goal: the visitor closes the tab thinking "están en lo suyo" — they know their trade.

## Anti-references

- **Bootstrap-template SaaS look** (explicit reject) — gradient hero, three identical feature cards, pricing tiers, hero-metric template, big-number/small-label decoration. A construction supplier must not look like a productivity app.
- Generic big-box hardware-store cliché (cluttered grids, primary-color banners, sale stickers, exclamation-point copy).
- Toy/cartoon construction iconography (hard-hat emoji as decoration, primary-color blocks). DJM is a real supplier, not a kids' theme.
- Over-styled architect/luxury studio aesthetic. DJM is a working warehouse, not a showroom.

## Design Principles

1. **Direct over decorative.** Every block must serve "find what I need" or "contact DJM". No section earns its place by looking nice alone. If a heading restates the section title or a paragraph restates a heading, cut it.
2. **Trade-grade trust signals.** Real product names, real address, real hours, real WhatsApp number, real Instagram handle. No stock-photo construction sites, no invented testimonials, no rounded happy-customer stats. Specifics beat adjectives.
3. **Two doors, one floor.** Pros and particulares share the page. The information architecture and copy must let each self-identify within seconds without making the other feel out of place. Don't fork into separate flows; speak plainly enough that both understand.
4. **Speak the trade.** Argentine Spanish, material names as they're actually used in the yard (telgopor, no "EPS expandido"; "dinteles RETAK", not "elementos prefabricados de hormigón"). No Anglicisms unless the trade uses them.
5. **Mobile-first reality, not mobile-first slogan.** Most traffic is Instagram → mobile → 4G on a building site. The page should be useful before it's fully loaded: address, hours, and WhatsApp button must be reachable on the first paint, not after the parallax hero finishes settling.

## Accessibility & Inclusion

- **WCAG AA** baseline: contrast on `#E8620A` orange against `#111111` near-black checked; keyboard focus visible; `prefers-reduced-motion` respected (parallax and reveals turn off).
- **Mobile-data conscious**: lean payload, no large JS libraries, no above-the-fold full-screen video, lazy-load gallery imagery, prefer system fonts or one webfont subset.
- **Older-user friendly**: minimum body type ~17px; tap targets ≥44×44px; WhatsApp/phone CTAs labelled in words, not icon-only; no ambiguous iconography for primary actions.
- Language is Spanish (es-AR). `lang="es"` set; copy uses Argentine conventions (vos, "cerrado", "cómo llegar").
