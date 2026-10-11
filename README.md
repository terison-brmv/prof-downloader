<div align="center">

English · [Русский](README.ru.md)

# Prof Downloader

**Paste a link. Get the video, photo, sound or cover.**
No accounts, no watermarks, no servers in between.

A free, native Mac app for saving content from YouTube, Instagram, TikTok and Threads.
Everything runs on your own Mac.

![macOS 13+](https://img.shields.io/badge/macOS-13%2B-black)
![Apple silicon](https://img.shields.io/badge/Apple%20silicon-native-black)
![Free](https://img.shields.io/badge/price-free-7FFF00)
![Languages](https://img.shields.io/badge/UI-EN%20%C2%B7%20RU%20%C2%B7%20UZ-black)

<h1 align="center"><a href="https://github.com/terison-brmv/prof-downloader/releases/latest/download/ProfDownloader.zip">⬇ Download</a></h1>

<p align="center"><sub>Free · macOS 13+ · Apple silicon · <a href="../../releases/latest">all versions</a> · <a href="../../issues">Questions and ideas</a></sub></p>

> **Reporting a problem or an idea?** Please use the [issue templates](../../issues/new/choose) and write in English or Russian. Reports without the link, app version and macOS version are hard to reproduce.

<p align="center">
  <img src="docs/screens/01-start.png" width="49%" alt="Start screen" title="Start screen">
  <img src="docs/screens/02-options.png" width="49%" alt="Quality and format" title="Quality and format">
</p>
<p align="center">
  <img src="docs/screens/04-fragment.png" width="49%" alt="Download a clip" title="Download a clip">
  <img src="docs/screens/05-carousel.png" width="49%" alt="Instagram carousel" title="Instagram carousel">
</p>
<p align="center">
  <img src="docs/screens/06-history.png" width="49%" alt="History" title="History">
  <img src="docs/screens/08-palettes.png" width="49%" alt="Palettes" title="Palettes">
</p>

</div>

---

## What it does

Paste a link and the app recognises what it is, shows a preview and offers the right options: video in the quality you pick, audio only, a cover image, or photos from a carousel. Then it saves the file to the folder you choose.

| Platform | What you can save |
|---|---|
| **YouTube** | Videos and Shorts up to 4K, audio only, cover images, clips by time range |
| **Instagram** | Reels, posts, photo and video carousels, profile photos |
| **TikTok** | Videos, photo carousels with their music, the sound alone |
| **Threads** | The main post of a thread (video, photos) |

## Highlights

- **Honest size estimates.** Every quality shows the approximate file size before you download.
- **Download only a clip.** Set start and end times with a draggable range or exact timecodes, with ±1 second steps.
- **Pick the exact photos.** In a carousel, tick the frames you want, or grab photos, video and audio in one click.
- **Smart conversion.** If a service gives a codec that QuickTime or video editors handle badly, the app offers to convert it.
- **History.** Search, filter by type or platform, show the file in Finder, or repeat a download in one click.
- **Gentle on services.** Built-in pauses and rest periods help avoid rate limits, and clear messages explain what to do if a service blocks your network.
- **Always up to date.** The download engine and the app itself can update automatically (you can turn this off in Settings).
- **Private by design.** No account, no login, no analytics. Your links and files never leave your Mac.

## Make it yours

Eleven hand-made palettes, each with a light and a dark version, plus a **Custom** palette where you choose the colours, fonts, corners and effects.

The **Glass classic** palette uses Apple's real **Liquid Glass**, which is supported on **macOS 26 and later**. The rest of the app works on macOS 13 and newer.

The interface speaks **English, Russian and Uzbek**, and you can switch the language at any time.

## Install

1. Open the [latest release](../../releases/latest) and download `ProfDownloader-x.y.z.zip`.
2. Unzip it and drag **Prof Downloader** to your Applications folder.
3. The first time, macOS says it cannot verify the app (it is not from the App Store). Open **System Settings → Privacy & Security**, scroll down, click **Open Anyway** next to Prof Downloader and confirm. You only need to do this once. (On macOS 15 and later, right-click → Open no longer skips this warning.)

**Requirements:** a Mac with Apple silicon and macOS 13 or newer (tested on macOS 26).

## How it works

Under the hood the app drives two open-source tools, **yt-dlp** (finds and fetches the media) and **FFmpeg** (merges, cuts and converts), wrapped in a native SwiftUI interface. Everything runs locally.

## Good to know

Save only what you have the right to save, and respect the terms of each service and the work of creators. Some content (private accounts, age-restricted or removed posts) cannot be downloaded without signing in, and the app does not use your accounts.

## Feedback

Found a bug or have an idea? Open an [issue](../../issues). A short description with a link and a screenshot helps the most.

## Privacy

No accounts, no analytics, no tracking. Read the short [privacy note](PRIVACY.md).

## Author and license

Made by **terison_brmv**. Free to use, all rights reserved: see [LICENSE](LICENSE). Bundled open-source components: [third-party notices](THIRD-PARTY-NOTICES.md). Modifying, reselling or redistributing the app without the author's permission is not allowed.
