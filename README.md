# Projet n°3 - Parcours Développeur Web - OpenClassrooms
## Dynamisez une page web avec des animations CSS

Ce projet est réalisé dans le cadre du parcours **Développeur Web** du site [OpenClassrooms](https://openclassrooms.com/ "OpenClassrooms")

### Documentations
* [Note de cadrage](docs/brief.pdf)

### Technologies utilisées
* HTML5
* CSS3
* SASS
* PREFIX

### Objectifs de la mission
Concevoir un site web de référencement de restaurants dans le cadre du parcours développeur web d'OpenClassrooms.
La maquette est fournie dans le cadre de ce projet : 
* [Maquette](docs/maquette)

### Compétences évaluées
* Mettre en œuvre des effets CSS graphiques avancés
* Assurer la cohérence graphique d'un site web
* Mettre en place une structure de navigation pour un site web

### Site web statique :

Pour explorer le site, rendez vous simplement [ici](https://www.hugohemon.fr/projet3/)


### Procédure ajout d'un menu
- 
    - Créer sa page html en y inscrivant le numéro correspondant dans les classes.
    - Dans index.html : Ajouter une balise en précisant son numéro:
    
    ```html
    <article class="menu-#">
                <a href="">
                    <div class="menu__ico"></div>
                    <h2 class="menu__titre">La palette du goût</h2>
                    <p class="menu__menu">Menu</p>
                </a>
            </article>
    ```
    - Dans variables.scss
        - ajouter les variables du nouveau menu dans les maps (3 couleurs,les polices)
    - Dans menu.scss:
        - ajouter un appel de mixin en attribuant les valeurs
     - Dans list.scss:
        - ajouter un appel de mixin en attribuant les valeurs
