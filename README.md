# Paper-to-Code: ResNet-18 in PyTorch

This project reimplements the ResNet-18 architecture from the paper  
**“Deep Residual Learning for Image Recognition” (He et al., 2015)** using PyTorch.

The goal of this project is to gain hands-on experience implementing a research model with PyTorch, building a training
pipeline, and analyzing results.

---

## 📄 Paper Reference
He, K., Zhang, X., Ren, S., Sun, J.  
Deep Residual Learning for Image Recognition  
arXiv:1512.03385

---

## 🧠 Model Overview
- Residual blocks with skip connections
- Deep CNN architecture enabling stable gradient flow
- Implemented from scratch using PyTorch `nn.Module`

---

## 📊 Dataset
- CIFAR-10
- 10 image classes
- 32×32 RGB images

---

## ⚙️ Implementation Details
- Framework: PyTorch
- Loss function: Cross-Entropy Loss
- Optimizer: Adam or SGD
- GPU support when available
- Custom training and evaluation loops

---

## 📈 Results
| Metric | Value |
|------|------|
| Training Accuracy | XX% |
| Validation Accuracy | XX% |

(*Results depend on training time and hyperparameters.*)

---

## ⚠️ Limitations
- Model trained on a small dataset
- No extensive hyperparameter tuning
- Not optimized for production deployment

---

