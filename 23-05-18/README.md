# Exercice individuel

## Création d'un formulaire HTML + page PHP de récupération des données en DB

* Une partie HTML/CSS
  * un formulaire contenant :
    * Un label "Titre" avec 2 boutons radio "Mme" "Mr" **(obligatoire)**
    * Un label "Prénom" + champ **obligatoire**
    * Un label "Nom" + champ **obligatoire**
    * Un label "E-mail" + champ
    * Un label "Se souvenir de moi" + case à cocher
    * Un bouton "Envoyer" pour valider le formulaire
### Respect des bonnes pratiques des formulaires HTML : https://openclassrooms.com/courses/apprenez-a-creer-votre-site-web-avec-html5-et-css3/les-formulaires-8
  
* Une partie JavaScript
  * Quand on clique sur le bouton "Envoyer", une fonction vérifie que les champs oligatoires sont remplis :
    * Si les champs obligatoires sont remplis, on passe à l'étape suivante
    * Si les champs obligatoires ne sont pas remplis, on affiche une boite d'alerte indiquant les champs qui doivent être renseignés
  
* Une partie PHP (documentation PHP officielle : http://php.net/manual/fr/)
  * Dans une 2ème page, on récupère les valeurs des champs du formulaire
  
* Une partie DB/SQL
  * Création d'une base de données MySQL via phpMyAdmin comprenant une table avec :
    * Un champ #ID
    * Un champ Titre
    * Un champ Prénom
    * Un champ Nom
    * Un champ E-mail
    * Un champ Souvenir
    * Un champ Date indiquant la date de saisie
### AIDE : https://openclassrooms.com/courses/concevez-votre-site-web-avec-php-et-mysql/phpmyadmin-5

# !! Dès que vous avez terminé, vous me prévenez !!
