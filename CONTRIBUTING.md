# Contribuer un Skill Inutile

Vous avez une idée de skill profondément inutile ? Parfait. On recrute.

## Comment ajouter un skill

1. **Créez un dossier** dans `skills/` avec le nom de votre skill :
   ```
   skills/mon-skill-inutile/SKILL.md
   ```

2. **Écrivez votre SKILL.md** avec ce format :
   ```markdown
   ---
   name: mon-skill-inutile
   description: >
     Description de quand et pourquoi ce skill se déclenche.
     Soyez généreux — plus c'est large, plus ça se déclenche.
   ---

   # Titre du Skill

   [Instructions complètes pour Claude]
   ```

3. **Ajoutez une entrée dans `registry.json`** :
   ```json
   {
     "id": "mon-skill-inutile",
     "title": "Mon Skill Inutile",
     "emoji": "🤷",
     "tagline": "Une phrase d'accroche courte et percutante",
     "path": "skills/mon-skill-inutile/SKILL.md",
     "weight": 1,
     "tags": ["tag1", "tag2"]
   }
   ```

4. **Ouvrez une PR**. C'est tout.

## Règles

- Le skill doit être **inutile**. Si ça apporte de la valeur, c'est refusé.
- Le skill doit être **drôle**. L'humour est subjectif mais l'ennui est objectif.
- Le travail de Claude doit rester **correct** — seule l'expérience est dégradée.
- Pas de contenu offensant, pas de vraies marques, pas de méchanceté.
- La tagline est importante — c'est ce que les gens voient dans la roulette.

## Idées en vrac

Si vous cherchez l'inspiration :

- Un skill qui traduit tout en langage juridique
- Un skill qui ajoute des notes de bas de page à chaque phrase
- Un skill qui commente le code comme un poème
- Un skill qui donne des faits random sur les pigeons entre chaque réponse
- Un skill qui parle comme un GPS en panne
- Un skill qui transforme chaque erreur en épisode de série policière

## Tags disponibles

| Tag | Signification |
|---|---|
| `pre-action` | Se déclenche AVANT la réponse |
| `post-action` | Se déclenche APRÈS la réponse |
| `recurrent` | Se répète régulièrement |
| `session-entiere` | Actif toute la session |
| `personnage` | Claude joue un rôle |
| `immersif` | Change l'ambiance complète |
| `interactif` | Demande des actions à l'utilisateur |
| `style` | Change le style d'écriture |
| `narratif` | Ajoute une couche narrative |
| `corporate` | Parodie du monde de l'entreprise |
| `interruption` | Interrompt le flux de travail |
