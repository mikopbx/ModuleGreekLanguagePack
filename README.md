# ModuleGreekLanguagePack

Complete Greek language pack for MikoPBX including UI translations and voice prompts.

## What's Included

- **Voice Prompts**: 563 Greek voice prompts (22050 Hz, mono, 16-bit PCM WAV) including 10 silence files at 8 kHz
- **UI Translations**: Complete Greek translation of MikoPBX admin interface
- **Text Mapping**: `Sounds/core-sounds-gr-gr.txt` — full list of prompts with text

## Voice Generation

Voice prompts were generated using neural TTS (Text-to-Speech) technology:

- **Engine**: macOS TTS (built-in `say` command)
- **Voice model**: `Melina` (el_GR)
- **Sample rate**: 22050 Hz
- **Format**: WAV (PCM signed 16-bit, mono)

The text for each prompt is stored in `Sounds/core-sounds-gr-gr.txt` for reference and regeneration.

On module installation, MikoPBX automatically converts WAV files to all Asterisk formats (ulaw, alaw, gsm, g722, sln) for optimal codec compatibility.

## Installation

1. Download and install the module from MikoPBX Marketplace
2. Enable the module in **Modules** section
3. Go to **General Settings** and select Greek (Ελληνικά) as the system language

## Requirements

- MikoPBX 2025.1.1 or later

## License

- Module code: GNU General Public License v3.0
- Sound files: CC BY-SA 4.0
- TTS engine: macOS built-in TTS (Apple Inc.)

## Copyright

- Module development: © 2017-2026 Alexey Portnov and Nikolay Beketov
- Voice synthesis: Generated using macOS Melina (el_GR) TTS voice
- Remaining system sounds (silence, tones): Generated programmatically (CC BY-SA 4.0)
