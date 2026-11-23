# Quran Data (JSON)

This repository hosts static JSON files containing Quranic metadata and audio segment timings  
for multiple reciters.

## 📂 Repository Structure

The data is organized by reciter name. Each reciter folder contains Surah metadata  
and audio segment timestamps.

~~~text
Recitation-data/
├── yasser_dossary/
│   ├── surah.json      # Surah metadata
│   └── segments.json   # Audio segment timestamps
├── saad_ghamdi/
│   ├── surah.json
│   └── segments.json
└── ...
~~~

## 📚 Data Source

The Quranic data and audio segment timings in this repository are sourced from:

- **QUL (Quranic Universal Library)** by **Tarteel.ai**  
  🔗 https://qul.tarteel.ai/resources/recitation
- **MP3Quran.net** (`abdullah_ali_jaber`, `nasser_al_qatami`, `maher_muaiqly`, `saud_shuraim`)  
  🔗 https://www.mp3quran.net
- **Quran Foundation (Quran.com API v4)** (`saud_shuraim` fallback timings for Surahs 9, 12, 65, 91)  
  🔗 https://quran.com

## ⚖️ License & Attribution

### Code & Repository Structure

The repository structure, documentation, and any helper scripts (if added) are licensed under  
the **MIT License**.

### Data License

The Quranic JSON data files (`surah.json`, `segments.json`) are **not original content**.  
They are sourced from **QUL (Tarteel.ai)**, **MP3Quran.net**, and **Quran Foundation (Quran.com)**.

> Data sourced from QUL (Quranic Universal Library) by Tarteel.ai, MP3Quran.net and Quran Foundation (Quran.com).
