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
     
  ![image](https://github.com/Nathan2413/POO2_Snake/assets/109501880/777223c0-b91b-41ea-9b7e-e7f5e3d2de45)


5. **Ouverture du fichier source :**
   - Ouvrez le fichier `Java_Snake_Fx/src/SnakeApp.java` dans Eclipse.
     
![image](https://github.com/Nathan2413/POO2_Snake/assets/109501880/4332a1df-6c90-4be8-9b98-cb1a6ab71049)

6. **Configuration du Build Path :**
   - Cliquez avec le bouton droit sur le projet, puis sélectionnez "Build Path" et enfin "Configure Build Path".
     
![image](https://github.com/Nathan2413/POO2_Snake/assets/109501880/ad80357b-1451-4a68-a230-4699ba2cf920)

7. **Ajout des JARs externes :**
   - Sélectionnez l'onglet "Modulepath", puis cliquez sur "Add External JARs".

![image](https://github.com/Nathan2413/POO2_Snake/assets/109501880/8ef237f9-4cc3-4fd3-ba56-ba08bc6f8739)

8. **Sélection des fichiers JavaFX :**
   - Naviguez jusqu'au dossier où vous avez extrait le fichier JavaFX (chemin : `javafx-sdk-21.0.2\lib`).
   - Sélectionnez tous les fichiers JAR présents dans le dossier et cliquez sur "Open".

![image](https://github.com/Nathan2413/POO2_Snake/assets/109501880/ec55a3e2-0626-4a5a-88f0-6e855473106b)


9. **Application des modifications :**
   - Cliquez sur "Apply and Close" pour valider les modifications apportées au Build Path.

![image](https://github.com/Nathan2413/POO2_Snake/assets/109501880/f2171e2b-f0f5-4bad-9592-5d8ab5d108f7)


10. **Lancement du projet :**
    - Cliquez sur "Run", puis sélectionnez "Run Configurations".

![image](https://github.com/Nathan2413/POO2_Snake/assets/109501880/50ea29d5-6e74-4037-ba02-b8341df81b01)


11. **Configuration des arguments VM :**
    - Cliquez sur "Arguments" puis sur "VM arguments".
    - Modifiez les arguments VM en écrivant le code suivant : 
      ```
      --module-path "path/to/javafx-sdk/lib" --add-modules javafx.controls,javafx.fxml
      ```

![image](https://github.com/Nathan2413/POO2_Snake/assets/109501880/b7720407-4ac0-44df-b870-8d9e3f5476fb)


12. **Lancement du programme :**
    - Cliquez sur "Run" pour lancer le programme.

![image](https://github.com/Nathan2413/POO2_Snake/assets/109501880/594600d7-bcdc-4782-995a-ba54b643c864)


13. **Exécution après le lancement :**
    - Amusez-vous en jouant à Snake sur votre application JavaFX fraîchement lancée !

![image](https://github.com/Nathan2413/POO2_Snake/assets/109501880/71c2515a-a1b2-4542-bc83-fab6c78dbdbd)

![image](https://github.com/Nathan2413/POO2_Snake/assets/109501880/b108247f-3c5e-4caf-a13f-e31c0ac5c6a6)

![image](https://github.com/Nathan2413/POO2_Snake/assets/109501880/47ca0fad-bde5-4ac1-b557-6605dbc7b745)




