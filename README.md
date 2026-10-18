# Origami voice packs

Voice packs that Origami Reader setup downloads when someone chooses read-aloud voices in a language. They are made with Origami's voice designer.

Copyright (c) 2026 Sov3ryn. For use with Origami Reader only; see the Origami Reader app license.

## Studio model files

The release `studio-models-1` holds files that Origami Studio downloads when someone sets up Studio: the AudioSeal watermark generator and detector converted to ONNX (from Meta's AudioSeal, MIT license) and an int8 encoder of NVIDIA Parakeet TDT 0.6B v3 (CC-BY-4.0). They keep their own licenses, not the voice pack terms above; see NOTICE-studio-models.txt in the release. Origami checks each file against a pinned SHA-256 before use.
