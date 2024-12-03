# Jeu du Sudoku

# Projet Sudoku, 1ère annnée de BUT Informatique

Ce projet est une application Java permettant de **créer** et **résoudre** des grilles de Sudoku grâce à une interface utilisateur conviviale. Il comprend deux programmes distincts : un pour l'édition et la création de grilles, et un autre pour leur résolution.

## Fonctionnalités

### 1. Programme de Création de Grilles
- **Chargement et Sauvegarde** :
  - Charger une grille existante depuis un fichier.
  - Partir d'une grille vide.
- **Édition de la Grille** :
  - Ajouter ou supprimer des chiffres.
  - Empêcher les placements contradictoires.
- **Sauvegarde** :
  - Sauvegarder une grille finalisée au format spécifié.

### 2. Programme de Résolution de Grilles
- **Chargement de Grille** :
  - Importer une grille depuis un fichier.
- **Modes de Résolution** :
  - **Automatique** : 
    - Résoudre automatiquement la grille et afficher le temps de résolution.
  - **Manuel** :
    - Modifier les cases en respectant les contraintes d'unicité.


## Compilation et Exécution

1. Clonez ce dépôt sur votre machine locale :

   ```bash
   git clone https://github.com/FabioEtoile/Sudoku.git

2. Accédez au répertoire du jeu :

    ```bash
   cd Sudoku
3. Compilez le code source

    ```bash
   make
4. Exécutez le jeu :

    ```bash
   make run1

   make run2

5. Générer la JavaDoc :

   ```bash
   make javadoc

