# Cysmu : Le lecteur qui vous ressemble

Un lecteur musical complet et léger, entièrement personnalisable qui offre une expérience de navigation et d'écoute unique et innovant.

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

### Mini Lecteur
Une version plus petite du lecteur permettant d'effectuer des interactions simples lorsque le lecteur de Cysmu est en arrière plan.

Celui ci intervient:
- Dans la bar de notification lorsqu'une musique se lance
- En bas de l'écran lorsque l'utilisateur navigue dans l'application 
- Sur l’écran de verrouillage

Le mini lecteur propose une interface simplifiée avec les informations et interactions minimum:
- Lancer et mettre en pause la musique
- Aller à la piste suivante / précédente
- Voir le titre, l'album et l'artiste du titre en cours de lecture

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
Il s'agit d'un tableau de bord entièrement personnalisable où des items (musique, albums, playlist, ...) peuvent être **pin** par l'utilisateur, ils jouent alors le rôle de raccourci.

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
| Classique|  |
| ...|  |
| ...|  |



# English Version

# Cysmu : The music player that looks like you


A completed, light, and fully cuztomizable music player that offers an unique, and innovative and listening experience.

## Features
### Music Player
An interface representing a reader to play music.
It displays informations about the current track such as title, author, and album.


 ##### Play music
Start the music through a button.

 ##### Mettre en pause
 Stop the music through a button 

 ##### Go to the next / previous track
 Go to the next/previous track by using the **go back** and **next track** buttons.
 
 Expected behaviour : 
 - When the music is not played, **go back** reset the current track.
 - **Next track** aims at to go the next track in any case.

 ##### Time Jump
 A quick press on the right / left side of the screen generate a 15 sec jump forward / backward of the current music.
 The value of 15 sec will be customizable by the user.
 
 ##### See the progress of the current queue 
 Displays an interactive progress bar representing the progress of track
  
 ##### Loop playback
 Loops a single or entire queue through a button that has the following states : 
 - Desactivated
 -  Loop playback (queue)
 -  Loop playback (track)

### Mini Player
A smaller version of player to perform simple interactions when Cysmu is in the background.

Mini Player is present : 
- In the notification bar when a music starts
- At the bottom of the screen when the user navigates in Cysmu
- On the locked screen

The Mini Player offers a simplified interface with the minimum informations and interactions : 
 - Play and pause the music
 - Go to the next / previous track
 - See the title, ambum and artiste of the title being played

### Playlist
These are custom lists created by the user.

##### Favorite
A special playlist named **Favorite** permit to save user's favorate musics with an icon  ❤.

##### Quick creation  :zap:
We will able to create a playlist  directly with the contextual menu for adding a track.

### Playback file
This is a list with all the tracks to be played by the music player.

##### Après-vous
Add a track at the top of the playback file.

##### Shuffle play
Mix the list randomly.

##### Swipe to delete
Quick suppression of item from the queue.

### Modula
This is the main page and entry point of the application.
It is a fully cuztomizable dashboard where items (music, ambum, playlist ... ) can be **pin** by the user, they are shortcut.

:warning: **personnalisation** and **suppression** parts will be subject of a study in a dedicated User Story.

##### Pin
Pin any item to the homepage with an icon 📌 next to the items.

An **item** can be:
- an music
- an album
- an artist
- a playlist
 
##### :warning: Personnalisation 
The user can reorganize his Modula with a **Drag and Drop** system that will be activated with a **long press**

##### :warning: Suppression
L'utilisateur pourra supprimer un item de son Modula en appuyant sur une icône :x: qui s'affichera sur un des bords de l'item.

##### Reinitialisation
The user we be able to resert his Modula with the default configuration.

### Various

##### Dynamic atmospheree
Offers the user the possiblity to vary the ambiance between  multiple predefined listening modes.
These modes result from a particularr settings of filters or amplifiers of sound frecuency bands.
The theme adapts to the selected mood.

| Ambiance | Description |
|--|--|
| Cozy|  |
| Classic|  |
| ...|  |
| ...|  |

