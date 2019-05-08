##Project the_monkees_band
####The purpose of this project is to showcase the history of a famous '60s band - the monkees

There are functions to:
* display the history of the band including a youtube video
* allow some of the band's material (songs and videos) to be played
* include several of the band / band members photos

There are 4 pages: ABOUT US, PLAY MUSIC, PLAY VIDEOS and VIEW PHOTOS. 
Each page includes the following:
* a title
* social media links
* a cartoon picture of the band
* buttons for page selection
Note: these are the same on each page.

Bootstrap has been used to simplify the front end development. 
As the mouse is moved over each button, it 'hovers' - Bootstrap is initiated (hvr-sweep-to-bottom).

Also, a mobile-first approach has been used to ensure that lower resolution screens are catered for - responsive design has been implemented to ensure that each page is visible when in 'inspect' mode.

1. Page 1 - ABOUT US (index.html) gives a brief history of the band. Most of this has been taken from wikipedia.
There is a separate link to wikipedia for further in-depth information. There is also a link to youtube which gives a more complete history - sound / vision experience.

2. Page 2 - PLAY MUSIC includes a selection of 4 tracks to be played including CLARKSVILLE / I'M A BELIEVER / DAY DREAM BELIEVER / STEPPING STONE.

3. Page 3 - PLAY VIDEOS includes 1 video to be played - DAY DREAM BELIEVER.

4. Page 4 - VIEW PHOTOS - includes several pictures to view.

Background colour is consistent across all pages.
Fonts used are Roboto and Exo.
For all of the external links eg. facebook / twitter / youtube / wikipedia, target="__blank" is used such that a new window is opened.
Some of the code (buttons, hovering) has been based on code used in the Resume example in the course.
Version control has been implemented by use of git.

Testing:

1. Run index.html.
Page 1 is displayed with links to pages 1 - 4, facebook, twitter, youtube and band history information.
Pressing each button carries out it's desired function as described above.

2. Press PLAY_MUSIC to locate to 2nd page.
Page 2 is displayed with links to pages 1 - 4, facebook, twitter, youtube.
Pressing each button carries out it's desired function as described above.
In turn, press play for each of the music tracks - each 'song' should be played in turn.

3. Press PLAY_VIDEO to locate to 3rd page.
Page 3 is displayed with links to pages 1 - 4, facebook, twitter, youtube.
Pressing each button carries out it's desired function as described above.
Press play for the video . The video should start.

4. Press VIEW_PHOTOS to locate to 4th page.
Page 4 is displayed with links to pages 1 - 4, facebook, twitter, youtube.
All pictures are displayed.