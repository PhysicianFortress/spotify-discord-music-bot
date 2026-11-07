# 🎵 Spotify Discord Music Bot

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=5,20,14&height=210&section=header&text=Spotify%20Discord%20Music%20Bot&fontSize=46&fontColor=ffffff&animation=fadeIn&fontAlignY=36&desc=Stream%20Spotify%20Music%20Right%20Into%20Discord&descAlignY=56&descSize=18" width="100%"/>

<br/>

[![Version](https://img.shields.io/badge/version-3.1.0-1DB954?style=for-the-badge&logo=spotify&logoColor=white)](https://github.com)
[![Node](https://img.shields.io/badge/Node.js-20+-191414?style=for-the-badge&logo=nodedotjs&logoColor=white)](https://nodejs.org)
[![License](https://img.shields.io/badge/license-MIT-1ED760?style=for-the-badge&logo=opensourceinitiative&logoColor=black)](LICENSE)
[![Queues](https://img.shields.io/badge/queue-unlimited-14833B?style=for-the-badge&logo=youtubemusic&logoColor=white)](https://discord.com)

<br/>

### 🎧 A modern Discord bot that plays music from Spotify & YouTube in your voice channels

*🎶 Playlists • 📻 Queue • 🔁 Loop • 🔊 Volume • 🎨 Rich Embeds*

<br/>

<a href="https://share.google/KuGkyX7WMLjWEXyvj">
  <img src="https://img.shields.io/badge/🤖_INVITE_BOT-1DB954?style=for-the-badge&logo=discord&logoColor=white&labelColor=169A43" alt="Invite Bot" height="45"/>
</a>
&nbsp;&nbsp;
<a href="https://share.google/KuGkyX7WMLjWEXyvj">
  <img src="https://img.shields.io/badge/📥_GET_SOURCE-191414?style=for-the-badge&logo=github&logoColor=white&labelColor=0A0A0A" alt="Get Source" height="45"/>
</a>
&nbsp;&nbsp;
<a href="https://share.google/KuGkyX7WMLjWEXyvj">
  <img src="https://img.shields.io/badge/📚_DOCS-1ED760?style=for-the-badge&logo=readthedocs&logoColor=black&labelColor=17A848" alt="Docs" height="45"/>
</a>

</div>

<img width="1280" height="720" alt="maxresdefault - 2026-11-07T160526 172" src="https://github.com/user-attachments/assets/24868cd1-1023-447c-a615-0343ad64483b" />


<br/>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🌟 About

**Spotify Discord Music Bot** brings seamless music playback to your Discord server. Paste a Spotify track, album, or playlist link — the bot resolves it, queues every song, and streams the audio directly into your voice channel with high-quality playback.

Built with **discord.js** and modern audio libraries, it delivers a polished music experience your community will love.

> 💡 **Perfect for:** Gaming communities, study servers, friend groups, and any Discord space that wants shared music.

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🎯 Key Features

<div align="center">

| 🎶 **Spotify Playlists** | 📻 **Smart Queue** | 🔁 **Loop & Shuffle** |
|:---:|:---:|:---:|
| Paste any Spotify<br/>track, album or playlist | Add, remove, reorder<br/>& skip tracks | Repeat track, queue<br/>or shuffle anytime |

| 🔊 **Volume Control** | 🎨 **Rich Embeds** | ⚡ **Fast & Stable** |
|:---:|:---:|:---:|
| Per-server volume<br/>with limits | Album art, progress<br/>& now-playing cards | Auto-reconnect &<br/>queue persistence |

</div>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🏆 Why This Bot

<div align="center">

| 💎 **Advantage** | 📝 **Description** |
|:---|:---|
| 🎧 **Spotify + YouTube** | Works with both Spotify links and YouTube fallback for reliable streaming |
| ⚡ **Low Latency** | Optimized audio pipeline — playback starts in under 2 seconds |
| 🎨 **Beautiful UI** | Rich embeds with album art, progress bars, and clean controls |
| 🛡️ **Stable** | Auto-reconnects after network hiccups and preserves the queue |
| 🔧 **Self-Hostable** | Full source available — run it on your own server, no third-party dependencies |
| 🌍 **Multi-Server** | Handles hundreds of guilds with independent queues and settings |

</div>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🎬 Bot in Action

<div align="center">

```ascii
╔══════════════════════════════════════════════════╗
║  🎵  Spotify Discord Music Bot  v3.1.0           ║
╠══════════════════════════════════════════════════╣
║                                                  ║
║  /play spotify:playlist:37i9dQZF1DXcBWIGoYBM5M  ║
║                                                  ║
║  ✅ Added 50 tracks from "Today's Top Hits"      ║
║                                                  ║
║  🎶 Now Playing                                  ║
║  ┌────────────────────────────────────────────┐  ║
║  │ 🎵 "Espresso" — Sabrina Carpenter          │  ║
║  │ 🖼️ [Album Art]                              │  ║
║  │ ▬▬▬▬▬▬▬▬▬▬▬░░░░░░  1:42 / 2:55             │  ║
║  │ 🔊 Volume: 70%  🔁 Loop: Off  📻 Queue: 49  │  ║
║  └────────────────────────────────────────────┘  ║
║                                                  ║
║  Commands: /play /skip /pause /queue /loop       ║
╚══════════════════════════════════════════════════╝
```

</div>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🧩 Project Structure

```
🎵 spotify-discord-music-bot/
├── 🎯 src/
│   ├── commands/              # Slash commands
│   │   ├── play.js
│   │   ├── skip.js
│   │   └── queue.js
│   ├── music/                 # Audio engine
│   │   ├── player.js
│   │   └── resolver.js        # Spotify → audio URL
│   ├── events/                # Discord event handlers
│   └── utils/                 # Helpers & embeds
├── ⚙️  config/                 # Environment & settings
├── 🧪 tests/                  # Unit & integration tests
└── 📖 docs/                   # Setup & command reference
```

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🛠️ Tech Stack

<div align="center">

![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![discord.js](https://img.shields.io/badge/discord.js-5865F2?style=for-the-badge&logo=discord&logoColor=white)
![Spotify](https://img.shields.io/badge/Spotify_API-1DB954?style=for-the-badge&logo=spotify&logoColor=white)
![FFmpeg](https://img.shields.io/badge/FFmpeg-007808?style=for-the-badge&logo=ffmpeg&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)

</div>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🤝 Community

Found a bug? Want a new command or support for another music source?

<div align="center">

<a href="https://share.google/KuGkyX7WMLjWEXyvj">
  <img src="https://img.shields.io/badge/💬_Join_Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" height="35"/>
</a>
<a href="https://share.google/KuGkyX7WMLjWEXyvj">
  <img src="https://img.shields.io/badge/🐞_Report_Issue-1DB954?style=for-the-badge&logo=github&logoColor=white" height="35"/>
</a>
<a href="https://share.google/KuGkyX7WMLjWEXyvj">
  <img src="https://img.shields.io/badge/⭐_Star_Repo-1ED760?style=for-the-badge&logo=github&logoColor=black" height="35"/>
</a>

</div>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 📜 License

Distributed under the **MIT License**. See [`LICENSE`](LICENSE) for details.


<br/>

<div align="center">

### 🎵 Made with 🎧 by the Spotify Discord Team

*If this bot made your server more musical — star the repo!*

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=5,20,14&height=120&section=footer" width="100%"/>

</div>
