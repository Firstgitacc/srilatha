# Portfolio Frontend Architecture

## 1. Experience concept

**IDE Framework / Azure Enterprise**

The interface borrows the visual language of a modern IDE without becoming a gimmick. The hero contains a realistic code editor panel, syntax-style token coloring and an execution-status footer. The rest of the site shifts into a premium enterprise dashboard system with subtle glass surfaces, sharp borders and cloud-blue/violet accents.

This direction matches the resume because the profile is not only a .NET developer. It combines solution design, full-stack implementation, Azure delivery, technical leadership, SaaS platform ownership, production support, data governance and user enablement.

## 2. Information architecture

1. **Hero** — title, 15+ years positioning, dynamic technology flipper, core proof points and IDE profile card.
2. **Capability Matrix** — backend/APIs, frontend, cloud/data, databases/delivery.
3. **Enterprise Project Showcase** — ORC, GoTechnology/Hub2, PROACT, HLS, eCareLogic, Ratabase and EDGE.
4. **Architecture Mindset** — interactive enterprise delivery map based on documented resume capabilities.
5. **Professional Journey** — animated and expandable career timeline.
6. **Recognition & Beyond Code** — awards, governance, training, documentation and mentoring.
7. **Contact** — email, LinkedIn, phone and static-host-safe mailto form.

## 3. Interaction model

- Intersection Observer drives fade-up entrance animations.
- Magnetic hover is applied only to primary actions.
- Project cards open an accessible native `<dialog>` with deeper architecture/impact detail.
- Architecture nodes update a contextual description panel.
- Experience entries expand/collapse inline.
- A canvas network provides lightweight ambient motion and respects reduced-motion preferences.
- Mobile navigation uses explicit ARIA state.

## 4. Responsive strategy

- Mobile-first layout with progressive 2-column and 3-column enhancement.
- No layout-critical fixed widths except a capped desktop editor panel.
- Touch targets are at least ~40px high for primary navigation/actions.
- Project cards, timeline and contact form collapse to single-column on small screens.

## 5. Accessibility

- Semantic sections and headings.
- ARIA labels on nav, tabs, dialog close, and contact form.
- `aria-expanded` on mobile nav and timeline controls.
- `aria-live` on rotating technology text.
- Strong keyboard focus ring.
- Native `<dialog>` for focus behavior.
- Reduced motion media query.

## 6. Performance

- Single HTML document.
- Tailwind via CDN, as requested.
- No large image assets, icon packages or animation libraries.
- Ambient canvas uses a bounded particle count.
- JavaScript is dependency-free.
