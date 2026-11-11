# Hikaru no Go: Insei Choujou Kessen / ヒカルの碁 院生頂上決戦 — English translation

This is an unfinished English fan translation of the Japanese **PlayStation** game. It’s a separate project from my [Hikaru no Go 3 translation](https://github.com/KodakWizard/hikaru-no-go-3-english) for GameCube.

I’m saving this checkpoint so the work doesn’t depend on one person or one computer. If someone wants to carry it on, the handover explains how to find the dialogue, edit the English, check that it fits, and build a fresh test copy.

## How much is translated?

| Part of the game | English in v20 | Coverage |
|---|---:|---:|
| Main story archive | 3,941 / 3,986 | **98.9%** |
| Basic tutorials | 1,001 / 1,001 | **100%** |
| Applied lessons | 510 / 539 | **94.6%** |
| Morishita study group | 303 / 1,548 | **19.6%** |
| Live-match scripts | 1,239 / 10,493 | **11.8%** |
| **All identified script entries** | **6,994 / 17,567** | **39.8%** |

The **story handover table is 100% bilingual**: all 3,986 exported rows have English. Its last 45 entries are in the table only. They haven’t been added to v20, and some full speaker names won’t fit without more work on the game’s text layout.

These percentages count script entries, not how long the game takes to play or how many screens are finished. v20 also includes English menus, match prompts and save/load screens. The ending credits, some graphics and text outside the script archives still need work, so there’s no reliable percentage for the whole game yet.

## Pick up the work

Start with `HANDOVER.md` inside the private handover archive. If you’re translating, open `localization/untranslated-text.csv` and fill in the English column. The table shows the byte and line limits where we know them. If you’re reviewing the story, use `localization/story-text-complete.csv`; it has Japanese and English side by side, with the source scene and an inferred speaker where available.

The build tools work with your own matching Japanese disc image. They check the text before putting it into a new build and refuse to cut a line down to fit. The tools reproduced v20 byte for byte in a clean workspace. That checks the build process; it doesn’t mean every scene has been tested in an emulator.

## AI assistance

I worked on this with ChatGPT, which helped translate text, build the tools and troubleshoot the game files. There are still places where a person familiar with the game can help, especially by checking speakers, short text boxes and routes we haven’t tested.

This is an unofficial fan project. The original game and its assets belong to their respective rights holders. No game disc image is included.
