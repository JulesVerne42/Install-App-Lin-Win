# Pour une machine Linux Mint :
*Pour d'autres distro à vérifier, peut-être besoin d'installer flatpak (voir site flathub)*

- Aller sur le site [https://flathub.org/](https://flathub.org/)  
- Rechercher un logiciel  
- Sur la page en haut a droite il y a le bouton install, cliquer sur la flêche vers le bas
- Copier la première ligne de code (ex pour vlc "flatpak install flathub org.videolan.VLC")
- Coller dans son terminal (pas besoin de sudo)
- Nécessite de valider avec "y" par moment, mais on peut automatiser avec "-y"

* Sur les pages de chaque application, il y a des infos sur la sécurité et ce qui est propriétaire ou non.  
** Se faire un script bash afin d'automatiser l'install de toute les applications préféré, lors d'une fresh install.  


# Pour une machine Windows :
*A partir de Win10*

- Installer "winget"
- Aller sur le site https://winstall.app/
- Choisir une application et cliquer sur "Select app"
- Continuer avec toutes les applications voulu
- Puis cliquer sur "Generate script"
- Copier/coller le script dans powershell
- Laisser l'installation ce finir
