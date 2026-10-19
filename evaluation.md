# 📊 Évaluation automatique — Semaine 13 (JavaScript)

> Générée le 2026-10-19 21:31 UTC · commit `0181a40` · évaluation déterministe basée uniquement sur le cahier d'exercices et le barème.

## Note finale : **9 / 15**

Exercices : **80 / 95** · Parfaits : 9 / 19 · Non rendus : 1

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
| **M2** — Le distributeur automatique (DAB) | **5** | ✅ Parfait | 9/9 | 0 | ✅ | Parfait ! Règles vérifiées dans le bon ordre, cas limites gérés, la fonction renvoie son message.<br>📚 Recherche non rédigée. |
| **M3** — Le détecteur de champs vides (Truthy / Falsy) | **5** | ✅ Parfait | 11/11 | 0 | ✅ | Parfait ! Les valeurs truthy / falsy sont maîtrisées, ternaire sans comparaison.<br>📚 Recherche non rédigée. |
| **M4** — Le score par défaut : \|\| contre ?? | **4** | 🟡 Règles non respectées | 5/5 | 0 | ✅ | Les résultats sont justes, mais montre la version `\|\|`, corrige avec `??` et explique le bug en commentaire.<br>• Explique en commentaire pourquoi 0 donne « aucun » avec `\|\|`.<br>📚 Recherche non rédigée. |
| **M5** — La vitre teintée (portée de bloc) | **4** | 🟡 Règles non respectées | 3/3 | 0 | ✅ | Plus d'erreur, mais les déclarations doivent rester dans leurs blocs et tes prédictions/explications doivent être en commentaire.<br>• Écris tes prédictions et explique pourquoi `afficher` ne s'exécutait jamais (l'erreur arrête le programme).<br>📚 Recherche non rédigée. |
| **M6** — Le détective du return | **4** | 🟡 Règles non respectées | 5/5 | 0 | ✅ | Les 3 fonctions sont corrigées, mais explique chaque bug en commentaire et garde le gabarit littéral.<br>• Explique chacun des 3 bugs en commentaire (return manquant, console.log au lieu de return, ASI).<br>📚 Recherche non rédigée. |
| **M7** — La tirelire numérique | **5** | ✅ Parfait | 3/3 | 0 | ✅ | Parfait ! Accumulateur bien initialisé, 12 tours exacts et bonus toutes les 4 semaines : 27000 FC.<br>📚 Recherche non rédigée. |
| **M8** — La batterie qui se décharge | **0** | ⬜ Non rendu | — | 0 | ❌ | Exercice non commencé : écris ton code dans `semaine-13/M8-batterie.js` sous l'énoncé.<br>📚 Recherche non rédigée. |
| **A1** — Kadea Express v2 : le calculateur de livraison | **5** | ✅ Parfait | 9/9 | 0 | ❌ | Parfait ! Règles métier, paramètre par défaut, TVA et arrondi corrects, y compris aux bornes.<br>📚 Recherche non rédigée. |
| **A2** — Le moteur de paie v2 | **5** | ✅ Parfait | 7/7 | 0 | ✅ | Parfait ! Accumulateur avec .forEach(), heures supplémentaires et recherche du maximum corrects.<br>📚 Recherche non rédigée. |
| **A3** — L'inventaire en console | **3** | 🟠 Résultat incorrect | 4/7 | 0 | ❌ | Un résultat est faux ou introuvable : stocke chaque résultat (filter, map) dans une variable ou affiche-le, et gère le cas undefined de .find() avec « Produit introuvable ».<br>• chercherProduit(104) renvoie ReferenceError: chercherProduit is not defined au lieu de l'objet de la gourde.<br>• `chercherProduit(999)` renvoie ReferenceError: chercherProduit is not defined au lieu de 'Produit introuvable'.<br>• Affiche le nombre de produits en rupture de stock (2).<br>• Utilise `.find()` dans `chercherProduit`.<br>📚 Recherche non rédigée. |
| **A4** — Le classement de la promo | **4** | 🟡 Règles non respectées | 9/9 | 0 | ❌ | Les résultats sont justes, mais respecte les consignes : boucle dans calculerMoyenne, .map(), .filter(), .find() avec return, if / else if / else.<br>• Mot-clé `function` utilisé (`calculerMoyenne` l.33) : écris une fonction fléchée.<br>• `calculerMoyenne` doit être une fonction fléchée.<br>📚 Recherche non rédigée. |
| **A5** — Le nombre mystère | **4** | 🟡 Règles non respectées | 4/4 | 0 | ❌ | Le jeu fonctionne, mais respecte les consignes : while, Math.random() + Math.floor(), prompt() + Number(), détection de NaN, gabarits littéraux.<br>• `let` jamais réassigné : `saisie`, `nombre` → utilise `const`.<br>📚 Recherche non rédigée. |

## 2. Barème officiel (/15)

| Critère | Niveau | Points /3 | Feedback |
|---|---|:-:|---|
| Fondations : variables, types primitifs et conversions | Compétent : Satisfaisant (69 %) | **2** | Déclarations correctes avec const / let, aucun var. Les 5 types primitifs sont reconnus. Le piège '5' + 3 est identifié et corrigé avec Number().<br>_Preuves : F1, F2, M3_ |
| Logique conditionnelle et opérateurs | Compétent : Satisfaisant (74 %) | **2** | if / else if / else corrects, égalité stricte === systématique, modulo maîtrisé (pair / impair, multiples). Ternaire simple fonctionnel.<br>_Preuves : F3, F4, M1, M2, M4_ |
| Fonctions, return et portée | Compétent : Satisfaisant (72 %) | **2** | Les fonctions renvoient leur résultat avec return (pas de console.log à l'intérieur) et sont appelées avec les bons arguments. Portée de bloc respectée : aucune ReferenceError.<br>_Preuves : F5, M2, M5, M6_ |
| Boucles, accumulateurs et méthodes de tableau | Compétent : Satisfaisant (70 %) | **2** | Boucle for correcte (départ, condition, pas), accumulateur initialisé avant la boucle, while avec une condition d'arrêt sûre. Résultats attendus exacts (27000 FC pour M7, 6 h pour M8).<br>_Preuves : F6, M1, M7, M8 ; niveau Avancé : A2, A3, A4, A5_ |
| Recherche, qualité du code et restitution | En développement : À améliorer (39 %) | **1** | Recherches partielles ou sans test. Peu de commits (un seul commit en fin de semaine).<br>_Recherches 0 % · commits par exercice 68 % · règles de code 89 %_ |
| **Total** | | **9 / 15** | |

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
