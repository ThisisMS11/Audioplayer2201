# Audio Player
It is simple audio player created using basic html,css and js that lets you play some specific songs.

## Some highlights of the project
1. The design is entirely created using basic css and no other css framework used.
    ![](/imageproject/ip1.png)
---
2. The user can perform the following tasks in the audio player.
    * switching between any two songs
    * using jump buttons user can jump upto 3sec in one click for a song either in forward or in backward direction.
    * Play, Pause, next, previous, jumps buttons are well aligned with the buttons shown in the right side of each song item box.
    ---
    ![](/imageproject/ip2.png)

## How it works?
1. The songs used in the audio player are hard-coded and they are played by using them as a javascript object and aligning them with the music player functions.
    ![](/imageproject/ip3.png)

2. Each songlist item is linked with it's corresponding folder address and given a specific id in html code and using js selectors ,on click of the play button we are playing the corresponding song using 'audioelement' functions.

## Future scope for improvements
* Rather than hard-coding everything any music api (e.g. spotify api) could be integrated so that we would have access to wider range of music unlike in current version where we can only play some specific songs stored in the folder structure.

* Adding a user authentication so that every user can practice features like bookmarking favourite songs, or creating their own playlist of songs , viewing history etc.

---
# Thanks






