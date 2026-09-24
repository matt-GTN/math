# Programme

Objectif à long terme : comprendre les mathématiques nécessaires pour aborder la recherche sur les LLM. Le périmètre vient de [concepts.md](concepts.md) ; l’apprentissage se déroule dans le chat.

## Suivi

- `- [ ]` : notion à travailler ou compréhension encore fragile.
- `- [x]` : notion comprise et vérifiée par une reformulation et un petit exercice ou exemple autonome, pas simplement lue.
- Les notions abordées, les hésitations et les révisions à prévoir sont consignées dans [history/](history/), avec un fichier par mois (`AAAA-MM.md`). Une case peut être décochée si une lacune réapparaît.
- Parcourir toute la liste, en passant vite sur les premières notions. Un bref échange et de petits exemples permettent de vérifier les bases ; ralentir dès qu’une incompréhension apparaît.
- Utiliser des calculs à la main et Python dès le début : l’utilisateur est déjà à l’aise avec Python.
- L’ordre est un guide, pas un calendrier. On traite un prérequis dès qu’il manque pour comprendre ; la section 24 reste facultative.

## Sommaire

- [1. Nombres et opérations élémentaires](#chapitre-1)
- [2. Fractions, décimaux et proportions](#chapitre-2)
- [3. Puissances, racines et nombres réels](#chapitre-3)
- [4. Langage mathématique et raisonnement](#chapitre-4)
- [5. Algèbre élémentaire](#chapitre-5)
- [6. Géométrie, coordonnées et trigonométrie](#chapitre-6)
- [7. Fonctions](#chapitre-7)
- [8. Suites, sommes et dénombrement](#chapitre-8)
- [9. Algèbre linéaire : vecteurs et matrices](#chapitre-9)
- [10. Algèbre linéaire : structure et décompositions](#chapitre-10)
- [11. Calcul différentiel à une variable](#chapitre-11)
- [12. Calcul intégral et séries](#chapitre-12)
- [13. Calcul à plusieurs variables](#chapitre-13)
- [14. Probabilités](#chapitre-14)
- [15. Statistiques](#chapitre-15)
- [16. Théorie de l’information](#chapitre-16)
- [17. Optimisation](#chapitre-17)
- [18. Calcul numérique et tenseurs](#chapitre-18)
- [19. Fondations mathématiques du machine learning](#chapitre-19)
- [20. Réseaux de neurones et rétropropagation](#chapitre-20)
- [21. Modèles de langage : des comptages aux embeddings](#chapitre-21)
- [22. Attention et Transformers](#chapitre-22)
- [23. LLM : approfondissements après les bases](#chapitre-23)
- [24. Branches mathématiques plus lointaines — facultatives](#chapitre-24)
- [25. Repères pour suivre Karpathy sans attendre de tout maîtriser](#chapitre-25)

## Liens entre les notions

Ces chemins indiquent quelques dépendances majeures, sans remplacer les prérequis propres à chaque notion.

- [Nombres et opérations](#chapitre-1) → [fractions et proportions](#chapitre-2) → [puissances](#chapitre-3) ; le [langage mathématique](#chapitre-4) accompagne tout le parcours.
- [Algèbre](#chapitre-5) et [coordonnées](#chapitre-6) → [fonctions](#chapitre-7) → [dérivées](#chapitre-11) → [calcul à plusieurs variables](#chapitre-13), avec les [vecteurs et matrices](#chapitre-9).
- [Sommes et dénombrement](#chapitre-8) → [probabilités](#chapitre-14) → [statistiques](#chapitre-15) et [information](#chapitre-16). Les [intégrales](#chapitre-12) servent notamment aux distributions continues.
- [Algèbre linéaire](#chapitre-9), [décompositions](#chapitre-10), [dérivées](#chapitre-11) et [gradients](#chapitre-13) alimentent l’[optimisation](#chapitre-17) et le [machine learning](#chapitre-19).
- [Calcul numérique et tenseurs](#chapitre-18), [machine learning](#chapitre-19) et [rétropropagation](#chapitre-20) → [modèles de langage](#chapitre-21) → [attention et Transformers](#chapitre-22) → [approfondissements LLM](#chapitre-23).
- Les [repères Karpathy](#chapitre-25) permettent de relier les notions à des constructions concrètes au fil du parcours.

<a id="chapitre-1"></a>

## 1. Nombres et opérations élémentaires

### 1.1. Comprendre les nombres

- [x] Quantité.
- [x] Comptage.
- [x] Nombre zéro.
- [x] Nombres entiers naturels.
- [x] Chiffre et nombre.
- [x] Écriture décimale positionnelle.
- [x] Unités, dizaines, centaines.
- [x] Égalité : \(=\).
- [x] Infériorité et supériorité : \(<\), \(>\).
- [x] Comparaison de nombres.
- [x] Classement de nombres.
- [x] Droite numérique.
- [x] Nombres pairs.
- [x] Nombres impairs.

### 1.2. Comprendre les opérations

- [x] Addition.
- [x] Soustraction.
- [x] Multiplication.
- [x] Division.
- [x] Division comme partage.
- [x] Division comme recherche d’un nombre de groupes.
- [x] Opérations inverses.
- [x] Tables de multiplication.
- [x] Quotient entier.
- [x] Reste d’une division.
- [x] Division par zéro non définie.
- [x] Parenthèses.
- [x] Priorités opératoires.
- [x] Commutativité.
- [x] Associativité.
- [x] Distributivité.
- [x] Élément neutre de l’addition.
- [x] Élément neutre de la multiplication.
- [x] Estimation d’un résultat.
- [x] Vérification d’un résultat par l’opération inverse.

### 1.3. Étendre les nombres

- [x] Nombres négatifs.
- [x] Nombres entiers relatifs.
- [x] Opposé d’un nombre.
- [x] Valeur absolue.
- [x] Distance entre deux nombres.
- [x] Addition de nombres relatifs.
- [x] Soustraction de nombres relatifs.
- [x] Règle des signes pour la multiplication.
- [x] Règle des signes pour la division.

<a id="chapitre-2"></a>

## 2. Fractions, décimaux et proportions

### 2.1. Fractions

- [x] Fraction comme partie d’un tout.
- [x] Fraction comme quotient.
- [x] Numérateur.
- [x] Dénominateur.
- [x] Fractions équivalentes.
- [x] Multiples d’un entier.
- [x] Diviseurs d’un entier.
- [x] Nombres premiers.
- [x] Décomposition en facteurs premiers.
- [x] Plus grand commun diviseur.
- [x] Plus petit commun multiple.
- [x] Simplification d’une fraction.
- [x] Mise au même dénominateur.
- [x] Comparaison de fractions.
- [x] Addition de fractions.
- [x] Soustraction de fractions.
- [x] Multiplication de fractions.
- [x] Inverse d’un nombre non nul.
- [x] Division de fractions.
- [x] Fraction d’une quantité.

### 2.2. Décimaux et approximations

- [x] Nombres décimaux.
- [x] Passage d’une fraction à une écriture décimale.
- [x] Écriture décimale finie.
- [x] Écriture décimale périodique.
- [x] Nombres rationnels.
- [x] Arrondi.
- [x] Troncature.
- [x] Erreur absolue.
- [x] Erreur relative.
- [x] Ordre de grandeur.

### 2.3. Proportions

- [x] Rapport entre deux quantités.
- [x] Proportion.
- [x] Proportionnalité.
- [x] Coefficient de proportionnalité.
- [x] Règle de trois.
- [x] Pourcentage.
- [x] Conversion entre fraction, décimal et pourcentage.
- [x] Pourcentage d’augmentation.
- [x] Pourcentage de diminution.
- [x] Variations multiplicatives successives.
- [x] Proportionnalité inverse.
- [x] Moyenne arithmétique.
- [x] Moyenne pondérée.
- [x] Unités de mesure.
- [x] Conversion d’unités.
- [x] Cohérence des unités dans une formule.

<a id="chapitre-3"></a>

## 3. Puissances, racines et nombres réels

- [x] Carré d’un nombre.
- [x] Cube d’un nombre.
- [x] Puissance à exposant entier positif.
- [x] Puissance d’exposant zéro.
- [x] Puissance à exposant entier négatif.
- [x] Produit de puissances de même base.
- [x] Quotient de puissances de même base.
- [x] Puissance d’une puissance.
- [x] Puissance d’un produit.
- [x] Racine carrée.
- [x] Racine cubique.
- [x] Racine d’ordre quelconque.
- [x] Exposant fractionnaire.
- [x] Nombres irrationnels.
- [x] Nombres réels.
- [ ] Approximation d’un nombre irrationnel.
- [ ] Notation scientifique.
- [ ] Ordres de grandeur en puissances de dix.
- [ ] Distinction entre \(-x^2\) et \((-x)^2\).
- [ ] Relation \(\sqrt{x^2}=|x|\).

<a id="chapitre-4"></a>

## 4. Langage mathématique et raisonnement

### 4.1. Lire une expression

- [ ] Constante.
- [ ] Variable.
- [ ] Inconnue.
- [ ] Paramètre.
- [ ] Expression mathématique.
- [ ] Formule.
- [ ] Substitution d’une valeur dans une expression.
- [ ] Multiplication implicite : \(ab=a\times b\).
- [ ] Indice : \(x_i\).
- [ ] Double indice : \(a_{ij}\).
- [ ] Distinction entre indice et exposant.
- [ ] Égalité exacte.
- [ ] Égalité approchée : \(\approx\).
- [ ] Définition par une égalité.

### 4.2. Ensembles et logique

- [ ] Ensemble.
- [ ] Élément d’un ensemble.
- [ ] Appartenance : \(\in\).
- [ ] Ensemble vide.
- [ ] Inclusion.
- [ ] Union.
- [ ] Intersection.
- [ ] Complémentaire.
- [ ] Cardinal d’un ensemble fini.
- [ ] Couple ordonné.
- [ ] Produit cartésien.
- [ ] Intervalle ouvert.
- [ ] Intervalle fermé.
- [ ] Proposition vraie ou fausse.
- [ ] Négation.
- [ ] Conjonction : « et ».
- [ ] Disjonction : « ou ».
- [ ] Implication.
- [ ] Équivalence.
- [ ] Condition nécessaire.
- [ ] Condition suffisante.
- [ ] Quantificateur « pour tout » : \(\forall\).
- [ ] Quantificateur « il existe » : \(\exists\).
- [ ] Contre-exemple.
- [ ] Preuve directe.
- [ ] Raisonnement par contraposée.
- [ ] Raisonnement par contradiction.
- [ ] Raisonnement par récurrence.

<a id="chapitre-5"></a>

## 5. Algèbre élémentaire

### 5.1. Manipuler des expressions

- [ ] Terme d’une expression.
- [ ] Coefficient.
- [ ] Termes semblables.
- [ ] Réduction d’une expression.
- [ ] Développement.
- [ ] Factorisation.
- [ ] Mise en facteur commun.
- [ ] Identité \((a+b)^2\).
- [ ] Identité \((a-b)^2\).
- [ ] Identité \(a^2-b^2\).
- [ ] Expression polynomiale.
- [ ] Degré d’un polynôme.
- [ ] Expression rationnelle.
- [ ] Valeurs interdites d’une expression.
- [ ] Simplification d’une expression rationnelle.

### 5.2. Équations et inéquations

- [ ] Équation.
- [ ] Solution d’une équation.
- [ ] Opérations préservant une égalité.
- [ ] Équation du premier degré.
- [ ] Équation avec fractions.
- [ ] Isolation d’une variable dans une formule.
- [ ] Système de deux équations linéaires.
- [ ] Résolution par substitution.
- [ ] Résolution par élimination.
- [ ] Système sans solution.
- [ ] Système à plusieurs solutions.
- [ ] Équation produit nul.
- [ ] Équation du second degré.
- [ ] Discriminant.
- [ ] Racines d’un polynôme du second degré.
- [ ] Inéquation.
- [ ] Changement du sens d’une inégalité lors d’une multiplication par un nombre négatif.
- [ ] Tableau de signes.
- [ ] Équation avec valeur absolue.
- [ ] Inéquation avec valeur absolue.

<a id="chapitre-6"></a>

## 6. Géométrie, coordonnées et trigonométrie

### 6.1. Géométrie de base

- [ ] Point.
- [ ] Droite.
- [ ] Segment.
- [ ] Longueur.
- [ ] Angle.
- [ ] Droites parallèles.
- [ ] Droites perpendiculaires.
- [ ] Triangle rectangle.
- [ ] Théorème de Pythagore.
- [ ] Aire d’un rectangle.
- [ ] Aire d’un triangle.
- [ ] Cercle.
- [ ] Rayon.
- [ ] Diamètre.
- [ ] Nombre \(\pi\).
- [ ] Circonférence d’un cercle.
- [ ] Aire d’un disque.
- [ ] Volume.

### 6.2. Coordonnées

- [ ] Axe gradué.
- [ ] Repère cartésien.
- [ ] Abscisse.
- [ ] Ordonnée.
- [ ] Coordonnées d’un point.
- [ ] Distance entre deux points.
- [ ] Milieu d’un segment.
- [ ] Pente d’une droite.
- [ ] Ordonnée à l’origine.
- [ ] Équation d’une droite.
- [ ] Intersection de deux droites.
- [ ] Coordonnées en trois dimensions.
- [ ] Extension à un espace de dimension \(n\).

### 6.3. Trigonométrie

- [ ] Mesure d’un angle en degrés.
- [ ] Mesure d’un angle en radians.
- [ ] Conversion entre degrés et radians.
- [ ] Cercle trigonométrique.
- [ ] Sinus.
- [ ] Cosinus.
- [ ] Tangente.
- [ ] Identité \(\sin^2(x)+\cos^2(x)=1\).
- [ ] Périodicité.
- [ ] Amplitude.
- [ ] Fréquence.
- [ ] Phase.
- [ ] Rotation dans le plan.

<a id="chapitre-7"></a>

## 7. Fonctions

### 7.1. Comprendre une fonction

- [ ] Fonction comme correspondance entre entrée et sortie.
- [ ] Notation \(f(x)\).
- [ ] Ensemble de définition.
- [ ] Ensemble d’arrivée.
- [ ] Image d’une valeur.
- [ ] Antécédent d’une valeur.
- [ ] Courbe représentative.
- [ ] Zéro d’une fonction.
- [ ] Signe d’une fonction.
- [ ] Fonction croissante.
- [ ] Fonction décroissante.
- [ ] Maximum.
- [ ] Minimum.
- [ ] Fonction paire.
- [ ] Fonction impaire.
- [ ] Fonction définie par morceaux.
- [ ] Composition de fonctions.
- [ ] Fonction injective.
- [ ] Fonction surjective.
- [ ] Fonction bijective.
- [ ] Fonction réciproque.

### 7.2. Fonctions usuelles

- [ ] Fonction constante.
- [ ] Fonction identité.
- [ ] Fonction linéaire : \(f(x)=ax\).
- [ ] Fonction affine : \(f(x)=ax+b\).
- [ ] Fonction carré.
- [ ] Fonction cube.
- [ ] Fonction puissance.
- [ ] Fonction inverse : \(f(x)=1/x\).
- [ ] Fonction racine carrée.
- [ ] Fonction valeur absolue.
- [ ] Fonction exponentielle de base \(a>0\).
- [ ] Nombre \(e\).
- [ ] Exponentielle naturelle : \(\exp(x)\).
- [ ] Logarithme de base \(a\).
- [ ] Logarithme naturel : \(\ln(x)\).
- [ ] Relation réciproque entre exponentielle et logarithme.
- [ ] Logarithme d’un produit.
- [ ] Logarithme d’un quotient.
- [ ] Logarithme d’une puissance.
- [ ] Changement de base d’un logarithme.
- [ ] Croissance linéaire.
- [ ] Croissance polynomiale.
- [ ] Croissance exponentielle.
- [ ] Croissance logarithmique.

### 7.3. Transformer une fonction

- [ ] Translation horizontale.
- [ ] Translation verticale.
- [ ] Changement d’échelle horizontal.
- [ ] Changement d’échelle vertical.
- [ ] Symétrie d’une courbe.
- [ ] Lecture d’un graphique logarithmique.
- [ ] Lecture d’un graphique log-log.

<a id="chapitre-8"></a>

## 8. Suites, sommes et dénombrement

### 8.1. Suites et sommes

- [ ] Suite numérique.
- [ ] Terme d’une suite.
- [ ] Suite définie explicitement.
- [ ] Suite définie par récurrence.
- [ ] Suite arithmétique.
- [ ] Suite géométrique.
- [ ] Somme finie.
- [ ] Notation de somme : \(\sum\).
- [ ] Indice muet.
- [ ] Bornes d’une somme.
- [ ] Linéarité d’une somme.
- [ ] Somme double.
- [ ] Changement d’indice.
- [ ] Produit fini.
- [ ] Notation de produit : \(\prod\).
- [ ] Somme d’une suite arithmétique.
- [ ] Somme d’une suite géométrique.
- [ ] Somme pondérée.

### 8.2. Dénombrement

- [ ] Principe additif de comptage.
- [ ] Principe multiplicatif de comptage.
- [ ] Factorielle.
- [ ] Permutation.
- [ ] Arrangement.
- [ ] Combinaison.
- [ ] Coefficient binomial.
- [ ] Tirage avec remise.
- [ ] Tirage sans remise.
- [ ] Distinction entre choix ordonné et non ordonné.
- [ ] Formule du binôme.

<a id="chapitre-9"></a>

## 9. Algèbre linéaire : vecteurs et matrices

### 9.1. Vecteurs

- [ ] Scalaire.
- [ ] Vecteur comme liste ordonnée de nombres.
- [ ] Vecteur comme déplacement.
- [ ] Composante d’un vecteur.
- [ ] Dimension d’un vecteur.
- [ ] Vecteur ligne.
- [ ] Vecteur colonne.
- [ ] Vecteur nul.
- [ ] Addition de vecteurs.
- [ ] Soustraction de vecteurs.
- [ ] Multiplication d’un vecteur par un scalaire.
- [ ] Combinaison linéaire.
- [ ] Produit scalaire.
- [ ] Norme euclidienne.
- [ ] Norme \(L^1\).
- [ ] Norme \(L^\infty\).
- [ ] Distance euclidienne.
- [ ] Vecteur unitaire.
- [ ] Normalisation d’un vecteur.
- [ ] Angle entre deux vecteurs.
- [ ] Orthogonalité.
- [ ] Similarité cosinus.
- [ ] Projection sur une direction.
- [ ] Inégalité de Cauchy-Schwarz.
- [ ] Inégalité triangulaire.

### 9.2. Matrices

- [ ] Matrice.
- [ ] Nombre de lignes.
- [ ] Nombre de colonnes.
- [ ] Forme d’une matrice.
- [ ] Coefficient \(a_{ij}\).
- [ ] Matrice nulle.
- [ ] Matrice carrée.
- [ ] Matrice diagonale.
- [ ] Matrice identité.
- [ ] Matrice triangulaire.
- [ ] Matrice symétrique.
- [ ] Transposée.
- [ ] Addition de matrices.
- [ ] Multiplication d’une matrice par un scalaire.
- [ ] Produit matrice-vecteur.
- [ ] Produit matrice-matrice.
- [ ] Compatibilité des dimensions.
- [ ] Non-commutativité du produit matriciel.
- [ ] Produit terme à terme.
- [ ] Produit extérieur de deux vecteurs.
- [ ] Transposée d’un produit.
- [ ] Matrice par blocs.

### 9.3. Transformations et systèmes

- [ ] Transformation linéaire.
- [ ] Transformation affine.
- [ ] Matrice représentant une transformation.
- [ ] Composition de transformations.
- [ ] Changement d’échelle.
- [ ] Réflexion.
- [ ] Matrice de rotation.
- [ ] Matrice de projection.
- [ ] Système linéaire sous la forme \(Ax=b\).
- [ ] Élimination de Gauss.
- [ ] Pivot.
- [ ] Substitution arrière.
- [ ] Matrice inversible.
- [ ] Matrice inverse.
- [ ] Matrice singulière.
- [ ] Résolution d’un système sans calcul explicite de l’inverse.

<a id="chapitre-10"></a>

## 10. Algèbre linéaire : structure et décompositions

### 10.1. Espaces vectoriels

- [ ] Espace vectoriel.
- [ ] Sous-espace vectoriel.
- [ ] Espace engendré.
- [ ] Dépendance linéaire.
- [ ] Indépendance linéaire.
- [ ] Famille génératrice.
- [ ] Base.
- [ ] Dimension d’un espace.
- [ ] Coordonnées dans une base.
- [ ] Changement de base.
- [ ] Noyau d’une application linéaire.
- [ ] Image d’une application linéaire.
- [ ] Rang.
- [ ] Théorème du rang.
- [ ] Base orthogonale.
- [ ] Base orthonormée.
- [ ] Procédé de Gram-Schmidt.
- [ ] Complément orthogonal.
- [ ] Projection sur un sous-espace.

### 10.2. Décompositions — approfondissement utile au ML

- [ ] Déterminant.
- [ ] Trace.
- [ ] Valeur propre.
- [ ] Vecteur propre.
- [ ] Diagonalisation.
- [ ] Théorème spectral pour les matrices symétriques réelles.
- [ ] Forme quadratique.
- [ ] Matrice définie positive.
- [ ] Matrice semi-définie positive.
- [ ] Valeur singulière.
- [ ] Décomposition en valeurs singulières : SVD.
- [ ] Approximation de faible rang.
- [ ] Pseudo-inverse.
- [ ] Décomposition QR.
- [ ] Décomposition de Cholesky.
- [ ] Norme de Frobenius.
- [ ] Norme spectrale.
- [ ] Nombre de conditionnement.

<a id="chapitre-11"></a>

## 11. Calcul différentiel à une variable

### 11.1. Limites et continuité

- [ ] Voisinage d’un point.
- [ ] Limite d’une suite.
- [ ] Convergence.
- [ ] Divergence.
- [ ] Limite d’une fonction en un point.
- [ ] Limite à gauche.
- [ ] Limite à droite.
- [ ] Limite à l’infini.
- [ ] Limite infinie.
- [ ] Opérations sur les limites.
- [ ] Forme indéterminée.
- [ ] Continuité.
- [ ] Discontinuité.
- [ ] Théorème des valeurs intermédiaires.

### 11.2. Dérivées

- [ ] Variation d’une quantité : \(\Delta x\).
- [ ] Taux de variation moyen.
- [ ] Droite sécante.
- [ ] Taux de variation instantané.
- [ ] Tangente.
- [ ] Dérivée en un point.
- [ ] Fonction dérivée.
- [ ] Notations \(f'(x)\) et \(\frac{df}{dx}\).
- [ ] Dérivabilité.
- [ ] Continuité d’une fonction dérivable.
- [ ] Dérivée d’une constante.
- [ ] Dérivée d’une puissance.
- [ ] Dérivée d’une somme.
- [ ] Dérivée d’un produit.
- [ ] Dérivée d’un quotient.
- [ ] Dérivée d’une fonction composée : règle de la chaîne.
- [ ] Dérivée de l’exponentielle.
- [ ] Dérivée du logarithme.
- [ ] Dérivée du sinus.
- [ ] Dérivée du cosinus.
- [ ] Dérivée seconde.
- [ ] Dérivées d’ordre supérieur.

### 11.3. Utiliser les dérivées

- [ ] Approximation linéaire locale.
- [ ] Différentielle.
- [ ] Relation entre signe de la dérivée et variations.
- [ ] Point critique.
- [ ] Minimum local.
- [ ] Maximum local.
- [ ] Minimum global.
- [ ] Maximum global.
- [ ] Critère de la dérivée seconde.
- [ ] Convexité d’une fonction.
- [ ] Concavité d’une fonction.
- [ ] Point d’inflexion.
- [ ] Théorème des accroissements finis.
- [ ] Développement de Taylor.
- [ ] Approximation au premier ordre.
- [ ] Approximation au second ordre.
- [ ] Reste d’une approximation.

<a id="chapitre-12"></a>

## 12. Calcul intégral et séries

### 12.1. Intégrales

- [ ] Accumulation d’une quantité.
- [ ] Aire signée sous une courbe.
- [ ] Somme de Riemann.
- [ ] Intégrale définie.
- [ ] Primitive.
- [ ] Constante d’intégration.
- [ ] Théorème fondamental de l’analyse.
- [ ] Linéarité de l’intégrale.
- [ ] Additivité sur les intervalles.
- [ ] Changement de variable.
- [ ] Intégration par parties.
- [ ] Intégrale impropre.
- [ ] Convergence d’une intégrale.
- [ ] Valeur moyenne d’une fonction.
- [ ] Intégration numérique.
- [ ] Méthode des rectangles.
- [ ] Méthode des trapèzes.

### 12.2. Séries — approfondissement

- [ ] Série numérique.
- [ ] Somme partielle.
- [ ] Convergence d’une série.
- [ ] Série géométrique.
- [ ] Convergence absolue.
- [ ] Série entière.
- [ ] Rayon de convergence.
- [ ] Série de Taylor.
- [ ] Série de l’exponentielle.

<a id="chapitre-13"></a>

## 13. Calcul à plusieurs variables

### 13.1. Fonctions multivariées

- [ ] Fonction de plusieurs variables.
- [ ] Fonction à valeurs vectorielles.
- [ ] Surface représentative.
- [ ] Courbe de niveau.
- [ ] Surface de niveau.
- [ ] Dérivée partielle.
- [ ] Distinction entre variation partielle et variation totale.
- [ ] Gradient.
- [ ] Direction du gradient.
- [ ] Dérivée directionnelle.
- [ ] Différentielle totale.
- [ ] Plan tangent.
- [ ] Matrice jacobienne.
- [ ] Matrice hessienne.
- [ ] Dérivées partielles croisées.
- [ ] Règle de la chaîne multivariée.
- [ ] Produit jacobienne-vecteur.
- [ ] Produit vecteur-jacobienne.
- [ ] Développement de Taylor multivarié.
- [ ] Point selle.
- [ ] Convexité en plusieurs dimensions.

### 13.2. Calcul matriciel

- [ ] Gradient par rapport à un vecteur.
- [ ] Gradient par rapport à une matrice.
- [ ] Dérivée d’un produit scalaire.
- [ ] Gradient d’une norme au carré.
- [ ] Gradient d’une forme quadratique.
- [ ] Dérivée d’une transformation affine.
- [ ] Dérivée d’une opération appliquée composante par composante.
- [ ] Accumulation des dérivées lorsqu’une variable est utilisée plusieurs fois.
- [ ] Vérification des dimensions d’un gradient.

### 13.3. Intégration multivariée — approfondissement

- [ ] Intégrale double.
- [ ] Intégrale multiple.
- [ ] Intégration successive.
- [ ] Conditions d’interversion des intégrales.
- [ ] Changement de variables multivarié.
- [ ] Déterminant jacobien.
- [ ] Élément de volume.

<a id="chapitre-14"></a>

## 14. Probabilités

### 14.1. Fondations

- [ ] Expérience aléatoire.
- [ ] Issue.
- [ ] Univers des possibles.
- [ ] Événement.
- [ ] Événement complémentaire.
- [ ] Événements incompatibles.
- [ ] Probabilité.
- [ ] Axiomes des probabilités.
- [ ] Équiprobabilité.
- [ ] Probabilité d’une union.
- [ ] Probabilité conditionnelle.
- [ ] Règle du produit.
- [ ] Indépendance de deux événements.
- [ ] Distinction entre indépendance et incompatibilité.
- [ ] Partition de l’univers.
- [ ] Formule des probabilités totales.
- [ ] Théorème de Bayes.
- [ ] Probabilité a priori.
- [ ] Probabilité a posteriori.
- [ ] Indépendance conditionnelle.

### 14.2. Variables aléatoires

- [ ] Variable aléatoire.
- [ ] Réalisation d’une variable aléatoire.
- [ ] Variable aléatoire discrète.
- [ ] Variable aléatoire continue.
- [ ] Support d’une distribution.
- [ ] Fonction de masse.
- [ ] Densité de probabilité.
- [ ] Distinction entre densité et probabilité.
- [ ] Fonction de répartition.
- [ ] Quantile.
- [ ] Espérance.
- [ ] Espérance d’une fonction d’une variable aléatoire.
- [ ] Linéarité de l’espérance.
- [ ] Variance.
- [ ] Écart-type.
- [ ] Moment d’ordre \(k\).
- [ ] Variable centrée.
- [ ] Variable centrée réduite.
- [ ] Indicatrice d’un événement.

### 14.3. Plusieurs variables aléatoires

- [ ] Distribution jointe.
- [ ] Distribution marginale.
- [ ] Marginalisation.
- [ ] Distribution conditionnelle.
- [ ] Indépendance de variables aléatoires.
- [ ] Covariance.
- [ ] Corrélation de Pearson.
- [ ] Distinction entre absence de corrélation et indépendance.
- [ ] Matrice de covariance.
- [ ] Espérance conditionnelle.
- [ ] Loi de l’espérance totale.
- [ ] Loi de la variance totale.
- [ ] Variance d’une somme.
- [ ] Règle de la chaîne des probabilités.
- [ ] Transformation d’une variable aléatoire.

### 14.4. Distributions usuelles

- [ ] Loi de Bernoulli.
- [ ] Loi binomiale.
- [ ] Loi catégorielle.
- [ ] Loi multinomiale.
- [ ] Loi uniforme discrète.
- [ ] Loi uniforme continue.
- [ ] Loi normale.
- [ ] Loi normale centrée réduite.
- [ ] Loi normale multivariée.
- [ ] Loi de Poisson.
- [ ] Loi exponentielle.
- [ ] Loi bêta.
- [ ] Loi de Dirichlet.

### 14.5. Échantillonnage et convergence

- [ ] Échantillon aléatoire.
- [ ] Variables indépendantes et identiquement distribuées : i.i.d.
- [ ] Moyenne empirique.
- [ ] Loi des grands nombres.
- [ ] Théorème central limite.
- [ ] Erreur standard de la moyenne.
- [ ] Inégalité de Markov.
- [ ] Inégalité de Bienaymé-Tchebychev.
- [ ] Estimation par Monte-Carlo.

<a id="chapitre-15"></a>

## 15. Statistiques

### 15.1. Décrire des données

- [ ] Population.
- [ ] Échantillon.
- [ ] Observation.
- [ ] Variable quantitative.
- [ ] Variable qualitative.
- [ ] Effectif.
- [ ] Fréquence.
- [ ] Histogramme.
- [ ] Moyenne.
- [ ] Médiane.
- [ ] Mode.
- [ ] Quartiles.
- [ ] Percentiles.
- [ ] Étendue.
- [ ] Écart interquartile.
- [ ] Variance empirique.
- [ ] Variance corrigée.
- [ ] Écart-type empirique.
- [ ] Nuage de points.
- [ ] Valeur aberrante.
- [ ] Asymétrie d’une distribution.
- [ ] Standardisation.
- [ ] Mise à l’échelle min-max.

### 15.2. Estimer

- [ ] Modèle statistique.
- [ ] Paramètre d’une distribution.
- [ ] Statistique calculée sur un échantillon.
- [ ] Estimateur.
- [ ] Estimation.
- [ ] Biais d’un estimateur.
- [ ] Variance d’un estimateur.
- [ ] Erreur quadratique moyenne d’un estimateur.
- [ ] Convergence d’un estimateur.
- [ ] Vraisemblance.
- [ ] Distinction entre vraisemblance et probabilité des paramètres.
- [ ] Log-vraisemblance.
- [ ] Maximum de vraisemblance.
- [ ] Maximum a posteriori.
- [ ] Distribution prédictive.
- [ ] Intervalle de confiance.
- [ ] Intervalle de crédibilité.
- [ ] Bootstrap.

### 15.3. Tester et interpréter — approfondissement

- [ ] Hypothèse nulle.
- [ ] Hypothèse alternative.
- [ ] Statistique de test.
- [ ] Valeur \(p\).
- [ ] Seuil de significativité.
- [ ] Erreur de type I.
- [ ] Erreur de type II.
- [ ] Puissance statistique.
- [ ] Taille d’effet.
- [ ] Comparaisons multiples.
- [ ] Biais de sélection.
- [ ] Variable confondante.
- [ ] Distinction entre corrélation et causalité.

<a id="chapitre-16"></a>

## 16. Théorie de l’information

- [ ] Quantité d’information d’un événement : \(-\log p\).
- [ ] Bit comme unité d’information.
- [ ] Nat comme unité d’information.
- [ ] Entropie d’une distribution discrète.
- [ ] Entropie jointe.
- [ ] Entropie conditionnelle.
- [ ] Entropie croisée.
- [ ] Divergence de Kullback-Leibler.
- [ ] Asymétrie de la divergence KL.
- [ ] Information mutuelle.
- [ ] Relation entre entropie croisée, entropie et divergence KL.
- [ ] Relation entre log-vraisemblance négative et entropie croisée.
- [ ] Perplexité.
- [ ] Dépendance de la perplexité à la tokenisation.
- [ ] Longueur de codage.
- [ ] Relation entre compression et prédiction.

<a id="chapitre-17"></a>

## 17. Optimisation

### 17.1. Formuler un problème

- [ ] Variable de décision.
- [ ] Fonction objectif.
- [ ] Minimisation.
- [ ] Maximisation.
- [ ] Ensemble admissible.
- [ ] Contrainte d’égalité.
- [ ] Contrainte d’inégalité.
- [ ] Minimum et argument du minimum : \(\min\) et \(\arg\min\).
- [ ] Maximum et argument du maximum : \(\max\) et \(\arg\max\).
- [ ] Ensemble convexe.
- [ ] Fonction convexe.
- [ ] Convexité stricte.
- [ ] Optimisation non convexe.
- [ ] Condition stationnaire.
- [ ] Conditions du second ordre.

### 17.2. Méthodes d’optimisation

- [ ] Descente de gradient.
- [ ] Taux d’apprentissage.
- [ ] Itération de mise à jour.
- [ ] Critère d’arrêt.
- [ ] Convergence d’un algorithme.
- [ ] Oscillation.
- [ ] Divergence.
- [ ] Descente de gradient stochastique.
- [ ] Descente de gradient par mini-lots.
- [ ] Gradient comme estimateur aléatoire.
- [ ] Variance du gradient estimé.
- [ ] Momentum.
- [ ] Moyenne mobile exponentielle.
- [ ] Correction du biais d’une moyenne mobile initialisée à zéro.
- [ ] Adaptation du pas par coordonnée.
- [ ] RMSProp.
- [ ] Adam.
- [ ] Décroissance du taux d’apprentissage.
- [ ] Montée progressive du taux d’apprentissage : warmup.
- [ ] Écrêtage de la norme du gradient.

### 17.3. Approfondissements

- [ ] Gradient lipschitzien.
- [ ] Influence du conditionnement sur la convergence.
- [ ] Recherche linéaire du pas.
- [ ] Méthode de Newton.
- [ ] Méthodes quasi-Newton.
- [ ] Descente de coordonnées.
- [ ] Descente de gradient projetée.
- [ ] Multiplicateurs de Lagrange.
- [ ] Conditions de Karush-Kuhn-Tucker.
- [ ] Dualité.
- [ ] Sous-gradient.
- [ ] Optimisation proximale.

<a id="chapitre-18"></a>

## 18. Calcul numérique et tenseurs

### 18.1. Nombres sur ordinateur

- [ ] Écriture binaire.
- [ ] Représentation en virgule flottante.
- [ ] Précision finie.
- [ ] Erreur d’arrondi.
- [ ] Accumulation des erreurs numériques.
- [ ] Non-associativité de l’addition en virgule flottante.
- [ ] Débordement numérique : overflow.
- [ ] Sous-dépassement numérique : underflow.
- [ ] Annulation catastrophique.
- [ ] Valeur infinie.
- [ ] Valeur non numérique : NaN.
- [ ] Stabilité numérique d’un calcul.
- [ ] Différence entre stabilité d’un algorithme et conditionnement d’un problème.
- [ ] Différences finies.
- [ ] Choix du pas pour une différence finie.
- [ ] Astuce log-sum-exp.
- [ ] Calcul stable de softmax.
- [ ] Calcul stable de log-softmax.

### 18.2. Tenseurs dans les bibliothèques de deep learning

- [ ] Tenseur comme tableau multidimensionnel.
- [ ] Ordre d’un tenseur : nombre d’axes.
- [ ] Distinction entre ordre d’un tenseur et rang d’une matrice.
- [ ] Forme d’un tenseur.
- [ ] Taille d’un axe.
- [ ] Indexation.
- [ ] Extraction d’une tranche.
- [ ] Changement de forme : reshape.
- [ ] Permutation des axes.
- [ ] Ajout d’un axe.
- [ ] Suppression d’un axe de taille un.
- [ ] Concaténation.
- [ ] Empilement.
- [ ] Broadcasting.
- [ ] Réduction par somme.
- [ ] Réduction par moyenne.
- [ ] Réduction par maximum.
- [ ] Conservation d’un axe après réduction.
- [ ] Produit matriciel par lots.
- [ ] Contraction d’indices.
- [ ] Notation d’Einstein.
- [ ] Vectorisation d’un calcul.

<a id="chapitre-19"></a>

## 19. Fondations mathématiques du machine learning

### 19.1. Formaliser l’apprentissage

- [ ] Exemple d’entrée \(x\).
- [ ] Cible \(y\).
- [ ] Vecteur de caractéristiques.
- [ ] Matrice de données.
- [ ] Modèle paramétré \(f_\theta\).
- [ ] Paramètre appris.
- [ ] Hyperparamètre.
- [ ] Fonction de perte.
- [ ] Risque espéré.
- [ ] Risque empirique.
- [ ] Minimisation du risque empirique.
- [ ] Ensemble d’entraînement.
- [ ] Ensemble de validation.
- [ ] Ensemble de test.
- [ ] Généralisation.
- [ ] Sous-apprentissage.
- [ ] Surapprentissage.
- [ ] Fuite de données.
- [ ] Validation croisée.
- [ ] Décalage de distribution.
- [ ] Compromis biais-variance.

### 19.2. Régression et classification

- [ ] Régression linéaire simple.
- [ ] Régression linéaire multiple.
- [ ] Résidu.
- [ ] Perte quadratique.
- [ ] Erreur quadratique moyenne.
- [ ] Erreur absolue moyenne.
- [ ] Moindres carrés.
- [ ] Équations normales.
- [ ] Interprétation probabiliste d’une régression avec bruit gaussien.
- [ ] Classification binaire.
- [ ] Classification multiclasse.
- [ ] Cote probabiliste : odds.
- [ ] Log-cote : logit.
- [ ] Fonction sigmoïde.
- [ ] Régression logistique.
- [ ] Perte d’entropie croisée binaire.
- [ ] Fonction softmax.
- [ ] Entropie croisée multiclasse.
- [ ] Frontière de décision.

### 19.3. Régularisation et évaluation

- [ ] Pénalisation \(L^1\).
- [ ] Pénalisation \(L^2\).
- [ ] Régression ridge.
- [ ] Régression lasso.
- [ ] Décroissance des poids : weight decay.
- [ ] Distinction entre pénalité \(L^2\) et weight decay selon l’optimiseur.
- [ ] Arrêt anticipé.
- [ ] Matrice de confusion.
- [ ] Exactitude : accuracy.
- [ ] Précision.
- [ ] Rappel.
- [ ] Score F1.
- [ ] Seuil de décision.
- [ ] Calibration des probabilités.

### 19.4. Autres applications — approfondissement

- [ ] Plus proches voisins.
- [ ] Distance de Mahalanobis.
- [ ] Centroïde.
- [ ] Algorithme des \(k\)-moyennes.
- [ ] Analyse en composantes principales.
- [ ] Variance expliquée.
- [ ] Reconstruction après projection.
- [ ] Blanchiment des données.
- [ ] Fonction noyau.
- [ ] Matrice de Gram.
- [ ] Astuce du noyau.
- [ ] Marge de classification.
- [ ] Machine à vecteurs de support.
- [ ] Modèle de mélange gaussien.
- [ ] Variable latente.
- [ ] Algorithme espérance-maximisation.

<a id="chapitre-20"></a>

## 20. Réseaux de neurones et rétropropagation

### 20.1. Construire un réseau

- [ ] Neurone artificiel.
- [ ] Poids.
- [ ] Biais.
- [ ] Préactivation.
- [ ] Fonction d’activation.
- [ ] Fonction ReLU.
- [ ] Fonction tangente hyperbolique.
- [ ] Fonction GELU.
- [ ] Fonction SiLU.
- [ ] Couche dense.
- [ ] Couche cachée.
- [ ] Couche de sortie.
- [ ] Perceptron multicouche.
- [ ] Composition de transformations affines et non linéaires.
- [ ] Nécessité de la non-linéarité.
- [ ] Passage avant.
- [ ] Perte moyenne sur un mini-lot.
- [ ] Nombre de paramètres d’un réseau.

### 20.2. Différentiation automatique

- [ ] Graphe de calcul.
- [ ] Nœud du graphe.
- [ ] Arête du graphe.
- [ ] Graphe orienté acyclique.
- [ ] Dérivée locale d’une opération.
- [ ] Application de la règle de la chaîne sur un graphe.
- [ ] Accumulation des contributions au gradient.
- [ ] Ordre topologique.
- [ ] Différentiation automatique en mode avant.
- [ ] Différentiation automatique en mode inverse.
- [ ] Rétropropagation.
- [ ] Gradient d’une multiplication matricielle.
- [ ] Gradient d’un biais partagé.
- [ ] Gradient d’une somme.
- [ ] Gradient d’une moyenne.
- [ ] Gradient d’une opération avec broadcasting.
- [ ] Dérivée de la sigmoïde.
- [ ] Dérivée de la tangente hyperbolique.
- [ ] Dérivée de ReLU hors de zéro.
- [ ] Convention de dérivation de ReLU en zéro.
- [ ] Jacobienne de softmax.
- [ ] Gradient de softmax suivi de l’entropie croisée.
- [ ] Vérification du gradient par différences finies.
- [ ] Accumulation de gradients sur plusieurs mini-lots.

### 20.3. Stabilité de l’apprentissage

- [ ] Rupture de symétrie à l’initialisation.
- [ ] Initialisation aléatoire.
- [ ] Variance des activations.
- [ ] Variance des gradients.
- [ ] Nombre d’entrées d’une couche : fan-in.
- [ ] Nombre de sorties d’une couche : fan-out.
- [ ] Initialisation Xavier.
- [ ] Initialisation He.
- [ ] Saturation d’une activation.
- [ ] Disparition du gradient.
- [ ] Explosion du gradient.
- [ ] Normalisation par lot : BatchNorm.
- [ ] Statistiques d’entraînement et d’inférence de BatchNorm.
- [ ] Normalisation par couche : LayerNorm.
- [ ] Normalisation RMSNorm.
- [ ] Paramètre numérique \(\varepsilon\) dans une normalisation.
- [ ] Dropout.
- [ ] Mise à l’échelle du dropout.
- [ ] Connexion résiduelle.
- [ ] Jacobienne d’une connexion résiduelle.
- [ ] Optimiseur AdamW.

### 20.4. Convolutions et récurrence

- [ ] Fenêtre locale.
- [ ] Partage des poids.
- [ ] Convolution discrète.
- [ ] Corrélation croisée.
- [ ] Filtre convolutionnel.
- [ ] Pas de convolution.
- [ ] Padding.
- [ ] Dilatation.
- [ ] Champ réceptif.
- [ ] Convolution causale.
- [ ] État récurrent.
- [ ] Déroulement temporel d’une récurrence.
- [ ] Rétropropagation à travers le temps.

<a id="chapitre-21"></a>

## 21. Modèles de langage : des comptages aux embeddings

### 21.1. Représenter une séquence

- [ ] Alphabet de symboles.
- [ ] Token.
- [ ] Vocabulaire.
- [ ] Identifiant d’un token.
- [ ] Séquence de tokens.
- [ ] Longueur d’une séquence.
- [ ] Fenêtre de contexte.
- [ ] Encodage one-hot.
- [ ] Fréquence d’un token.
- [ ] Fréquence d’une paire de tokens.
- [ ] Fusion de paires fréquentes : principe du BPE.

### 21.2. Modéliser les probabilités

- [ ] Modèle unigramme.
- [ ] Modèle bigramme.
- [ ] Modèle \(n\)-gramme.
- [ ] Hypothèse de Markov.
- [ ] Matrice de transition.
- [ ] Normalisation d’une ligne de comptages.
- [ ] Lissage additif.
- [ ] Probabilité du prochain token conditionnée par le contexte.
- [ ] Factorisation autorégressive d’une probabilité de séquence.
- [ ] Log-probabilité d’une séquence.
- [ ] Log-vraisemblance négative par token.
- [ ] Moyenne de la perte sur les tokens.
- [ ] Masquage des tokens de padding dans la perte.
- [ ] Décalage entre séquence d’entrée et séquence cible.
- [ ] Entraînement avec le contexte réel : teacher forcing.
- [ ] Échantillonnage autorégressif.
- [ ] Token de fin de séquence.

### 21.3. Embeddings et sortie probabiliste

- [ ] Table d’embeddings.
- [ ] Sélection d’une ligne par un identifiant.
- [ ] Équivalence entre sélection d’un embedding et multiplication par un vecteur one-hot.
- [ ] Dimension d’un embedding.
- [ ] Concaténation d’embeddings de contexte.
- [ ] Embeddings appris.
- [ ] Distances entre embeddings.
- [ ] Similarité cosinus entre embeddings.
- [ ] Projection vers la taille du vocabulaire.
- [ ] Logits comme scores non normalisés.
- [ ] Invariance de softmax à l’ajout d’une même constante.
- [ ] Température de softmax.
- [ ] Sélection du token le plus probable.
- [ ] Échantillonnage catégoriel.
- [ ] Échantillonnage top-\(k\).
- [ ] Échantillonnage top-\(p\).
- [ ] Renormalisation après filtrage.
- [ ] Partage des poids entre embeddings et projection de sortie.

<a id="chapitre-22"></a>

## 22. Attention et Transformers

Les notions suivantes décomposent le mécanisme mathématique du Transformer introduit dans [*Attention Is All You Need*](https://arxiv.org/abs/1706.03762).

### 22.1. Attention

- [ ] Somme pondérée de vecteurs.
- [ ] Poids positifs de somme un.
- [ ] Combinaison convexe.
- [ ] Requête : query.
- [ ] Clé : key.
- [ ] Valeur : value.
- [ ] Projection linéaire des requêtes.
- [ ] Projection linéaire des clés.
- [ ] Projection linéaire des valeurs.
- [ ] Score d’attention par produit scalaire.
- [ ] Matrice des scores \(QK^\top\).
- [ ] Mise à l’échelle par \(1/\sqrt{d_k}\).
- [ ] Relation entre dimension et variance d’un produit scalaire.
- [ ] Softmax sur l’axe des clés.
- [ ] Matrice des poids d’attention.
- [ ] Agrégation pondérée des valeurs.
- [ ] Auto-attention.
- [ ] Attention croisée.
- [ ] Masque causal.
- [ ] Masque de padding.
- [ ] Masquage des logits avant softmax.

### 22.2. Attention multi-têtes

- [ ] Dimension d’une tête.
- [ ] Répartition des projections entre plusieurs têtes.
- [ ] Calcul indépendant de chaque tête.
- [ ] Concaténation des sorties.
- [ ] Projection de sortie.
- [ ] Forme des tenseurs avec axes lot, tête, position et caractéristique.
- [ ] Nombre de paramètres des projections d’attention.

### 22.3. Position et ordre

- [ ] Permutation des positions.
- [ ] Équivariance à la permutation de l’auto-attention sans information de position.
- [ ] Embedding de position appris.
- [ ] Encodage positionnel sinusoïdal.
- [ ] Position absolue.
- [ ] Position relative.
- [ ] Rotation de paires de coordonnées.
- [ ] Encodage positionnel rotatif : RoPE.
- [ ] Relation entre rotation relative et produit scalaire.

### 22.4. Bloc Transformer

- [ ] Sous-couche d’attention.
- [ ] Réseau feedforward appliqué à chaque position.
- [ ] Expansion de la dimension cachée.
- [ ] Projection vers la dimension initiale.
- [ ] Mécanisme de porte multiplicative.
- [ ] Fonction SwiGLU.
- [ ] Addition résiduelle.
- [ ] Normalisation avant une sous-couche.
- [ ] Normalisation après une sous-couche.
- [ ] Empilement de blocs.
- [ ] Projection finale vers les logits.
- [ ] Perte autorégressive du modèle complet.

### 22.5. Coût de calcul

- [ ] Notation asymptotique \(O(\cdot)\).
- [ ] Coût d’un produit matriciel.
- [ ] Coût quadratique de l’attention dense en longueur de séquence.
- [ ] Taille mémoire de la matrice d’attention.
- [ ] Nombre d’opérations d’un passage avant.
- [ ] Cache des clés et des valeurs.
- [ ] Distinction entre calcul du contexte initial et génération token par token.

<a id="chapitre-23"></a>

## 23. LLM : approfondissements après les bases

### 23.1. Adaptation et compression

- [ ] Mise à jour d’une matrice par une correction de faible rang.
- [ ] Factorisation de la correction : \(\Delta W=BA\).
- [ ] Rang maximal d’un produit de matrices.
- [ ] Comptage des paramètres de LoRA.
- [ ] Quantification uniforme.
- [ ] Pas de quantification.
- [ ] Arrondi et saturation.
- [ ] Erreur de quantification.
- [ ] Quantification par canal.
- [ ] Distillation d’une distribution prédictive.
- [ ] Température dans la distillation.

### 23.2. Apprentissage à partir de préférences

- [ ] Comparaison de deux réponses.
- [ ] Modèle probabiliste de préférence.
- [ ] Modèle de Bradley-Terry.
- [ ] Fonction de récompense.
- [ ] Politique probabiliste.
- [ ] Espérance de récompense.
- [ ] Rapport de probabilités.
- [ ] Pénalité de divergence KL envers un modèle de référence.
- [ ] Gradient d’une espérance paramétrée.
- [ ] Identité du gradient du logarithme.
- [ ] Estimateur REINFORCE.
- [ ] Baseline pour réduire la variance.
- [ ] Avantage.
- [ ] Objectif de préférence directe : DPO.

### 23.3. Passage à l’échelle

- [ ] Loi de puissance.
- [ ] Exposant d’une loi de puissance.
- [ ] Ajustement sur axes logarithmiques.
- [ ] Relation empirique entre perte et taille du modèle.
- [ ] Relation empirique entre perte et quantité de données.
- [ ] Budget de calcul.
- [ ] Optimisation d’une allocation de calcul.
- [ ] Distinction entre loi empirique et garantie théorique.

<a id="chapitre-24"></a>

## 24. Branches mathématiques plus lointaines — facultatives

### 24.1. Analyse et théorie des probabilités

- [ ] Borne supérieure.
- [ ] Borne inférieure.
- [ ] Suites de Cauchy.
- [ ] Complétude des nombres réels.
- [ ] Compacité.
- [ ] Continuité uniforme.
- [ ] Convergence uniforme.
- [ ] Conditions d’échange entre limite, dérivée et intégrale.
- [ ] Tribu d’événements.
- [ ] Mesure.
- [ ] Intégrale de Lebesgue.
- [ ] Convergence presque sûre.
- [ ] Convergence en probabilité.
- [ ] Convergence en distribution.
- [ ] Entropie différentielle.

### 24.2. Géométrie de grande dimension et théorie de l’apprentissage

- [ ] Concentration de la mesure.
- [ ] Concentration des distances en grande dimension.
- [ ] Quasi-orthogonalité de vecteurs aléatoires.
- [ ] Malédiction de la dimension.
- [ ] Projection aléatoire.
- [ ] Lemme de Johnson-Lindenstrauss.
- [ ] Inégalité de Hoeffding.
- [ ] Borne de généralisation.
- [ ] Dimension VC.
- [ ] Complexité de Rademacher.
- [ ] Apprentissage PAC.
- [ ] Inégalité de Jensen.
- [ ] Information de Fisher.
- [ ] Gradient naturel.

### 24.3. Analyse harmonique et systèmes dynamiques

- [ ] Nombres complexes.
- [ ] Partie réelle.
- [ ] Partie imaginaire.
- [ ] Module d’un nombre complexe.
- [ ] Conjugué.
- [ ] Formule d’Euler.
- [ ] Transformée de Fourier.
- [ ] Transformée de Fourier discrète.
- [ ] Théorème de convolution.
- [ ] Équation différentielle ordinaire.
- [ ] Condition initiale.
- [ ] Méthode d’Euler.
- [ ] Champ de vecteurs.
- [ ] Point d’équilibre.
- [ ] Stabilité d’un équilibre.
- [ ] Descente de gradient vue comme discrétisation d’un flot.

### 24.4. Graphes

- [ ] Sommet.
- [ ] Arête.
- [ ] Graphe orienté.
- [ ] Chemin.
- [ ] Cycle.
- [ ] Matrice d’adjacence.
- [ ] Degré d’un sommet.
- [ ] Laplacien d’un graphe.
- [ ] Marche aléatoire.
- [ ] Propagation de messages.

<a id="chapitre-25"></a>

## 25. Repères pour suivre Karpathy sans attendre de tout maîtriser

Ces repères correspondent aux étapes du [programme officiel](https://github.com/karpathy/nn-zero-to-hero). Les sections précédentes constituent ma décomposition pédagogique ; les grandes familles ont également été recoupées avec [*Mathematics for Machine Learning*](https://mml-book.com/) et [*Deep Learning*](https://www.deeplearningbook.org/).

- [ ] **Micrograd** : calcul algébrique, fonctions, dérivées, règle de la chaîne, gradient, graphe de calcul, descente de gradient.
- [ ] **Makemore — bigrammes** : comptages, probabilités conditionnelles, matrices, logarithmes, vraisemblance, softmax, échantillonnage.
- [ ] **Makemore — MLP** : produits matriciels, embeddings, fonctions d’activation, mini-lots, entropie croisée.
- [ ] **Activations et BatchNorm** : moyenne, variance, standardisation, initialisation, propagation des activations et des gradients.
- [ ] **Backprop Ninja** : dérivées partielles, calcul matriciel, règle de la chaîne multivariée, gradients des réductions et du broadcasting.
- [ ] **WaveNet** : formes des tenseurs, concaténation, partage des poids, champ réceptif, organisation hiérarchique du contexte.
- [ ] **GPT** : probabilités autorégressives, produits scalaires, attention, masquage causal, positions, connexions résiduelles, LayerNorm.
- [ ] **Tokenizer** : séquences discrètes, comptages de paires, fréquences, fusion de symboles, lien entre segmentation et compression.
