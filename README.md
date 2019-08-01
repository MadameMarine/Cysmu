# Cysmu : The music player that suits you best 

Translations: EN | [FR](https://github.com/MadameMarine/Cysmu/blob/master/README-fr-FR.md)

A completed, light, and fully cuztomizable music player that offers an unique, and innovative listening experience.

## Features
### Music Player
An interface representing a music player.
Information about the current track such as title, author, and album are displayed.


 ##### Play music
Start the music using a button.

 ##### Mettre en pause
 Stop the music using a button 

 ##### Go to the next / previous track
 Go to the next/previous track by using the **go back** and **next track** buttons.
 
 Expected behaviour : 
 - When the music is not played, **go back** reset the current track.
 - **Next track** starts the next track in any case.

 ##### Time Jump
 A quick press on the right / left side of the screen generate a 15 sec jump forward / backward of the current music.
 The value of 15 sec will be customizable by the user.
 
 ##### See the progress of the current queue 
 Displays an interactive progress bar representing the progress of the track
  
 ##### Loop playback
 Loops a single or entire queue through a button that has the following states : 
 - Deactivated
 - Loop playback (queue)
 - Loop playback (track)

### Mini Player
A smaller version of the music player to perform simple interactions when Cysmu is in the background.

Mini Player is present : 
- In the notification bar when a music starts
- At the bottom of the screen when the user navigates in Cysmu
- On the locked screen

The Mini Player offers a simplified interface with the minimum informations and interactions : 
 - Play and pause the music
 - Go to the next / previous track
 - See the title, ambum and artist of the title being played

### Playlist
These are customs lists created by the user.

##### Favorite
A special playlist named **Favorite** allows to save the favorites song with an icon ❤.

##### Quick creation :zap:
We will able to create a playlist directly with the dialog for adding a track.

### Playback file
This is a list with all the tracks to be played by the music player.

##### Après-vous
Add a track at the top of the playback file.

##### Shuffle play
Mix the list randomly.

##### Swipe to delete
Quick deletion of item from the queue.

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
The user can reorganize his Modula with a **Drag and Drop** behavior after a **long press**

##### :warning: Deletion
The user can delete an item from his Modula by pressing :x: on its top right corner.

##### Reset
The user can reset his Modula back to the default configuration.

### Miscellaneous 

##### Dynamic atmospheree
A pool of predifined listening mode will set an unique atmosphere across the app.
These modes result from a particularr settings of filters or amplifiers of sound frecuency bands.
The app theme adapts to match the selected mood.

Here a list of all the current **ambiances**:

| Ambiance | Description |
| -- | -- |
| Cozy |  |
| Classic |  |
| ... |  |
| ... |  |

