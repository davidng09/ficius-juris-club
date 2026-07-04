# Ficius Juris Club

Site web vitrine du **Ficius Juris Club**, un club dédié à la formation, l'information et l'accompagnement dans le domaine du droit.

## Aperçu

Ce projet est un site statique (HTML/CSS) présentant les activités du club, son histoire et un formulaire d'inscription pour les nouveaux membres.

**Site en ligne :** [https://davidng09.github.io/ficius-juris-club/](https://davidng09.github.io/ficius-juris-club/)

## Fonctionnalités

- Page d'accueil avec navigation par ancres
- Sections : Qui sommes-nous, Que faisons-nous, Nos activités, Pourquoi nous rejoindre
- Formulaire d'inscription avec validation des champs
- Design responsive (mobile et desktop)
- Hébergement via GitHub Pages

## Technologies

- HTML5
- CSS3 (Flexbox, Grid, media queries)
- Google Fonts (Kanit, Roboto)
- Aucune dépendance externe

## Structure du projet

```
ficius-juris-club/
??? index.html          # Page d'accueil principale
??? home.html           # Redirection vers index.html
??? Formulaire.html     # Formulaire d'inscription
??? style.css           # Styles de la page d'accueil
??? Style2.css          # Styles du formulaire
??? images/
?   ??? Logo.png
?   ??? Logo.svg
?   ??? imageprinc.jpg
?   ??? activite_fc.jfif
?   ??? activite_fc1.jfif
?   ??? activite_fc2.jfif
?   ??? joinus.jpg
?   ??? icone.ico
??? .vscode/
?   ??? launch.json     # Configuration de débogage Chrome
??? README.md
```

## Installation et lancement

### Prérequis

- Un navigateur web moderne
- Python 3 (pour le serveur local) ou un autre serveur HTTP statique

### Lancer en local

1. Clonez le dépôt :

```bash
git clone https://github.com/davidng09/ficius-juris-club.git
cd ficius-juris-club
```

2. Démarrez un serveur local :

```bash
python -m http.server 8080
```

3. Ouvrez [http://localhost:8080](http://localhost:8080) dans votre navigateur.

### Débogage avec VS Code

Le fichier `.vscode/launch.json` est configuré pour lancer Chrome sur `http://localhost:8080`. Démarrez d'abord le serveur local, puis utilisez la configuration **Launch Chrome against localhost**.

## Pages

| Fichier           | Description                                      |
|-------------------|--------------------------------------------------|
| `index.html`      | Page d'accueil avec toutes les sections du club  |
| `Formulaire.html` | Inscription (nom, post-nom, prénom, email, tél.) |
| `home.html`       | Redirection automatique vers `index.html`        |

## Contact

- Email : contact@ficiusjurisclub.org
- LinkedIn · Facebook · Instagram (liens à configurer dans `index.html`)

## Auteur

Projet développé pour le **Ficius Juris Club**.

## Licence

Ce projet est à usage éducatif et associatif.
