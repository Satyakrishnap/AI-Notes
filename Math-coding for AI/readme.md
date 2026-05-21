#  1. PyTorch-NN Notebook

> Part of a growing collection of hands-on ML notebooks.

---

## What's Inside

| Section | What you learn |
|---|---|
| **Part 1 — Tensors** | Tensor ranks, dtypes, linear algebra ops, indexing and reshaping |
| **Part 2 — Autograd** | Chain rule, `requires_grad`, `retain_grad`, computation graph visualisation |
| **Part 3 — Backprop** | Manual backprop on a tiny MLP, verified against autograd, gradient flow diagram |
| **Part 4 — PyTorch Toolbox** | `nn`, `optim`, activations, the standard training step |
| **Part 5 — Convolutions** | The math, stride/padding formula, kernel effects visualised |
| **Part 6 — CIFAR-10 CNN** | Build, train, and evaluate a CNN — loss curves, confusion matrix, feature maps |
| **Part 7 — Best Practices** | Saving models, transfer learning, schedulers, custom datasets |
| **Bonus — nn vs F** | `nn` vs `nn.functional` vs custom modules, with four built-from-scratch examples |

---

## Requirements

```bash
pip install torch torchvision matplotlib numpy networkx
```
> Authorship Note: Written by Satya Krishna Pothapragada. Reviewed and corrected with Claude (Anthropic), which also contributed the visualisation modules at Sections 2.7,§3.6, 4.2, 5.7, and 6.10.
