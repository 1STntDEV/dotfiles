# My Arch Linux Dotfiles

Mes fichiers de configuration pour Arch Linux.

## Installation

Installer les logiciels nécessaires :

```bash
sudo pacman -S \
i3-wm kitty picom conky rofi feh ranger mpv firefox \
cmus rtorrent vim git
```

Cloner le dépôt :

```bash
git clone https://github.com/1STntDEV/dotfiles.git
cd dotfiles
```

Copier les fichiers de configuration :

```bash
mkdir -p ~/.config

cp -r i3 ~/.config/
cp -r kitty ~/.config/
cp -r picom ~/.config/
cp -r conky ~/.config/
```

Redémarrer i3 :

```bash
i3-msg reload
i3-msg restart
```

Ou redémarrer la session.

---

# Utiliser Git

Voir les fichiers modifiés :

```bash
git status
```

Ajouter toutes les modifications :

```bash
git add .
```

Créer un commit :

```bash
git commit -m "Description des changements"
```

Envoyer les modifications sur GitHub :

```bash
git push
```

Récupérer les dernières modifications :

```bash
git pull
```

Voir l'historique :

```bash
git log --oneline
```

