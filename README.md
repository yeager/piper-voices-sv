# Swedish Voices for Piper TTS

Community-trained Swedish (sv_SE) voices for [Piper](https://github.com/rhasspy/piper), a fast local neural text-to-speech engine.

These voices are developed primarily for **accessibility applications** targeting children and young people with autism (NPF) and language disorders, but are freely available for any use.

## Voices

| Voice | Gender | Quality | Status | Sample Rate |
|-------|--------|---------|--------|-------------|
| **Alma** | Female | Medium | ✅ Ready | 22050 Hz |
| **Axel** | Male | Medium | 🚧 Pending | — |

### Alma

A female Swedish voice trained on ~2 hours of studio-quality speech data. Suitable for TTS in apps, assistive tools, and smart home devices.

- Model: `sv_SE-alma-medium.onnx`
- Config: `sv_SE-alma-medium.onnx.json`
- See [`alma/`](alma/) for files and details.

### Axel

A male Swedish voice — training is pending (dataset collection in progress).

- See [`axel/`](axel/) for status.

## Usage

```bash
echo "Hej, jag heter Alma." | piper \
  --model alma/sv_SE-alma-medium.onnx \
  --output_file output.wav
```

## Links

- 🌐 [autismappar.se](https://autismappar.se) — Accessibility apps for children with NPF
- 🤗 [HuggingFace: yeager/piper-voice-sv-alma](https://huggingface.co/yeagersthlm/piper-voice-sv-alma)
- 📖 [Piper documentation](https://github.com/rhasspy/piper)

## Swedish Language (sv_SE)

Swedish is spoken by ~10 million people. Quality TTS voices for Swedish are scarce, especially open-source ones suitable for accessibility applications. This project aims to fill that gap.

## License

See [LICENSE](LICENSE).

## Author

Daniel Nylander ([@yeager](https://github.com/yeager))
