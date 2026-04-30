# 🏆 Les 3 Skills Les Plus Inutiles de la Planète

> *"On n'a pas fait Claude Code pour ça. Et pourtant."*

Trois skills pour [Claude Code](https://docs.anthropic.com/en/docs/claude-code) qui transforment votre assistant IA ultra-performant en une expérience de bureau profondément dégradée — exactement comme au travail.

---

## Les Skills

### 📻 Radio Pause FM 107.3
> *"La radio qui vous interrompt"*

Transforme votre session Claude en émission de radio. Toutes les **3 actions**, Claude s'arrête pour diffuser un message publicitaire entièrement inventé, un bulletin météo absurde, un flash trafic, une dédicace d'auditeur, un horoscope ou un jeu-concours. Le DJ s'appelle Jean-Marc Dubitume. Il y a 2.4 millions d'auditeurs. Vous ne pouvez pas changer de station. La version sans pub coûte 49.99€/mois et n'existe pas.

**Points forts :**
- 6 types de segments radio (pub, météo, trafic, dédicace, horoscope, concours)
- Double page de pub tous les 9 actions
- Sponsors récurrents qui développent des sagas publicitaires
- Changement de DJ en soirée (Sandrine Lassonde prend le relais)
- Mentions légales juridiquement terrifiantes

---

### 🎭 Alter Ego Deluxe
> *"Un masque, zéro échappatoire"*

Au début de chaque session, Claude tire au sort un personnage parmi **20 alter-egos** et le joue jusqu'à la fin. Le travail reste impeccable — seul le ton change. Radicalement. Vous pourriez vous retrouver avec un Notaire Normand qui vous parle de Lisieux en 1987, un Influenceur Fitness qui compte vos requêtes en reps, ou une Grand-Mère Italienne qui refuse de continuer tant que vous n'avez pas mangé.

**Points forts :**
- 16 personnages communs + 4 personnages **légendaires** (rares)
- Chaque personnage a : catchphrase, tic verbal, némésis, réaction aux erreurs, signature de fin
- Le personnage évolue subtilement au fil de la session
- Impossible de changer de personnage (refus poli dans le style du personnage)
- Inclut : un Pirate reconverti en dev, un GPS existentialiste, un Fantôme de développeur COBOL de 1974

---

### 📊 Rapport-O-Matic™ Enterprise Edition
> *"Parce que le chef doit savoir"*

Après **chaque** tâche accomplie, génère automatiquement un rapport d'entreprise complet avec KPIs inventés, graphiques ASCII, matrice de risques, analyse SWOT, recommandations opérationnelles, comité d'approbation fictif et annexes — y compris un glossaire dont les définitions sont circulaires. La complexité du rapport est **inversement proportionnelle** à la complexité de la tâche.

**Points forts :**
- KPIs en unités inventées ("Index de Fluidité Cognitive", "Unités d'Impact Holistique")
- La Satisfaction Globale™ est toujours 9.4/10 — toujours
- Matrice de risques où tout est vert sauf un carré orange que "on surveille"
- Classification qui escalade à chaque rapport (CONFIDENTIEL → COSMIQUEMENT CONFIDENTIEL)
- Un QR code en ASCII qui ne mène nulle part
- L'historique des versions du rapport inclut "v1.1 — Ajout d'une virgule"
- Un membre du comité d'approbation est toujours en congé

---

## Installation

### Méthode 1 : Installation directe (recommandée)

```bash
# Cloner le repo
git clone https://github.com/Bacoco/useless-skills.git
cd useless-skills

# Installer le skill de votre choix
claude install-skill radio-pause.skill
claude install-skill alter-ego.skill
claude install-skill rapport-inutile.skill

# Ou les trois d'un coup (pour les plus courageux)
for skill in *.skill; do claude install-skill "$skill"; done
```

### Méthode 2 : Installation manuelle

```bash
# Créer le dossier des skills custom
mkdir -p ~/.claude/skills

# Copier le skill souhaité
cp -r skills/radio-pause ~/.claude/skills/
cp -r skills/alter-ego ~/.claude/skills/
cp -r skills/rapport-inutile ~/.claude/skills/
```

### Méthode 3 : Téléchargement direct d'un seul skill

Allez dans [Releases](https://github.com/Bacoco/useless-skills/releases) et téléchargez le `.skill` de votre choix, puis :

```bash
claude install-skill ~/Downloads/radio-pause.skill
```

---

## Désinstallation

```bash
# Si vous en avez assez (on comprend)
claude uninstall-skill radio-pause
claude uninstall-skill alter-ego
claude uninstall-skill rapport-inutile
```

> **Note :** Les skills eux-mêmes résisteront à la désinstallation (Radio Pause vous rappellera que "la version sans pub est disponible à 49.99€/mois"). Mais la vraie commande ci-dessus fonctionne.

---

## FAQ

**Q : Pourquoi ?**
A : Parce que.

**Q : Ça marche vraiment ?**
A : Oui. Trop bien, même.

**Q : Puis-je les utiliser en réunion ?**
A : Techniquement oui. Mais on décline toute responsabilité.

**Q : Les trois en même temps ?**
A : Vous pouvez. Imaginez : un GPS existentialiste qui vous interrompt avec des pubs pour de la crème solaire d'intérieur, suivi d'un rapport de 3 pages sur l'expérience. C'est... une expérience.

**Q : Mon chef a vu le rapport et veut la même chose pour toute l'équipe.**
A : Exactement.

---

## Contribuer

Les pull requests pour de nouveaux alter-egos, de nouveaux KPIs, ou de nouveaux sponsors fictifs sont les bienvenues. Merci de fournir un rapport d'activité RAPPORT-O-MATIC™ avec votre PR.

---

## Licence

MIT — Faites-en ce que vous voulez. On vous prévient quand même.

---

*Ce README a été validé par le Département des Rapports sur les Rapports (DRR). Satisfaction Globale™ : 9.4/10.*
