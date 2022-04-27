<div align="center">
  <a href="https://github.com/nathack-dev/gmod-rp-roll">
    <img src="présentation.png" alt="Logo" width="120" height="120">
  </a>

  <h3 align="center">Commande de Roll</h3>

  <p align="center">
Cette addon sert à augmenter le niveau de roleplay sur vos serveurs.
    <br/>
</div>

    
## ⚙️ How-To setup 
    - Dans la racine /addons
    - Crée un nouveau fichier nomée "roll"
    - Glissez-y le fichier lua
    
 ```lua
ROLLCONF = { 
tchatmsg = " obtient un résultat de : ",
cmd = "roll"

}
```
    Vous pouvez remplacer dans `tchatmsg` le message obtenu lors de l'exécution de la commande;
    ⚠️ Laisser le vide après le guillemet, le joueur qui aurait exécuté la commande apparéteras dans ce vide.
