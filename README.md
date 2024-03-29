# Eurocodes-library-Function-VBA
Librarys of Eurocodes functions to integrate them in Excel.

# Contributing
Feel free to download use and contribute to the project. Feedback is welcome, you cans also tell tour colleagues and friends about the project or just ... use it as it is ! Feel free to get in touch with me if you want to add functions yourself or spreadsheets using the functions already there!

# Français
La création de de feuilles de macro dédiée aux Eurocodes est issue de la volonté de créer un ensemble de « briques », composantes de base des calculs Eurocodes. Ces briques sont composées des calculs de base qui sont susceptibles d’être utilisés régulièrement dans les calculs et l’utilisation des Eurocodes.
L’objectif de tout ceci est de permettre de s’affranchir des calculs dit « de base » afin que ceux-ci soient traités une seule fois. La création de feuilles de calculs, d’outils personnels en devient simplifiée et l’ingénieur peut se consacrer à des tâches plus complexes en prenant le temps d’y apporter une valeur ajoutée.

Les fonctions ont été développées dans le but de faciliter leurs utilisations, même en dehors d’une feuille de calcul élaborée. Elles sont bien entendu utilisables pour la création de feuilles de calculs aux Eurocodes plus complexes mais doivent pouvoir être utilisées plus ponctuellement, soit seules, soit pour créer une procédure de calcul éphémère destinée à résoudre un problème ponctuel. Un grand nombre de paramètres sont donc optionnels, ils prennent les valeurs par défaut d’une situation courante. Ainsi, pour l’exemple, le seul argument obligatoire pour le calcul de la résistance en cisaillement d’un boulon est son diamètre ! Les autres arguments prennent une valeur par défaut courante telle la considération du plan de cisaillement passant par le filetage.

Cette bibliothèque de fonction est donc résolument orientée dans le sens des utilisateurs, utilisant quotidiennement et de façon pratique les Eurocodes et leurs fonctions. Il ne serait pas souhaitable d’imposer la demande de trop nombreux paramètres qui sont d’ordinaires pris par « réflexe ». Cela rendrait moins pratique l’utilisation de ces fonctions et conduirait à faire le calcul manuellement, étant devenu plus rapide. Toutefois, dans le cadre de développement d’une feuille de calcul plus complète, ces fonctions disposent tout de même d’options de calcul suffisamment fournies pour être utilisables de façon complète.

# English
The creation of macro sheets dedicated to Eurocodes stems from the desire to create a set of «bricks», basic components of Eurocodes calculations. These bricks consist of basic calculations which are likely to be used regularly in the calculations and use of Eurocodes.
The purpose of all of this is to get rid of the so-called “basic” calculations so that they are processed only once. The creation of spreadsheets, personal tools become simplified and the engineer can devote himself to more complex tasks by taking the time to add value.

The functions have been developed to facilitate their use, even outside of an elaborate spreadsheet. They are of course usable for the creation of more complex Eurocode spreadsheets but must be able to be used more punctually, either alone or to create an ephemeral calculation procedure intended to solve a punctual problem. A large number of parameters are optional, they take the default values of a current situation. Thus, for example, the only mandatory argument for calculating the shear strength of a bolt is its diameter! The other arguments take a common default value such as considering the shear plane through the thread.

This library of functions is therefore resolutely user-oriented, using the Eurocodes and their functions on a daily and practical basis. It would not be desirable to impose the demand on too many parameters that are usually taken by «reflex». This would make the use of these functions less convenient and would lead to doing the calculation manually having become faster. However, as part of the development of a more comprehensive spreadsheet, these functions still have sufficient calculation options to be fully usable.

# Utilisation
- Les fichiers se terminant par ".xlam" sont des fichiers d'extensions de Excel ils doivent être ajoutés dans le dossier "C:\Users\[Nom]\AppData\Roaming\Microsoft\AddIns" puis activés dans Excel Onglet "Développeur", sous menu "Compléments", bouton "Compléments Excel". La procédure pour activer ces compléments est rappelée dans le wiki.
- Toutes les explications d'utilisation des fonctions contenues dans les fichiers .xlam sont directement accessibles dans la partie "wiki" de ce projet. Il est également détaillé les tests effectués pour vérifier le bon fonctionnement des fonctions.
- le sous-dossier 'Feuilles-réalisées" continent à la fois des feuilles de calcul par type d'assemblage utilisant les fonctions précédentes et des fichiers en format Word fournissant une notice d'utilisation, détail des hypothèses et les vérifications qui ont été menés sur les feuilles de calcul.
