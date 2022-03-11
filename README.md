# Configuration de DWM Juline Edition

## Téléchargement / prérequis 


Variante bleu :

```
https://github.com/juliiine/dwm-st-slstatus/blob/main/dwm-blue.tar.gz
```

L'ensemble des fichiers sont dans l'archive.

Pré-requis :

* nerd-fonts (CaskaydiaCove)
* picom
* feh
* slim (Display Manager conseillé si vous n'en avez pas déjà un).
* base-devel (Arch) ou équivalent suivant votre distribution.

## Déploiement

Il faut d'abord copier le fichier `.xinitrc` contenu dans l'archive dans `~/`, ainsi que `picom.conf` dans `~/.config/`.
Un script est peut-être nécessaire pour xrandr, qui détermine la résolution/framerate de vos écrans.

Ensuite, il faut se rendre dans chacun des dossiers `dwm`, `slstatus`, `dmenu`, `st` puis effectuer les actions suivantes :

* Editer si besoin le fichier config.h en fonctions de vos attentes et de votre matériel (nécessaire pour `slstatus` par exemple).
* `sudo make`
* `sudo make install`

Si vous n'avez pas d'erreur, c'est que tout est bon.

## Changer le fond d'écran

```
feh --bg-scale /home/<votreutilisateur>/image.png
```