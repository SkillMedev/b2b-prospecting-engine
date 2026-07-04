# B2B Prospecting Engine

**For SDRs and founders: build a targeted pipeline from ICP to booked meeting — tool-agnostic, with an Apollo.io playbook.** — built in-house by [Skill&nbsp;Me](https://skillme.dev).

The top-of-funnel prospecting system that feeds an outbound motion — everything before the deal that the Outbound Sales Engine pack picks up. Define a targetable ICP and buying-committee personas, turn them into a clean, tiered, suppression-checked prospect list, enrich and verify contact data so you don't bounce, track buying signals and trigger events to prioritize by timing, design a multi-channel cadence, and protect cold-email deliverability with proper sending domains and SPF/DKIM/DMARC. Then a funnel-metrics skill backsolves the weekly activity your quota actually requires. The methodology is tool-agnostic; a final Apollo.io skill maps every step to concrete Apollo filters, lists, credits, and sequences so you can execute it in the tool most teams already use.

⭐ **If this is useful, star the repo** — it's how we gauge what to build next.

## Install

- **From the catalog:** [skillme.dev/pack/b2b-prospecting-engine](https://skillme.dev/pack/b2b-prospecting-engine) — install the whole pack into Claude in one step.
- **With the skills CLI:** `npx skills add SkillMedev/b2b-prospecting-engine`
- **Manually:** copy any `skills/<slug>/SKILL.md` into your Claude skills directory.

## Skills in this pack

- **[ICP & Buyer Persona Builder](skills/icp-persona-builder/SKILL.md)** — Use FIRST, before any list-building or outreach, to turn a vague "who we sell to" into TARGETABLE filter criteria plus a per-persona pain/trigger map.
- **[Targeted Prospect List Builder](skills/prospect-list-builder/SKILL.md)** — Use when you have an ICP and need to turn it into an actual list of accounts and contacts to put into a sequence.
- **[Lead Enrichment & Verification](skills/lead-enrichment/SKILL.md)** — Use this skill to turn a raw or partial prospect list into a usable, send-safe dataset by filling missing fields (work email, direct/mobile phone, title, firmographics, technographics, LinkedIn URL) and verifying emails before any send.
- **[Buying Signal & Trigger Tracker](skills/buying-signal-tracker/SKILL.md)** — Use when you need to decide WHO IN YOUR ICP TO HIT NOW based on timing and trigger events rather than static fit — "who should I reach out to this week", "what's a good reason to reach out", "track buying signals", "find trigger events", "champion changed jobs", "they just raised a round", "new VP just started", "they're hiring for X", "they installed a competitor", "intent data spiked", "why now opener", "warm up our outbound", "score and prioritize accounts by signal".
- **[Multi-Channel Sequence Designer](skills/outreach-sequence-designer/SKILL.md)** — Use when you need to design the cadence/sequence structure that moves a cold prospect to a booked meeting across multiple channels — the orchestration of touches, not the copy of any one message.
- **[Cold-Email Deliverability](skills/cold-email-deliverability/SKILL.md)** — Use this skill BEFORE launching any cold outbound — it is the infrastructure layer beneath every sequence.
- **[Prospecting Funnel Metrics](skills/prospecting-metrics/SKILL.md)** — Use when you need to turn outbound prospecting into a measurable, backsolvable funnel instead of guesswork — for quota planning, activity targets, funnel diagnosis, and A/B test sizing.
- **[Apollo.io Prospecting](skills/apollo-prospecting/SKILL.md)** — Use when executing your B2B prospecting strategy inside Apollo.io specifically — turning an ICP into stacked Apollo search filters, building and tiering Apollo Lists, finding and verifying emails with credit discipline, tracking buying signals via Apollo filters and saved-search alerts, and running multi-step Apollo Sequences.
- **[Cold Email Craft](skills/cold-email-craft/SKILL.md)** — B2B cold outreach that gets replies: tight personalization, brevity, and a low-friction ask.

## License

MIT — see [LICENSE](LICENSE). Skills are portable `SKILL.md` files; the canonical
copies live in the [Skill&nbsp;Me catalog](https://skillme.dev).
