# Naikiyah models

Speech-recognition model files downloaded by the Naikiyah app for its
"Recite to Naikiyah" feature. Model files are attached to the
[releases](../../releases), not stored in the repository.

## ggml-deepdml-small-ar-quran-q5_1.bin

- Source model: [deepdml/whisper-small-ar-quran-mix-norm](https://huggingface.co/deepdml/whisper-small-ar-quran-mix-norm)
  (Whisper small fine-tuned on Quran recitation), licensed under the
  Apache License 2.0.
- Converted to [whisper.cpp](https://github.com/ggml-org/whisper.cpp) ggml
  format and quantised to q5_1. No other changes were made to the weights.
- Size: 190,085,504 bytes
- MD5: `d87d0874b8747744b627167133c444dd`
- SHA-256: `225f6fec1129050902d5d8d51cc9dca09a4e2815e14826b53508a6c82024361e`

All credit for the model goes to its authors. This repository redistributes
the converted file under the same Apache License 2.0 (see LICENSE).
