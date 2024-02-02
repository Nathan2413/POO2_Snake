# POO2_Snake

Ce dépôt contient le code source d'un jeu Snake développé en Java avec l'utilisation de JavaFX. Suivez les étapes ci-dessous pour télécharger, configurer et exécuter le projet sur votre machine.

## Prérequis
- [JavaFX SDK](https://gluonhq.com/products/javafx/) : Téléchargez le SDK JavaFX depuis le site officiel de Gluon.
- Eclipse IDE : Assurez-vous d'avoir Eclipse installé sur votre machine.

## Instructions

1. **Téléchargement du JavaFX SDK :**
   - Téléchargez le JavaFX SDK depuis [ce lien](https://gluonhq.com/products/javafx/).

2. **Extraction du fichier JavaFX :**
   - Extrayez le fichier JavaFX téléchargé au format zip sur votre machine.

3. **Clonage du projet POO2_Snake :**
   - Utilisez la commande suivante dans votre terminal pour cloner le projet depuis GitHub :
     ```
     git clone https://github.com/Nathan2413/POO2_Snake.git
     ```

4. **Ouverture dans Eclipse :**
   - Lancez Eclipse et ouvrez le workspace.
   - Cliquez sur "File" puis "Open File".
![image](https://github.com/Nathan2413/POO2_Snake/assets/109501880/08980fe9-6c7f-48d3-8eff-cb8433095e46)

5. **Ouverture du fichier source :**
   - Ouvrez le fichier `Java_Snake_Fx/src/SnakeApp.java` dans Eclipse.

6. **Configuration du Build Path :**
   - Cliquez avec le bouton droit sur le projet, puis sélectionnez "Build Path" et enfin "Configure Build Path".

7. **Ajout des JARs externes :**
   - Sélectionnez l'onglet "Modulepath", puis cliquez sur "Add External JARs".

8. **Sélection des fichiers JavaFX :**
   - Naviguez jusqu'au dossier où vous avez extrait le fichier JavaFX (chemin : `javafx-sdk-21.0.2\lib`).
   - Sélectionnez tous les fichiers JAR présents dans le dossier et cliquez sur "Open".

9. **Application des modifications :**
   - Cliquez sur "Apply and Close" pour valider les modifications apportées au Build Path.

10. **Lancement du projet :**
    - Cliquez sur "Run", puis sélectionnez "Run Configurations".

11. **Configuration des arguments VM :**
    - Cliquez sur "Arguments" puis sur "VM arguments".
    - Modifiez les arguments VM en écrivant le code suivant : 
      ```
      --module-path "path/to/javafx-sdk/lib" --add-modules javafx.controls,javafx.fxml
      ```

12. **Lancement du programme :**
    - Cliquez sur "Run" pour lancer le programme.

13. **Exécution après le lancement :**
    - Amusez-vous en jouant à Snake sur votre application JavaFX fraîchement lancée !

