# RECHERCHES — Semaine 13

> Pour chaque exercice : reformule avec tes mots (pas de copier-coller), ajoute un test que tu as exécuté toi-même,
> et cite une source précise (une page, pas juste « Google »). MDN en français est la référence.
> Si tu as utilisé une IA, indique ton prompt et vérifie sa réponse sur MDN.
> Ne modifie pas les titres `## F1 — …` : ils servent à l'évaluation automatique.

## F1 — Ma carte d'apprenant

**Question :** Pourquoi typeof null renvoie-t-il 'object' alors que null n'est pas un objet ?

**Ma réponse (avec mes mots, 3 à 5 lignes) :**
typeof null renvoie "object" à cause d’une vieille erreur dans JavaScript.
Au départ, null a été rangé dans la même case que les objets.
Ce bug est resté pour ne pas casser les anciens programmes, même si null n’est pas un objet.

...

**Mon test dans la console :**

```js
// colle ici le test que tu as exécuté et le résultat obtenu
```
PS C:\Users\HP\dw-matin-b-w1-kin-exercices-introduction-a-la-programmation-mushokodivin-spec> node c:\Users\HP\dw-matin-b-w1-kin-exercices-introduction-a-la-programmation-mushokodivin-spec\semaine-13\F1-carte-apprenant.js
Je m'appelle Grâce, j'ai 22 ans et j'habite à Lemba.
string
number
string
boolean
undefined
object
PS C:\Users\HP\dw-matin-b-w1-kin-exercices-introduction-a-la-programmation-mushokodivin-spec> 

**Source :** 

**IA utilisée ? (prompt + vérification sur MDN) :** non

## F2 — Le convertisseur de saisie

**Question :** Qu'est-ce que NaN, et pourquoi NaN === NaN renvoie false ? Quelle fonction utiliser pour le détecter ?

**Ma réponse (avec mes mots, 3 à 5 lignes) :**
NaN veut dire Not a Number, une valeur spéciale quand un calcul n’a pas de sens.
En JavaScript, NaN === NaN renvoie false car NaN est défini comme différent de lui-même.
Pour le détecter correctement, on utilise Number.isNaN(valeur).
...

**Mon test dans la console :**

```js
// colle ici le test que tu as exécuté et le résultat obtenu
```
PS C:\Users\HP\dw-matin-b-w1-kin-exercices-introduction-a-la-programmation-mushokodivin-spec> node c:\Users\HP\dw-matin-b-w1-kin-exercices-introduction-a-la-programmation-mushokodivin-spec\semaine-13\F1-carte-apprenant.js
Je m'appelle Grâce, j'ai 22 ans et j'habite à Lemba.
string
number
string
boolean
undefined
object
**Source :** 

**IA utilisée ? (prompt + vérification sur MDN) :** non

## F3 — Pair ou impair : le tirage des tickets

**Question :** Que renvoie -7 % 2 ? Déduis-en pourquoi il vaut mieux tester % 2 !== 0 plutôt que % 2 === 1 pour détecter un nombre impair.

**Ma réponse (avec mes mots, 3 à 5 lignes) :**
-7 % 2 donne -1, car le reste garde le signe du nombre.
Si on teste % 2 === 1, nous ne verrons pas les impairs négatifs.
Avec % 2 !== 0, nous trouverons tous les impairs, positifs ou négatifs.
...

**Mon test dans la console :**

```js
// colle ici le test que tu as exécuté et le résultat obtenu
```
PS C:\Users\HP\dw-matin-b-w1-kin-exercices-introduction-a-la-programmation-mushokodivin-spec> node c:\Users\HP\dw-matin-b-w1-kin-exercices-introduction-a-la-programmation-mushokodivin-spec\semaine-13\F3-pair-impair.js
Ticket 17 : impair, tu gagnes un stylo.
Ticket 17 : impair, tu gagnes un stylo.
Ticket 24 : pair, tu gagnes un tote bag.
Ticket 0 : pair, tu gagnes un tote bag.
**Source :** 

**IA utilisée ? (prompt + vérification sur MDN) :** non

## F4 — Le contrôleur du bus

**Question :** Peut-on enchaîner plusieurs ternaires ? Pourquoi est-ce souvent déconseillé ?

**Ma réponse (avec mes mots, 3 à 5 lignes) :**
Oui, on peut enchaîner plusieurs ternaires.
Mais c’est souvent déconseillé car ça rend le code difficile à lire et à comprendre.
Il vaut mieux utiliser if / else pour garder un code clair et simple.
...

**Mon test dans la console :**

```js
// colle ici le test que tu as exécuté et le résultat obtenu
```
PS C:\Users\HP\dw-matin-b-w1-kin-exercices-introduction-a-la-programmation-mushokodivin-spec> node c:\Users\HP\dw-matin-b-w1-kin-exercices-introduction-a-la-programmation-mushokodivin-spec\semaine-13\F4-controleur-bus.js
Statut : mineur — Tarif : 500 FC
**Source :** 

**IA utilisée ? (prompt + vérification sur MDN) :** non

## F5 — Ma première fonction fléchée

**Question :** Quand peut-on enlever les parenthèses autour des paramètres, et quand peut-on enlever return et les accolades ?

**Ma réponse (avec mes mots, 3 à 5 lignes) :**
On peut enlever les parenthèses s’il n y a un seul paramètre.
On peut enlever return et les accolades si la fonction fait une seule opération.
Si la fonction a zéro ou plusieurs paramètres, il faut tout garder.                    
...

**Mon test dans la console :**

```js
// colle ici le test que tu as exécuté et le résultat obtenu
```
PS C:\Users\HP\dw-matin-b-w1-kin-exercices-introduction-a-la-programmation-mushokodivin-spec> node c:\Users\HP\dw-matin-b-w1-kin-exercices-introduction-a-la-programmation-mushokodivin-spec\semaine-13\F5-fonction-flechee.js
Mbote Lys !
49
**Source :** 

**IA utilisée ? (prompt + vérification sur MDN) :** non

## F6 — Le compte à rebours

**Question :** À quoi sert le mot-clé continue ? Quelle différence avec break ?

**Ma réponse (avec mes mots, 3 à 5 lignes) :**
continue saute une étape de la boucle et passe directement à la suivante.
break arrête complètement la boucle, même s’il reste des tours.
Donc continue = sauter, et break = stopper.
...

**Mon test dans la console :**

```js
// colle ici le test que tu as exécuté et le résultat obtenu
```
PS C:\Users\HP\dw-matin-b-w1-kin-exercices-introduction-a-la-programmation-mushokodivin-spec> node c:\Users\HP\dw-matin-b-w1-kin-exercices-introduction-a-la-programmation-mushokodivin-spec\semaine-13\F6-compte-a-rebours.js
10
9
8
7
6
5
4
3
2
1
Décollage !
**Source :** 

**IA utilisée ? (prompt + vérification sur MDN) :** non

## M1 — FizzBuzz kinois

**Question :** Pourquoi FizzBuzz est-il célèbre dans les entretiens d'embauche de développeurs ?

**Ma réponse (avec mes mots, 3 à 5 lignes) :**
FizzBuzz est célèbre car il teste les bases du code (boucles, conditions, modulo).
Il montre vite si quelqu’un sait écrire un programme simple et logique.
C’est devenu un exercice classique dans les entretiens de développeurs.
...

**Mon test dans la console :**
PS C:\Users\HP\dw-matin-b-w1-kin-exercices-introduction-a-la-programmation-mushokodivin-spec> node c:\Users\HP\dw-matin-b-w1-kin-exercices-introduction-a-la-programmation-mushokodivin-spec\semaine-13\M1-fizzbuzz.js
1
2
Malewa
4
Wewa
Malewa
7
8
Malewa
Wewa
11
Malewa
13
14
MalewaWewa
16
17
Malewa
19
Wewa
Malewa
22
23
Malewa
Wewa
26
Malewa
28
29
MalewaWewa
```js
// colle ici le test que tu as exécuté et le résultat obtenu
```

**Source :** 

**IA utilisée ? (prompt + vérification sur MDN) :** non

## M2 — Le distributeur automatique (DAB)

**Question :** Comment afficher 75000 sous la forme 75 000 avec toLocaleString() ?

**Ma réponse (avec mes mots, 3 à 5 lignes) :**
Pour afficher 75000 comme 75 000, on utilise toLocaleString().
Exemple : (75000).toLocaleString("fr-FR") donne "75 000".
Le "fr-FR" met un espace comme séparateur de milliers.
...

**Mon test dans la console :**
PS C:\Users\HP\dw-matin-b-w1-kin-exercices-introduction-a-la-programmation-mushokodivin-spec> node c:\Users\HP\dw-matin-b-w1-kin-exercices-introduction-a-la-programmation-mushokodivin-spec\semaine-13\M2-dab.js
Retrait accepté. Nouveau solde : 75 000 FC
Montant invalide : multiples de 5 000 FC uniquement
Plafond dépassé : 500 000 FC maximum
Solde insuffisant
```js
// colle ici le test que tu as exécuté et le résultat obtenu
```

**Source :** 

**IA utilisée ? (prompt + vérification sur MDN) :** non

## M3 — Le détecteur de champs vides (Truthy / Falsy)

**Question :** Quelle est la liste complète des valeurs falsy en JavaScript ? (Indice : il y en a plus que dans cet exercice.)

**Ma réponse (avec mes mots, 3 à 5 lignes) :**
Les valeurs falsy sont : false, 0, -0, 0n, "", null, undefined, et NaN.
Ça veut dire qu’elles comptent comme fausses dans une condition.
Toutes les autres valeurs sont truthy, même "0" ou un tableau vide []. 
...

**Mon test dans la console :**
PS C:\Users\HP\dw-matin-b-w1-kin-exercices-introduction-a-la-programmation-mushokodivin-spec> node c:\Users\HP\dw-matin-b-w1-kin-exercices-introduction-a-la-programmation-mushokodivin-spec\semaine-13\M3-champs-vides.js
vide
rempli
vide
rempli
vide
vide
vide
rempli
rempli
vide
```js
// colle ici le test que tu as exécuté et le résultat obtenu
```

**Source :** 

**IA utilisée ? (prompt + vérification sur MDN) :** non

## M4 — Le score par défaut : || contre ??

**Question :** Que fait l'opérateur ?? (coalescence des nuls) et en quoi est-il différent de || ?

**Ma réponse (avec mes mots, 3 à 5 lignes) :**
L’opérateur ?? (nullish coalescing) sert à donner une valeur par défaut uniquement si la variable vaut null ou undefined. Contrairement à ||, il ne considère pas les autres valeurs “fausses” comme 0, "" ou false.
...

**Mon test dans la console :**
PS C:\Users\HP\dw-matin-b-w1-kin-exercices-introduction-a-la-programmation-mushokodivin-spec> node c:\Users\HP\dw-matin-b-w1-kin-exercices-introduction-a-la-programmation-mushokodivin-spec\semaine-13\M4-score-defaut.js
Score : 15
Score : aucun
Score : aucun
Score : 15
Score : 0
Score : aucun
Bienvenue !
```js
// colle ici le test que tu as exécuté et le résultat obtenu
```

**Source :** 

**IA utilisée ? (prompt + vérification sur MDN) :** non

## M5 — La vitre teintée (portée de bloc)

**Question :** Pourquoi var est-il banni du code moderne ? Cherche ce que sont la portée de fonction et le « hoisting ».

**Ma réponse (avec mes mots, 3 à 5 lignes) :**
var est banni du code moderne car il crée des bugs liés à sa portée et au hoisting. Contrairement à let et const, il est fonction‑scopé et non bloc‑scopé, et son hoisting initialise la variable à undefined, ce qui rend le code imprévisible.
...

**Mon test dans la console :**
PS C:\Users\HP\dw-matin-b-w1-kin-exercices-introduction-a-la-programmation-mushokodivin-spec> node c:\Users\HP\dw-matin-b-w1-kin-exercices-introduction-a-la-programmation-mushokodivin-spec\semaine-13\M5-vitre-teintee.js
Kinshasa
Gombe
pondu
```js
// colle ici le test que tu as exécuté et le résultat obtenu
```

**Source :** 

**IA utilisée ? (prompt + vérification sur MDN) :** non

## M6 — Le détective du return

**Question :** Le troisième bug vient de l'« insertion automatique de point-virgule » (ASI). Explique ce mécanisme en 3 lignes.

**Ma réponse (avec mes mots, 3 à 5 lignes) :**

...

**Mon test dans la console :**
PS C:\Users\HP\dw-matin-b-w1-kin-exercices-introduction-a-la-programmation-mushokodivin-spec> node c:\Users\HP\dw-matin-b-w1-kin-exercices-introduction-a-la-programmation-mushokodivin-spec\semaine-13\M6-detective-return.js
8
660
Mbote Ney
```js
// colle ici le test que tu as exécuté et le résultat obtenu
```

**Source :** 

**IA utilisée ? (prompt + vérification sur MDN) :** non

## M7 — La tirelire numérique

**Question :** Cite tous les opérateurs d'affectation composée (+=, -=…) et donne un exemple pour chacun.

**Ma réponse (avec mes mots, 3 à 5 lignes) :**

+=	x += 5;	
-=	x -= 3;	
*=	x *= 2;	
/=	x /= 4;	
%=	x %= 2;	
**=	x **= 3;	
<<=	x <<= 1;	
>>=	x >>= 1;	
>>>= x >>>= 1;	
&=	x &= y;	
`	=`	`x ;	
^=	x ^= y;	



...

**Mon test dans la console :**
PS C:\Users\HP\dw-matin-b-w1-kin-exercices-introduction-a-la-programmation-mushokodivin-spec> node c:\Users\HP\dw-matin-b-w1-kin-exercices-introduction-a-la-programmation-mushokodivin-spec\semaine-13\M7-tirelire.js
Semaine 1 : 2000 FC
Semaine 2 : 4000 FC
Semaine 3 : 6000 FC
Semaine 4 : 9000 FC (bonus !)
Semaine 5 : 11000 FC
Semaine 6 : 13000 FC
Semaine 7 : 15000 FC
Semaine 8 : 18000 FC (bonus !)
Semaine 9 : 20000 FC
Semaine 10 : 22000 FC
Semaine 11 : 24000 FC
Semaine 12 : 27000 FC (bonus !)
Total après 12 semaines : 27000 FC
```js
// colle ici le test que tu as exécuté et le résultat obtenu
```

**Source :** 

**IA utilisée ? (prompt + vérification sur MDN) :** non

## M8 — La batterie qui se décharge

**Question :** Quelle est la différence entre while et do...while ? Que donnerait l'étape 4 avec un do...while ?

**Ma réponse (avec mes mots, 3 à 5 lignes) :**
while vérifie la condition avant de faire la boucle, donc peut ne jamais tourner.
do...while fait la boucle au moins une fois, puis vérifie la condition.
À l’étape 4, avec do...while, la boucle tournerait 1 fois même avec batterie = 15 %.
...

**Mon test dans la console :**
PS C:\Users\HP\dw-matin-b-w1-kin-exercices-introduction-a-la-programmation-mushokodivin-spec> node c:\Users\HP\dw-matin-b-w1-kin-exercices-introduction-a-la-programmation-mushokodivin-spec\semaine-13\M8-batterie.js
Après 1 h, batterie à 85 %
Après 2 h, batterie à 70 %
Après 3 h, batterie à 55 %
Après 4 h, batterie à 40 %
Après 5 h, batterie à 25 %
Après 6 h, batterie à 10 %
Après 6 h, batterie à 10 % : branche ton téléphone !
Avec départ à 15 %, la boucle fait 0 tours.
```js
// colle ici le test que tu as exécuté et le résultat obtenu
```

**Source :** 

**IA utilisée ? (prompt + vérification sur MDN) :** non

## A1 — Kadea Express v2 : le calculateur de livraison

**Question :** Pourquoi 0.1 + 0.2 ne donne-t-il pas 0.3 en JavaScript ? Et pourquoi toFixed() est un piège si on veut continuer à calculer ?

**Ma réponse (avec mes mots, 3 à 5 lignes) :**

...

**Mon test dans la console :**

```js
// colle ici le test que tu as exécuté et le résultat obtenu
```

**Source :** 

**IA utilisée ? (prompt + vérification sur MDN) :** non

## A2 — Le moteur de paie v2

**Question :** La méthode .reduce() n'a pas été vue en atelier. Explique ce qu'elle fait et réécris l'étape 2 avec elle.

**Ma réponse (avec mes mots, 3 à 5 lignes) :**

...

**Mon test dans la console :**

```js
// colle ici le test que tu as exécuté et le résultat obtenu
```

**Source :** 

**IA utilisée ? (prompt + vérification sur MDN) :** non

## A3 — L'inventaire en console

**Question :** Comment afficher seulement les colonnes nom et stock avec console.table() ? Et que renvoient .find() et .filter() quand rien ne correspond ?

**Ma réponse (avec mes mots, 3 à 5 lignes) :**

...

**Mon test dans la console :**

```js
// colle ici le test que tu as exécuté et le résultat obtenu
```

**Source :** 

**IA utilisée ? (prompt + vérification sur MDN) :** non

## A4 — Le classement de la promo

**Question :** Comment classer le bulletin de la meilleure à la moins bonne moyenne avec .sort() ? Pourquoi .sort() modifie-t-il le tableau d'origine, et comment l'éviter ?

**Ma réponse (avec mes mots, 3 à 5 lignes) :**

...

**Mon test dans la console :**

```js
// colle ici le test que tu as exécuté et le résultat obtenu
```

**Source :** 

**IA utilisée ? (prompt + vérification sur MDN) :** non

## A5 — Le nombre mystère

**Question :** Explique la « recherche dichotomique » et pourquoi 7 essais suffisent toujours pour trouver un nombre entre 1 et 100.

**Ma réponse (avec mes mots, 3 à 5 lignes) :**

...

**Mon test dans la console :**

```js
// colle ici le test que tu as exécuté et le résultat obtenu
```

**Source :** 

**IA utilisée ? (prompt + vérification sur MDN) :** non
