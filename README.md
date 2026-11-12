# Speed of Light

An interactive, level-by-level course that goes from how a chip moves one byte to training and serving frontier models: GPU and Apple-silicon hardware, CUDA and Metal kernels, inference, training, decentralised training, and reinforcement learning.

**Live site:** https://pusse-01.github.io/speed-of-light/

## What is inside

- **29 levels**, one chapter each, from *Start here* to the interview bank. Each level is a short run of one-screen steps. Finishing a level takes you straight to the next one, and the map shows your progress.
- **23 hands-on labs** inside the steps, including:
  - a float-format explorer, an interactive roofline, occupancy and Little's law, and coalescing and bank-conflict viewers;
  - online softmax and FlashAttention steppers, matmul tiling, wave quantisation, and a model-on-a-chip calculator for memory, decode and prefill;
  - quantization with outliers and Hadamard rotation, kernel-gap (bubble) costs, speculative decoding, and α–β communication costs;
  - Newton–Schulz for Muon, GPipe and 1F1B schedules, and the Protocol NanoGPT step-time simulator;
  - GAE, PPO clipping, GRPO advantages, the *Pitch* football simulator, and a UCB kernel-search demo.
- **Exercises** at the end of every level, with a box for your working and the book's answer. Your answers and ticked questions are saved in your browser.
- **A short print edition** (49 A4 pages): [speed-of-light-short-print-edition.pdf](speed-of-light-short-print-edition.pdf).

The Claude tutor ("Ask Claude" and "Check my attempt with Claude") only works when the page is opened inside Claude. On this GitHub-hosted copy, everything else works.

## Run it locally

The site is one self-contained `index.html`. Open it directly in a browser, or serve the folder:

```bash
python3 -m http.server 8000
# then open http://localhost:8000
```

Formulas, code highlighting and fonts load from public CDNs (jsDelivr and Google Fonts), so the first load needs an internet connection.
