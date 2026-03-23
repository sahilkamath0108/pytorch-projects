# PyTorch — personal learning repo

This is my own workspace for working through deep learning with **PyTorch**: numbered topic folders, scripts, and notebooks where I implement ideas, break things on purpose, and leave notes that match how I actually think—not a polished course site.

I use it to go from tensor basics through training loops, CNNs and sequence models, up to heavier topics (deployment, Lightning, distributed training, etc.) as I need them for projects or interviews. The layout is sequential enough to follow in order, but you can jump to a folder if you only care about one area.

## Setup

```bash
git clone <this-repo-url>
cd pytorch-projects
python -m venv .venv
# Windows: .venv\Scripts\activate
# macOS/Linux: source .venv/bin/activate
pip install -r requirements.txt
```

Run a script from any module folder, or open the matching notebook in Jupyter / VS Code:

```bash
jupyter lab
# or open .ipynb files directly in your editor
```

**Suggested:** Python 3.10+ and a recent PyTorch build that matches your CUDA/CPU setup from [pytorch.org](https://pytorch.org).

## What’s in here (by folder)

Topics map to the numbered directories at the repo root—each one is a self-contained slice (README / `.py` / `.ipynb` where I added them).

| # | Folder | What I focus on |
|---|--------|-----------------|
| 01 | `01_pytorch_basics` | Tensors, graphs, autograd basics, GPU |
| 02 | `02_neural_networks_fundamentals` | Layers, activations, loss, optimizers, `nn.Module` |
| 03 | `03_automatic_differentiation` | Gradients, custom autograd, higher-order |
| 04 | `04_training_neural_networks` | Loops, validation, scheduling, early stopping |
| 05 | `05_data_loading_preprocessing` | `Dataset`, `DataLoader`, transforms |
| 06 | `06_convolutional_neural_networks` | CNNs, classification, transfer learning |
| 07 | `07_recurrent_neural_networks` | RNN / LSTM / GRU, sequences |
| 08 | `08_transformers_and_attention_mechanisms` | Attention, transformers, fine-tuning |
| 09 | `09_generative_models` | VAEs, GANs, diffusion-style ideas |
| 10 | `10_model_deployment` | TorchScript, ONNX, serving, quantization |
| 11 | `11_pytorch_lightning` | Lightning modules, trainers, logging |
| 12 | `12_distributed_training` | DDP, multi-GPU patterns |
| 13 | `13_custom_extensions` | Custom ops, CUDA/C++ when I touch them |
| 14 | `14_performance_optimization` | AMP, profiling, memory |
| 15 | `15_advanced_model_architectures` | ViT, GNNs, newer architectures |
| 16 | `16_reinforcement_learning` | RL basics with PyTorch |
| 17 | `17_model_optimization_techniques` | Quantization, pruning, distillation |
| 18 | `18_meta_learning` | Few-shot / meta-learning experiments |
| 19 | `19_neural_architecture_search` | NAS experiments |
| 20 | `20_bayesian_deep_learning` | Bayesian NN / uncertainty |
| 21 | `21_advanced_research_topics` | Misc research-shaped notebooks |

Not every subtopic in a folder is “done” in my head forever—some are reference runs I revisit when I need them.

## License

This repository includes material that builds on publicly shared educational resources and the **MIT License** in [`LICENSE`](LICENSE). I keep my own edits and notes here as part of my learning; if you reuse code, respect that license and cite upstream work where it applies.

---

*If something is confusing or a notebook is half-finished, that’s normal—it’s a lab, not a product manual.*
