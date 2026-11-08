<p align="center">
  <a href="../../releases/latest">
    <img src="./assets/readme-banner.png" alt="userfy: Spotify, but for the music you own" width="100%">
  </a>
</p>

<div align="center">

# userfy

</div>

<div align="center">

  userfy is Spotify for the music you already own. Point it at your folders and get home shelves, daily mixes, synced lyrics, radio and Wrapped, with no ads, no account and nothing online you didn't turn on.<br>
  Runs on Windows, Mac, Linux, iPhone, Android and your TV, and your phone stays in sync with your PC.<br><br>
  <a href="https://userfy.top"><b>userfy.top</b></a> &nbsp;·&nbsp; <a href="https://discord.gg/gtZ3WenvcJ"><b>Discord</b></a>

</div>

## Screenshots

<p align="center">
  <img src="./Screenshots/home.png" alt="userfy - Home" width="100%">
</p>

userfy comes with five themes (userfy, Brutal, Aqua Y2K, Terminal and Frutiger Aero), each in light, dark and OLED, with five color schemes:

<p align="center">
  <img src="./Screenshots/theme-userfy.png" alt="The userfy theme, dark, caramel" width="32%">
  <img src="./Screenshots/theme-brutal.png" alt="The Brutal theme, light, pink" width="32%">
  <img src="./Screenshots/theme-aqua.png" alt="The Aqua Y2K theme, light, blue" width="32%">
</p>
<p align="center">
  <img src="./Screenshots/theme-terminal.png" alt="The Terminal theme, dark, green" width="32%">
  <img src="./Screenshots/theme-aero.png" alt="The Frutiger Aero theme, light, blue" width="32%">
  <img src="./Screenshots/theme-oled.png" alt="The userfy theme, OLED, crimson" width="32%">
</p>

| | |
|:---:|:---:|
| ![Made For You](./Screenshots/made-for-you.png) | ![Stats](./Screenshots/stats.png) |
| Made For You and your top mixes | Listening stats |
| ![Artist page](./Screenshots/artist.png) | ![Album page](./Screenshots/album.png) |
| Artist page | Album page |
| ![Playlist](./Screenshots/playlist.png) | ![Liked Songs](./Screenshots/liked-songs.png) |
| Playlist | Liked Songs with genre filters |
| ![Search](./Screenshots/search.png) | ![Tidal album](./Screenshots/tidal.png) |
| Search across your library and Tidal | A Tidal album, ready to download |
| ![Full-screen lyrics](./Screenshots/lyrics.png) | ![AI DJ](./Screenshots/ai-dj.png) |
| Full-screen synced lyrics | The AI DJ |

New in 2.0.0: friends, Jam, Connect, books and comics, and podcast transcripts:

| | |
|:---:|:---:|
| ![Friends](./Screenshots/friends.png) | ![Jam](./Screenshots/jam.png) |
| Friends, with a friend code and no sign-up | Jam: listen together, one shared queue |
| ![Connect](./Screenshots/connect.png) | ![Books](./Screenshots/books.png) |
| Connect: move playback to your phone, a TV or a speaker | Books, comics and manga |
| ![Get books](./Screenshots/get-books.png) | ![Podcast transcript](./Screenshots/podcast.png) |
| Free books from public-domain sources | Podcasts with ad skipping and read-along transcripts |

Keep it on top of everything else with the mini player:

<p align="center">
  <img src="./Screenshots/mini-player.png" alt="The userfy mini player" width="400">
</p>

Every December 24th, userfy wraps up your year in music, moving in time to your top song:

<p align="center">
  <video src="https://github.com/user-attachments/assets/37073b27-16aa-4c35-8b22-b30084351131" width="640" controls></video>
</p>

## Download

Grab the latest version for your device from the [Releases page](../../releases/latest).

| Platform | Formats |
|----------|---------|
| Windows 10 / 11 (64-bit) | `.exe` installer (per user, no admin) |
| macOS 10.15 or later (Intel and Apple silicon) | `.dmg` |
| Linux, 64-bit PC or ARM64 (Raspberry Pi 4/5) | AppImage, `.deb` or `.rpm` |
| iPhone, iOS 16 or later | installed from the PC or Mac app (Settings > About > Install on your phone), or the `.ipa` |
| Android 10 or later | `.apk`, or installed from the PC or Mac app |
| Android TV (64-bit) | the same `.apk`: it shows up in the TV's app row |

userfy updates itself after that. This repository is the download page and issue tracker; the app itself is closed source.

## Features

- Plays the music already on your drives: MP3, FLAC, WAV, Ogg, Opus and M4A (AAC and ALAC)
- Home shelves, Daily Mixes, a daylist, Discover Weekly, Release Radar and top mixes, all worked out on your PC
- Song and artist radio, autoplay and smart shuffle
- Synced lyrics from `.lrc` files or tags, in the side rail and full screen
- Artist pages, album pages, credits and a now playing rail
- Playlists, folders, smart playlists, drag and drop, undo and Recently deleted
- Wrapped every December 24th, and listening stats all year
- Import Spotify playlists by link, or your whole Spotify data export
- Optional Tidal sign-in to stream, like and download what you don't own as tagged FLAC
- Podcasts, audiobooks and audio CDs (play, rip and burn)
- Gapless playback, crossfade, volume leveling, a 10-band EQ and a sleep timer
- An optional AI DJ and AI playlists that run entirely on your PC
- Mini player, media keys, global hotkeys and a command palette (`Ctrl+K`)
- Phone apps for iPhone and Android that play your PC's library over home Wi-Fi, download songs to keep, and stay in sync
- Friends, Friend activity, Blend and Jam (listen together), with no sign-up
- Connect: move playback between your PC, phone, TVs and speakers (DLNA, Google Cast, AirPlay)
- Books, comics and manga readers, read aloud, and free public-domain books
- Podcast ad skipping and read-along transcripts, made on your PC
- An Android TV app, driven with the remote: Home, Search, Your Library and a big Now Playing with synced lyrics
- Discord: show what you're playing as your Discord activity (even from your phone), invite friends to a Jam from Discord, see which Discord friends use userfy and add them in one tap, and send them songs and playlists
- Auto-updates

## Privacy

Your library, plays, likes and playlists live in a database on your PC. No ads, no analytics, no sign-up. userfy only goes online for things you turn on: Tidal, a Spotify import, podcasts, online book sources, Discord presence, the one-time AI model download and the update check. Friends, Blends, Jams, Friend activity, Connect and syncing your phone or other PCs go through userfy's own small relay server. It passes along only what those features need (your Profile name and picture, what you're playing if Friend activity is on, the Jam queue, and with Discord presence on, the cover of the song you're playing, deleted a day after it was last shown), and the sync data it keeps for your devices is encrypted. A linked phone plays your PC's songs straight over your home Wi-Fi.

## Bugs

Open an [issue](../../issues/new/choose) with what you were doing, what happened, and your version (**Settings → About**). A screenshot helps.

## Credits

Built on [Tauri 2](https://tauri.app), [React](https://react.dev), [SQLite](https://sqlite.org), [Lofty](https://github.com/Serial-ATA/lofty-rs), [Symphonia](https://github.com/pdeljanov/Symphonia), [llama.cpp](https://github.com/ggml-org/llama.cpp), [Qwen3](https://huggingface.co/Qwen), [Piper](https://github.com/rhasspy/piper) and [Inter](https://rsms.me/inter/). Much of the code was written with AI assistance (Anthropic's Claude), directed, reviewed and tested by me. The in-app AI runs entirely on your PC.

userfy ships no music and is not affiliated with Spotify, Tidal or any of the projects above. © 2026 JURMR.
