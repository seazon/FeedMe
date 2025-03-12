FeedMe now supports TTS and podcast, you can read articles with your ear.

- For podcast feed, FeedMe supports manual download for offline reading.
- For normal feed, FeedMe compliances with the standard Android TTS specification, you can read with your favorite TTS engine, such as Google TTS or Ivona.

FeedMe integrates these two different forms, and you can listen all items like listening to music.

FeedMe provides play section into the playlist in the left navigation bar. To simplify the logic, FeedMe has only one playlist.

<img src="https://github.com/seazon/FeedMe/blob/main/doc/en/imgs/tts_2.png" width="25%" height="25%" />

There is a new layout in article list: podcast. This layout contains a progress button, you can play a item or download the audio file if it is a podcast item.

<img src="https://github.com/seazon/FeedMe/blob/main/doc/en/imgs/tts_8.png" width="25%" height="25%" /> <img src="https://github.com/seazon/FeedMe/blob/main/doc/en/imgs/tts_9.png" width="25%" height="25%" />

# Play control
There are 4 play menus in article list long-tap dialog:
- `Single play` (add to top of playlist, mark with `Stop tag`, and play this item)
- `Play` (add to playlist and play, if playing now, stop the playing item)
- `Next play` (add after the playing item)
- `Add to playlist` (add to last of playlist)

`Stop tag`: When played a item with `Stop tag`, stop play and clear it.

<img src="https://github.com/seazon/FeedMe/blob/main/doc/en/imgs/tts_1.png" width="25%" height="25%" />

# Playlist
- The played item will be automatically removed from playlist, including podcast audio files. So no need to remove item by yourself.
- FeedMe can remember the play position automatically.
- You can remove item via swipe from right to left.
- Now FeedMe does not support podcast online playing.
- Playlist only supports order playback, no single loop, loop, random play.
- You can reorder playlist via long-tap and drag.
- It skips the played items when play the playlist.

When an item is playing, a notification adds in notification bar. And you can enter playing page via tap it.

<img src="https://github.com/seazon/FeedMe/blob/main/doc/en/imgs/tts_6.png" width="25%" height="25%" />

# Playing page
There are 3 pages in playing page. You can find a cross icon in playlist page, that is `Stop tag`.

<img style="float: left;" src="https://github.com/seazon/FeedMe/blob/main/doc/en/imgs/tts_3.png" width="25%" height="25%" /> <img style="float: left;" src="https://github.com/seazon/FeedMe/blob/main/doc/en/imgs/tts_4.png" width="25%" height="25%" /> <img style="float: left;" src="https://github.com/seazon/FeedMe/blob/main/doc/en/imgs/tts_5.png" width="25%" height="25%" />

# TTS setting
There is an `Audio` tab in `Settings`, you can goto TTS setting page from here.

<img src="https://github.com/seazon/FeedMe/blob/main/doc/en/imgs/tts_7.png" width="25%" height="25%" />

# Tips
### Play feed view or web view
##### Q: Sometimes feed does not provide full text, and when we switch to web view and play, it still play the feed view text. How can I play the web view text?
A: You can read <a href="https://github.com/seazon/FeedMe/blob/main/doc/en/mobilizer.md#default-view">this section</a> to know how it works.