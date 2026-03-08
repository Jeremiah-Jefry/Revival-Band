# 🎸 Revival Band

> *A version-controlled worship songbook for **Revival Band** — a curated collection of Tamil Christian worship song chord sheets, organized alphabetically and by weekly Sunday setlists.*

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
![Songs](https://img.shields.io/badge/Songs-3-blue)
![Setlists](https://img.shields.io/badge/Sunday%20Sets-1-green)
![Language](https://img.shields.io/badge/Language-Tamil-red)

---

## 📖 About

**Revival Band** is a worship team dedicated to leading praise and worship through Tamil Christian songs. This repository serves as our **digital songbook** — a shared, version-controlled resource where band members can access chord charts, setlists, and musical resources anytime, anywhere.

Each song is written in **Markdown** using a **chord-over-lyrics** format, making it easy to read on any device — whether it's a laptop on the music stand or a phone during rehearsal.

### Why Git for a Songbook?

| Benefit | Description |
|---------|-------------|
| 🔄 **Version History** | Track every change to chords, keys, and arrangements over time |
| 👥 **Collaboration** | Band members can suggest edits, corrections, and new songs via pull requests |
| 📱 **Accessibility** | Access the songbook from any device via GitHub — no app needed |
| 📦 **Organized** | Clean folder structure keeps songs alphabetized and setlists dated |
| 🔍 **Searchable** | Quickly find any song or lyric using GitHub's built-in search |

---

## 📂 Repository Structure

```
Revival-Band/
├── Songs/                          # 🎵 Master song library
│   ├── K/
│   │   └── Kerubin Serabinghal.md  #    Key: Gm | Slow/Worship
│   ├── M/
│   │   └── Magimayin Raja Maghimaiyodu.md  #    Key: F# | Mid-Tempo
│   └── Y/
│       └── Yesu Ennaku Jeevan.md   #    Key: C | Upbeat
├── Sunday Sets/                    # 📅 Weekly setlists organized by date
│   └── 08-03-2026.md              #    Sunday service song set
├── Resources/                      # 📚 Band resources (coming soon)
├── LICENSE                         # MIT License
└── README.md                       # You are here
```

### Directory Breakdown

| Folder | Description | Organization |
|--------|-------------|--------------|
| **`Songs/`** | Master library of individual chord sheets — one `.md` file per song | Alphabetically grouped into subdirectories by first letter (e.g., `K/`, `M/`, `Y/`) |
| **`Sunday Sets/`** | Weekly setlists — each file is a complete chord booklet for a specific Sunday service | Named by date in `DD-MM-YYYY.md` format |
| **`Resources/`** | Planned space for music theory guides, scale charts, gear references, and tutorials | *Currently empty — contributions welcome!* |

---

## 🎵 Song Collection

The songbook currently contains **3 Tamil worship songs** spanning different moods and styles — from slow worship to upbeat praise.

### Song Index

| # | Song (Tamil) | Song (Transliterated) | Key | Tempo | Sections | Link |
|---|-------------|----------------------|-----|-------|----------|------|
| 1 | கேரூபின் சேராபின்கள் | Kerubin Serabinghal | Gm | Slow / Worship | Intro · Verse · Chorus · Stanza | [View](Songs/K/Kerubin%20Serabinghal.md) |
| 2 | இயேசு எனக்கு ஜீவன் | Yesu Ennaku Jeevan | C | Upbeat | Intro · Verse · Pre-Chorus · Chorus · Stanza | [View](Songs/Y/Yesu%20Ennaku%20Jeevan.md) |
| 3 | மகிமையின் ராஜா மகிமையோடு | Magimayin Raja Maghimaiyodu | F# | Mid-Tempo | Intro · Verse · Chorus · Stanza | [View](Songs/M/Magimayin%20Raja%20Maghimaiyodu.md) |

### Chords at a Glance

| Song | Primary Chords |
|------|---------------|
| Kerubin Serabinghal | `Gm` · `D` · `Eb` · `F` · `C` |
| Yesu Ennaku Jeevan | `C` · `F` · `G` · `A` · `Dm` |
| Magimayin Raja Maghimaiyodu | `F#` · `C#` · `B` · `G#m` · `Bbm` |

---

## 📅 Sunday Setlists

Each Sunday setlist is a self-contained document that includes the full chord charts for every song played during that service — like a portable chord booklet.

| Date | Songs | Link |
|------|-------|------|
| **08-03-2026** | Kerubin Serabinghal · Yesu Ennaku Jeevan · Magimayin Raja Maghimaiyodu | [View Setlist](Sunday%20Sets/08-03-2026.md) |

---

## 📝 Chord Sheet Format

All songs follow a consistent **chord-over-lyrics** format using Markdown code blocks, making them easy to read and edit.

### Example

```text
F#                    B
மகிமையின் ராஜா மகிமையோடு
C#                 F#
வருகின்றார் மேகமீதில்
```

- **Chords** appear on the line *above* the lyrics they correspond to
- **Alignment** is maintained using spaces so chords sit directly over the syllable where the chord change occurs
- Each song is wrapped in ` ```text ``` ` blocks for monospace rendering on GitHub

### Song Sections

Every chord sheet is structured with clearly labeled sections (where applicable):

| Section | Description |
|---------|-------------|
| **INTRO** | Instrumental intro — chord progression only, no lyrics |
| **Verse** | Main verse with chords aligned above Tamil lyrics |
| **Pre-Chorus** | Transitional section building into the chorus *(used in some songs)* |
| **Chorus** | The main refrain / hook of the song |
| **Stanza** | Additional verses, bridge material, or alternate stanzas |

### Song Header

Each song file includes a header with essential metadata:

```markdown
# Song Title
**Key:** Gm | **Tempo:** Slow/Worship
```

---

## 🤝 Contributing

Band members and contributors are welcome to help grow the songbook! Here's how:

### ➕ Adding a New Song

1. Create a new `.md` file inside `Songs/<First-Letter>/` (e.g., a song starting with "A" goes in `Songs/A/`)
2. Name the file using the transliterated song title (e.g., `Kerubin Serabinghal.md`)
3. Follow the chord sheet format described above
4. Include the header with: **Song title** (Tamil + transliterated), **Key**, and **Tempo**
5. Add all applicable sections: Intro, Verse, Pre-Chorus, Chorus, Stanza

### 📅 Adding a Sunday Setlist

1. Create a new `.md` file in the `Sunday Sets/` folder
2. Name it using the date format: `DD-MM-YYYY.md`
3. Add a **Table of Contents** at the top with anchor links
4. Include the full chord charts for all songs played that Sunday
5. Each song should have its **Key** and **Tempo** noted in the header

### ✏️ Suggesting Changes

| Change Type | What To Do |
|-------------|------------|
| 🎹 **Key Change** | Update all chords in the song and update the Key in the header |
| ✍️ **Lyric Correction** | Edit the Tamil text directly in the relevant section |
| 🎼 **New Arrangement** | Add or modify sections (e.g., add a Bridge or Pre-Chorus) |
| 🐛 **Formatting Fix** | Ensure chord alignment and section headers are consistent |

### Contribution Workflow

1. **Fork** the repository (or create a branch if you have write access)
2. Make your changes following the conventions above
3. Submit a **Pull Request** with a clear description of what was changed
4. Changes will be reviewed and merged

---

## 🛠️ Tech Stack

This isn't a software project — it's a **content repository**. No build tools, dependencies, or runtime needed.

| Tool | Usage |
|------|-------|
| **Markdown** | Song chord sheets and setlists are written in `.md` format |
| **Git** | Version control for tracking changes and collaboration |
| **GitHub** | Hosting, access, and collaboration platform |

---

## 📊 Repository Stats

| Metric | Value |
|--------|-------|
| **Total Songs** | 3 |
| **Total Setlists** | 1 |
| **Languages** | Tamil (தமிழ்) |
| **Musical Keys Used** | Gm, C, F# |
| **Tempo Range** | Slow/Worship → Upbeat |
| **Maintainer** | [Jeremiah Jefry.G](https://github.com/Jeremiah-Jefry) |
| **License** | MIT |

---

## 📜 License

This project is licensed under the **MIT License** — see the [LICENSE](LICENSE) file for details.

© 2026 Jeremiah Jefry.G

---

<p align="center">
  <i>🙏 சகல மகிமையும் கர்த்தருக்கே — All glory to God 🙏</i>
</p>