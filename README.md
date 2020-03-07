# P3_hemon_hugo
Projet 3 OpenClassrooms

Concevoir un site web de référencement de restaurants dans le cadre du parcours développeur web d'OpenClassrooms.

- Procédure ajout d'un menu :
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
        - ajouter les variables du nouveau menu dans les maps
    - Dans menu.scss:
        - ajouter un appel de mixin en attribuant les valeurs
     - Dans list.scss:
        - ajouter un appel de mixin en attribuant les valeurs
