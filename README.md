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
@article{,
  title={FAME: Feature Attribution via Multilevel Embeddings for Deepfake Model Attribution},
  author={Wasim Ahmad et al.},
  journal={Accepted at Expert Systems With Applications (ESWA)},
  year={2025},
  publisher={Elsevier}
}
