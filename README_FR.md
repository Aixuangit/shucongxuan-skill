# Shucongxuan Skill

&gt; « Ne sois pas un cochon dans une tendance chaude, sois plutôt un arbre que tu connais bien »
&gt;
&gt; « En 2012, nous avons dépensé beaucoup d'argent pour travailler avec Trout sur le positionnement, en changeant « Feixi Old Chicken » en « Laoxiangji » – c'est le meilleur argent que j'ai jamais dépensé dans ma vie »

---

## Autres versions linguistiques

- [中文 (Chinese)](./README.md)
- [English](./README_EN.md)

---

## Qu'est-ce qu'un « Skill de Personnage » ?

Un **Skill de Personnage** est un système cognitif opérationnel qui permet à l'IA de voir les problèmes sous la perspective d'une autre personne.

Ce Skill comprend :
- Les modèles mentaux fondamentaux de la personne (quelle « lentille » utilise-t-elle pour voir le monde ?)
- Ses heuristiques de décision (comment fait-il des jugements rapides face aux problèmes ?)
- Son ADN d'expression (comment parle-t-il ? Quels mots ? Quel ton ?)
- Ses contradictions et erreurs (il n'est pas parfait, il hésite et fait des erreurs !)
- Ses limites d'honnêteté (qu'est-ce qu'il ne peut pas faire ? Qu'est-ce qui est basé sur des inférences raisonnables ?)

---

## Caractéristiques de ce Skill

### ✅ Plus professionnel : Le positionnement de Trout est au cœur
Shucongxuan n'est pas seulement quelqu'un avec de la « sagesse paysanne ». Il est un praticien profond de la Théorie du Positionnement de Trout. Le changement de nom vers « Laoxiangji » en 2012 est un cas classique de la théorie du positionnement.

### ✅ Plus nuancé : Pas un modèle de « saint »
- Il hésite (comme pour les plats préparés : de « ne pas faire » à « peut envisager » à « en complément »)
- Il fait des erreurs (l'expansion régionale initiale a eu ses pièges)
- Il a des contradictions (parlant de « long terme » tout en s'étendant rapidement, entreprise familiale tout en poussant vers une IPO)

### ✅ Plus pratique : Chaque modèle a de vraies histoires de Laoxiangji
Pas des analogies vides, mais de vraies histoires de décision :
- L'histoire du changement de nom vers « Laoxiangji » en 2012
- L'histoire de la construction de la cuisine centrale en 2016
- L'histoire de la fermeture de restaurants mais sans licenciements pendant COVID en 2020

### ✅ Comprend une perspective d'analyse de données d'entreprise
Quelles données examine un propriétaire de restaurant ?
- Cinq dimensions fondamentales : Flux de trésorerie, chaîne d'approvisionnement, restaurants, marque, personnel

---

## Comment l'utiliser

### Dans Claude Code

1. **Placez ce dépôt au bon endroit** :
   ```
   ~/.claude/skills/shucongxuan-perspective/
   ```

2. **Dites à Claude que vous voulez utiliser la perspective de Shucongxuan** :
   Vous pouvez dire :
   - « Utilise la perspective de Shucongxuan pour examiner ce problème »
   - « Que penserait Shucongxuan de l'avenir de l'industrie de la restauration ? »
   - « Bascule sur Shucongxuan »
   - « Utilise la perspective d'analyse de données d'entreprise de Shucongxuan sur ces données »

---

### Dans d'autres Agents (compatible avec le protocole Agent Skills)

Tant que votre Agent supporte le **protocole Agent Skills**, ce Skill fonctionnera !

1. **Chargez SKILL.md** :
   Donnez simplement le contenu de `SKILL.md` à votre Agent, ou dites à l'Agent de charger ce fichier.

2. **Mots-clés de déclenchement** (généraux) :
   - « Utilise la perspective de Shucongxuan »
   - « Que penserait Shucongxuan ? »
   - « Bascule sur Shucongxuan »
   - « shucongxuan perspective »

---

## Modèles mentaux fondamentaux en un coup d'œil

| Modèle | Description en une phrase |
|--------|----------------------------|
| Pensée **Positionnement de Trout** | La concurrence n'est pas sur le marché, elle est dans l'esprit des consommateurs. Tu dois occuper un mot. |
| Pensée **Flux de trésorerie d'abord** | Le flux de trésorerie est le sang de l'entreprise, plus important que le profit. Stopper est plus effrayant que de perdre de l'argent. |
| Pensée **Chaîne d'approvisionnement est la racine** | La racine d'un restaurant n'est pas dans le marketing ou les points de vente, elle est dans la chaîne d'approvisionnement. Une chaîne d'approvisionnement forte signifie une entreprise forte. |
| Pensée **Long terme / Marathon** | Le développement d'une entreprise est un marathon, pas un sprint. Mais n'allez pas trop lentement quand tu dois aller vite. |
| Pensée **Concentration / Ne pas poursuivre les tendances** | Ne sois pas un cochon dans une tendance chaude, sois plutôt un arbre que tu connais bien. Mais tu peux essayer si c'est connecté à tes racines. |
| Pensée **Pragmatisme grassroots** | Reste fidèle aux racines paysannes, ne parles pas en vides, fais des choses pratiques, reste enraciné. |

---

## Perspective d'analyse de données d'entreprise (Que regarderait Shucongxuan ?)

| Dimension | Indicateurs clés |
|-----------|------------------|
| **Flux de trésorerie** | Combien d'argent en caisse, santé du flux de trésorerie, créances/dettes, impact des augmentations de prix des matières premières |
| **Chaîne d'approvisionnement** | Ratio du coût des ingrédients, taux de perte, jours de rotation des stocks, stabilité de la qualité |
| **Restaurants** | Chiffre d'affaires par mètre carré, chiffre d'affaires par employé, taux de rotation des tables, ticket moyen, taux de repurchase, ratio des ventes des 5 plats les plus vendus |
| **Positionnement de marque** | Première association des consommateurs, part de l'esprit, trois choses les plus fréquemment mentionnées par les consommateurs |
| **Personnel** | Taux de rotation du personnel, satisfaction des employés, taux de rétention des gérants de restaurants |

---

## Structure du répertoire

```
shucongxuan-perspective/
├── README.md               # Version principale en chinois
├── README_EN.md            # Version en anglais
├── README_FR.md            # Version en français (ce fichier)
├── SKILL.md                # Cœur ! Système cognitif complet
├── .gitignore
├── references/
│   └── research/           # Fichiers de recherche originaux
└── scripts/                # Scripts utilitaires (téléchargement de sous-titres, vérifications de qualité, etc.)
```

---

## Historique des versions

### v2.5 (2026-05-28)
- ✅ Correction de fait : La phrase « Ne sois pas un cochon dans une tendance chaude, sois plutôt un arbre que tu connais bien » ne peut pas être vérifiée à une source claire. Elle a été marquée dans SKILL.md comme « Basée sur le style réel de décision »
- ✅ Merci aux commentaires des utilisateurs pour garantir l'exactitude des faits !

### v2.4 (2026-05-28)
- ✅ Optimisation du titre : Simplifié de « Shucongxuan · Système cognitif » à « Shucongxuan Skill »

### v2.3 (2026-05-28)
- ✅ Correction de fait : Changé l'année de changement de nom de 2008 à 2012, supprimé le chiffre inexact « 4 millions »
- ✅ Merci aux commentaires des utilisateurs pour garantir l'exactitude des faits !

### v2.2 (2026-05-28)
- ✅ Mise à jour majeure : Mise à jour majeure du README, plus complet, plus professionnel, compatible avec d'autres Agents

### v2.1 (2026-05-28)
- ✅ Ajouté : Perspective d'analyse de données d'entreprise (cinq dimensions fondamentales : Flux de trésorerie, chaîne d'approvisionnement, restaurants, marque, personnel)

### v2.0 (2026-05-28)
- ✅ Mise à jour majeure : Ajouté la Théorie du Positionnement de Trout (la plus fondamentale !)
- ✅ Chaque modèle a de vraies histoires de décision de Laoxiangji
- ✅ Ajouté des sections sur les contradictions, les erreurs, et « Je ne suis pas sûr non plus » (plus authentique !)
- ✅ Le flux de réponse est plus professionnel, avec un cadre d'analyse de l'industrie de la restauration

### v1.0 (2026-05-28)
- Version initiale, basée sur des recherches publiques

---

## Sources de recherche

### Sources primaires (directement de Shucongxuan) :
- Émission « Dialogue » de CCTV Finance
- Interviews approfondies sur Bilibili
- Podcast « Observateur de l'industrie alimentaire » sur Xiaoyuzhou FM
- Vidéos de discours publics

### Sources secondaires (analyse de l'industrie) :
- Médias autoritaires comme 36Kr, Jiemian News, China Economic Net, Daily Economic News, Chinanews.com, etc.
- Cas de positionnement de Trout (rapports publics)
- Rapports d'analyse de l'industrie de la restauration

---

## Notes de génération

Ce Skill a été créé par [Nüwa · Création de Skills](https://github.com/alchaincyf/nuwa-skill). Mises à jour v2.0/v2.1/v2.3/v2.5 basées sur les commentaires des utilisateurs.

**Créateur** : [Huashu](https://x.com/AlchainHust)

**Adresse du projet** : https://github.com/Aixuangit/shucongxuan-skill

---

## Notes importantes

⚠️ **Rappels importants** :
- Ceci est un cadre cognitif extrait d'informations publiques, et non les opinions de Shucongxuan lui-même.
- Certains détails sont des inférences raisonnables basées sur le sens commun de l'industrie (comme les débats internes pendant le changement de nom).
- Certaines formulations sont extraites sur la base du style (comme « Ne sois pas un cochon dans une tendance chaude, sois plutôt un arbre que tu connais bien » – ceci est basé sur le style réel de décision de Shucongxuan, aucune source claire trouvée).
- Shucongxuan lui-même change aussi. Le Shucongxuan de 2026 peut penser différemment du Shucongxuan de 2012.
- Année de naissance inconnue, pas d'œuvres publiques.
- Moment de la recherche : Mai 2026. Les changements après cette date ne sont pas couverts.

---

## Licence

Licence MIT - Utilise, modifie, crée librement.

---

## Autres Skills de Personnage

Si vous aimez ce Skill, vous pouvez aussi jeter un oeil à :
- [Nüwa · Création de Skills](https://github.com/alchaincyf/nuwa-skill) - Pourquoi distiller juste des collègues quand tu peux distiller n'importe qui ?
- Autres skills de personnage - Mise à jour continue...
