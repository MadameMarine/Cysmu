# Cysmu : Le lecteur qui vous ressemble

Un lecteur musical complet et léger, entièrement personnalisable qui offre une expérience de navigation et d'écoute unique et innovante.

## Features
### Lecteur de musique
Une interface représentant un lecteur permettant de gérer la lecture d'un morceau. Il affiche des informations sur la piste en cours tels que le titre, l'auteur et l'album.

 ##### Lire la musique
Mettre en marche la musique par l'intermédiaire d'un bouton.
 ##### Mettre en pause
Mettre en pause la musique par l'intermédiaire d'un bouton. 
 ##### Passer à la piste suivante / précédente
 Permet de passer à la piste suivante / précédente de la file de lecture par l'intermédiaire de boutons **retour arrière** et **piste suivante**.
 Comportement attendu:
 - Quand la musique n'est pas lancée, **retour arrière** passe à la piste précédente.
 - Quand la musique est déjà lancée, **retour arrière** réinitialise la piste en cours.
 - **Piste suivante** permet de passer à la piste suivante dans tout les cas.
 
 ##### Saut temporel 
 Un appuie rapide sur le coter droit / gauche de l'écran entraîne un saut de 15 sec vers l'avant / l'arrière de la musique en cours.
 Cette valeur de 15 sec sera personnalisable par l'utilisateur.
 
 ##### Voir la progression de la lecture en cours
 Affiche une bar de progression interactive représentant la progression de la lecture.
  
 ##### Lecture en boucle
Permet de lire en boucle une unique piste ou une file de lecture entier par l'intermédiaire d'un bouton qui comporte les états suivants:
- Désactivé
- Lecture en boucle (file)
- Lecture en boucle (piste)

### Playlist
Ce sont des listes personnalisées créées par l'utilisateur.

##### Favori
Une playlist particulière nommée **Favori** permet de sauvegarder les musiques favorites de l'utilisateur via une icone ❤.

##### Création éclaire :zap:
On pourra créer directement une playlist via le menu contextuel de l'ajout d'une piste.

### File de lecture
C'est une liste contenant l'ensemble des morceaux devant être joué par le lecteur de musique.

##### Après-vous
Permet d'ajouter une piste tout en haut de la file de lecture.

##### Aléatoire
Mélange la liste aléatoirement.

##### Swipe to delete
Permet la suppression rapide d'un élément de la file.

### Modula
La page centrale et le point d'entrer de l'application.
Il s'agit d'un tableau bord entièrement personnalisable où des items (musique, albums, playlist, ...) peuvent être **pin** par l'utilisateur, ils jouent alors le rôle de raccourci.

:warning: La partie **personnalisation** et **suppression** feront l'objet d'une étude dans une User Story dédiée.

##### Pin
Permet d'épingler n'importe quel items sur la page d'accueil par l'intermédiaire d'une icône 📌présent à coter des items.
Un **item** peut représenter :
- Une musique
- Un album
- Un artiste
- Une playlist
 
##### :warning: Personnalisation 
L'utilisateur pourra réorganiser son Modula via un système de **Drag and drop** qui s'activera grâce à un **appuie long**. 

##### :warning: Suppression 
L'utilisateur pourra supprimer un item de son Modula en appuyant sur une icône :x: qui s'affichera sur un des bords de l'item.

##### Réinitialisation
L'utilisateur pourra réinitialiser son Modula avec la configuration par défaut.

### Divers

##### Ambiance dynamique 
Permet à l'utilisateur de varier les saveurs entre plusieurs modes d'écoutes prédéfinis.
Ces modes résultent d'un paramétrage particulier de filtres ou d'amplificateurs de bandes de fréquences sonores.
Le thème s'adapte à l'ambiance sélectionnée. 

| Ambiance | Description |
|--|--|
| Cozy|  |
| ...|  |
| ...|  |
| ...|  |


