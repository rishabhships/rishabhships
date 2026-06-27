### Hi, I'm Rishabh 👋

I'm a senior Android engineer on a billion-install consumer app, where I lead growth, engagement, and monetization engineering — one of the most-installed Android apps in the world (**1B+ installs, 95M+ MAU**, Google Play Billing globally).

My work sits at the intersection of mobile architecture and revenue:

- 💳 **Payments & subscriptions** — I own the in-app payments stack end-to-end. Recently led a cross-product subscription upgrade / downgrade / cross-grade rollout that's run stably in production.
- 📈 **Growth engineering** — server-driven paywalls, on-device ML personalization, A/B-tested upsell touchpoints, driving measurable gains in retention and upsell.
- 🛠️ **Mobile DevEx** — building the automations that let a large Android org ship monetization changes weekly: a Figma design linter, a release-cherry-pick + Jira workflow, a weekly executive KPI digest pipeline.

Mentoring engineers earlier in their careers is also a meaningful share of what I do day-to-day. Earlier at Aon I built [CoCubes](https://play.google.com/store/apps/details?id=com.cocubes.candidate) (50K+ installs, 4.1★) and the Assessment app (150K+ installs, 4.0★). Started at Samsung R&D on Samsung Pay.

---

### Building in public

Some of what I think about subscription architecture I'm putting into open libraries.

🔄 **[renew-kt](https://github.com/rishabhships/renew-kt)** — a deterministic Kotlin state machine for the Google Play Billing subscription lifecycle. 7 canonical states, 11 events, RTDN adapter, 40 unit tests, Apache 2.0. The Play Billing docs answer *"what should happen"* across many pages; this library encodes the answer in one place. *Most recent.*

📝 **[Modeling Google Play Billing subscriptions as a state machine](https://rishabhships.com/blog/subscription-state-machine)** — the thinking behind `renew-kt`. Why subscription state isn't a single source of truth, why grace / hold / paused don't compose, and the small Kotlin library I extracted from doing this at scale.

---

### Reach me

🌐 [rishabhships.com](https://rishabhships.com) — writing about mobile payments architecture and Android DevEx
💼 [LinkedIn](https://linkedin.com/in/rg-rishabh-gupta) · [X / Twitter](https://x.com/rishabhships) · ✉️ rishabh@rishabhships.com

---

### Selective consulting

Outside my day job, I take a small number of engagements per quarter — **mobile payments architecture audits** for consumer apps with >100K MAU. Details: [rishabhships.com/consulting](https://rishabhships.com/consulting). Email me if your subscription stack feels like it has hidden revenue leakage.
