# LIMINAL INSTRUMENTS

> Browser-native sound machines. Zero dependencies. Pure Web Audio API.  
> Open a tab → start playing.

[🌐 Live Demo (EN)](https://effdst.github.io/LiminalInstruments/) | [🌐 Live Demo (RU)](https://effdst.github.io/LiminalInstruments/index-ru.html)

---

## 📡 About

A collection of six standalone browser-based instruments for sound design and live performance. 
Each instrument is a single, self-contained HTML file that runs locally, without installation, user accounts, or external libraries. 
The interface is designed as a hardware control panel: fixed frame, tactile response, block-level randomization, and full keyboard accessibility.

## 🎛 Instruments

| # | Instrument | Description | Link |
|---|------------|-------------|------|
| 01 | **GRANULA** | Liminal granular workstation. True stereo grain cloud, time freezing, polyphony, parametric EQ, and WAV rendering. | [Open](./Granula.html) |
| 02 | **NULLROOM Ø** | Liminal ambient workstation. 100 presets, 16×8 step sequencer, generative scenes, and immersive reverbs (Room, Hall, Shimmer, Space, Cavern). | [Open](./NullRoom.html) |
| 03 | **MUTABLE•WEB XL** | Modular synthesizer. 20 modules, CV everywhere, patch cables, and generative ambient capabilities (Marbles, Plaits, Rings, Aether, etc.). | [Open](./MutableWeb.html) |
| 04 | **OCTA//WEB** | Performance sampler. 16-step knob automation, A/B scene morphing crossfader, 8-band parametric EQ, and master compression. | [Open](./OktaWeb.html) |
| 05 | **KICKFORGE** | Kick performance unit. BPM-synced 4/4 loop, limiter with gain reduction meter, random patterns, JSON project save/load, and offline 16-bit / 44.1 kHz WAV rendering. | [Open](./KickForge.html) |
| 06 | **NEUROGRID** | OP–IDM drum & synth machine. 8 voices, polymetric 16×8 sequencer, per-step parameter locks, 4 LFOs, and shimmer effects. | [Open](./NeuroGrid.html) |

## ⚙️ System Requirements

- **Engine**: Web Audio API
- **Dependencies**: 0 (Zero)
- **Installation**: None (Single File)
- **Offline Mode**: Yes (runs from local disk or USB drive)
- **Export**: WAV (audio), JSON (patches)
- **Browsers**: Chrome, Edge, Safari, Firefox (latest versions)

## ⌨️ Global Controls (on Landing Page)

- `1` ... `6` : Open the corresponding instrument in a new tab
- `↑` / `↓` : Navigate the rack
- `ENTER` : Launch the selected instrument
- `I` : Show selected unit specs
- `S` : Toggle the site's background ambient drone
- `R` : Select a random instrument (⚄)
- `?` : Open the operator's manual

## 📂 Repository Structure

```text
.
├── index.html          # Landing page (English)
├── index-ru.html       # Landing page (Russian)
├── Granula.html        # Granular synthesis workstation
├── NullRoom.html       # Ambient & generative workstation
├── MutableWeb.html     # Modular synthesis environment
├── OktaWeb.html        # Performance sampler & automation
├── KickForge.html      # Kick performance unit
└── NeuroGrid.html      # Polymetric step sequencer