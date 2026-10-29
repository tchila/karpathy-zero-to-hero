# Karpathy — Neural Networks: Zero to Hero

My implementations of Andrej Karpathy's [Zero to Hero](https://karpathy.ai/zero-to-hero.html) lectures.

| # | Lecture | Folder |
|---|---------|--------|
| 1 | micrograd: backprop from scratch | `lectures/01_micrograd` |
| 2 | makemore 1: bigram language model | `lectures/02_makemore_bigram` |
| 3 | makemore 2: MLP | `lectures/03_makemore_mlp` |
| 4 | makemore 3: activations, gradients, BatchNorm | `lectures/04_makemore_batchnorm` |
| 5 | makemore 4: becoming a backprop ninja | `lectures/05_makemore_backprop_ninja` |
| 6 | makemore 5: WaveNet | `lectures/06_makemore_wavenet` |
| 7 | Let's build GPT from scratch | `lectures/07_gpt_from_scratch` |
| 8 | Let's build the GPT tokenizer | `lectures/08_tokenizer` |
| 9 | Let's reproduce GPT-2 (124M) | `lectures/09_reproduce_gpt2` |

## Setup

```bash
uv sync
source .venv/bin/activate
python -m ipykernel install --user --name zth --display-name "Python (zero-to-hero)"
jupyter lab
```

Shared helpers live in `src/zth` (e.g. `from zth.device import get_device`).
Datasets go in `data/` (ignored by git except small text files like `names.txt`).
