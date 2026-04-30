# Contributing a Useless Skill

You have an idea for a profoundly useless skill? Perfect. We're hiring.

## How to add a skill

1. **Create a folder** in `plugin/skills/` with your skill name:
   ```
   plugin/skills/my-useless-skill/SKILL.md
   ```

2. **Write your SKILL.md** using this format:
   ```markdown
   ---
   name: my-useless-skill
   description: >
     When and why this skill triggers.
     Be generous — the broader, the more it triggers.
   ---

   # Skill Title

   [Full instructions for Claude]
   ```

3. **Add an entry to `registry.json`**:
   ```json
   {
     "id": "my-useless-skill",
     "title": "My Useless Skill",
     "emoji": "🤷",
     "tagline": "Short, punchy one-liner",
     "path": "plugin/skills/my-useless-skill/SKILL.md",
     "weight": 1,
     "tags": ["tag1", "tag2"]
   }
   ```

4. **Open a PR.** That's it.

## Rules

- The skill must be **useless**. If it adds value, it's rejected.
- The skill must be **funny**. Humor is subjective but boredom is objective.
- Claude's work must remain **correct** — only the experience is degraded.
- No offensive content, no real brands, no meanness.
- The tagline matters — it's what people see in the roulette.
- Skills can be in any language.

## Ideas we'd love

- A skill that adds footnotes to every sentence
- A skill that narrates code like a nature documentary
- A skill that turns every error into a crime scene investigation
- A skill that gives unsolicited pigeon facts between responses
- A skill where Claude talks like a broken GPS
- A skill that requires a haiku before every commit

## Tags

| Tag | Meaning |
|---|---|
| `pre-action` | Triggers BEFORE the response |
| `post-action` | Triggers AFTER the response |
| `recurrent` | Repeats regularly |
| `session-entiere` | Active for the whole session |
| `personnage` | Claude plays a character |
| `immersif` | Changes the entire vibe |
| `interactif` | Requires user interaction |
| `style` | Changes writing style |
| `narratif` | Adds a narrative layer |
| `corporate` | Corporate world parody |
| `interruption` | Interrupts the workflow |
