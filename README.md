# PyTorch Tutorial (learning repo)

Personal **Jupyter notebooks** while learning **PyTorch**—from tensors and operations through autograd and a simple neural network.
## Contents
| Notebook | Topic |
|----------|--------|
| `Intro_to_colab.ipynb` | Environment / Colab setup |
| `Tensor_Math.ipynb` | Tensor basics |
| `tensor_ops.ipynb` | Tensor operations |
| `Pytorch_DeepDive.ipynb` | Autograd and core PyTorch concepts |
| `simple_NeuralNetwork.ipynb` | Simple `nn.Module` model |
## Prerequisites
- **Python 3.10+** recommended  
- [PyTorch](https://pytorch.org/get-started/locally/) (CPU or CUDA—match your machine)
## Run locally
```bash
python -m venv .venv
# Windows PowerShell:
.\.venv\Scripts\Activate.ps1
# macOS / Linux:
# source .venv/bin/activate
pip install -r requirements.txt
jupyter lab
```
Open the notebooks from the repo root, or use VS Code / Cursor with the Jupyter extension.

## Note
Educational experiments only—not production code.
