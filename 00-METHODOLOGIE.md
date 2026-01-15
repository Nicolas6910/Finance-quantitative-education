# Methodologie Pedagogique

Guide de format et d'apprentissage pour le cours de Finance Quantitative.

---

## PRINCIPES PEDAGOGIQUES

### 1. Active Recall + Spaced Repetition
Base sur les recherches en sciences cognitives (Ebbinghaus, 1885):
- **Active Recall**: Se tester plutot que relire passivement
- **Spaced Repetition**: Espacer les revisions dans le temps
- Resultat: +50-70% de retention vs etude passive

### 2. Problem-Based Learning (PBL)
- Apprendre par la resolution de problemes reels
- Chaque concept est ancre dans une application concrete
- Progression: Comprendre -> Appliquer -> Analyser -> Creer

### 3. Interleaving
- Melanger les sujets pour renforcer les connexions
- Reviser les modules precedents en parallele des nouveaux
- Exercices qui combinent plusieurs concepts

### 4. Learn by Doing
- 30% theorie / 70% pratique
- Chaque concept mathematique a son implementation Python
- Projets incrementaux tout au long du parcours

---

## STRUCTURE D'UN MODULE

Chaque module suit le format **TCEP**:

```
Module-XX-Nom/
├── 01-THEORIE.md           # Cours theorique
├── 02-CODE.ipynb           # Implementation Python
├── 03-EXERCICES.md         # Problemes a resoudre
├── 04-PROJET.md            # Mini-projet applique
├── flashcards.md           # Cartes de revision
└── solutions/              # Corrections
    ├── exercices-solutions.md
    └── code-solutions.ipynb
```

---

## FORMAT DES FICHIERS

### A. Fichier THEORIE.md

```markdown
# Module XX: Titre du Module

## Objectifs d'apprentissage
A la fin de ce module, tu seras capable de:
- [ ] Objectif 1 (verbe d'action + resultat mesurable)
- [ ] Objectif 2
- [ ] Objectif 3

## Prerequis
- Module(s) requis: [liens]
- Concepts cles: [liste]

## Plan
1. Section 1
2. Section 2
3. Section 3

---

## 1. Section 1

### 1.1 Concept

[Explication claire et concise]

**Definition**
> Definition formelle encadree

**Intuition**
Explication intuitive, analogie, ou exemple du monde reel.

**Formule**
$$
formule\_mathematique
$$

**Exemple**
Exemple numerique detaille etape par etape.

### 1.2 Concept suivant
[...]

---

## Points cles a retenir
- Point 1
- Point 2
- Point 3

## Pour aller plus loin
- Reference livre: [page]
- Paper academique: [lien]
- Video: [lien]

## Prochaine etape
-> Module suivant: [lien]
```

---

### B. Fichier CODE.ipynb (Jupyter Notebook)

Structure standard d'un notebook:

```
1. EN-TETE
   - Titre et objectifs
   - Imports et setup

2. SECTION THEORIQUE RAPIDE
   - Rappel des formules cles
   - Lien vers THEORIE.md

3. IMPLEMENTATION GUIDEE
   - Code commente etape par etape
   - Cellules executables
   - Visualisations

4. EXERCICES INTERACTIFS
   - Cellules a completer (TODO)
   - Tests de validation

5. APPLICATIONS
   - Donnees reelles
   - Cas pratique complet
```

**Conventions de code:**

```python
# ============================================================
# SECTION: Nom de la section
# ============================================================

def fonction_exemple(param: float) -> float:
    """
    Description courte de la fonction.

    Parameters
    ----------
    param : float
        Description du parametre

    Returns
    -------
    float
        Description du retour

    Example
    -------
    >>> fonction_exemple(1.0)
    2.0
    """
    # Implementation
    return param * 2


# --- Sous-section ---

# TODO: A completer par l'etudiant
# Indice: utiliser la formule X
```

---

### C. Fichier EXERCICES.md

```markdown
# Exercices - Module XX

## Niveau 1: Comprehension

### Exercice 1.1
**Enonce**: [Question directe sur un concept]

**Indice**: [Si necessaire]

---

### Exercice 1.2
[...]

---

## Niveau 2: Application

### Exercice 2.1
**Contexte**: [Situation concrete]

**Donnees**:
- Variable 1 = valeur
- Variable 2 = valeur

**Questions**:
a) Question 1
b) Question 2
c) Question 3

---

## Niveau 3: Analyse

### Exercice 3.1
**Cas d'etude**: [Scenario reel ou realiste]

**Objectif**: [Ce qu'on cherche a determiner]

**Contraintes**: [Limites et hypotheses]

**Livrable**: [Format attendu de la reponse]

---

## Niveau 4: Synthese (Optionnel)

### Defi
[Probleme ouvert combinant plusieurs modules]
```

---

### D. Fichier flashcards.md

Format optimise pour revision active:

```markdown
# Flashcards - Module XX

## Definitions

Q: Qu'est-ce que [concept] ?
A: [Definition concise]

---

Q: Quelle est la formule de [X] ?
A: $$ formule $$

---

## Applications

Q: Dans quel cas utilise-t-on [technique] ?
A: [Contexte d'utilisation]

---

Q: Quelles sont les 3 hypotheses de [modele] ?
A: 1) ... 2) ... 3) ...

---

## Pieges courants

Q: Quelle erreur frequente fait-on avec [concept] ?
A: [Description de l'erreur et correction]
```

---

## PROGRESSION ET EVALUATION

### Systeme de niveaux

| Niveau | Description | Critere |
|--------|-------------|---------|
| 1 | Novice | Peut definir les concepts |
| 2 | Debutant | Peut appliquer les formules |
| 3 | Intermediaire | Peut resoudre des problemes standards |
| 4 | Avance | Peut analyser des cas complexes |
| 5 | Expert | Peut creer des solutions originales |

### Checklist de completion par module

```markdown
## Module XX - Progression

- [ ] Lecture de THEORIE.md
- [ ] Execution de CODE.ipynb
- [ ] Exercices Niveau 1 (3/3)
- [ ] Exercices Niveau 2 (3/3)
- [ ] Exercices Niveau 3 (2/2)
- [ ] Mini-projet complete
- [ ] Flashcards revisees (J+1, J+3, J+7, J+14)
- [ ] Quiz final reussi (>80%)
```

### Calendrier de revision (Spaced Repetition)

```
Jour 0: Etude du module
Jour 1: Revision flashcards (10 min)
Jour 3: Revision flashcards (10 min)
Jour 7: Revision flashcards + 1 exercice (20 min)
Jour 14: Quiz rapide (15 min)
Jour 30: Revision generale (30 min)
```

---

## FORMAT D'UNE SESSION D'ETUDE

**Session standard: 90 minutes**

```
[0-5 min]   Revision rapide module precedent (flashcards)
[5-25 min]  Lecture theorie (THEORIE.md)
[25-30 min] Pause
[30-60 min] Implementation (CODE.ipynb)
[60-65 min] Pause
[65-85 min] Exercices (EXERCICES.md)
[85-90 min] Creation flashcards personnelles
```

**Session courte: 30 minutes**
- Revision flashcards (10 min)
- 2-3 exercices (20 min)

**Session projet: 2-3 heures**
- Travail sur projet capstone
- Pas d'interruption

---

## OUTILS RECOMMANDES

### Environnement
- **IDE**: VSCode avec extensions Python/Jupyter
- **Notebooks**: JupyterLab ou VSCode Jupyter
- **Terminal**: pour git et scripts

### Bibliotheques Python
```python
# Core
numpy
pandas
matplotlib
scipy

# Finance
yfinance
pandas-datareader
quantlib  # optionnel

# Stats/ML
statsmodels
scikit-learn
pytorch  # pour ML avance

# Visualisation
seaborn
plotly
```

### Revision
- **Obsidian** ou **Notion**: pour notes liees
- **Anki**: pour flashcards avec spaced repetition
- Ce cours: fichiers flashcards.md convertibles

---

## CONSEILS D'APPRENTISSAGE

### A faire
1. **Coder soi-meme**: ne pas copier-coller, retaper
2. **Expliquer a voix haute**: technique Feynman
3. **Faire des erreurs**: elles ancrent la memoire
4. **Connecter**: lier chaque concept aux precedents
5. **Appliquer**: utiliser des donnees reelles rapidement

### A eviter
1. **Lecture passive**: toujours avoir un stylo/clavier
2. **Sauter les exercices**: la pratique est essentielle
3. **Avancer trop vite**: maitriser avant de continuer
4. **Ignorer les prerequis**: les maths sont fondamentales
5. **Etudier trop longtemps**: sessions de 90 min max

---

## STRUCTURE DES PROJETS CAPSTONE

Chaque projet suit le format professionnel:

```
Projet-XX/
├── README.md               # Description et objectifs
├── rapport.md              # Rapport final structure
├── notebooks/
│   ├── 01-exploration.ipynb
│   ├── 02-implementation.ipynb
│   └── 03-analyse.ipynb
├── src/
│   ├── __init__.py
│   ├── data.py            # Chargement donnees
│   ├── models.py          # Modeles implementes
│   └── utils.py           # Fonctions utilitaires
├── tests/
│   └── test_models.py
├── data/
│   └── .gitkeep
└── requirements.txt
```

### Format du rapport

```markdown
# Projet: Titre

## 1. Introduction
- Contexte et motivation
- Objectifs
- Donnees utilisees

## 2. Methodologie
- Approche theorique
- Choix d'implementation
- Hypotheses

## 3. Implementation
- Architecture du code
- Algorithmes cles
- Defis rencontres

## 4. Resultats
- Metriques de performance
- Visualisations
- Analyse

## 5. Discussion
- Limites
- Ameliorations possibles
- Comparaison avec litterature

## 6. Conclusion

## References
```

---

## SOURCES PEDAGOGIQUES

- [Teaching and Learning with Jupyter](https://jupyter4edu.github.io/jupyter-edu-book/)
- [Anki Manual - Background](https://docs.ankiweb.net/background.html)
- [Harvard - Pedagogical Best Practices](https://teachremotely.harvard.edu/best-practices)
- [Active Learning Research](https://guides.lib.uw.edu/research/activelearningclass/research)
- Springer: "Pedagogical Framework for Quantitative Disciplines" (2024)

---

*Methodologie creee le 2026-01-15*
