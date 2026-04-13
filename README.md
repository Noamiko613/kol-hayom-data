# Kol Hayom Data - Complete Jewish Text Library

## Overview
This repository contains a comprehensive collection of classical Jewish texts in clean, readable format. All texts have been processed from Torat Emet format to provide multiple versions with different vocalization and cantillation options.

## Directory Structure

### 📚 Tanach (תנ״ך)
```
Tanach/
├── Torah/ (תורה)
│   ├── 01_BERESHIT/
│   ├── 02_SHEMOT/
│   ├── 03_VAIKRA/
│   ├── 04_BAMIDBAR/
│   └── 05_DEVARIM/
├── Neviim/ (נביאים)
│   ├── 06_YEHOSUA/ through 26_MALACHI/
└── Ketuvim/ (כתובים)
    ├── 27_TEHILIM/ through 39_DIVRE_B/
```

Each book contains:
- **with_nikud_with_teamim/** - Full vocalization with cantillation marks (teamim)
- **with_nikud_without_teamim/** - Vocalized text without cantillation
- **without_nikud_without_teamim/** - Plain text (no nikud, no teamim)
- **mefarshim/** - Classical commentaries

### 📖 Mishna (משנה)
```
Mishna/
├── 100_SEDER_ZRAIM/
├── 101_SEDER_MOED/
├── 102_SEDER_NASHIM/
├── 103_SEDER_NEZIKIN/
├── 104_SEDER_KADASHIM/
└── 105_SEDER_TAHAROT/
```

Each seder contains masechtot (tractates), each with:
- **with_nikud/** - Mishna text with vocalization
- **mefarshim/** - Commentaries (Bartenura, Rambam, etc.)

### 📚 Gemara Bavli (גמרא)
```
Gemara_Bavli/
├── 01_MAS_BRACHOT/ through 39_MAS_NIDA/
```

Each masechet contains:
- **with_nikud/** - Gemara text with vocalization
- **mefarshim/** - Rashi, Tosafot, and other commentaries

### 📜 Rambam - Mishneh Torah (רמב״ם)
```
Rambam/
├── with_nikud/ - Main text with vocalization
└── mefarshim/ - Commentaries (Kesef Mishneh, Lechem Mishneh, Raavad, etc.)
```

### ⚖️ Tur & Shulchan Aruch (טור ושולחן ערוך)
```
Tur_Shulchan_Aruch/
├── with_nikud/ - Vocalized versions
├── without_nikud/ - Plain text versions
└── mefarshim/ - Commentaries and glosses
```

## File Naming Conventions

### Tanach Files
- `a##__Name.txt` - Text with nikud AND teamim (double underscore)
- `a##_Name.txt` - Text with nikud only (no teamim)
- `b##_Name.txt` - Plain text, no nikud, no teamim
- Commentary files are organized in the `mefarshim/` folder

### Commentary Files Include:
- **Rashi** (רש״י)
- **Ramban** (רמב״ן)
- **Ibn Ezra** (אבן עזרא)
- **Or HaChaim** (אור החיים)
- **Sforno** (ספורנו)
- **Baal HaTurim** (בעל הטורים)
- **Kli Yakar** (כלי יקר)
- **Rabenu Bechayei** (רבנו בחיי)
- **Targum Onkelos** (תרגום אונקלוס)
- **Targum Yonatan** (תרגום יונתן)
- **Midrash Raba** (מדרש רבה)
- **Siftei Chachamim** (שפתי חכמים)
- And many more...

## Text Processing

All files have been cleaned for readability:
- ✅ HTML-like tags removed (bold, italic, etc.) - text remains
- ✅ Torat Emet markup cleaned and formatted
- ✅ UTF-8 encoding for universal compatibility
- ✅ Nikud (vowel points) preserved in vocalized versions
- ✅ Teamim (cantillation marks) preserved where applicable
- ✅ Structured with clear chapter and verse markers

## Usage

### Reading
Simply open any `.txt` file in a text editor or reader that supports UTF-8 and Hebrew text. For best results, use:
- A font with full Hebrew support (e.g., Ezra SIL, SBL Hebrew, David)
- RTL text support
- Unicode support for nikud and teamim

### Study
The multiple versions allow for:
1. **Full traditional text** - with_nikud_with_teamim
2. **Vocalized text** - with_nikud_without_teamim (easier to read)
3. **Plain text** - without_nikud_without_teamim (for advanced readers)
4. **Commentaries** - mefarshim folder (classical commentators)

## Sources
- Original texts from Torat Emet software
- Organized and cleaned for universal readability
- All processing done locally

## Maintaining
This repository is maintained to provide clean, accurate Jewish texts for study and reference.

## Notes
- Prayer texts (tfillot) are preserved separately and not affected by this update
- All texts are provided for study and educational purposes
- File structure follows traditional Jewish text organization

## License
These texts are provided for personal study and educational use.

---
**Thank you for using Kol Hayom Data!**
For questions or contributions, please open an issue or pull request.
