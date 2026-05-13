# Google Colab for Neurotechnology

A Quarto book of notes and recipes for running neurotech workflows on Google Colab.

Published at <https://bkowshik.github.io/google-colab-for-neurotech/>.

## What's inside

- **Preface** — why Google Colab is a good fit for neurotech (principles).
- **Common** — setup shared across projects: mounting Drive, Colab's filesystem, retina plots, VS Code Colab extension.
- **NeuroAI** — recipes for Meta's NeuroAI suite (NeuralSet / NeuralFetch / NeuralTrain / NeuralBench).

## Build

```bash
quarto preview   # live preview
quarto render    # build to _book/
```

## Structure

- `index.qmd` — Preface
- `common.qmd` — common setup across projects
- `neuroai.qmd` — NeuroAI chapter
- `references.qmd` / `references.bib` — citations
- `_quarto.yml` — book config
- `cover.png` — book cover image

## License

MIT — see [`LICENSE`](LICENSE).

Author: Bhargav Kowshik
