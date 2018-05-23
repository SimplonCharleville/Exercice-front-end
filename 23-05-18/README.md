# Exercice individuel
# A réaliser correctement le plus rapidement possible

## Création d'un formulaire HTML + page PHP de récupération des données et envoi par e-mail

* Une partie HTML/CSS
  * Un header simple avec image de fond en background et titre
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
  * Dans une 2ème page (avec la même présentation), on récupère les valeurs des champs du formulaire :
   * On affiche un message "Demande prise en compte" ou "Une erreur est survenue".
   * On affiche les données saisies (même présentation que dans le formulaire)
   * On envoie les données par e-mail


# !! Dès que vous avez terminé, vous me prévenez !!
