<p align="center">
  <img src="https://img.shields.io/badge/valeur%20ajoutée-0-red" alt="Valeur ajoutée">
  <img src="https://img.shields.io/badge/Satisfaction%20Globale™-9.4%2F10-brightgreen" alt="Satisfaction">
  <img src="https://img.shields.io/badge/production--ready-oui%20(malheureusement)-yellow" alt="Production Ready">
  <img src="https://img.shields.io/github/license/Bacoco/useless-skills" alt="License">
</p>

# Useless Roulette 🎰

> *"The first community-driven, open-source, extensible, production-ready framework for delivering zero value at scale."*

A [Claude Code](https://docs.anthropic.com/en/docs/claude-code) plugin marketplace. With a registry. And a contribution guide. And validation. And versioning. For skills that make your AI do things nobody asked for.

## Why

People are building marketplaces of skills. Repos of repos. Awesome-lists of awesome-lists of plugins. Registries of registries. Curated collections of curated collections. The entire AI tooling ecosystem is an infinite recursion of repos pointing to other repos that point to other repos.

We looked at all that infrastructure — the manifests, the validation, the semver, the governance — and we thought: *this is being wasted on useful things.*

So here's a marketplace. With a registry. And validation. And versioning. For plugins that do absolutely nothing.

---

## Installation

```bash
claude plugin marketplace add Bacoco/useless-skills
claude plugin install useless-roulette
```

Open a new session. The roulette spins. You don't choose what happens.

Sometimes it activates two at once. Sometimes three. Sometimes it switches mid-session without warning. We call that a *Plot Twist*. You'll call it something else.

---

## Contributing

**This is a community project.** The roulette draws from a live registry — every skill anyone adds becomes part of the pool worldwide.

1. Create `plugin/skills/your-skill/SKILL.md`
2. Add it to `registry.json`
3. Open a PR

Your skill enters the roulette. Every user who has the plugin installed can land on it. The more skills people contribute, the more unpredictable it gets.

[Full contributing guide](CONTRIBUTING.md)

### What makes a good useless skill

A good useless skill is one where Claude still does the work perfectly — but the *experience* of receiving that work is profoundly, inexplicably degraded. The SKILL.md describes how Claude should behave. The rest is between Claude and whoever installed this.

### What we'd reject

Anything useful.

---

## Architecture

```
.claude-plugin/marketplace.json   ← validated marketplace manifest
registry.json                     ← live skill catalog with weighted selection
plugin/
  .claude-plugin/plugin.json      ← validated plugin manifest
  skills/                         ← the pool
```

Yes, we have a `marketplace.json`, a `plugin.json`, AND a `registry.json`. Three config files. For jokes. That's the point.

---

## Roadmap

- [x] Marketplace with validated manifests
- [x] Live registry with weighted random selection
- [x] Combo system with named pairings
- [x] Plot twist mid-session switching
- [x] Chaos mode (3 simultaneous skills)
- [x] Contributing guide with tag taxonomy
- [ ] Governance model and RFC process
- [ ] Skill of the Month voting
- [ ] Enterprise tier with SLA on joke delivery
- [ ] Conference talk: *"Scaling Uselessness: Lessons from Building a Community-Driven Registry of Things Nobody Asked For"*

---

## FAQ

**Q: Why is this a marketplace and not just a folder of files?**
A: If we're going to do something useless, we're going to do it with proper infrastructure.

**Q: Is this production-ready?**
A: Regrettably, yes.

**Q: Can I use this at work?**
A: We decline all responsibility.

**Q: How many skills are in there?**
A: Install and find out.

---

<p align="center">
  <i>Satisfaction Globale™ : 9.4/10</i>
  <br>
  <sub>Built with the same rigor as tools that actually matter. Just, without the mattering part.</sub>
</p>
