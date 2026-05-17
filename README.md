# BeatForge — Browser Drum Machine & Beat Maker

Make beats in your browser. 8-channel drum sequencer with fully synthesized sounds — no audio files needed.

**Live Demo:** [beatforge.surge.sh](https://beatforge.surge.sh/)

## Features

- **8 synthesized drums** — Kick, Snare, Hi-Hat, Open HH, Clap, Tom, Ride, Percussion
- **16-step sequencer** — Click cells to create patterns
- **7 genre presets** — Rock, Hip Hop, Techno, Jazz, Latin, Drum & Bass, Trap
- **BPM control** — 60-200 BPM
- **Per-channel volume** + mute
- **Swing control** — Add groove to your beats
- **Real-time waveform** — Visual audio feedback
- **WAV export** — Download your beat as a WAV file
- **Save/Load** — Patterns persist in localStorage
- **Keyboard shortcuts** — Space to play/stop

## How It Works

All sounds are synthesized in real-time using the **Web Audio API**. No audio samples, no downloads, no server.

- Kick: Frequency-swept oscillator + click
- Snare: White noise + resonant oscillator
- Hi-Hat: High-pass filtered noise
- Clap: Multi-burst bandpass noise
- Tom, Ride, Percussion: Various oscillator + noise combinations

## Tech

- Pure HTML/CSS/JavaScript — zero dependencies
- Web Audio API for synthesis and scheduling
- OfflineAudioContext for WAV rendering
- AnalyserNode for waveform visualization
- Single HTML file, works offline

## License

MIT
