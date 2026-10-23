# Anis — Operations, Software & Internal Tools

I work at the intersection of **day-to-day operations and software development**. My professional background is operational coordination; I also design and build applications to structure workflows, track execution and reduce manual follow-up.

**I distinguish tools I use, working prototypes, and reference implementations.** A code repository or live demo is not evidence of a paying client, production adoption or employment in software.

## Start here — three concrete examples

| Project | What to inspect | Real status | Where to see it |
|---|---|---|---|
| **MyBi** | Client → mission → invoice → payment workflow | Personal business tool in use; source private | [Lyan Studio case](https://www.lyanstudio.com/work.html#mybi) |
| **StayOps Core** | Reservation → check-in → check-out → housekeeping → room ready; role separation | Working hospitality PMS prototype; private source | [Read-only demo](https://stayops.lyanstudio.com/demo/workspace) · [Planning](https://stayops.lyanstudio.com/demo/planning) |
| **AlCaisse** | Offline POS on Windows; local SQLite transactions, stock, cash sessions and backups | Functional desktop prototype; physical hardware and compliance validation pending; source private | [Case study](https://www.lyanstudio.com/alcaisse.html) · [Browser presentation](https://www.lyanstudio.com/alcaisse-demo.html) |

### Other work

- **[IT Ops Desk](https://www.lyanstudio.com/itopsdesk/)** — interactive, *browser-local* incident and asset management proof of concept. [Incidents](https://www.lyanstudio.com/itopsdesk/incidents.html) · [Assets](https://www.lyanstudio.com/itopsdesk/assets.html) · [Source and automated tests](https://github.com/Granis75/lyanstudio.com/tree/main/itopsdesk). **No authentication or shared backend**.
- **[Kepler Express](https://github.com/Granis75/Kepler-Express)** — logistics operations reference implementation. [Public UI](https://kepler.lyanstudio.com/). Adoption and business impact are not independently verified.

## What these projects demonstrate

- Translating operational constraints into data models, interfaces and end-to-end workflows.
- CRUD, relational consistency, status lifecycles, dashboards and exports.
- Web interfaces (React, TypeScript, Next.js), PostgreSQL/Supabase integration and desktop/offline development (Electron and SQLite).
- Explaining technical limitations, documenting decisions and testing core workflows.

## Evidence and limitations

**Verified public entry points:** StayOps read-only demonstration, IT Ops Desk interactive local demonstration and Kepler's public UI. Repositories for MyBi, StayOps and AlCaisse remain private intentionally. The browser-only AlCaisse presentation is **not** a Windows hardware validation.

**IT Ops Desk:** [model tests](https://github.com/Granis75/lyanstudio.com/blob/main/itopsdesk/core.test.mjs), [routing tests](https://github.com/Granis75/lyanstudio.com/blob/main/itopsdesk/routes.test.mjs), [architecture and limitations](https://github.com/Granis75/lyanstudio.com/blob/main/itopsdesk/README.md).

No unverified client names, revenue improvements or job experience are claimed. For technical reviews of private projects, use documented workflows and scoped demonstrations rather than exposing internal data or secrets.

## Two complementary websites

- **[Lyan Studio](https://www.lyanstudio.com/)** — software, prototypes and product work.
- **[AnisConsult](https://anisconsult.com/)** — operational activity, coordination and processes, in French and English.

**Contact:** [LinkedIn](https://www.linkedin.com/in/anisallouachepro) · [Lyan Studio](https://www.lyanstudio.com/contact.html)

_Updated October 2026. All statuses refer to what is actually documented; production readiness requires independent verification._