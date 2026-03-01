# Alma — Swedish Female Voice

A medium-quality female Swedish voice for Piper TTS.

## Details

- **Language:** Swedish (sv_SE)
- **Gender:** Female
- **Quality:** Medium
- **Sample Rate:** 22050 Hz
- **Format:** ONNX (Piper-compatible)

## Files

- `sv_SE-alma-medium.onnx` — Voice model
- `sv_SE-alma-medium.onnx.json` — Model configuration
- `samples/` — Audio samples

## Usage

```bash
echo "Hej, jag heter Alma." | piper \
  --model sv_SE-alma-medium.onnx \
  --output_file output.wav
```

## Training

Trained using Piper's training pipeline on ~2 hours of studio-recorded Swedish speech.

## Also Available On

- 🤗 [HuggingFace: yeager/piper-voice-sv-alma](https://huggingface.co/yeager/piper-voice-sv-alma)
