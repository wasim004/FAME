# FAME: Feature Attribution via Multilevel Embeddings for Deepfake Model Attribution

**FAME** is a lightweight, spatio-temporal deep learning architecture designed for **Deepfake model attribution** — identifying the source generative model behind manipulated face-swap videos. It combines VGG-based frame-level representation with LSTM-based temporal attention for robust multi-class classification.

> 🔒 **Note:** The source code and pretrained models will be released shortly upon acceptance/publication.

---

## 🧠 Overview

- 🧩 Combines truncated VGG19 for spatial feature extraction with Bi-LSTM for temporal modeling
- 🔍 Attention module to highlight salient frames in video sequences
- 💡 Designed for attribution across multiple Deepfake generation models, not just detection
- ⚡ Lightweight and efficient, suitable for real-time or resource-constrained deployment

---

## 📈 Key Results

FAME has been evaluated on multiple public benchmarks:

| Dataset         | Accuracy (%) | Macro F1 Score | AUC     |
|-----------------|--------------|----------------|---------|
| DFDM            | 97.3         | 0.975          | 0.999   |
| FaceForensics++ | 96.4         | 0.968          | 0.997   |
| FakeAVCeleb     | 84.6         | 0.841          | 0.986   |

FAME shows strong generalization across different types of face-swap and GAN-based Deepfake generators.

---

## 📦 Code & Models

The codebase will include:

- Full PyTorch implementation of the FAME model
- Training & evaluation scripts
- Support for DFDM, FF++, and FakeAVCeleb datasets
- Pretrained model checkpoints (to be released)

> ⏳ **Coming Soon**: The code and models will be publicly released on this repository upon official acceptance/publication.

---

## 📄 Citation

If you find our work useful, please consider citing:

```bibtex
@article{AHMAD2025128571,
  title = {FAME: A Lightweight Spatio-Temporal Network for Model Attribution of Face-Swap Deepfakes},
  journal = {Expert Systems with Applications},
  pages = {128571},
  year = {2025},
  issn = {0957-4174},
  doi = {https://doi.org/10.1016/j.eswa.2025.128571},
  url = {https://www.sciencedirect.com/science/article/pii/S0957417425021906},
  author = {Wasim Ahmad and Yan-Tsung Peng and Yuan-Hao Chang},
  keywords = {Face-swap Deepfakes, Deepfake Model Attribution, Attention Mechanism, Multimedia Forensics, Information Security}
}
