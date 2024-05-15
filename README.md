<h1>
  alto architecture
</h1>
<h3>Key points:</h3>
  Any user can add their own music, and it will be visible to everyone else, you can find it in search and add it to your playlists or favorite music.<br>
	If an application is going to be created, then songs will be able to downloaded, not to the device, but to the cache.<br>
	When logging in for the first time, the user finds himself on the “main” window; when trying to play a song, a window pops up asking for registration (questionable). Add tracks, create your own playlists, listen to music, etc. - free functions, paid functions will be personalization and adding tracks, and creating playlists beyond the norm (50 of your songs, 5 playlists).<br>
	4 playlists can be pinned to favorites and will always be displayed on the navigation component.<br>
	Components: header, navigation, trackpad are always fixed, regardless of the user's wishes. They occupy such space that they do not interfere with long-term use. All actions, such as logging into the user’s personal profile, creating your own playlist, selecting music for playlists, are carried out on the main space.<br>
 	There are no transition animations in the project.<br>
 	Login and registration are the same; you only need a phone number and code verification via SMS. There is no other way to register; there can only be one number in the system. This is done to avoid “dead” accounts.<br>
	The language of the site will correspond to the selected region; if the region is not selected, then the language is set to the base language - English, but it can be changed by clicking on the corresponding icon and selecting the desired language from the pop-up window.<br>








<h3>Parsing pages:</h3>
<h4>1.	Home</h4>
This page first reveals the user's recently listened to playlists (created or added by them). Next are the most popular listening playlists (the list is updated at midnight for the selected region). Next is adapted music for the user, by genre (rock, electro, pop). Etc. The logic of the page is simple, everything I wanted to do quickly, but not too much.

<h4>2.	Search</h4>
This page contains a search that prioritizes music, playlists, song lyrics, etc.

<h4>3.	Music</h4>
There are 2 tabs on this page. The main (first) one contains the music that the user has added to himself; this feature is present for each music (adding from this list). In the second tab is music added by the user himself from his device.

<h4>4.	Playlists</h4>
There are 2 tabs on this page. The main (first) one contains playlists that the user has added to himself; this feature is present for each playlist (adding from this list). In the second tab there is a playlist created by the user himself, in this case you can choose whether it is private or not.<br><br>
	These are the main pages that the user can go to; when entering a playlist, you can turn on any song from it, add it to yourself, or add any song from this playlist. The playlist takes up the entire space of the main space. The transition history is also saved, so you can go back to the page before the playlist.<br>
 	It is possible to go to your profile; it consists of a username, avatar, and background. At the bottom of the profile, playlists created by the user are displayed, if they are public, and the music they have added. The user himself can set up privacy and nothing will be displayed except his name, avatar and background. All of the above can be changed.<br>
<h3>Technical solution of the project:</h3>
 The entire project will be created with NextJs, the design will be created in Figma, a database to store all the information is MongoDb. User data is saved in a separate database folder. When you log in or register, information is saved in a cache for 14 days. The cache is used for verification; if the user does not have this cache, then they need to log in again.
	
Link to design in Figma: https://www.figma.com/design/hTtGvwZg9uEsUDVH0bcOk5/Alto?m=dev&node-id=1%3A2&t=JlTTIZoHfEZdi9nt-1
