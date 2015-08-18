# Trampolean

Suivi de l'expérience en direct

[website](http://trampolean.github.io/trampolean/)

## Installation modification

### cloner le dépôt github en local

Ouvrir un terminal
```bash
// dans le dossier approprié, par exemple sites
$ cd ~/sites
$ git clone git@github.com:trampolean/trampolean.git
```
### récupérer les modifications effectuer sur github par un collaborateur

Ouvrir le terminal
```bash
$ cd ~/sites/trampolean
$ git pull
```

### effectuer une modification

Ouvrir le terminal et lancer un petit serveur local, par exemple :
```bash
$ cd ~/sites/trampolean
$ python3 -m http.server 8000
ou
$ python -m SimpleHTTPServer 8000
```

Ouvrir les fichiers avec un éditeur : [brackets](http://brackets.io/) ou [atom](https://atom.io/) par exemple.
Faire une modification.

Vérifier dans un navigateur : http://localhost:8000

### publier une modification

Ouvrir le terminal
```bash
$ cd ~/sites/trampolean
$ git add .
$ git commit -m "Un message explicite qui explique ma petite modification"
$ git push
```

## Template

"Boxify" One Page Website Template by Peter Finlan for Codrops

Demo: http://tympanus.net/Freebies/Boxify/
Download and article: http://tympanus.net/codrops/?p=22554

Use it freely but please do not redistribute or sell.
Read more here: http://tympanus.net/codrops/licensing/
