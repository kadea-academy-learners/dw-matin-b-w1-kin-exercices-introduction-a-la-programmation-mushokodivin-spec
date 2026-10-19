# 📊 Évaluation automatique — Semaine 13 (JavaScript)

> Générée le 2026-10-19 19:04 UTC · commit `c787aaf` · évaluation déterministe basée uniquement sur le cahier d'exercices et le barème.

## Note finale : **3 / 15**

Exercices : **53 / 95** · Parfaits : 6 / 19 · Non rendus : 7

## 1. Résultat par exercice

| Exercice | Note /5 | Statut | Tests | Recherche /3 | Commit | Feedback |
|---|:-:|---|:-:|:-:|:-:|---|
| **F1** — Ma carte d'apprenant | **4** | 🟡 Règles non respectées | 5/5 | 0 | ❌ | Le résultat est bon, mais les règles ne sont pas toutes respectées : const par défaut, justification en commentaire, un seul gabarit littéral.<br>• Justifie en commentaire le choix de `const` ou `let` pour tes variables.<br>📚 Recherche non rédigée. |
| **F2** — Le convertisseur de saisie | **4** | 🟡 Règles non respectées | 3/3 | 0 | ✅ | Résultat correct, mais il manque une notion imposée : Number() ou tes explications/prédictions en commentaire.<br>• Explique en commentaire pourquoi le résultat est faux et note tes prédictions avant de tester.<br>📚 Recherche non rédigée. |
| **F3** — Pair ou impair : le tirage des tickets | **5** | ✅ Parfait | 3/3 | 0 | ✅ | Parfait ! Modulo et égalité stricte maîtrisés, les cas 17, 24 et 0 sont corrects.<br>📚 Recherche non rédigée. |
| **F4** — Le contrôleur du bus | **5** | ✅ Parfait | 5/5 | 0 | ✅ | Parfait ! Ternaire simple et conditions à trois branches corrects, bornes respectées.<br>📚 Recherche non rédigée. |
| **F5** — Ma première fonction fléchée | **5** | ✅ Parfait | 4/4 | 0 | ✅ | Parfait ! Fonctions fléchées concises avec retour implicite et gabarit littéral.<br>📚 Recherche non rédigée. |
| **F6** — Le compte à rebours | **5** | ✅ Parfait | 2/2 | 0 | ✅ | Parfait ! Les 3 parties de la boucle `for` sont maîtrisées et `continue` est bien placé.<br>📚 Recherche non rédigée. |
| **M1** — FizzBuzz kinois | **4** | 🟡 Règles non respectées | 3/3 | 0 | ✅ | Le FizzBuzz est juste, mais respecte les consignes : boucle for, %, === et explication de l'ordre en commentaire.<br>• Explique en commentaire pourquoi l'ordre de tes conditions est important.<br>📚 Recherche non rédigée. |
| **M2** — Le distributeur automatique (DAB) | **0** | ⬜ Non rendu | — | 0 | ❌ | Exercice non commencé : écris ton code dans `semaine-13/M2-dab.js` sous l'énoncé.<br>📚 Recherche non rédigée. |
| **M3** — Le détecteur de champs vides (Truthy / Falsy) | **0** | ⬜ Non rendu | — | 0 | ❌ | Exercice non commencé : écris ton code dans `semaine-13/M3-champs-vides.js` sous l'énoncé.<br>📚 Recherche non rédigée. |
| **M4** — Le score par défaut : \|\| contre ?? | **0** | ⬜ Non rendu | — | 0 | ❌ | Exercice non commencé : écris ton code dans `semaine-13/M4-score-defaut.js` sous l'énoncé.<br>📚 Recherche non rédigée. |
| **M5** — La vitre teintée (portée de bloc) | **0** | ⬜ Non rendu | — | 0 | ❌ | Exercice non commencé : écris ton code dans `semaine-13/M5-vitre-teintee.js` sous l'énoncé.<br>📚 Recherche non rédigée. |
| **M6** — Le détective du return | **0** | ⬜ Non rendu | — | 0 | ❌ | Exercice non commencé : écris ton code dans `semaine-13/M6-detective-return.js` sous l'énoncé.<br>📚 Recherche non rédigée. |
| **M7** — La tirelire numérique | **0** | ⬜ Non rendu | — | 0 | ❌ | Exercice non commencé : écris ton code dans `semaine-13/M7-tirelire.js` sous l'énoncé.<br>📚 Recherche non rédigée. |
| **M8** — La batterie qui se décharge | **0** | ⬜ Non rendu | — | 0 | ❌ | Exercice non commencé : écris ton code dans `semaine-13/M8-batterie.js` sous l'énoncé.<br>📚 Recherche non rédigée. |
| **A1** — Kadea Express v2 : le calculateur de livraison | **5** | ✅ Parfait | 9/9 | 0 | ❌ | Parfait ! Règles métier, paramètre par défaut, TVA et arrondi corrects, y compris aux bornes.<br>📚 Recherche non rédigée. |
| **A2** — Le moteur de paie v2 | **5** | ✅ Parfait | 7/7 | 0 | ✅ | Parfait ! Accumulateur avec .forEach(), heures supplémentaires et recherche du maximum corrects.<br>📚 Recherche non rédigée. |
| **A3** — L'inventaire en console | **3** | 🟠 Résultat incorrect | 4/7 | 0 | ❌ | Un résultat est faux ou introuvable : stocke chaque résultat (filter, map) dans une variable ou affiche-le, et gère le cas undefined de .find() avec « Produit introuvable ».<br>• chercherProduit(104) renvoie ReferenceError: chercherProduit is not defined au lieu de l'objet de la gourde.<br>• `chercherProduit(999)` renvoie ReferenceError: chercherProduit is not defined au lieu de 'Produit introuvable'.<br>• Affiche le nombre de produits en rupture de stock (2).<br>• Utilise `.find()` dans `chercherProduit`.<br>📚 Recherche non rédigée. |
| **A4** — Le classement de la promo | **4** | 🟡 Règles non respectées | 9/9 | 0 | ❌ | Les résultats sont justes, mais respecte les consignes : boucle dans calculerMoyenne, .map(), .filter(), .find() avec return, if / else if / else.<br>• Mot-clé `function` utilisé (`calculerMoyenne` l.33) : écris une fonction fléchée.<br>• `calculerMoyenne` doit être une fonction fléchée.<br>📚 Recherche non rédigée. |
| **A5** — Le nombre mystère | **4** | 🟡 Règles non respectées | 4/4 | 0 | ❌ | Le jeu fonctionne, mais respecte les consignes : while, Math.random() + Math.floor(), prompt() + Number(), détection de NaN, gabarits littéraux.<br>• `let` jamais réassigné : `saisie`, `nombre` → utilise `const`.<br>📚 Recherche non rédigée. |

## 2. Barème officiel (/15)

| Critère | Niveau | Points /3 | Feedback |
|---|---|:-:|---|
| Fondations : variables, types primitifs et conversions | En développement : À améliorer (43 %) | **1** | let utilisé partout par réflexe, ou confusion entre null et undefined. Conversion oubliée : des calculs donnent '2500500' ou NaN sans que ce soit remarqué.<br>_Preuves : F1, F2, M3_ |
| Logique conditionnelle et opérateurs | En développement : À améliorer (45 %) | **1** | Ordre des conditions erroné (MalewaWewa jamais affiché) ou confusion entre = et ===. Les cas limites ne sont pas testés.<br>_Preuves : F3, F4, M1, M2, M4_ |
| Fonctions, return et portée | Débutant : Insuffisant (20 %) | **0** | Aucune fonction, le code est copié-collé ; ou fonctions déclarées mais jamais appelées.<br>_Preuves : F5, M2, M5, M6_ |
| Boucles, accumulateurs et méthodes de tableau | En développement : À améliorer (45 %) | **1** | Erreur de bornes (un tour en trop ou en moins), accumulateur remis à zéro dans la boucle, break / continue mal placés.<br>_Preuves : F6, M1, M7, M8 ; niveau Avancé : A2, A3, A4, A5_ |
| Recherche, qualité du code et restitution | Débutant : Insuffisant (30 %) | **0** | Pas de RECHERCHES.md ou aucune source. Code non poussé sur GitHub.<br>_Recherches 0 % · commits par exercice 37 % · règles de code 83 %_ |
| **Total** | | **3 / 15** | |

## Comment lire cette évaluation

| Statut | Signification | Note /5 |
|---|---|:-:|
| ⬜ Non rendu | Fichier absent ou zone de travail vide / non modifiée | 0 |
| ❌ Erreur d'exécution | SyntaxError, ReferenceError, exception ou boucle infinie (> 2 s) | 1 |
| 🟠 Résultat incorrect | Au moins un résultat attendu du cahier n'est pas obtenu | 2 (3 si au moins la moitié des tests passe) |
| 🟡 Règles non respectées | Résultats justes, mais var, ==, concaténation, `function`, `let` inutile ou notion imposée absente | 4 |
| ✅ Parfait | Résultats justes et toutes les règles respectées | 5 |

Recherche /3 : 1 point pour une réponse rédigée (≥ 120 caractères), 1 point pour un test exécuté, 1 point pour un lien source précis. Commit : un commit dont le message cite l'exercice (ex. `feat: M2 dab`).

> ℹ️ L'explication orale de ton code reste évaluée par ton coach. Corrige, commit, merge sur `develop` et push : l'évaluation est relancée automatiquement.
