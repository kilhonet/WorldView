# WorldView

**A free Windows image viewer for browsing images, archives and PDF documents quickly and comfortably.**

English · [한국어](README.ko.md) · [简体中文](README.zh-CN.md) · [日本語](README.ja.md) · [Español](README.es.md) · [Português (Brasil)](README.pt-BR.md) · [Français](README.fr.md)

> This document is a translation. If anything differs, the [Korean version](README.ko.md) is authoritative.

![Platform](https://img.shields.io/badge/platform-Windows%2010%20%2F%2011%20(64--bit)-0078D4)
![License](https://img.shields.io/badge/license-Freeware-brightgreen)
![Version](https://img.shields.io/badge/version-0.9.3-blue)
[![Download](https://img.shields.io/badge/download-kilho.net-orange)](https://down.kilho.net/worldview?lang=en)

![WorldView window](images/worldview-ko.webp)

## Overview

WorldView lets you flip through folders full of photos, read comic archives two pages at a time without extracting them, and scroll down webtoons as one continuous strip. PDF documents open the same way, one page at a time.

Drop an image on the window and it opens immediately, with the other images in the same folder lined up after it. The screen shows only the picture — the buttons appear only when you move the mouse to the top or bottom of the window.

Images are drawn by the graphics card, so even large photos zoom smoothly, and the pages before and after are read ahead so turning a page rarely makes you wait.

## Features

- **Many image formats** — JPEG, PNG, GIF, WebP, TIFF, BMP, SVG, JPEG XL, HEIC, AVIF, PSD, camera RAW and more.
- **Archives without extracting** — Page through the images inside ZIP, RAR, 7Z, CBZ, CBR, EGG, ALZ and other archives.
- **PDF documents** — Each page is one image; zooming redraws the page at that size so text stays sharp.
- **Four view modes** — One page, two pages (left→right / right→left), first page as cover, and continuous webtoon.
- **Animated images** — Plays GIF, APNG and animated WebP.
- **Auto-rotation and color correction** — Portrait photos open upright, and photos with a color profile show their true colors.
- **Zoom and navigator** — Zoom around the cursor; when a picture overflows, the navigator in the bottom-right corner takes you anywhere in it.
- **Image info and EXIF** — Press `Tab` once to see file details plus capture time, camera, lens and exposure.
- **Handy extras** — File associations, full screen, always on top, recent files, reopen where you left off, delete to the Recycle Bin, custom shortcuts.
- **8 languages** — Korean · English · Japanese · Chinese · Russian · Italian · French · Spanish.

## Download / Installation

| Type | Link |
|---|---|
| Installer | [Download](https://down.kilho.net/worldview?lang=en) |
| Portable (ZIP) | [Download](https://down.kilho.net/worldview?lang=en&nosetup) |

The installer opens WorldView as soon as setup finishes. For the portable version, unzip it and run `WorldView.exe` — keep the `vendor` folder next to the executable. Settings are saved in the program folder, so if you carry the portable version on a USB drive, your settings travel with it.

Neither version sets up file associations on its own. To open images in WorldView by double-clicking them, turn them on in **Preferences → File Types** (see "When you want to…" below).

## Usage

### Getting started

1. Run WorldView and drop an image file, folder, archive or PDF onto the window. You can also pick a file with the folder button on the bottom bar or the `O` key.
2. The image opens fitted to the window, and the other images in the same folder form a list in name order. The title at the top shows where you are, e.g. `Folder > File name [69/308]`.
3. Scroll the mouse wheel or press `←` `→` · `PageUp` `PageDown` to go to the previous or next page. You can also click the arrow buttons that appear when you move the mouse to the left or right side of the window.
4. Move the mouse to the bottom of the window to show the bottom bar. It has zoom, rotate and page buttons plus a seek bar — drag the seek bar to jump straight to any page.
5. Use the **View** button on the right of the bottom bar to choose the zoom (fit to window, original size, width, height) and the view mode (one page, two pages, webtoon). Your choice is remembered for the next page and the next launch.
6. **Right-click** anywhere in the window for Open File, Recent Files, Show in Explorer, Delete File and Preferences.

### Screen layout

**Top bar** (appears when the mouse is near the top of the window)

| Element | What it does |
|---|---|
| App icon | Opens the same menu as right-clicking |
| Title | Folder > file name [current page/total]. `Loading` is added for pages that take a while |
| Pin | Turns **Always on top** on or off |
| Minimize · `[]` · Close | `[]` toggles full screen |

**Bottom bar** (appears when the mouse is near the bottom of the window)

| Button | What it does |
|---|---|
| Folder | Open a file |
| `+` · `−` | Zoom in · zoom out |
| Rotate | Rotate 90 degrees clockwise |
| `‹` · `›` | Previous page · next page |
| Seek bar | Drag or click to go to any page |
| View | The View menu — zoom, two pages, cover, webtoon |
| Gear | Preferences |

**Right-click menu**

| Item | What it does |
|---|---|
| **Open File** · **Open Folder** | Choose a file or folder to open |
| **Recent Files** | The last 5 items you opened |
| **Show in Explorer** | Opens Explorer with the current file selected |
| **View** | The same menu as the View button on the bottom bar |
| **Delete File** | Sends the current file to the Recycle Bin |
| **About WorldView** · **Preferences** · **Quit** | Product page · settings window · exit |

**Preferences** — Changes apply immediately; there is no `OK` button. **Reset** at the bottom left returns every setting to its default and also removes the file associations.

| Page | Items |
|---|---|
| **General** | Quit with the Esc key · Ask before deleting a file · Reopen last file at start · Always on top · Logging · Language |
| **View** | Zoom · View mode · First page as cover · Wide pages alone · Show scrollbars · EXIF in image info · Show the navigator · Show the left/right arrow buttons · At the first/last file |
| **File Types** | Extensions that open in WorldView on double-click |
| **Shortcuts** | Change the key for each action |

### When you want to…

**Flip through the photos in a folder**
Drop or double-click one photo and the images in that folder become a list in name order. Numbers are sorted as numbers, so `photo2.jpg` comes before `photo10.jpg`. Turn pages with the wheel · `←` `→` · `PageUp` `PageDown` · `Space`, and jump to the first and last page with `Home` `End`.

**Read a comic archive without extracting it**
Drop a ZIP · RAR · 7Z · CBZ · CBR archive as it is, and the images inside turn page by page. No extracting and no temporary folder. Folders inside the archive are shown in name order, one after another.

**Read a whole bookshelf folder**
Drop a folder and WorldView scans every subfolder, unfolds the archives and PDFs inside it page by page, and makes one list. You can read from start to finish without opening each volume separately.

**Pick several items and view only those**
Select several files, folders or archives in Explorer and drop them together — only what you selected becomes the list. Neighboring files you didn't pick stay out.

**Read comics two pages at a time**
Choose **View** → **Two Pages (Left to Right)** to show two pages side by side like a book. For Japanese manga, which reads right to left, choose **Two Pages (Right to Left)**. Even with an odd page count, the last page keeps its half of the spread instead of suddenly growing.

**When the cover throws the pairs off**
If page 1 is a cover and every spread looks shifted by one page, turn on **First Page as Cover**. The cover stands alone, and pages then pair up as 2–3, 4–5 and so on.

**Comics with double-page spreads**
Turn on **Wide Pages Alone**: a wide image scanned as two pages is shown alone and large, while the rest keep pairing up two by two.

**Read a webtoon as one continuous strip**
Turn on **View** → **Webtoon (Continuous)** and all pages are joined vertically at the window's width, so you just keep scrolling. Drag the scrollbar on the right to jump anywhere in the whole strip.

**One very tall image**
An image more than three times taller than it is wide opens fitted to the width, **starting at the top**. Scroll down with the wheel · `↑` `↓` · `Space`; reaching the bottom does not jump to the next page, so you never lose your place. Go to the next page with `PageDown` or the arrow button. `Ctrl`+`Home` / `Ctrl`+`End` jump to the very top or bottom of that image.

**Read a PDF page by page**
Drop a PDF and each page turns as one image. You can also spread it like a book with two-page view or scroll through it in webtoon view. When you zoom in or enlarge the window, the page is redrawn at that size so small text stays sharp, and the white background keeps it readable with a dark theme.

**Zoom in to examine a large photo**
`Ctrl`+wheel zooms in and out **around the cursor**. The `+` `-` keys and the bottom buttons work too. Drag the zoomed picture to move it, and use `Shift`+wheel to move sideways. When the picture is larger than the window, the **navigator** appears in the bottom-right corner, marking the part you are looking at with a rectangle — click or drag it to go straight there. Zooming in re-reads the original, so fine detail stays sharp.

**Hide the navigator**
Hover over the navigator and click the X that appears. To bring it back, turn on **Preferences → View → Show the navigator**.

**Change the zoom quickly**
`1` fit to window, `2` original size, `3` fit width, `4` fit height. The zoom you pick carries over to the next page and the next launch — choose it once to always read wide scans fitted to the width, or to always check photos at original size.

**Check a photo's shooting details**
Press `Tab` to show the file name · file size · modified date · image details in the top-left corner. If the photo has EXIF data, the capture time · camera · lens · exposure · focal length · flash · location (GPS) appear too, with only the lines that have values. In two-page view, each page gets its own info on its half. Press `Tab` again to hide it.

**Open iPhone photos (HEIC), camera RAW or Photoshop files**
HEIC · AVIF · JPEG XL, RAW files from Canon · Nikon · Sony · Olympus · Pentax · Panasonic, and Photoshop PSD files open just like any other image when you drop them. Photos open upright in the direction they were taken, and embedded color profiles are applied so they show their true colors.

**Watch animated GIF and WebP**
Open an animated GIF · APNG · WebP in one-page view and it plays. Two-page and webtoon views show the first frame only.

**Tidy up photos while viewing**
Press `Delete` on a photo you don't want; a confirmation appears, and **Yes** sends it to the Recycle Bin. It isn't erased for good — you can restore it from the Recycle Bin. If the confirmation gets in the way, turn off **Preferences → General → Ask before deleting a file**. This works for files in folders only; images inside archives are left untouched.

**Pick up where you left off**
Just run WorldView and the list and page you were viewing last time open again, so an unfinished comic continues from that page. The last 5 items you opened are under right-click → **Recent Files**. If you'd rather start with an empty window, turn off **Reopen last file at start**.

**Enjoy images in full screen**
Press `Enter` or click `[]` in the title bar for a full screen that covers the taskbar too. Press `Esc` or `Enter` to return. In full screen, `Esc` never quits the program — it only leaves full screen.

**Keep it on top as a reference**
Click the pin in the title bar to turn on **Always on top**, so WorldView stays visible while you work in other programs — handy for drawing from a reference or keeping a document beside your work.

**Compare two images side by side**
Run another WorldView and the new window opens slightly offset so it doesn't cover the first one. Place the windows side by side to compare.

**Loop back to the start after the last page**
By default, going past the last page stops and shows `This is the last image`. To keep cycling like a slideshow, set **Preferences → View → At the first/last file** to **Wrap around**.

**Make images open in WorldView on double-click**
In **Preferences → File Types**, check the extensions you want WorldView to open (there is **Select all** too). You can choose JPG · PNG · GIF · WebP · TIFF · BMP · TGA · PSD · JPEG 2000 · DDS · PCX · PDF · CBZ · CBR, and extensions of the same format (`.jpg` `.jpeg` `.jfif`) share one box. If **Not applied** appears next to a box, Windows is giving another program priority — click that label to open the default-app picker for that extension and choose WorldView. Uninstalling WorldView restores the associations.

**Set shortcuts to suit your hands**
In **Preferences → Shortcuts**, click the key box of an action and press the new key. `Ctrl` · `Shift` · `Alt` combinations work. `Backspace` restores the default and `Esc` cancels. A key already used by another action is refused, and you are told which action uses it.

| Action | Default key |
|---|---|
| Fit to window · Original size · Fit width · Fit height | `1` · `2` · `3` · `4` |
| Rotate 90 degrees clockwise | `R` |
| Show/hide image info | `Tab` |
| Toggle full screen | `Enter` |
| Open a file · Open a folder | `O` · `Ctrl`+`O` |

Previous/next page (`PageUp` `PageDown`), first/last page (`Home` `End`), zoom in/out (`+` `-`), Recycle Bin (`Delete`), and the arrow keys · `Space` · `Esc` are fixed.

**Move and resize the window**
Drag an empty area outside the picture, or a picture that is fitted to the window, to move the window; drag an edge to resize it. Dragging with the middle mouse button also moves the window. The window's position and size are remembered, and it opens in the same place next time.

**Find where the current file is**
Right-click → **Show in Explorer** opens Explorer with that file selected — handy for renaming or copying it.

**A cleaner screen**
In **Preferences → View**, turn off **Show scrollbars** and **Show the left/right arrow buttons** to reduce what appears over the picture. You can still move and turn pages the same way with the wheel · arrow keys · dragging.

## Configuration

Changes made in **Preferences**, and the zoom and view mode picked from the View menu, are saved automatically and used again at the next launch.

| Item | Default |
|---|---|
| Zoom | Fit to window |
| View mode | One page |
| First page as cover · Wide pages alone | Off |
| Scrollbars · Navigator · Left/right arrow buttons · EXIF in image info | On |
| At the first/last file | Stop |
| Quit with the Esc key · Ask before deleting a file | On |
| Reopen last file at start | On |
| Always on top · Logging | Off |
| Language | System (follows the Windows region setting; English if the language isn't supported) |

## Requirements

- Windows 10 · Windows 11 (64-bit)
- Everything needed to open images is included — nothing else to install. No administrator rights are needed to run it.
- The internet connection is used only for new-version notices. All images are opened on your PC.

## Updates

WorldView does **not** update itself. At startup it checks for a new version and shows a notice; clicking **[Yes]** opens the download page and closes the program. New versions are released manually after internal testing and announced on the [WorldView page](https://kilho.net/worldview). See the [update policy notice](https://en.kilho.net/archives/notice/2940).

**Version history**

| Version | Date | Changes |
|---|---|---|
| 0.9.3 | 2026-09-24 | Preferences rebuilt on a custom UI engine, more responsive shortcut input and settings, navigator added, EXIF info, zoom and view mode remembered, improved original-size view, multiple windows no longer cover each other, open PDFs directly with WorldView |
| 0.9.2 | 2026-09-18 | View mode and zoom saved automatically, one/two-page/webtoon view and cover settings in Preferences, faster View menu, View added to the right-click menu, wider PDF · TIFF file association support with matching formats grouped |
| 0.9.1 | 2026-09-14 | JFIF image support, improved file and delete dialogs |
| 0.9.0 | 2026-09-12 | First release |

## License

WorldView is **freeware**. Use it for free without restriction anywhere — at work, at home, in government offices or at school — and redistribute it freely.

## Links

- Website: <https://kilho.net/worldview>
- Forum: <https://groups.google.com/g/kilhonet>
- X (Twitter): <https://www.twitter.com/kilhonet>

© KILHO.NET
