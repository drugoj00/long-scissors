[English](README.md) · [Українська](README.uk.md) · [Русский](README.ru.md)

🌐 All our programs: https://drugoj00.github.io/

Description and screenshots: https://drugoj00.github.io/phone-in-window-with-sound/long-scissors.html

<img src="screenshots/icon_128.png" alt="" width="96" align="right">

# Long Scissors

Windows screenshots: area, window, screen and a long scrolling page; video and GIF recording; editor, text from a shot, searchable history.

A free Windows program. Captures an area, a window, the whole screen and a long page: the page scrolls down automatically and the frames are stitched without repeats. Records video with sound and GIFs with a size limit. Editor with drawing, steps and blur, “Pretty” for a frame and background, copy text from a shot (OCR), history with text search, joining and converting files. Lives in the tray: a click on the icon starts a capture at once.

⭐ If the program is useful, please star this repository: it costs nothing and helps other people find it.

## Download

**Version 1.0.** [LongScissors-1.0.exe](https://github.com/drugoj00/long-scissors/releases/latest) (Assets) · [Releases](https://github.com/drugoj00/long-scissors/releases)

SHA-256: `153688d37dfc5728e6ebb0f3113bcedf377e05f126a9a2dafd5afddbb7cff41d`

## What's new in 1.0

- First public version: everything listed above.

## Features

### Screenshots

- Area, window, whole screen and a long shot: scrolls down automatically and stitches frames without repeats.
- Timer up to 10 s to open a menu or a list.
- PNG, JPG, WEBP, BMP, PDF, Word, Excel; copy to the clipboard.
- A click on the tray icon starts a capture at once; middle click picks the format; Ctrl+Shift+S opens the panel.

### Video and GIF

- MP4 video with sound: system, microphone or both, device choice.
- GIF with a size and duration limit, width, frame rate and colors picked automatically.
- Scrolling GIF: the page scrolls automatically.

### Editor

- Pen, highlighter, line, arrow, rectangle, ellipse, text, numbers, steps with a caption, blur, crop.
- “Pretty”: window or phone frame, shadow, background.
- Copy text from a shot (Windows OCR); tables go to Word and Excel.

### Files and history

- Shot history with search by the text on the shots.
- Join a long shot from ready images or PDFs.
- Converter: images, PDF, Word, Excel, text; merge files into one PDF.

### Everything else

- Tray icon, autostart without a window, a single running copy.
- Russian, Ukrainian, English; light and dark theme.

## Screenshots

![Panel: what to capture, timer, format, folder](screenshots/en/01_панель_съёмки.png)

![Panel: GIF with automatic settings](screenshots/en/02_панель_GIF.png)

![Editor: arrows, steps, numbers, blur](screenshots/en/03_редактор.png)

![“Pretty”: frame, shadow, background](screenshots/en/04_красиво.png)

![Shot history with text search](screenshots/en/05_история_и_поиск.png)

![Joining a long shot from files](screenshots/en/06_склейка.png)

![File converter and merge into one PDF](screenshots/en/07_конвертер_PDF.png)

![Copy text from a shot](screenshots/en/08_копировать_текст.png)

![Tray icon menu](screenshots/en/09_меню_значка.png)

## Requirements

Windows 10 or 11 (64-bit). Administrator rights are optional. Copying text uses Windows recognition (the Russian language pack must be installed); no internet needed.

## Quick start

1. Download LongScissors-1.0.exe and run it; Windows asks for permission (if declined, the program goes into your user folder).
2. The program lives in the tray by the clock: click the icon to select an area at once; right click for all modes, format, language, theme.
3. Ctrl+Shift+S opens the panel with settings: what to capture, timer, format, folder.
4. The shot opens in the editor: draw, copy, save.

## Limits

- A long shot scrolls the page with the mouse wheel and moves the cursor: better not to use the mouse while it runs.
- Copying text relies on Windows recognition: Ukrainian “і”, “ї”, “є” are sometimes lost.
- System and microphone sound are recorded separately and aligned by the clock; a small shift is possible.
- Tested on Windows 11; screen and sound recording was not tested separately on Windows 10.
- The installer is not signed with a publisher certificate: Windows may show a SmartScreen warning (“More info” → “Run anyway”).
- ffmpeg is inside, LGPL/GPL.
