# Cysmu : The music player that suits you best 

Translations: EN | [FR](https://github.com/MadameMarine/Cysmu/blob/master/README-fr-FR.md)

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

