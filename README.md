# spicetifyconfig
This is my Spicetify config/setup that I've tested and I'm using now, based on lots of .js sources I found (included Marketplace for Snippets/CSS itself).
All the downloads will lead to the original author/link.

--- Extensions ---
1. immersiveView: to hide library/ now playing bar/ right sidebar (@ohitstom)
https://github.com/ohitstom/spicetify-extensions/tree/main/immersiveView

<img width="1551" alt="Screenshot 2025-07-10 at 14 47 36" src="https://github.com/user-attachments/assets/6f9ba83a-8603-481e-9146-2ff30fe7da52" />


2. LibX-Reborn: enable the old global navigation sidebar on the left and search on the top (@sanoojes)
https://github.com/sanoojes/Spicetify-Extensions/tree/master/LibX-Reborn
  -> Fix the Marketplace icon that having a gap using CSS (@silver-wizard11):
      .Kgjmt7IX5samBYUpbkBu {
        display: none;
      }
  * You must install Marketplace to insert your own CSS in the Snippets due to cli doesn't support it anyway. *

<img width="1551" alt="Screenshot 2025-07-10 at 14 29 59" src="https://github.com/user-attachments/assets/2073dcf4-39ed-4f5d-9f8d-910333cbf240" />

<img width="1551" alt="Screenshot 2025-07-10 at 14 32 08" src="https://github.com/user-attachments/assets/b274a503-a8d6-4d72-8683-e04831dceb07" />
<img width="1551" alt="Screenshot 2025-07-10 at 14 33 41" src="https://github.com/user-attachments/assets/868cfbdc-6071-4787-8d97-7910c1cf7b9c" />

  -> By default, the search is not a bar, it's just the icon. Add this CSS to restore the bar back (@sanoojes)
      https://github.com/sanoojes/Spicetify-Extensions/issues/2#issuecomment-2613788142

<img width="580" alt="Screenshot 2025-07-10 at 14 35 57" src="https://github.com/user-attachments/assets/bcf79b1d-ad19-45fa-a43a-6fe72fc64b01" />
<img width="581" alt="Screenshot 2025-07-10 at 14 36 56" src="https://github.com/user-attachments/assets/ad7131f8-850e-4d49-9a98-9bab861425ff" />

3. NowPlayingReleaseDate: displays the release date of the track next to the song name/author (@Plueres)
https://github.com/Plueres/spicetify-extensions/tree/main/now-playing-release-date

<img width="1551" alt="Screenshot 2025-07-10 at 14 45 05" src="https://github.com/user-attachments/assets/b26bdfb7-5d1e-457a-909b-fd070e6577b2" />


4. npvAmbience: this add a colorful gradient glow behind the cover art in right sidebar (@ohitstom)
https://github.com/ohitstom/spicetify-extensions/tree/main/npvAmbience

5. playback-bar-waveform: turn your playback bar into waveform (@Konsl)
https://github.com/Konsl/spicetify-extensions/tree/main/playback-bar-waveform

6. QueueTime: show remaining times in queue (@Theblockbuster1)
https://github.com/Theblockbuster1/spicetify-extensions/tree/main/QueueTime

7. quickQueue: quickly add a track into queue (@ohitstom)
https://github.com/ohitstom/spicetify-extensions/tree/main/quickQueue

8. romajin: show romaji under the original japanese lyrics (@Richie-Z)
https://github.com/Richie-Z/romajin

<img width="1551" alt="Screenshot 2025-07-10 at 14 52 52" src="https://github.com/user-attachments/assets/8fe40c88-7b14-446b-bcb7-4d3844b181ef" />

9. shuffle+: this shuffle use Fisher–Yates algorithm, you can select as many tracks and use it to provides similiar taste. (@spicetify)
https://github.com/spicetify/cli/blob/main/Extensions/shuffle%2B.js

<img width="376" alt="Screenshot 2025-07-10 at 14 59 24" src="https://github.com/user-attachments/assets/7429ff16-363e-4a41-b06d-2dadf1e31c86" />

10. SleepTimer: stop playing after the amount of time/track you set (@Theblockbuster1)
https://github.com/Theblockbuster1/spicetify-extensions/tree/main/SleepTimer

11. songstats: show statistics of the track (@rxri)
https://github.com/rxri/spicetify-extensions/tree/main/songstats

<img width="417" alt="Screenshot 2025-07-10 at 15 03 18" src="https://github.com/user-attachments/assets/6ce5d048-ae00-46a4-b1d0-aecb95641db3" />


12. SpicyTracker: copy a clean link without tracking parameters (@yodaluca23)
https://github.com/yodaluca23/spicetify-extensions/tree/main/SpicyTracker

13. better-spotify-genres: show genres of a track in the playback bar (@Vexcited)
https://github.com/Vexcited/better-spotify-genres?tab=readme-ov-file

14. trashbin-plus: stop playing songs or artists that you don't like automatically/automix mode based on original trashbin extension (@0-don)
https://github.com/0-don/trashbin-plus

15. vinylcover: add a little vinyl that rotate when playing (@AkselVdev)
https://github.com/AkselVdev/AkselV-Spicetify

<img width="386" alt="Screenshot 2025-07-10 at 15 10 01" src="https://github.com/user-attachments/assets/90330b2d-0717-4486-bffb-233708497a2d" />

16. volume-plus: use scroll wheels to adjust volume and show percentage when hover the volume bar (@Aspecky)
https://github.com/Aspecky/spicetify-extensions/tree/main/volume-plus

17. scannables: view a spotify codes url (@ohitstom)
https://github.com/ohitstom/spicetify-extensions/tree/main/scannables

  * Install it via Marketplace, otherwise it won't work *

<img width="327" alt="Screenshot 2025-07-10 at 15 14 42" src="https://github.com/user-attachments/assets/00697150-4776-4ee4-b8a7-6a825c50642b" />

18. beautiful-fullscreen: a minimal alternate option to default full screen with customization and lyrics-plus support (@Oein)
https://github.com/Oein/beautifulfullscreen

  * Personally I don't use lyrics-like so you can give it a try *

--- Snippets/CSS ---
* Requires Spicetify Marketplace *

1. Declutch right sidebar: Hide unnecessary stuff like Merch, Tours, etc. Keep the author and credits only (@silver-wizard)
  .main-nowPlayingView-artistOnTour {
  display: none;
  }

.main-nowPlayingView-merch {
  display: none;
  }

.main-nowPlayingView-queue {
  display: none;
  }

2. Rounded Images: add rounded corners to the cover art
3. Fix 'Episodes' icon: turn the episodes into monochrome icon
4. Fix 'Liked' icon: turn liked songs into monochrome icon
5. Smooth Reveal Playlist Gradient: fade-in effect when reveals the playlist gradient header
6. Oneko: adds a slepping cat (oneko) into the playback bar
7. Remove Popular sections from homepage: remove lots of clutter stuff like Popular radio/albums/new releases, etc.
8. Hide recent searches: to hide search history from search bar.
9. Smooth Progress/Volume Bar: enable the glide animation on playback/volume bar when changing.
10. Hide Friend Activity Button: I don't have friend, this hides from the top right corner.
11. Hide Mini Player Button: I don't use it much, so I hide it anyway.
12. Hide 'Scroll through previews': hide the previews icon of track.

--- Themes ---

Personally, I love the default looks of Spotify so I'm not gonna change it.
But the default UI is missing rounded corners in the playing bar (Snippets doesn't work for me).
This is what I did...

Step 1:
<img width="697" alt="Screenshot 2025-07-10 at 15 34 36" src="https://github.com/user-attachments/assets/37755a59-613a-49ef-a42a-b8ccb9c1ba40" />

Step 2:
Install a theme called "Colorful" (@sanoojes)
  * I installed it via Marketplace, but you can you CLI as well *

And there you have it. This keeps the original look (personal taste) and have a rounded corners at the playing bar as well.

<img width="1551" alt="Screenshot 2025-07-10 at 15 41 11" src="https://github.com/user-attachments/assets/1ee6693c-f7c9-41af-8d76-fbe4678614c5" />
<img width="1551" alt="Screenshot 2025-07-10 at 15 42 59" src="https://github.com/user-attachments/assets/368462b9-d879-40ee-9afb-5a8c32548f03" />

Enjoy your setup!
