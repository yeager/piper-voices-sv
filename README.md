# Piper TTS Swedish Voices for NVDA (Sonata)

High-quality Swedish neural TTS voices for [NVDA screen reader](https://www.nvaccess.org/) via the [Sonata addon](https://github.com/mush42/sonata-nvda).

## Voices

### Alma (sv_SE-alma-medium)
- **Gender:** Female
- **Quality:** Medium (22050 Hz)
- **Size:** 56 MB
- **Training data:** NST Swedish speech corpus
- **License:** CC-BY 4.0

## Installation

### Prerequisites
1. Install [NVDA](https://www.nvaccess.org/download/) (2024.1 or later)
2. Install the [Sonata Neural Voices addon](https://github.com/mush42/sonata-nvda/releases/latest)

### Install Voice
1. Download the voice package (`.tar.gz`) from [Releases](../../releases)
2. In NVDA, open **Tools → Sonata Voice Manager**
3. Click **Install from local file**
4. Select the downloaded `.tar.gz` file
5. Restart NVDA
6. Go to **Settings → Speech** and select **Sonata Neural Voices**
7. Choose **Alma** from the voice list

## Quick Test
You can test the voice with [Piper](https://github.com/rhasspy/piper) directly:
```bash
echo "Hej! Det här är den svenska rösten Alma." | piper --model sv_SE-alma-medium.onnx --output_file test.wav
```

## About
These voices are trained using [Piper TTS](https://github.com/rhasspy/piper) and optimized for screen reader use. They provide significantly better quality than the default eSpeak NG synthesizer for Swedish.

Created by [Daniel Nylander](https://github.com/yeager) to improve accessibility for Swedish-speaking visually impaired users.

## License
Voice models: CC-BY 4.0
This repository: GPL v2 (matching NVDA and Sonata licenses)

### Daniel (sv_SE-daniel-medium) — NEW!
- **Gender:** Male
- **Quality:** Medium (22050 Hz)
- **Size:** 80 MB
- **Training data:** Voice cloned from 3 minutes of speech
- **License:** CC-BY 4.0
