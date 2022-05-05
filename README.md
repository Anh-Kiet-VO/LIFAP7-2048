# Projet 2048
Projet réalisé dans le cadre de l'UE LIFAP7.
Le 2048 est jouable version console et version interface (Swing)

-----------------
## Fonctionnalités :

- [X] améliorer le rendu de la vue graphique : coloration des cases, etc.
- [X] utiliser un pool de processus (classe Executor) au lieu des fonctionnalités directes de la classe Thread
- [X] enregistrer les données utilisateurs (meilleur score, temps, etc.)
- [X] possibilité de reprendre des coups (historique)
- [X] console avancée et interface graphique étendue : menus de navigations
- [X] une version deux joueurs (deux grilles côte à côte, les joueurs jouent alternativements, les coups sont appliqués aux deux grilles, le premier joueur dans une position bloquée perd la partie)

-----------------
## ⚒️ Installation :

Pour lancer le 2048 vous pouvez utiliser cette commande suivante :
```
cd dist && java -jar "TP2048.jar" 
```

Si vous êtes sous VSCode rendez-vous dans ``/src/vue_controleur/Main.java`` et faites ``F5``:

-----------------

### 🔖 Organisation de l'archive :  
```
├─ build/  (Fichier netbeans)
├─ dist/ (Fichier netbeans)
│  ├─ TP2048.jar (Fichier .jar pour éxecuter le jeu)
├─ nbproject/ (Fichier netbeans)
├─ src/ 
│  ├─ modele (Les fichiers modele du 2048)
│  ├─ vue_controleur (Les fichiers Vue et Controleur du 2048)
├─ test/ (Fichier neatbeans)
60214_undo_icon.png (Image utilisé pour le bouton pour annuler un coup)
best_score.txt (Fichier .txt pour stocker le meilleur score)