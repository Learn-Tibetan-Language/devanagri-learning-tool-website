# Sound Assets

This directory contains MP3 audio files for Devanagari characters organized by speaker.

## Structure

```
sounds/
├── speaker1/
│   ├── अ.mp3 (or a.mp3)
│   ├── आ.mp3 (or aa.mp3)
│   └── ...
├── speaker2/
│   ├── अ.mp3 (or a.mp3)
│   ├── आ.mp3 (or aa.mp3)
│   └── ...
```

## File Naming

Audio files can be named using either:
- Devanagari Unicode characters (e.g., `अ.mp3`)
- IAST romanization (e.g., `a.mp3`)

The app will automatically search for files using both naming conventions.