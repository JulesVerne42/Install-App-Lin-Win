# Dans ce guide je vous propose de partager deux solutions pour installer des applications automatiquement sur Linux et Windows.

> Faite vous un script pour automatiser l'installation lors de fresh install.

## Pour une machine Linux Mint :
*Pour d'autres distro à vérifier, peut-être besoin d'installer flatpak (voir site flathub)*

- Aller sur le site [https://flathub.org/](https://flathub.org/)  
- Rechercher un logiciel  
- Sur la page en haut a droite il y a le bouton install, cliquer sur la flêche vers le bas
- Copier la première ligne de code (ex pour vlc `flatpak install flathub org.videolan.VLC`)
- Coller dans son terminal (pas besoin de sudo)
- Nécessite de valider avec `y` par moment, mais l'on peut automatiser avec `-y`


## Pour une machine Windows :
*A partir de Win10*

- Installer `winget`
- Aller sur le site [https://winstall.app/](https://winstall.app/)
- Choisir une application et cliquer sur `Select app`
- Continuer avec toutes les applications voulu
- Puis cliquer sur `Generate script`
- Copier/coller le script dans powershell
- Laisser l'installation se finir
