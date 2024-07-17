# Protocole d'analyse des données

## Bonnes pratiques

### Utiliser git/github

Pour cloner le répertoire, utiliser `git clone https://github.com/emilienschultz/spacious.git`

Pour mettre à jour `git pull`

TODO : configurer l'accès au répertoire

## Europresse

### Mise en forme du corpus

- Données exportées en format HTML
- Mise en forme CSV avec https://dstool.onrender.com/

### Exploration du corpus

### Tâches spécifiques

#### Objectif 1 : Vallée/plateau

**Objectif** : identifier les articles qui mentionnent la "vallée" (évolution dans le temps, proportion, ...)

- Manipulation des données avec Pandas

#### Objectif 2 : entités géographiques

**Objectif**: identifier toutes les entités géographiques des textes

- Utilisation de GliNER : https://github.com/urchade/GLiNER

#### Objectif 4 : cadrage sur différents lieux

**Objectif** : coder comment on aborde différent lieux

Démarche :

- liste des entités d'intérêt {"Entité d'intérêt":["forme1", "forme2", ...], ...}
- extraction des phrases les mentionnant : premier document de phrases à checker
  - couper les textes à l'échelle des points et garder que les phrases mentionnant les entités
- survol des phrases et amélioration des règles de filtrage
- corpus de phrases d'intérêt
- définition d'une grille de codage : qu'est-ce qui est codé pour chaque phrase ?
- codage des phrases
- statistiques sur les distributions + évolutions temporelles

## Bibliographie

- Lire papier GéoLM : https://arxiv.org/abs/2310.14478
- Kalin Kopanov. 2024. Comparative Performance of Advanced NLP Models and LLMs in Multilingual Geo-Entity Detection. In Proceedings of the Cognitive Models and Artificial Intelligence Conference (AICCONF '24). Association for Computing Machinery, New York, NY, USA, 106–110. https://doi.org/10.1145/3660853.3660878
