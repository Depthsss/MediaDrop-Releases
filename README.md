# MediaDrop

**MediaDrop** is a small, local desktop downloader built by **Depthsss**.

It lets you paste a video link, analyze available formats, choose a quality, and download media from supported platforms with a clean desktop interface.

MediaDrop is built with **Tauri**, **Rust**, and **Vanilla JavaScript**. It runs locally on your computer and uses bundled runtime tools such as `yt-dlp`, `FFmpeg`, `FFprobe`, `aria2c`, and `Deno`.

---

## Supported Platforms

MediaDrop currently supports:

- YouTube
- YouTube MP3 / audio extraction
- Instagram
- X / Twitter
- TikTok

---

## Features

- Paste and analyze video links
- Select video quality before downloading
- Automatic best-quality audio download for MP3
- Download pause, resume, and cancel controls
- Automatic cleanup of incomplete files after cancellation
- Custom download folder selection
- Download history
- Show downloaded files directly in Windows Explorer
- Detect renamed downloaded files when possible
- Automatically remove missing/deleted files from history
- Platform badges for YouTube, Instagram, X, and TikTok
- Improved error reports for debugging
- Clickable error report access from the app UI
- Automatic `yt-dlp` update checks
- Bundled runtime tools; no separate Python, FFmpeg, or yt-dlp installation required

---

## Downloads

The latest Windows installer is available from the GitHub Releases page:

**MediaDrop Releases:**  
https://github.com/Depthsss/MediaDrop-Releases/releases

Download the latest `.msi` installer and run it.

---

## How It Works

1. Paste a video link.
2. Click **Analyze**.
3. Choose the quality or format.
4. Click **Download**.
5. Use **Pause**, **Resume**, or **Cancel** if needed.
6. After completion, use **Show in Folder** to locate the downloaded file.

Downloads are saved to:

```txt
%USERPROFILE%\Downloads\MediaDrop
````

You can also choose a custom download folder inside the app.

---

## Error Reports

When MediaDrop encounters an error, it automatically creates a detailed error report.

Reports are saved here:

```txt
%LOCALAPPDATA%\MediaDrop\Hata Raporlari
```

Error reports include useful debugging information such as:

* MediaDrop version
* Build mode
* Windows version
* System architecture
* Operation type
* Platform
* Format and quality
* Tool versions
* Runtime tool paths
* Storage status
* Proxy environment status
* Raw error details

Personal user paths are masked where possible, for example:

```txt
%LOCALAPPDATA%\MediaDrop\bin\yt-dlp.exe
```

If something breaks, send the latest `.txt` report from the error report folder.

---

## Runtime Tools

MediaDrop uses the following tools internally:

* `yt-dlp`
* `FFmpeg`
* `FFprobe`
* `aria2c`
* `Deno`

These tools are bundled with the installer and copied to:

```txt
%LOCALAPPDATA%\MediaDrop\bin
```

Users do not need to install them manually.

---

## Notes

Some platforms may occasionally change their video delivery systems. If a download stops working, it is usually related to platform changes or an outdated extractor.

MediaDrop checks for `yt-dlp` updates automatically to reduce these issues.

Network restrictions, antivirus web shields, VPNs, school networks, dormitory networks, or ISP-level filtering may still affect downloads, especially on YouTube.

---

## Privacy

MediaDrop is a local desktop tool.

It does not require an account and does not intentionally collect user data. Downloads, history, runtime tools, and error reports are stored locally on the user's device.

---

## Tech Stack

* Tauri
* Rust
* Vanilla JavaScript
* HTML / CSS
* yt-dlp
* FFmpeg
* aria2c
* Deno

---

## Developer

Created by **Depthsss**.

GitHub:
[https://github.com/Depthsss](https://github.com/Depthsss)
