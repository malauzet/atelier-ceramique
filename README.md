# TP - Site web: Atelier Céramique Lyon

## Sommaire

- [Le site](#Le-site)
	- [Accueil](#Accueil)
	- [Galerie](#Galerie)
	- [Contact](#Contact)
- [Chartre graphique](#Chartre-graphique)
  - [Couleurs](#Couleurs)
  - [Polices & Tailles](#Polices-et-Tailles)
- [Choix techniques personnels](#Choix-techniques-personnels)
	- [Structure](#Structure)
	- [Implémentation](#Implémentation)
	- [Remarques](#Remarques)
	- [Améliorations](#Améliorations)


## Le site

### Accueil

La page d'accueil contient un héro avec de légères informations sur l'atelier ainsi qu'un bouton renvoyant vers la gallerie.

Juste en dessous se trouve la section "À propos" ainsi que la section "Nos valeurs" decrivant l'atelier et ses valeurs avec plus de détails.

Enfin, une section "Sélection" donne un aperçu des réalistations de l'atelier.

### Galerie

La page *Galerie* donne un plus grand aperçu que la section précédente sur les réalisations de l'atelier.

### Contact

La page *Contact* offre une possibilté d'échange par mail avec l'atelier pour un devis ou une commande.

Une section à droite donnant plus d'informations sur le lieu est aussi présente.

## Chartre graphique

### Couleurs

```css
--white-ish: #faf5f5;
--bg-body: #f8eade;
--accent-bg-body: #f4e0cd;
--bg-nav-ft-btn: #e2ac79;
--primary-txt-i: #35231d;
```

![#faf5f5](https://raw.githubusercontent.com/gist/malauzet/1214ec857070e16797526dda42a2f2c4/raw/29b84d3dd3906c76e56465ca86e0a164db90eb1e/faf5f5.svg)  `#faf5f5` Utilisé pour l'écriture dans le ```héro``` et le survole des liens.

  

![#f8eade](https://raw.githubusercontent.com/gist/malauzet/6e6310d29fba1f3879676864a71ee404/raw/5743795a3db4407ef1a219befc405cb695112cde/svg_f8eade.svg)  `#f8eade` Utilisé pour le fond du ```main```.

  

![#f4e0cd](https://raw.githubusercontent.com/gist/malauzet/aa5408905080b711daad8c19282eeb58/raw/f4364a9c295a2bd801423273a2814256b3e701d3/f4e0cd.svg)  `#f4e0cd` Utilisé pour contrasté le fond du ```main``` (bouton, cartes).

  

![#e2ac79](https://raw.githubusercontent.com/gist/malauzet/1fdf25a6b67678f17b1b8272dd7eee15/raw/b1d367993a3bd1a16106de91239827bbf5b270e0/e2ac79.svg)  `#e2ac79` Utilisé pour la ```nav```, le ```footer```, les boutons et les liens sur le fond du ```body```.

  

![#35231d](https://raw.githubusercontent.com/gist/malauzet/b6740211ef93c1f643f5dba35eadc2e1/raw/fa36cc239d758deb344979bc80b9ca78431231ea/35231d.svg)  `#35231d` Utilisé pour le texte et les icons.

### Polices et Tailles

Tableaux récapitulatifs de l'utilistation des polices et de leurs tailles.

| Police | Éléments | HTML Tag |
|----------|:------------:|:----------:|
|Bree Serif| Titres | h1, h2, h3 |
| Domine | Texte, Liens | p, a |

---
| Éléments |HTML Tag | Valeur |
|----------|:----------:|:--------:|
| Titre | h1 | 2.5em |
| Titre r2 | h2 | 1.5em |
| Texte | p | 1rem |

*Tailles sur page (hors Header/Hero/Footer)*

## Choix techniques personnels

### Structure
Je n'ai pas beaucoup changé la mise en page du site par rapport aux maquettes données.

 1. J'ai décalé un peu sur la droite la ```navbar```, je préfère quand elle est plus à droite.
 2. J'ai centré la partie droite de [Contact](#Contact) car je n'aimais pas tout plaquer à gauche.
 3. J'ai changé le petit logo dans la ```navbar``` pour être dans le thème du site.
 4. J'ai ajouté la mise en évidence de l'onglet sur lequel l'utilisateur se trouve.

### Implémentation

 1. Beaucoup de [Bootstrap](https://getbootstrap.com), c'était ma première vrai utilisation du framework.
 2. Mon choix des couleurs était pour rester dans un thème artisanal et chaud.
 3. Choix de polices assez arrondies en évitant des polices trop carrées et strictes pour un site d'artisanat.

### Remarques

 1. Bootstrap est très embêtant à personnaliser en l'important via un lien externe.
 2. Toujours mettre sa propre feuille de style en dernier pour éviter les ```!important```.

### Améliorations

 1. Enlever l'```outline``` autour du formulaire et ajouter de vraies bordures.
 2. Ajouter des couleurs de validations ou non dans le formulaire au lieu de la bulle de base.
 3. Avoir une vraie adresse avec une meilleure carte dans les informations.
 4. Plus d'images différentes avec des descriptions plus sympas.
 5. Compléter la consigne sur le ```hover``` dans la galerie.