# FlashVerses

**The right verse on your screen, as the preacher says it.**

FlashVerses listens to your service and shows the Bible verse being read, quoted or even paraphrased, ready for one tap to put on the projector. No typing, no hunting through a Bible app while the pastor waits.

### [⬇ Download the latest version](https://github.com/autosueno/flashverses-releases/releases/latest)

Windows 10 or later, and Mac with Apple silicon. Free to download; you bring your own speech and AI keys (see [what it costs](#what-it-costs)).

---

## What it does

- **Finds the verse for you.** It catches spoken references ("turn to Romans chapter eight, verse twenty-eight"), verses read word for word, and paraphrases, even when the transcript mishears a name like Nehemiah.
- **You stay in control.** Each detection appears as a card. Press **Take** (Space) to send it to the screen, **Esc** to black it out instantly. Nothing goes live on its own.
- **Shows it well.** Lower-third or full-screen layouts, text that auto-sizes so long verses fit and short ones stay large, and your own fonts, colours and backgrounds.
- **Works with your gear.** A second-screen projector window, a browser feed for OBS and vMix, and **NDI** video for vision mixers, with a transparent background that keys over camera.
- **Catches the sermon points too.** It picks out teaching points, applications, quotes and numbered points as they are preached, and can show them on screen.
- **Writes the notes afterwards.** Get a suggested title, notes under headings with each scripture beside its point, key quotable lines and a summary. Email them to your congregation or save them as a text file.
- **Posts to social media, when you say so.** Queue verses and points as X posts and Instagram carousels. Nothing posts until you press Post.
- **Keeps going if the internet drops.** Listening switches to the computer itself and switches back when the connection returns.

## Bible versions

| | Versions |
|---|---|
| **Built in, works offline** | KJV, ASV, WEB, plus 13 African-language Bibles including Yoruba, Igbo, Hausa and Swahili |
| **Downloadable in the app** | More African-language Bibles |
| **Online, one verse at a time** | NIV, NLT, NASB, AMP, MSG and others (needs a free key from the provider; see Settings) |

Switch versions mid-service and the screen changes instantly.

---

## Install

### Windows

1. Download **FlashVerses-Setup.exe** from the [latest release](https://github.com/autosueno/flashverses-releases/releases/latest).
2. Run it and click Install. It takes about a minute and does not need an administrator.
3. If Windows shows "Windows protected your PC", choose **More info → Run anyway**.

### Mac (Apple silicon)

1. Download **FlashVerses-mac.dmg** and drag FlashVerses into Applications.
2. The first time, **right-click the app and choose Open**, then Open again.
3. Allow microphone access when asked.

### First-time setup (about five minutes)

1. Open FlashVerses and go to **Settings → API Keys**.
2. Paste a **Deepgram** key (live transcription) and an **OpenAI** key (verse detection). Both have free sign-ups; links are in the Settings screen.
3. Choose your microphone or mixer input on the dashboard.

Your keys and settings stay on your computer and survive updates.

---

## On Sunday

1. Press **Start** on the dashboard and check the level meter moves.
2. Drag the projector window to your second screen.
3. As the preacher speaks, verse cards appear. Click one to preview it.
4. Press **Take** (Space) to put it on screen. Press **Esc** to clear the screen.
5. Turn on **Sermon** to capture points and notes. When you finish, open the summary, rename it, and email or save it.

---

## What it costs

FlashVerses uses two pay-as-you-go services that you sign up for yourself, so you only pay for the time you use.

- **OpenAI:** roughly **$0.50 to $0.80 per two-hour service** for verse detection and notes.
- **Deepgram:** billed per minute of audio listened to; new accounts include free credit. See Deepgram's pricing page for current rates.

Offline listening (when the internet drops) costs nothing.

## What leaves your computer

- **Audio** is streamed to Deepgram while you listen online. With offline listening, audio stays on the computer.
- **Licensed Bible versions** fetch one verse at a time from their provider.
- Social posts go out only when you press Post. Your keys and tokens are stored in your user profile folder on your own computer.

---

## Questions

**Windows warns me about an unknown publisher.** FlashVerses is not yet code-signed, so Windows shows this for new installers. Choose More info, then Run anyway.

**No verses are appearing.** Check the level meter moves (right input chosen?), that both keys are saved in Settings, and that the internet is up. Detections need clear speech; try speaking a reference like "John 3:16".

**It showed the wrong verse.** Detections are suggestions, which is why nothing goes live without you pressing Take. Ignore the card and carry on.

**How do I update?** Download the newest installer and run it. Your settings, keys and saved sermons are kept.

**Where is the log if something breaks?** Windows: `%APPDATA%\FlashVerses\logs\flashverses.log`. Mac: `~/Library/Application Support/FlashVerses/logs/flashverses.log`. Attach it when you report a problem.

**Does it work on an older Mac or Intel Mac?** Not yet; the Mac version needs Apple silicon.

## Feedback

Found a bug or want a feature? [Open an issue](https://github.com/autosueno/flashverses-releases/issues). Please include your version (shown in Settings and the dashboard footer) and, for a bug, the log file.

---

<sub>NDI® is a registered trademark of Vizrt NDI AB. Bible texts remain the property of their respective publishers and are used under their licences or as public-domain works.</sub>
