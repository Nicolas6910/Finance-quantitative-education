# Guidelines - Creation des Modules du Cours

Ce document contient toutes les specifications pour creer chaque module du cours de Finance Quantitative.

**Objectif:** Creer un cours equivalent aux meilleurs programmes MFE (Berkeley Haas, Baruch, Columbia, CMU).

---

## 0. Sources Academiques de Reference

### Textbooks Fondamentaux (obligatoires)

| Livre | Auteur | Usage |
|-------|--------|-------|
| **Options, Futures, and Other Derivatives** | John C. Hull | Derivatives, pricing, risk - Standard industrie |
| **Stochastic Calculus for Finance I & II** | Steven Shreve | Calcul stochastique - Reference mathematique MFE |
| **The Concepts and Practice of Mathematical Finance** | Mark Joshi | Theorie + pratique, exercices |
| **Paul Wilmott on Quantitative Finance** | Paul Wilmott | Reference complete 3 volumes |
| **Against the Gods: The Remarkable Story of Risk** | Peter Bernstein | Histoire de la finance |

### Preparation Entretiens Quant

| Livre | Usage |
|-------|-------|
| **Heard on the Street** - Timothy Crack | Brainteasers, puzzles classiques |
| **A Practical Guide to Quantitative Finance Interviews** - Xinfeng Zhou | 200+ problemes reels |
| **150 Most Frequently Asked Questions on Quant Interviews** - Stefanica, Radoicic, Wang (Baruch) | Questions standards |

### Certifications de Reference

| Certification | Niveau | Usage |
|--------------|--------|-------|
| **CFA Level I, II, III** | Professionnel | Portfolio Management, Ethics |
| **FRM (Financial Risk Manager)** | Professionnel | Risk Management |
| **Certificate in Quantitative Finance (CQF)** | Specialise | Quant Finance |

### Sources Academiques en Ligne

- [QuantNet](https://quantnet.com/) - Forum MFE, rankings, ressources
- [Wilmott Forums](https://wilmott.com/) - Discussions quant avancees
- [SSRN](https://www.ssrn.com/) - Working papers finance
- [arXiv q-fin](https://arxiv.org/list/q-fin/recent) - Recherche quantitative

### Auteurs Internationaux Complementaires

| Auteur | Nationalite | Specialite | Ouvrage cle |
|--------|-------------|------------|-------------|
| **Paul Wilmott** | UK | Quant finance complete | Paul Wilmott on Quantitative Finance |
| **Riccardo Rebonato** | Italie/UK | Volatilite, taux | Volatility and Correlation |
| **Jim Gatheral** | UK | Surface de volatilite | The Volatility Surface |
| **Emanuel Derman** | Afrique du Sud | Philosophie quant | My Life as a Quant |
| **Nassim Taleb** | Liban/US | Risque, Black Swans | Dynamic Hedging, Black Swan |
| **Benoit Mandelbrot** | France/US | Fractales, fat tails | The (Mis)Behavior of Markets |
| **Nicole El Karoui** | France | Calcul stochastique | Reference francaise ENSAE |
| **Damiano Brigo** | Italie | Credit derivatives | Interest Rate Models |

### Programmes MFE Internationaux de Reference

| Region | Programme | Specialite |
|--------|-----------|------------|
| **USA** | Berkeley Haas, Baruch, CMU, Columbia | Standards mondiaux |
| **UK** | Oxford, Imperial, LSE, Cambridge | Math finance, City of London |
| **France** | ENSAE, X-HEC, El Karoui (Paris 6) | Tradition mathematique |
| **Suisse** | ETH Zurich | Quant research |
| **Italie** | Bocconi | Finance europeenne |
| **Singapour** | NUS | Hub Asie |
| **Hong Kong** | HKUST | Marches chinois |

### Marches Financiers Mondiaux

| Bourse | Pays | Capitalisation | Specialite |
|--------|------|----------------|------------|
| NYSE + NASDAQ | USA | ~50 T$ | Actions, tech |
| Shanghai + Shenzhen | Chine | ~12 T$ | Marche emergent majeur |
| Tokyo Stock Exchange | Japon | ~6 T$ | 3eme mondiale |
| Euronext | Europe | ~7 T$ | Paris, Amsterdam, Bruxelles |
| London Stock Exchange | UK | ~4 T$ | Finance internationale |
| Hong Kong | HK | ~5 T$ | Porte vers Chine |
| Deutsche Borse | Allemagne | ~2 T$ | Derives (Eurex) |

### Regulateurs Internationaux

| Regulateur | Juridiction | Role |
|------------|-------------|------|
| **SEC** | USA | Securities, reference mondiale |
| **CFTC** | USA | Futures, commodities |
| **FCA** | UK | Financial Conduct Authority |
| **ESMA** | Europe | European Securities and Markets Authority |
| **BaFin** | Allemagne | Regulateur allemand |
| **AMF** | France | Autorite des Marches Financiers |
| **MAS** | Singapour | Monetary Authority of Singapore |
| **SFC** | Hong Kong | Securities and Futures Commission |
| **FSA** | Japon | Financial Services Agency |

### Accords et Reglementations Internationales

| Regulation | Annee | Portee |
|------------|-------|--------|
| **Bale I, II, III, IV** | 1988-2023 | Capital bancaire mondial |
| **MiFID I, II** | 2007, 2018 | Marches europeens |
| **Dodd-Frank** | 2010 | Reforme US post-2008 |
| **EMIR** | 2012 | Derives OTC Europe |
| **Solvency II** | 2016 | Assurances Europe |

---

## 0.5 Curriculum Complet (Base MFE Berkeley/Baruch)

### PARTIE I - HISTOIRE & CONTEXTE (Modules 1-4)
Pas dans les MFE mais essentiel pour comprendre l'evolution

| Module | Titre | Duree |
|--------|-------|-------|
| 01 | Origines de la Finance (Antiquite - 1700) | 60 min |
| 02 | Fondations Mathematiques (1654-1900) | 75 min |
| 03 | Revolution Quantitative (1952-1973) | 75 min |
| 04 | Ere Moderne et Crises (1987-2023) | 90 min |

### PARTIE II - MATHEMATIQUES FONDAMENTALES (Modules 5-10)
Prerequis MFE - Niveau Licence/Master 1

| Module | Titre | Reference |
|--------|-------|-----------|
| 05 | Algebre Lineaire pour la Finance | Pre-MFE Baruch |
| 06 | Calcul Differentiel et Integral | Pre-MFE Baruch |
| 07 | Probabilites | Shreve Vol.1 Ch.1-2 |
| 08 | Statistiques et Econometrie | MFE 230E Berkeley |
| 09 | Optimisation et Programmation Lineaire | Portfolio optimization |
| 10 | Analyse Numerique (Monte Carlo, Finite Diff) | MFE 230D Berkeley |

### PARTIE III - PROCESSUS STOCHASTIQUES (Modules 11-14)
Coeur du MFE - Shreve Vol.1 & 2

| Module | Titre | Reference |
|--------|-------|-----------|
| 11 | Mouvement Brownien | Shreve I Ch.3-4 |
| 12 | Calcul d'Ito | Shreve II Ch.4 |
| 13 | Martingales et Pricing Risque-Neutre | Shreve I Ch.5, II Ch.5 |
| 14 | Equations Differentielles Stochastiques | Shreve II Ch.6 |

### PARTIE IV - DERIVATIVES & PRICING (Modules 15-20)
Hull + Shreve applications

| Module | Titre | Reference |
|--------|-------|-----------|
| 15 | Forwards et Futures | Hull Ch.1-5 |
| 16 | Options: Mecanismes et Strategies | Hull Ch.9-12 |
| 17 | Modele Binomial (Cox-Ross-Rubinstein) | Hull Ch.13, Shreve I |
| 18 | Black-Scholes-Merton | Hull Ch.15, Shreve II Ch.6 |
| 19 | Greeks et Hedging | Hull Ch.19 |
| 20 | Options Exotiques et Americaines | Hull Ch.26-27 |

### PARTIE V - GESTION DE PORTEFEUILLE (Modules 21-24)
MFE 230A Berkeley + CFA

| Module | Titre | Reference |
|--------|-------|-----------|
| 21 | Rendement et Risque | CFA Level I |
| 22 | Theorie de Markowitz | Markowitz 1952 |
| 23 | CAPM et APT | Sharpe 1964, Ross 1976 |
| 24 | Mesures de Performance | CFA Level II |

### PARTIE VI - FIXED INCOME (Modules 25-28)
MFE 230I Berkeley

| Module | Titre | Reference |
|--------|-------|-----------|
| 25 | Obligations et Pricing | Hull Ch.4 |
| 26 | Duration et Convexite | Hull Ch.4 |
| 27 | Structure par Terme des Taux | Hull Ch.32 |
| 28 | Derives de Taux (Swaps, Caps, Floors) | Hull Ch.7, 29 |

### PARTIE VII - RISK MANAGEMENT (Modules 29-32)
MFE 230H Berkeley + FRM

| Module | Titre | Reference |
|--------|-------|-----------|
| 29 | Value at Risk (VaR) | Hull Ch.22 |
| 30 | Credit Risk | Hull Ch.24-25 |
| 31 | Risque de Liquidite et Operationnel | FRM |
| 32 | Regulation (Bale, Dodd-Frank) | FRM |

### PARTIE VIII - MACHINE LEARNING EN FINANCE (Modules 33-36)
MFE 230P Berkeley + moderne

| Module | Titre | Reference |
|--------|-------|-----------|
| 33 | Introduction au ML pour la Finance | |
| 34 | Regression et Classification | |
| 35 | Time Series et Forecasting | |
| 36 | Deep Learning et NLP en Finance | |

### PARTIE IX - IMPLEMENTATION (Modules 37-40)
Pratique

| Module | Titre | Reference |
|--------|-------|-----------|
| 37 | Python pour la Finance | |
| 38 | C++ pour le Quant | Pre-MFE Baruch |
| 39 | Trading Algorithmique | |
| 40 | Projet Capstone | MFE 230O Berkeley |

---

## 1. Structure de chaque module

Chaque module doit contenir les sections suivantes dans cet ordre:

```
1. Header (titre, niveau, duree, prerequis)
2. Image d'introduction
3. Objectifs (liste)
4. Timeline (si pertinent historiquement)
5. Contenu theorique (sections h2/h3)
6. Graphiques interactifs (Chart.js)
7. Exercices (3 niveaux)
8. Flashcards
9. Ressources (documentaires, lectures)
10. Resume
11. Navigation (precedent/suivant)
```

---

## 2. Style visuel

### Couleurs (variables CSS)
```css
--bg-dark: #0a0a0a;        /* Fond principal */
--bg-card: #111111;        /* Fond des boxes */
--text: #ffffff;           /* Titres */
--text-body: #e0e0e0;      /* Corps de texte */
--text-muted: #999999;     /* Texte secondaire */
--accent-blue: #0066ff;    /* Titres, liens (couleur par defaut) */
--accent-red: #ff3333;     /* NOTIONS IMPORTANTES uniquement */
```

### IMPORTANT: Utilisation du rouge (text-red)

Le rouge est RESERVE aux **notions financieres importantes** qui auront des definitions.

**A METTRE EN ROUGE:**
- Concepts financiers: esperance mathematique, aversion au risque, mouvement brownien
- Termes techniques: prime de risque, responsabilite limitee, partie double
- Instruments: contrats a terme, derives, sukuk

**NE PAS METTRE EN ROUGE:**
- Dates (1602, 1900, etc.)
- Pourcentages (90%, 18%)
- Noms de personnes (Pascal, Bachelier)
- Noms d'entreprises (VOC, Banco Medici)
- Titres de livres

```html
<!-- CORRECT -->
<p>Le concept de <span class="text-red">prime de risque</span> explique...</p>

<!-- INCORRECT -->
<p>En <span class="text-red">1602</span>, la VOC...</p>
```

### Typographie
- Police: Inter, system fonts
- Body: 17px, line-height 1.8
- H1: 48px (titre module)
- H2: 32px (sections principales)
- H3: 24px (sous-sections)
- H4: 14px uppercase (labels)

### Regles de style
- PAS d'emojis
- PAS de bordures arrondies
- Rouge uniquement pour notions importantes (voir section ci-dessus)
- Images centrees, object-fit: contain
- Boxes sans couleur (juste `class="box"`)

### ACCENTS FRANCAIS (OBLIGATOIRE)

Tout le contenu doit avoir les accents francais corrects:

| Incorrect | Correct |
|-----------|---------|
| mathematiques | mathématiques |
| esperance | espérance |
| theoreme | théorème |
| systeme | système |
| probleme | problème |
| economie | économie |
| marche | marché |
| interet | intérêt |
| societe | société |
| siecle | siècle |
| premiere | première |
| aleatoire | aléatoire |

### PERSPECTIVE INTERNATIONALE (OBLIGATOIRE)

Chaque module historique doit inclure des contributions de plusieurs civilisations/regions:

| Region | Contributions a mentionner |
|--------|---------------------------|
| Mesopotamie | Code Hammurabi, premiers prets, interet |
| Grece antique | Trapezites, nautika daneia |
| Rome | Argentarii, Societas Publicanorum |
| Monde islamique | Mudaraba, Musharaka, Hawala, Sukuk |
| Chine | Papier-monnaie, lettres de change |
| Italie | Banques Medicis, partie double |
| Pays-Bas | VOC, Bourse Amsterdam |
| UK/USA | Developpements modernes |

Ne pas presenter la finance comme uniquement occidentale.

---

## 2.5 Sidebar avec sous-menus

### Structure HTML de la sidebar

```html
<nav class="sidebar">
    <div class="sidebar-title">Finance Quantitative</div>
    <ul>
        <li class="partie">I. Histoire</li>
        <li class="has-submenu">
            <a href="#" onclick="toggleSubmenu(this, 'module1')" class="module-link active">01. Origines</a>
            <ul class="submenu open">
                <li><a href="#exercices" onclick="scrollToSection('module1', 'exercices')">Exercices</a></li>
                <li><a href="#flashcards" onclick="scrollToSection('module1', 'flashcards')">Flashcards</a></li>
            </ul>
        </li>
        <li><a href="#" onclick="showModule('module2')">02. Fondations Math</a></li>
        <!-- Autres modules... -->
    </ul>
</nav>
```

### CSS pour les sous-menus

```css
.sidebar .submenu {
    display: none;
    margin: 0;
    padding: 0;
}

.sidebar .submenu.open {
    display: block;
}

.sidebar .submenu li {
    margin: 0;
}

.sidebar .submenu a {
    font-size: 13px;
    padding: 8px 25px 8px 38px;
    color: var(--text-muted);
    border-left: 2px solid transparent;
    display: block;
}

.sidebar .submenu a:hover {
    color: var(--accent-blue);
    background: var(--bg-hover);
}

.sidebar .has-submenu {
    margin-bottom: 0;
}
```

### JavaScript pour la navigation

```javascript
function toggleSubmenu(element, moduleId) {
    event.preventDefault();
    // Afficher le module
    document.querySelectorAll('.module').forEach(m => m.classList.remove('active'));
    document.getElementById(moduleId).classList.add('active');
    // Activer le lien
    document.querySelectorAll('.sidebar a').forEach(a => a.classList.remove('active'));
    element.classList.add('active');
    // Toggle submenu
    const submenu = element.nextElementSibling;
    document.querySelectorAll('.submenu').forEach(s => s.classList.remove('open'));
    submenu.classList.add('open');
    window.scrollTo(0, 0);
}

function scrollToSection(moduleId, sectionId) {
    event.preventDefault();
    const module = document.getElementById(moduleId);
    if (!module.classList.contains('active')) {
        document.querySelectorAll('.module').forEach(m => m.classList.remove('active'));
        module.classList.add('active');
    }
    document.getElementById(sectionId).scrollIntoView({ behavior: 'smooth', block: 'start' });
}
```

### Important: IDs des sections

Les sections Exercices et Flashcards doivent avoir des IDs:

```html
<h2 id="exercices">Exercices</h2>
<!-- ... -->
<h2 id="flashcards">Flashcards</h2>
```

---

## 3. Images

### Source: Wikimedia Commons via API

Pour recuperer une image, utiliser l'API MediaWiki:

```bash
curl -s "https://commons.wikimedia.org/w/api.php?action=query&titles=File:NOM_FICHIER.jpg&prop=imageinfo&iiprop=url&format=json"
```

La reponse JSON contient l'URL directe dans `query.pages.[id].imageinfo[0].url`

### Format HTML pour les images
```html
<figure class="image-container">
    <img src="URL_WIKIMEDIA" alt="Description">
    <figcaption>Legende - Source</figcaption>
</figure>
```

### Criteres de selection des images
- Images historiques authentiques (peintures, gravures, photos d'epoque)
- Portraits des personnages cles
- Documents originaux (manuscrits, tableaux)
- Pas d'images generiques/stock

---

## 4. Graphiques (Chart.js)

### Types de graphiques par usage
- **Line chart**: Evolution temporelle (prix, indices)
- **Bar chart**: Comparaisons (repartition, classements)
- **Doughnut**: Proportions (allocation, composition)

### Template de graphique
```html
<div class="chart-container">
    <canvas id="chartId"></canvas>
</div>

<script>
new Chart(document.getElementById('chartId'), {
    type: 'line',
    data: {
        labels: [...],
        datasets: [{
            label: 'Label',
            data: [...],
            borderColor: '#0066ff',
            backgroundColor: 'rgba(0, 102, 255, 0.1)',
            fill: true,
            tension: 0.4
        }]
    },
    options: {
        responsive: true,
        plugins: {
            legend: { display: false },
            title: {
                display: true,
                text: 'Titre du graphique',
                color: '#e0e0e0',
                font: { size: 12, weight: 'normal' }
            }
        },
        scales: {
            x: { grid: { color: '#222' }, ticks: { color: '#e0e0e0' } },
            y: { grid: { color: '#222' }, ticks: { color: '#e0e0e0' } }
        }
    }
});
</script>
```

---

## 5. Contenu textuel

### Densite de texte
- Chaque section h2 doit avoir au moins 2-3 paragraphes d'introduction
- Chaque concept doit etre explique avec contexte historique + application moderne
- Utiliser des exemples concrets et chiffres

### Boxes (SIMPLIFIEES)

**IMPORTANT:** Utiliser UNIQUEMENT la classe `box` sans variante de couleur.
Les anciennes classes box-purple, box-green, box-orange, box-red sont DEPRECIEES.

```html
<!-- Definition avec notion en rouge -->
<div class="box">
    <h4>Definition : <span class="text-red">Terme Important</span></h4>
    <p>Explication...</p>
</div>

<!-- Concept cle -->
<div class="box">
    <h4>Concept : <span class="text-red">Nom du Concept</span></h4>
    <p>Explication...</p>
</div>

<!-- Information generale -->
<div class="box">
    <h4>Titre</h4>
    <p>Contenu...</p>
</div>
```

Le rouge dans les titres de box met en valeur la notion qui sera definie.

### Citations
```html
<blockquote>
    <p>Texte de la citation...</p>
    <cite>Auteur, Source, Date</cite>
</blockquote>
```

---

## 6. Exercices Interactifs

### Types d'exercices disponibles

1. **Definitions** (textarea) - Pour reponses textuelles libres
2. **Chronologie** (input number) - Pour ordonner des evenements
3. **Calculs** (input number/text) - Pour reponses numeriques
4. **QCM** (checkboxes) - Pour choix multiples
5. **Analyse** (textarea) - Pour reflexion avec detection de mots-cles

### Template Exercice Definition (textarea)

```html
<div class="exercise-box">
    <h4>Exercice X.X - Titre</h4>
    <p>Consigne...</p>

    <p><strong>a) Terme 1 :</strong></p>
    <textarea class="exercise-input" id="def1" rows="2" placeholder="Votre definition..."></textarea>

    <button class="check-btn" onclick="checkDefinitions()">Verifier mes reponses</button>
    <div id="feedback-def" class="feedback"></div>

    <details>
        <summary>Voir la solution</summary>
        <div class="solution">
            <p><strong>a)</strong> Solution...</p>
        </div>
    </details>
</div>
```

### Template Exercice Chronologie (input number)

```html
<div class="exercise-box">
    <h4>Exercice X.X - Chronologie</h4>
    <p>Numerotez ces evenements (1 = le plus ancien) :</p>

    <div class="chronology-item">
        <input type="number" class="exercise-number-input" id="chrono1" min="1" max="6" placeholder="?">
        <span>Evenement A</span>
    </div>
    <div class="chronology-item">
        <input type="number" class="exercise-number-input" id="chrono2" min="1" max="6" placeholder="?">
        <span>Evenement B</span>
    </div>

    <button class="check-btn" onclick="checkChronology()">Verifier</button>
    <div id="feedback-chrono" class="feedback"></div>
</div>
```

### Template Exercice Calcul

```html
<div class="exercise-box">
    <h4>Exercice X.X - Calcul</h4>
    <p><strong>Donnees :</strong> ...</p>

    <div class="calc-row">
        <span class="calc-label">Resultat =</span>
        <input type="number" class="exercise-calc-input" id="calc1" placeholder="Ex: 90">
        <span class="calc-unit">%</span>
    </div>

    <button class="check-btn" onclick="checkCalc()">Verifier</button>
    <div id="feedback-calc" class="feedback"></div>
</div>
```

### Template Exercice QCM (checkboxes)

```html
<div class="exercise-box">
    <h4>Exercice X.X - QCM</h4>
    <p>Cochez les bonnes reponses :</p>

    <div style="margin: 15px 0;">
        <label style="display: block; padding: 8px 0; cursor: pointer;">
            <input type="checkbox" id="qcm1"> Option A (correcte)
        </label>
        <label style="display: block; padding: 8px 0; cursor: pointer;">
            <input type="checkbox" id="qcm2"> Option B (incorrecte)
        </label>
    </div>

    <button class="check-btn" onclick="checkQCM()">Verifier</button>
    <div id="feedback-qcm" class="feedback"></div>
</div>
```

### CSS pour les exercices interactifs

```css
/* Exercices base */
details { margin-top: 15px; }
summary { cursor: pointer; color: var(--accent-blue); font-weight: 500; padding: 10px 0; }
summary:hover { text-decoration: underline; }
.solution { margin-top: 15px; padding: 20px; background: var(--bg-hover); border-left: 3px solid var(--accent-green); }
.exercise-box { background: var(--bg-card); padding: 25px 30px; margin: 20px 0; border-left: 3px solid var(--border); }

/* Inputs */
.exercise-input {
    width: 100%;
    background: var(--bg-dark);
    border: 1px solid var(--border);
    color: var(--text-body);
    padding: 12px 15px;
    font-size: 15px;
    font-family: inherit;
    margin: 8px 0 15px;
    resize: vertical;
}
.exercise-input:focus { outline: none; border-color: var(--accent-blue); }
.exercise-input::placeholder { color: var(--text-muted); }

.exercise-number-input {
    width: 50px;
    background: var(--bg-dark);
    border: 1px solid var(--border);
    color: var(--text);
    padding: 8px 12px;
    font-size: 15px;
    text-align: center;
    margin-right: 10px;
}

.exercise-calc-input {
    width: 150px;
    background: var(--bg-dark);
    border: 1px solid var(--border);
    color: var(--text);
    padding: 10px 15px;
    font-size: 16px;
    font-family: monospace;
}

/* Layout */
.chronology-item {
    display: flex;
    align-items: center;
    padding: 10px 0;
    border-bottom: 1px solid var(--border);
}
.chronology-item:last-child { border-bottom: none; }

.calc-row {
    display: flex;
    align-items: center;
    gap: 15px;
    margin: 15px 0;
}
.calc-label { min-width: 200px; color: var(--text-body); }
.calc-unit { color: var(--text-muted); font-size: 14px; }

/* Bouton et feedback */
.check-btn {
    background: var(--accent-blue);
    color: white;
    border: none;
    padding: 12px 25px;
    font-size: 14px;
    font-weight: 500;
    cursor: pointer;
    margin-top: 15px;
}
.check-btn:hover { background: #0055dd; }

.feedback { margin-top: 15px; padding: 15px 20px; display: none; }
.feedback.correct { display: block; background: rgba(0,204,102,0.1); border-left: 3px solid var(--accent-green); color: var(--accent-green); }
.feedback.incorrect { display: block; background: rgba(255,51,51,0.1); border-left: 3px solid var(--accent-red); color: var(--accent-red); }
```

### JavaScript - Fonctions de validation

```javascript
// Validation definitions (verifie que tous les champs sont remplis)
function checkDefinitions() {
    const filled = ['def1', 'def2', 'def3', 'def4'].every(id =>
        document.getElementById(id).value.trim().length > 10
    );
    const feedback = document.getElementById('feedback-def');
    if (filled) {
        feedback.className = 'feedback correct';
        feedback.innerHTML = 'Reponses enregistrees. Comparez avec la solution.';
    } else {
        feedback.className = 'feedback incorrect';
        feedback.innerHTML = 'Completez toutes les definitions (min. 10 caracteres).';
    }
}

// Validation chronologie (compare avec reponses attendues)
function checkChronology() {
    const answers = { chrono1: 4, chrono2: 1, chrono3: 5 }; // A adapter
    let correct = 0;
    for (let id in answers) {
        if (parseInt(document.getElementById(id).value) === answers[id]) correct++;
    }
    const feedback = document.getElementById('feedback-chrono');
    feedback.className = correct === Object.keys(answers).length ? 'feedback correct' : 'feedback incorrect';
    feedback.innerHTML = correct + '/' + Object.keys(answers).length + ' correct.';
}

// Validation calcul numerique
function checkCalc() {
    const val = parseInt(document.getElementById('calc1').value);
    const feedback = document.getElementById('feedback-calc');
    if (val === 90) { // Valeur attendue
        feedback.className = 'feedback correct';
        feedback.innerHTML = 'Correct !';
    } else {
        feedback.className = 'feedback incorrect';
        feedback.innerHTML = 'Incorrect. Verifiez votre calcul.';
    }
}

// Validation QCM (checkboxes)
function checkQCM() {
    const r1 = document.getElementById('qcm1').checked; // doit etre true
    const r2 = document.getElementById('qcm2').checked; // doit etre false
    const feedback = document.getElementById('feedback-qcm');
    if (r1 && !r2) {
        feedback.className = 'feedback correct';
        feedback.innerHTML = 'Correct !';
    } else {
        feedback.className = 'feedback incorrect';
        feedback.innerHTML = 'Verifiez vos reponses.';
    }
}

// Validation analyse (detection mots-cles)
function checkAnalyse() {
    const text = document.getElementById('analyse1').value.toLowerCase();
    const hasKeyword = text.includes('mot-cle1') || text.includes('mot-cle2');
    const feedback = document.getElementById('feedback-analyse');
    if (hasKeyword && text.length > 50) {
        feedback.className = 'feedback correct';
        feedback.innerHTML = 'Bonne analyse !';
    } else {
        feedback.className = 'feedback incorrect';
        feedback.innerHTML = 'Developpez davantage votre reponse.';
    }
}
```

---

## 7. Flashcards

### Structure des flashcards

```html
<h2>Flashcards</h2>

<p>Cliquez sur une carte pour voir la reponse. Revisez a J+1, J+3, J+7, J+14, J+30.</p>

<div class="flashcards-grid">
    <div class="flashcard" onclick="this.classList.toggle('flipped')">
        <div class="flashcard-front">
            <p>Question ?</p>
        </div>
        <div class="flashcard-back">
            <p>Reponse</p>
        </div>
    </div>
    <!-- Autres cartes... -->
</div>
```

### CSS pour les flashcards (a ajouter)
```css
.flashcards-grid {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(280px, 1fr));
    gap: 20px;
    margin: 30px 0;
}

.flashcard {
    height: 180px;
    perspective: 1000px;
    cursor: pointer;
}

.flashcard-front,
.flashcard-back {
    position: absolute;
    width: 100%;
    height: 100%;
    backface-visibility: hidden;
    display: flex;
    align-items: center;
    justify-content: center;
    padding: 20px;
    text-align: center;
    background: var(--bg-card);
    border-left: 3px solid var(--accent-blue);
    transition: transform 0.6s;
}

.flashcard-back {
    background: var(--bg-card);
    border-left-color: var(--accent-green);
    transform: rotateY(180deg);
}

.flashcard.flipped .flashcard-front {
    transform: rotateY(180deg);
}

.flashcard.flipped .flashcard-back {
    transform: rotateY(0deg);
}
```

---

## 8. Ressources

### Format des ressources

```html
<h2>Ressources</h2>

<div class="box">
    <h4>Documentaires</h4>
    <ul>
        <li>
            <strong><a href="URL" target="_blank">Titre</a></strong> - Source (duree)<br>
            <span style="color: var(--text-muted);">Description courte</span>
        </li>
    </ul>
</div>

<div class="box box-purple">
    <h4>Lectures</h4>
    <ul>
        <li><strong>Titre</strong> - Auteur (annee) - Description</li>
    </ul>
</div>
```

### Recherche de ressources
Pour chaque module, rechercher sur:
- Arte.tv (documentaires francais)
- YouTube (documentaires, cours)
- PBS, BBC (documentaires anglais)
- Khan Academy, Coursera (cours)

---

## 9. Liste des modules a creer

### Partie I - Histoire (Modules 1-4)
| Module | Titre | Images cles | Graphiques |
|--------|-------|-------------|------------|
| 01 | Origines de la Finance | Hammurabi, Medicis, VOC, Tulipe | Prix tulipes, Repartition VOC |
| 02 | Fondations Mathematiques (1654-1900) | Pascal, Bernoulli, Bachelier | Marche aleatoire, Distribution normale |
| 03 | Revolution Quantitative (1952-1973) | Markowitz, Sharpe, Black-Scholes | Frontiere efficiente, Smile volatilite |
| 04 | Ere Moderne et Crises | Crash 1987, LTCM, 2008 | VIX historique, Drawdowns |

### Partie II - Mathematiques (Modules 5-8)
| Module | Titre | Concepts cles | Graphiques |
|--------|-------|---------------|------------|
| 05 | Algebre Lineaire | Vecteurs, Matrices, Valeurs propres | Transformation lineaire |
| 06 | Calcul Differentiel | Derivees, Integrales, Taylor | Tangente, Aire sous courbe |
| 07 | Probabilites | Distributions, Esperance, Variance | Normale, Log-normale |
| 08 | Statistiques | Regression, Tests, Econometrie | Nuage de points, Residus |

### Partie III - Processus Stochastiques (Modules 9-12)
| Module | Titre | Concepts cles | Graphiques |
|--------|-------|---------------|------------|
| 09 | Mouvement Brownien | Wiener, Proprietes, Simulations | Trajectoires browniennes |
| 10 | Calcul d'Ito | Lemme Ito, SDE, Solutions | GBM simule |
| 11 | Martingales | Definition, Proprietes, Applications | Martingale vs non-martingale |
| 12 | Applications | Pricing, Couverture | Convergence MC |

### Partie IV - Gestion de Portefeuille (Modules 13-16)
| Module | Titre | Concepts cles | Graphiques |
|--------|-------|---------------|------------|
| 13 | Rendement et Risque | Moyenne, Volatilite, Sharpe | Distribution rendements |
| 14 | Theorie de Markowitz | Optimisation, Frontiere | Frontiere efficiente |
| 15 | CAPM et APT | Beta, SML, Facteurs | Security Market Line |
| 16 | Mesures de Performance | Sharpe, Sortino, Alpha | Comparaison fonds |

---

## 10. Checklist avant publication

Pour chaque module, verifier:

### Contenu
- [ ] Header complet (titre, niveau, duree, prerequis)
- [ ] Image d'introduction (source Wikimedia)
- [ ] Objectifs (4-6 points)
- [ ] Contenu theorique (min 2000 mots)
- [ ] Au moins 2 graphiques Chart.js
- [ ] 3-4 boxes (classe `box` uniquement, pas de variantes colorees)
- [ ] Au moins 1 citation
- [ ] 6+ exercices (2 par niveau)
- [ ] 10+ flashcards
- [ ] 3+ ressources (documentaires/lectures)
- [ ] Resume avec dates et concepts cles

### Style (CRITIQUE)
- [ ] **Accents francais** sur tous les mots (mathematiques, esperance, systeme, etc.)
- [ ] **Rouge uniquement sur notions** (PAS sur dates, noms, pourcentages)
- [ ] **Pas d'emojis** nulle part
- [ ] **Pas de boxes colorees** (box-purple, box-green, etc. sont INTERDITS)
- [ ] **Perspective internationale** (pas uniquement occidentale)

### Technique
- [ ] Navigation fonctionnelle
- [ ] Images qui s'affichent correctement
- [ ] Balises HTML correctes (`<details>` pas `<détails>`)

---

## 11. Commandes utiles

### Recherche image Wikimedia
```bash
curl -s "https://commons.wikimedia.org/w/api.php?action=query&titles=File:FILENAME&prop=imageinfo&iiprop=url&format=json" | python3 -m json.tool
```

### Serveur local
```bash
cd "/Users/nicolaschalopin/Documents/project/Finance quantitative education"
python3 -m http.server 8080
```

### Test URL image
```bash
curl -sI "URL" | head -1
```

---

## 12. Notions en rouge par module

### Module 01 - Origines de la Finance (25 notions)
- Contrats de prets, Reconnaissances de dette, Contrats a terme
- prime de risque, trapezites, nautika daneia, assurance maritime
- argentarii, Societas Publicanorum, Partes (actions), Personnalite juridique, Dividendes
- riba, partage des risques, Mudaraba, Musharaka, Hawala, Sukuk
- responsabilite limitee, partie double
- Herding behavior, FOMO, Overconfidence, Mean reversion, comportement moutonne

### Module 02 - Fondations Mathematiques (17 notions)
- Esperance Mathematique, Triangle de Pascal, coefficients binomiaux
- Paradoxe de Saint-Petersbourg, utilite, Fonction d'Utilite Logarithmique
- aversion au risque, prime de risque
- mouvement brownien, Marche aleatoire
- Hypothese des marches efficients, Modele Black-Scholes
- Distribution normale, Value at Risk (VaR), Calcul stochastique, derives

### Module 03 - Revolution Quantitative (a definir)
- Frontiere efficiente, diversification, correlation
- Beta, alpha, rendement ajuste du risque
- Volatilite implicite, smile de volatilite
- ...

### Module 04 - Ere Moderne (a definir)
- VaR, Expected Shortfall, stress test
- Risque systemique, Too Big To Fail
- Credit Default Swap, CDO, titrisation
- ...

---

## 13. Sources de contenu par module

### Module 02 - Fondations Mathematiques
- Pascal/Fermat: Correspondance sur le probleme des partis (1654)
- Bernoulli: Specimen Theoriae Novae (1738)
- Bachelier: Theorie de la Speculation (1900)

### Module 03 - Revolution Quantitative
- Markowitz: Portfolio Selection (1952)
- Sharpe: CAPM (1964)
- Black-Scholes: Option Pricing (1973)

### Module 04 - Ere Moderne
- Black Monday 1987
- Crise LTCM 1998
- Crise Subprimes 2008
- Flash Crash 2010
