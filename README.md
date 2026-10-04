<p align="center">
  <img src="screenshots/icon.png" width="96" alt="Niappu Companion">
</p>

<h1 align="center">Niappu Companion</h1>

<p align="center">
  <b>Read Japanese games, videos and websites with a dictionary on top.</b><br>
  Click any word for its meaning, reading and pitch accent, and send it to Anki with the sentence, a screenshot and the character's own voice.
</p>

<p align="center">
  <a href="https://github.com/Zavodskyja/Niappu-Companion-releases/releases/latest"><b>Download for Windows</b></a>
  ·
  <a href="#getting-started">Getting started</a>
  ·
  <a href="#features">Features</a>
</p>

![Niappu Companion over a game: the text is outlined and a clicked word shows its dictionary entry](<img width="2559" height="1439" alt="image" src="https://github.com/user-attachments/assets/63e2d380-730d-4b7d-bb2e-33e06b8a9d63" />
)

You're playing a game in Japanese and hit a word you don't know. Press `Alt+Q`, click the word, and its meaning appears right on top of the game. Save it, and it lands in Anki with the sentence it came from. Keep playing.

Niappu Companion works with any game that shows text on screen, and with Netflix, YouTube and websites through its browser extension. It runs on your PC, uses your own Yomitan dictionaries, and never touches the game itself.

## Features

### Look up anything on screen
Press `Alt+Q` and everything on screen becomes clickable. Hover or click a word for its readings, meanings, pitch accent, frequency and audio. Conjugated forms are understood (食べさせられなかった → 食べる), and words split across two lines are still found.

![The scan overlay with a dictionary popup](<img width="2501" height="1347" alt="image" src="https://github.com/user-attachments/assets/d68fed5e-b170-41b2-9cfb-117f9ea3650a"/>
)

### Always-on overlay *(experimental)*
Boxes stay on the text while you play, and your clicks go through to the game. Press the hotkey whenever you want to look something up. Boxes disappear as soon as the text changes or the camera moves. To keep the screen calm, it can read only your dialogue box instead of every sign in the scene.

![The always-on overlay during gameplay](<img width="2559" height="1372" alt="image" src="https://github.com/user-attachments/assets/5da9a1aa-6980-4d74-967f-aee71fd28c80" />
)

### Mine to Anki in one click
**＋ Anki** creates a card with the word, reading, meaning, the sentence (with the word in bold), a screenshot, word audio and pitch accent. Use the ready-made note type, or map the fields to your own.

**Sentence audio:** the card can include the line the character actually spoke, cut from what your speakers played. If a line has no voice, a generated one is used instead.

![A card in Anki made from a game sentence](<img width="1120" height="775" alt="image" src="https://github.com/user-attachments/assets/b2cfbd42-ac48-440b-8a74-e8e567ef1633" />
)

### See what you already know
Words are underlined as **new**, **learning** or **known**, using your Anki cards, WaniKani and Bunpro. Words you know stay clean, so the ones worth learning stand out.

![Status underlines in a dialogue box](<img width="937" height="364" alt="image" src="https://github.com/user-attachments/assets/31f1292a-d56e-4e8e-a169-24b6946532d5" />
)

### Regions for dialogue boxes
Draw a box around the dialogue window once. Niappu Companion watches it and sends every new line to the text page on its own. It can even notice where the dialogue is and offer to make the region for you. Region presets switch automatically with the game in front.

![Drawing a region around a dialogue box](<img width="897" height="825" alt="image" src="https://github.com/user-attachments/assets/084dd37a-30b9-4761-baf8-5a213cd7e5fa" />
)

### The text page
Open `http://127.0.0.1:7707` in any browser (a second monitor, a tablet) to follow the text live, look words up, translate sentences and scroll back through what you read. The **Stats** tab shows your reading time, lines and characters per game, and how many of the words you already know.

![The text page with history and reading stats](<img width="2515" height="850" alt="image" src="https://github.com/user-attachments/assets/15bf91c6-98c5-4a28-86ca-931f64188cd5" />
)
![Statistics page](<img width="1263" height="962" alt="image" src="https://github.com/user-attachments/assets/b1c7c509-da01-4e75-90d8-011cd2d0e7ff" />
)

### Netflix, YouTube and the web
The browser extension (Chrome, Edge) brings the same popup to websites: hold `Shift` over a word. On Netflix and YouTube it underlines subtitle words by status, pauses the video while you read, shows the full subtitle list beside the video, and puts the actor's own voice on your cards.

![Netflix with the subtitle list and a lookup](<img width="2546" height="1219" alt="image" src="https://github.com/user-attachments/assets/98bb9ed7-3eda-432b-acd7-1a6dec3ca9c2" />
)

### Your dictionaries, your words
Use any Yomitan dictionary: terms, names, kanji, frequency lists and pitch accent. The setup guide downloads openly licensed ones for you (Jitendex, JMnedict, Jiten frequency, Kanjium pitch). Saved words keep their sentence, picture and audio, export to Anki or CSV, and are backed up daily.

![The saved words page](<img width="906" height="810" alt="image" src="https://github.com/user-attachments/assets/28b71f6d-1dd2-4aef-a2cd-111ec0413464" />
)

## Safe for online games

Niappu Companion only looks at screen pixels, the same way a screenshot or a screen recorder does. It never reads or changes game memory, never injects anything into a game and never hooks the keyboard, so anti-cheat has nothing to detect.

## Private by default

Everything runs on your PC. OCR, dictionaries, saved words and Anki stay local. Data leaves your PC only for features you turn on: translation (Google or DeepL), word audio (JapanesePod101), and WaniKani and Bunpro sync. API keys are stored encrypted for your Windows account.

## Getting started

1. Download the installer from the [latest release](https://github.com/Zavodskyja/Niappu-Companion-releases/releases/latest) and run it. Windows may warn that the installer isn't signed: click **More info → Run anyway**.
2. The setup guide downloads dictionaries and sets up the OCR engine.
3. Start a game in **borderless windowed** mode and press `Alt+Q`.

Requires Windows 10 or 11. Updates install from inside the app.
