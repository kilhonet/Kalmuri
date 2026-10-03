# Kalmuri

**A free Windows capture tool that grabs the full screen, a region, a window or an entire web page with one hotkey, and records the screen to MP4.**

English · [한국어](README.ko.md) · [简体中文](README.zh-CN.md) · [日本語](README.ja.md) · [Español](README.es.md) · [Português (Brasil)](README.pt-BR.md) · [Français](README.fr.md)

> This document is a translation. If anything differs, the [Korean version](README.ko.md) is authoritative.

![Platform](https://img.shields.io/badge/platform-Windows%2010%20%2F%2011-0078D4)
![License](https://img.shields.io/badge/license-Freeware-brightgreen)
[![Download](https://img.shields.io/badge/download-kilho.net-orange)](https://down.kilho.net/kalmuri?lang=en)

![Kalmuri window](images/kalmuri-en.webp)

## Overview

With Kalmuri you choose just two things — what to capture (**Capture**) and how to keep it (**SaveTo**) — and from then on a single press of `PrintScreen` does the rest. There's no window to open and no file name to type each time; results pile up in the save folder as `K-001.png`, `K-002.png` and so on.

You can capture the full screen, a fixed region, an area you drag with the mouse, the window you're using, a single button inside a window, or an entire scrolling web page. The same hotkey also records the screen to MP4, picks color codes from the screen and turns text in images into a text file.

Closing the window leaves Kalmuri running in the notification area (system tray), so once it's on you can capture with the hotkey at any time.

## Features

- **7 capture modes** — Full screen, a fixed region, a dragged area, the active window, a window control, an entire web page, and color picking.
- **Many output types** — PNG · JPG · GIF · BMP · WebP files, MP4 video, text recognition (TXT), clipboard, image sharing, printer, and on-screen floating images.
- **Screen recording** — Record the full screen or a region to MP4, with the sound playing on your PC if you like.
- **Full web page capture** — Save a page opened in Edge · Chrome as one image, all the way to the bottom of the scroll.
- **Text recognition (OCR)** — Save the text on the captured screen as a text file.
- **Color picker** — Copy the color under the cursor as HEX · RGB · Web · TColor.
- **Share captures** — Upload a capture to the web and open it right away to share the link.
- **Floating** — Keep a captured image on top of other windows, right where it was captured, for reference.
- **Keyboard region adjustment** — Fine-tune the region down to the pixel with the arrow keys · `Ctrl`+arrow · `Shift`+arrow.
- **Handy settings** — Custom hotkey, file name format (numbering · date and time), capture sound, include mouse cursor, run on system start.
- **8 languages** — Korean · English · Japanese · Chinese · Russian · Italian · French · Spanish.

## Download / Installation

| Type | Link |
|---|---|
| Installer | [Download](https://down.kilho.net/kalmuri?lang=en) |
| Portable (ZIP) | [Download](https://down.kilho.net/kalmuri?lang=en&nosetup) |

The installer launches Kalmuri as soon as setup finishes and turns on **Run on system start**, so Kalmuri starts in the tray every time Windows starts. For the portable version, unzip it and run `Kalmuri.exe`.

The portable version contains only the executable, so **MP4 recording and WebP saving are available in the installed version only**. Everything else is the same in both.

## Usage

### Getting started

1. Run Kalmuri. A small window appears, and the Kalmuri icon shows up in the notification area.
2. Under **Capture**, choose what to capture. The default is **Full Screen**.
3. Under **SaveTo**, choose how to keep it. The default is **PNG**. Choosing JPG · WebP shows a quality box next to it; choosing TXT shows a recognition-language box.
4. Press `PrintScreen`. With a shutter sound, the capture is saved to the save folder (the desktop at first) as `K-001.png`.
5. Click **Open Folder** to open the save folder and check the result.
6. Closing the window keeps Kalmuri running in the tray. Click the tray icon to bring the window back, and **right-click** the window or the tray icon for the settings menu.

### Screen layout

**Main window**

| Element | What it does |
|---|---|
| **Capture** | Choose what to capture (table below) |
| **SaveTo** | Choose how to keep the capture (table below). JPG · WebP show a quality box (100 – 60), TXT shows a recognition-language box |
| **Open Folder** | Opens the save folder in Explorer |
| **Crafted by Kilho** | Opens the Kalmuri product page |

**Capture**

| Item | What it captures |
|---|---|
| **Full Screen** | The whole screen |
| **Region** | The inside of a red frame window — for capturing the same place and size every time |
| **Drag** | The part you drag with the mouse after pressing the hotkey |
| **Active Window** | The one window you are using |
| **Window Control** | The window or element (button, panel…) under the mouse cursor |
| **WebBrowser** | The entire web page you're viewing in Edge · Chrome, down to the end of the scroll |
| **Color Picker** | The color code under the mouse cursor |

**SaveTo**

| Item | Result |
|---|---|
| **PNG** · **JPG** · **GIF** · **BMP** · **WebP** | An image file in that format |
| **MP4** | Screen recording (Full Screen · Region only) |
| **TXT** | Recognizes the text on the captured screen and saves it as a text file |
| **Clipboard** | Copies to the clipboard only, no file |
| **Upload Imgbox** | Uploads to the web and opens the image page in your browser |
| **Printer** | Prints right away |
| **Floating** | Keeps the image on top, right where it was captured |

**Right-click menu** (main window or tray icon)

| Item | What it does |
|---|---|
| **Open Folder** · **Folder setting** | Open or change the save folder |
| **Capture Settings** | **Capture Sound** (None · Before capture · After capture) · **Mouse cursor** · **With Clipboard** |
| **Recoder setting** | **Limit recording time** (Unlimited · 30 minutes · 1 hour · 2 hours · 4 hours) · **Mouse cursor** · **Include sound** |
| **Language** | Display language |
| **Filename setting** | **Auto increment number #1** · **Auto increment number #2** · **DateTime** |
| **Hotkey setting** | Change the capture hotkey |
| **Run on system start** | Start automatically in the tray when Windows starts |
| **Crafted by Kilho** · **Quit** | Product page · exit the program |

### When you want to…

**Capture the whole screen at once**
Leave **Capture** at **Full Screen** and press `PrintScreen`. You don't need to open the window — as long as Kalmuri is in the tray, it captures from anywhere.

**Capture the same place and size every time**
Choose **Region** and a red, blinking frame window appears. Drag the frame to move it, drag its edges to resize it, then press `PrintScreen` to capture only what's **inside** the frame. The current size (e.g. `480x360`) is shown at the top of the frame, and the frame's position and size are remembered for next time. Clicking the X at the top right closes the frame and switches back to **Full Screen**.

**Fit the region to the exact pixel**
Click the region frame and use the keyboard. The arrow keys **move** it by 1 pixel, while `Ctrl`+arrow resizes it by 10 pixels and `Shift`+arrow **resizes** it by 1 pixel. Rough it out with the mouse, then finish with the keyboard.

**Save sizes you use often**
Right-click the region frame for a list of sizes such as `320x240` · `640x480` · `720x480` to switch in one click. Change the sizes in the list under **Setting** by entering the width and height of **Custom #1 – #3**. Enter numbers under **Current state** and click **Apply** to set the current region to that size. **Hide** in the same menu just hides the frame for now.

**Pick just the part you want with the mouse**
Choose **Drag** and press `PrintScreen`: the screen freezes and dims. Drag over the part to capture and release to save just that part. Press `Esc` to cancel. Because it captures the frozen moment, you can even grab an open menu or a notification that only appears briefly.

**Capture only the window you're using**
Choose **Active Window**, click the window to bring it to the front, and press `PrintScreen`. The desktop and other windows are left out; only that window is saved.

**Capture a single button or panel inside a window**
Choose **Window Control** and a dotted frame follows the element under the mouse cursor. Hover over the button, input box or panel you want and press `PrintScreen` to save only the element inside the frame — handy for cutting out one part for a manual or a support request.

**Save a long web page as a single image**
Choose **WebBrowser** and Kalmuri opens a separate Edge window (Chrome if Edge isn't there). Open the page you want in that window and press `PrintScreen`: the whole page, including the part you'd have to scroll down to see, is saved as one image. With several tabs open, the tab you're looking at is captured. Closing that browser window switches back to **Full Screen**. Requires Windows 8 or later with Edge or Chrome installed.

**Find the color code of something on screen**
Choose **Color Picker** and the window shows the color and code under the mouse cursor in real time. Put the cursor where you want and press `PrintScreen`: that color is added to the top of the list and copied to the clipboard. Right-click the list and use **Format** to choose the copy format — **HEX** (`FF9933`) · **RGB** (`255, 153, 51`) · **Web** (`#FF9933`) · **TColor** (`$003399FF`) — and use **Copy** · **Delete** in the same menu to manage entries.

**Record the screen as a video**
Set **SaveTo** to **MP4** and press `PrintScreen` to start recording; the window shows **Recording** and the elapsed time. Press `PrintScreen` again to stop and save the MP4 file. Recording works with **Full Screen** and **Region**; while recording a region, `[REC]` and the time appear on the frame and the region is locked in place.

**Record the sound from your PC too**
Turn on **Recoder setting → Include sound** to record the sound playing on your PC (videos, games, notifications) along with the video. Turn it on when recording a lecture or video playback.

**Leave a recording running while you're away**
Set **Recoder setting → Limit recording time** to **30 minutes** · **1 hour** · **2 hours** · **4 hours**, and recording stops by itself once that time has passed — no more filling the disk because you forgot to stop it.

**Keep the mouse cursor out of recordings**
Turn off **Recoder setting → Mouse cursor** to hide the cursor in videos. It's separate from **Capture Settings → Mouse cursor** for captures, so you can leave the cursor out of screenshots but keep it in recordings, or vice versa.

**Turn text in an image into text**
Set **SaveTo** to **TXT** and a recognition-language box appears next to it. Choose the language of the text and capture: the text on screen is read and saved as a text file (`K-001.txt`). Great for text in images or documents that can't be copied. Combine it with **Drag** to recognize just the paragraph you need. The language list shows the text recognition languages installed in Windows.

**Paste a capture somewhere right away**
Set **SaveTo** to **Clipboard** to copy the capture to the clipboard only, without creating a file, so you can paste it into a chat or document with `Ctrl`+`V`. To keep a file and paste too, turn on **Capture Settings → With Clipboard**: whatever format you save in, the capture is also copied to the clipboard.

**Share a capture as a link**
Set **SaveTo** to **Upload Imgbox** and capture: the image is uploaded to the web and its image page opens in your browser. Copy the address and send it to share the capture without attaching a file.

**Print as soon as you capture**
Set **SaveTo** to **Printer** and the capture is printed on the default printer right away.

**Keep a captured image on screen for reference**
Set **SaveTo** to **Floating** and capture: an image of the same size stays on top of other windows, right where you captured it. Drag it to move it — handy for copying values or comparing two screens. Right-click the image and use **Save Image** to save it as PNG · JPG · GIF · BMP · WebP, or **Delete Floating** · **Delete All Floating** to close it.

**Make files smaller**
Set **SaveTo** to **JPG** or **WebP** and pick 100 · 90 · 80 · 70 · 60 in the quality box next to it (default 90). The smaller the number, the smaller the file. PNG suits screens with lots of text; JPG · WebP suit screens with lots of photos.

**Change the file naming rule**
Choose under **Filename setting**.
- **Auto increment number #1** (default) — continues from the highest number in the save folder (`K-001`, `K-002` …).
- **Auto increment number #2** — fills from the lowest unused number. If you deleted a file in the middle, its number is used again.
- **DateTime** — names files by capture time (`K-20260928-153012345`). Good for sorting captures from several days in time order.

Whatever the rule, if a file with the same name exists, it isn't overwritten; the capture is saved under a new name.

**Change the save folder**
Choose a folder with **Folder setting**. The default is the desktop. **Open Folder** in the menu (or **Open Folder** in the window) opens that folder at any time.

**Change the hotkey**
In **Hotkey setting**, check `Ctrl` · `Alt` · `Shift`, pick a key and click **OK**. You can pick `PrintScreen`, `A` – `Z`, `0` – `9`, `F1` – `F12` or `DEL`. If another program already uses that combination, you'll be told, so choose a different one.

**When `PrintScreen` opens the Windows Snipping Tool**
Windows 11 has a setting that makes `PrintScreen` open the Snipping Tool. Kalmuri turns this setting off when it starts, so `PrintScreen` works with Kalmuri.

**Change the capture sound**
Under **Capture Settings → Capture Sound**, choose **None** · **Before capture** (default) · **After capture**. **None** suits quiet places; **After capture** tells you by sound that saving has finished.

**Include or leave out the mouse cursor**
With **Capture Settings → Mouse cursor** on (default), the cursor appears in captures. Keep it on for screenshots that point at a button; turn it off for a clean screen.

**Have it ready whenever Windows starts**
With **Run on system start** on, Kalmuri starts in the tray without a window when Windows starts, ready for the hotkey. It's on from the start in the installed version.

**Keep using it after closing the window, or quit for good**
The window's X doesn't quit Kalmuri — it hides it in the tray. To quit completely, click **Quit** in the right-click menu and confirm. If a recording is running, stop it first, then quit.

**Change the display language**
Pick 한국어 · English · 日本語 · 中文 · Русский · Italiano · Français · Español under **Language** and it changes immediately.

### Copyright notice

Screens you capture or record with Kalmuri may contain other people's text, images, videos or music. Sharing or posting them beyond personal storage and reference may require permission from the rights holder, so please follow each service's terms of use and copyright law.

## Configuration

Every setting is saved as soon as you change it and used again at the next launch.

| Item | Default |
|---|---|
| Capture | Full Screen |
| SaveTo | PNG |
| JPG · WebP quality | 90 |
| Save folder | Desktop |
| Filename setting | Auto increment number #1 |
| Hotkey | `PrintScreen` |
| Capture Sound | Before capture |
| Mouse cursor (capture · recording) | On |
| With Clipboard | Off |
| Limit recording time | Unlimited |
| Include sound | Off |
| Run on system start | On in the installed version |
| Language | Follows the Windows region setting (English if the language isn't supported) |

## Requirements

- Windows 10 · Windows 11
- **WebBrowser** capture needs Microsoft Edge or Google Chrome.
- **TXT** (text recognition) uses the text recognition languages installed in Windows.
- The internet connection is used only for new-version notices, **Upload Imgbox** and **WebBrowser** capture.

## Updates

Kalmuri does **not** update itself. At startup it checks for a new version and shows a notice; clicking **[Yes]** opens the download page and closes the program. New versions are released manually after internal testing and announced on the [Kalmuri page](https://kilho.net/kalmuri). See the [update policy notice](https://en.kilho.net/archives/notice/2940).

## License

Kalmuri is **freeware**. Use it for free without restriction anywhere — at work, at home, in government offices or at school — and redistribute it freely.

## Links

- Website: <https://kilho.net/kalmuri>
- Forum: <https://kilho.top/forum/qna>
- X (Twitter): <https://www.twitter.com/kilhonet>

© KILHO.NET
