# lab00 - README

## Préparation
### Github
- création d'un compte sur https://github.com avec l'adresse email de la HEIG-VD,
- sélection du plan `free`, 
- validation de l'inscription (clic sur `verify email` dans l'email reçu de github),
- installer GitHub Desktop depuis https://desktop.github.com sur l'ordinateur,
- le configurer avec l'identifiant github.com.
### Docker
- installer l'application `docker` depuis https://www.docker.com,
- créer un répertoire de travail pour le cours (nommé ci-après `WORKDIR`) 
- utiliser l'image `314rch/info` depuis le terminal :

```bash
docker run -it -p 127.0.0.1:8080:8080 -v WORKDIR/Work/.local/share/code-server:/home/coder/.local/share/code-server -v WORKDIR/Work/:/home/coder/project 314rch/info:latest
```

Exemple avec `WORKDIR=/Users/pierre/Documents/01-HEIG-VD/10-CLASSES/2019-2020/Info2-Mi-1-B` :

```bash
docker run -it -p 127.0.0.1:8080:8080 -v /Users/pierre/Documents/01-HEIG-VD/10-CLASSES/2019-2020/Info2-Mi-1-B/Work/.local/share/code-server:/home/coder/.local/share/code-server -v /Users/pierre/Documents/01-HEIG-VD/10-CLASSES/2019-2020/Info2-Mi-1-B/Work/:/home/coder/project 314rch/info:latest
```


## Assignment
- accepter l'`Assignment` Labo00
- à l'aide de GitHub Desktop, récupérez la donnée du labo (labo00.md)

## Travail à effectuer
- prendre connaissance de la donnée du labo
- réalisez le travail demandé
- enregistrer les données : `commit`
- livrer le travail : `push`
