RAPPORT SUR LISTES CHAÎNÉES
 Introduction
 Les **listes chaînées** sont des structures de données dynamiques utilisées en informatique pour
 stocker et manipuler des ensembles d’éléments. Contrairement aux tableaux, elles ne nécessitent
 pas de taille fixe et permettent des insertions ou suppressions efficaces.
 Ce rapport présente plusieurs programmes en langage C mettant en œuvre différents types de
 listes chaînées (simplement chaînées, doublement chaînées et circulaires), ainsi que les opérations
 classiques de manipulation : création, lecture, insertion, suppression et tri.
 1. Liste simplement chaînée avec suppression d’occurrences
 Définition
 Une **liste simplement chaînée** est une structure composée de nœuds reliés par un pointeur
 `next`. Chaque nœud contient :- une **donnée** (valeur stockée),- un **pointeur vers le nœud suivant**.
 Notion d’occurrence
 Une **occurrence** d’un élément dans une liste est le nombre de fois où cet élément apparaît dans
 la liste.
 Fonctionnalités du programme- Créer et définir une liste simplement chaînée prédéfinie.- Permettre à l’utilisateur de **lire un élément** à rechercher.- Supprimer **toutes les occurrences** de cet élément dans la liste.
 2. Liste simplement chaînée avec test de tri et insertion
 Définition d’une liste triée
 Une **liste triée** est une liste dans laquelle les éléments sont organisés selon un ordre croissant
 ou décroissant.
 Fonctionnalités du programme- Créer et lire une liste simplement chaînée.- Vérifier si la liste est triée.- Si elle est triée : insérer un nouvel élément à sa position correcte.- Si elle n’est pas triée : trier la liste avant d’insérer.
 3. Liste doublement chaînée avec insertion dans une liste triée
 Définition
 Une **liste doublement chaînée** est une structure dans laquelle chaque nœud contient :- une **donnée**,- un pointeur vers le **nœud précédent** (`prev`),- un pointeur vers le **nœud suivant** (`next`).
Fonctionnalités du programme- Créer et définir une liste doublement chaînée prédéfinie.- Vérifier si la liste est triée.- Si elle n’est pas triée : la trier après l’affichage initial.- Insérer un élément dans la liste triée.
 4. Liste doublement chaînée circulaire avec insertion en tête
 Définition
 Une **liste doublement chaînée circulaire** est une variante où :- le pointeur `next` du dernier nœud pointe vers le premier nœud,- le pointeur `prev` du premier nœud pointe vers le dernier.
 Cela forme une boucle fermée (cercle).
 Fonctionnalités du programme- Créer une liste doublement chaînée circulaire contenant au moins 7 éléments.- Définir son principe de circularité.- Insérer un élément en **tête** de la liste.
 5. Liste doublement chaînée circulaire avec insertion en tête et en
 queue
 Fonctionnalités du programme- Créer une liste doublement chaînée circulaire contenant déjà des éléments.- Permettre à l’utilisateur d’insérer un élément :- en **tête**,- en **queue**.- Afficher la liste pour démontrer sa circularité.- Expliquer les principes d’insertion en tête et en queue.
 6. Programme principal
 Un **programme principal** regroupe toutes les fonctions précédentes.- L’utilisateur choisit l’opération qu’il souhaite exécuter au lancement.- Les contraintes suivantes sont respectées :- Si une liste simplement chaînée n’est pas triée, elle est automatiquement triée avant toute
 opération nécessitant un tri.
 Conclusion
 L’étude et l’implémentation des **listes chaînées** permettent de comprendre les avantages des
 structures de données dynamiques.
 Les listes simplement chaînées facilitent les suppressions et insertions rapides. Les listes
 doublement chaînées permettent une navigation dans les deux sens, et les listes circulaires
assurent une continuité entre le premier et le dernier élément.
 Ces programmes illustrent concrètement :- la création et la manipulation de différentes variantes de listes chaînées,- l’importance du tri dans certaines opérations,- les techniques d’insertion et de suppression,- et la démonstration pratique du principe de circularité.