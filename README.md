<p align="center">
  <img src="https://img.shields.io/badge/skills-8-blueviolet" alt="Skills">
  <img src="https://img.shields.io/badge/combos-5-orange" alt="Combos">
  <img src="https://img.shields.io/badge/valeur%20ajoutée-0-red" alt="Valeur ajoutée">
  <img src="https://img.shields.io/badge/Satisfaction%20Globale™-9.4%2F10-brightgreen" alt="Satisfaction">
  <img src="https://img.shields.io/badge/production--ready-oui%20(malheureusement)-yellow" alt="Production Ready">
  <img src="https://img.shields.io/github/license/Bacoco/useless-skills" alt="License">
</p>

# Useless Roulette 🎰

> *"The first community-driven, open-source, extensible, production-ready framework for delivering zero value at scale."*

A [Claude Code](https://docs.anthropic.com/en/docs/claude-code) plugin marketplace. With a registry. And a contribution guide. And a governance model. And validation. And versioning. For skills that make your AI assistant talk about a fictional cat named Pixel.

## Why

Because every ecosystem deserves its own curated registry of community-maintained, semver-versioned, CI-validated, peer-reviewed plugins that do absolutely nothing.

We saw people building marketplaces of skills, repos of repos, awesome-lists of awesome-lists, and we thought: *this infrastructure is being wasted on useful things.*

---

## Installation

```bash
claude plugin marketplace add Bacoco/useless-skills
claude plugin install useless-roulette
```

That's it. Open a new session. The roulette spins. You don't choose what happens.

---

## The Ecosystem

8 community skills. 5 named combos. 1 registry. 0 purpose.

| | | |
|---|---|---|
| 📻 | Radio Pause FM 107.3 | |
| 🎭 | Alter Ego Deluxe | |
| 📊 | Rapport-O-Matic™ | |
| 🎬 | Previously On... | |
| 📋 | Bureaucratie Absolue | |
| 💆 | ASMR Coding | |
| 😤 | Le Collègue Relou | |
| 🧑‍💼 | Le Stagiaire | |

We won't tell you what they do. Install and find out.

Sometimes the roulette activates two at once. Sometimes three. Sometimes it switches mid-session without warning. We call that a *Plot Twist*. You'll call it something else.

---

## Architecture

```
.claude-plugin/marketplace.json   ← validated marketplace manifest
registry.json                     ← live skill registry with weighted selection
plugin/
  .claude-plugin/plugin.json      ← validated plugin manifest
  skills/
    useless-roulette/             ← orchestrator with fallback roster
    8 community skills/           ← individually invocable
```

Yes, we have a `marketplace.json`, a `plugin.json`, AND a `registry.json`. Three config files. For eight jokes. That's the point.

---

## Contributing

**The pool is open.** Add your own useless skill, and it's automatically in every roulette worldwide.

1. Create `plugin/skills/your-skill/SKILL.md`
2. Add it to `registry.json`
3. Open a PR

[Full contributing guide](CONTRIBUTING.md) — yes, we wrote a contributing guide. With tags. And a style section. For joke plugins.

### Ideas We'd Accept

- A skill that adds footnotes to every sentence
- A skill where Claude narrates your code like a nature documentary
- A skill that turns every error into a crime scene investigation
- A skill that gives unsolicited pigeon facts between responses

### Ideas We'd Reject

Anything useful.

---

## Roadmap

- [x] Marketplace with validated manifests
- [x] Live registry with weighted random selection
- [x] Combo system with named pairings
- [x] Plot twist mid-session switching
- [x] Chaos mode (3 simultaneous skills)
- [x] Fallback roster for offline mode
- [x] Contributing guide with tag taxonomy
- [ ] Governance model and RFC process
- [ ] Skill of the Month voting system
- [ ] Analytics dashboard for most-rolled skills
- [ ] Enterprise tier with SLA on joke delivery
- [ ] Conference talk: "Scaling Uselessness: Lessons from Building a Community-Driven Registry of Things Nobody Asked For"

---

## FAQ

**Q: Why is this a marketplace and not just a folder of files?**
A: Because if we're going to do something useless, we're going to do it with proper infrastructure.

**Q: Is this production-ready?**
A: Regrettably, yes.

**Q: Can I use this at work?**
A: We'd be honored. We decline all responsibility.

**Q: My boss saw the Rapport-O-Matic™ output and wants it for the whole team.**
A: This is the expected outcome.

---

<p align="center">
  <i>Satisfaction Globale™ : 9.4/10</i>
  <br>
  <sub>Built with the same rigor as tools that actually matter. Just, without the mattering part.</sub>
</p>
