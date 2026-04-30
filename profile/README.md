<div align="center">

<!-- Replace with a proper banner image — game key art, logo, or custom banner -->


<br/>

# YYDS EN Fanslation Project

### A community retranslation of *Yunyun Syndrome!? Rhythm Psychosis*

[![Discord](https://img.shields.io/badge/Discord-Join%20the%20server-5865F2?style=flat-square&logo=discord&logoColor=white)](https://discord.gg/jYjTd5qpKv)
[![Releases](https://img.shields.io/github/v/release/YYDS-EN-Fanslation/yunyun-syndrome-mod?style=flat-square&label=Latest%20release&color=3a3a3a)](https://github.com/YYDS-EN-Fanslation/yunyun-syndrome-mod/releases)
[![Status](https://img.shields.io/badge/Status-Active-2d8a4e?style=flat-square)]()

</div>

---

*Yunyun Syndrome!? Rhythm Psychosis* is a game built specifically for people who grew up on niconico, denpa music, and early 2010s otaku internet culture. The writing is dense with that world — the humor, the speech patterns, the in-jokes, the specific flavor of anonymous comment culture that defined an era.

The official English localization doesn't know that world exists. Dry niconico-style comments get rewritten as aggressive anglophone slang. Character-specific speech patterns are stripped. Terms that have meaning — *nuko*, *denpa*, *doujin goro* — get replaced with generic equivalents or dropped entirely. Lines that are supposed to land as deadpan get punched up into something louder. The result is a translation that's readable but wrong, aimed at an audience that isn't playing this game.

This project retranslates it for the people who are actually playing it.

---

## Install

> If you just want to play — this is the only section you need.

**Requirements:** [MelonLoader](https://github.com/LavaGang/MelonLoader.Installer/releases) installed on Yunyun Syndrome.

1. Go to [Releases](https://github.com/YYDS-EN-Fanslation/yunyun-syndrome-mod/releases) and download the latest `YunyunLocalePatcher.zip`
2. Extract and copy the contents into your game folder, merging with the existing `Mods\` and `UserData\` directories
3. Launch the game

Translations apply automatically at runtime. No game files are modified.

---

## What's translated

| Area | Status |
|---|---|
| UI, menus, dialog boxes | Complete |
| Rhythm score data & results | Complete |
| Conspiracy theory posts (in-game social media) | Complete |
| Social feed posts (PostFukidashi) | Complete |
| Wiki / lore entries | Complete |
| Main story dialogue | In progress |
| Conspiracy theory voiced scenes | In progress |
| Side events & endings | In progress |

---

## Repositories

**[yunyun-syndrome-translation](https://github.com/YYDS-EN-Fanslation/yunyun-syndrome-translation)**
The translation files — CSV patches containing all translated text. Start here to contribute.

**[yunyun-syndrome-mod](https://github.com/YYDS-EN-Fanslation/yunyun-syndrome-mod)**
MelonLoader mod that applies CSV patches at runtime without touching game files. This is what end users install.

**[yunyun-syndrome-patch](https://github.com/YYDS-EN-Fanslation/yunyun-syndrome-patch)**
Python offline patcher that writes translations directly into the game's asset bundles. Handles string tables, `.lang` dialogue files, and `catalog.bin` CRC correction.

**[yunyun-syndrome-debugmenu](https://github.com/YYDS-EN-Fanslation/yunyun-syndrome-debugmenu)**
In-game editor for translators — live string editing with immediate feedback, `.lang` patching, scene jumping, and JSON export. A development tool, not needed to play.

---

## Contributing

**To dump all translatable strings from the game:**

Add `--localepatcher.dumpstrings` to the game's Steam launch options and launch once. This writes `00-base.csv` to `UserData\LocalePatches\` with every string in the game. Import it into the [community spreadsheet](https://docs.google.com/spreadsheets/d/1nKseRzV7VLbYQeV79oiWpTRxfSj_n8xqap94Bf6t2I4/) to start translating. Remove the flag when done — it disables patching while active.

**To submit:**

Fork [yunyun-syndrome-translation](https://github.com/YYDS-EN-Fanslation/yunyun-syndrome-translation), edit the CSV files (`TableName`, `Key`, `Text`), and open a pull request. Come talk to us on Discord first if you're not sure where to start — Japanese knowledge helps but isn't required.

---

## Discord

**[discord.gg/jYjTd5qpKv](https://discord.gg/jYjTd5qpKv)**

---

## Legal

Fan translation, distributed freely. All game content belongs to AllianceArts. We distribute only replacement text written by contributors, no game files.

Please [buy the game on Steam](https://store.steampowered.com/app/2914150/Yunyun_Syndrome_Rhythm_Psychosis/) and support the developers.

---

<div align="center">
<sub>Rim de Lacent.</sub>
</div>
