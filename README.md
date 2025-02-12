# Multi-Microphone Speech Emotion Recognition using HTS-AT

🚀 **Official repository for the paper:**
**"Multi-Microphone Speech Emotion Recognition using the Hierarchical Token-semantic Audio Transformer Architecture"** (ICASSP 2025)\
📄 [Read the Paper](https://arxiv.org/pdf/2406.03272)


---

## 🔍 Overview

This work proposes a **multi-microphone adaptation** of the **HTS-AT Transformer architecture** to enhance emotion recognition in challenging acoustic environments.

### 🔮 Key Features

- **Multi-Microphone Audio Processing**: Enhanced robustness against reverberation.
- **HTS-AT Transformer Model**: A state-of-the-art deep learning approach.
- **Evaluation on Real-World Data**: Tested using the **ACE RIR Database**.
- **Fine-Tuned on Emotional Speech Datasets**: RAVDESS, IEMOCAP, and CREMA-D.

---

## 💼 Paper Abstract

Most emotion recognition systems degrade in **real-life scenarios** where audio is contaminated by reverberation. This study explores new methods to mitigate this degradation and proposes a robust **multi-microphone SER system** based on **HTS-AT**. We evaluate two strategies:

1. **Averaging Mel-Spectrograms** across channels.
![](images/Avg_mel.png)

2. **Summing Patch-Embedded Representations**.
![](images/Sum.png)
Our multi-microphone models **outperform single-channel baselines**, demonstrating their superiority in real-world reverberant conditions.

---

## 🔧 How It Works

1. Multi-channel audio is preprocessed into **mel-spectrograms**.
2. The mel-spectrograms are processed using the selected multi-channel strategy (e.g., Averaging Mel-Spectrograms or Patch-Embed Summation).
3. The processed mel-spectrograms are converted into patch tokens.
4. The **HTS-AT Transformer** extracts deep features from the multi-microphone patch-token representations, enhancing robustness in reverberant environments.

---

## 💼 Project Structure

This repository **only serves as a landing page**. The actual implementation is hosted in a separate repository:

🔗 **[Code Repository](https://github.com/yourusername/Multi-Microphone-SER-Code)**

---

## 🏆 Citation

If you use this work, please cite:

```bibtex
@inproceedings{cohen2025multimic,
  author    = {Ohad Cohen, Gershon Hazan, Sharon Gannot},
  title     = {Multi-Microphone Speech Emotion Recognition using the Hierarchical Token-semantic Audio Transformer Architecture},
  booktitle = {ICASSP},
  year      = {2025}
}
```

---

## 🌟 Acknowledgments

This research was supported by the **European Union’s Horizon 2020 Program** and the **Audition Project, Data Science Program, Israel**.

---

## 👤 Contact

For questions or collaborations, feel free to reach out:
📧 **[ohad.cohen@biu.ac.il](mailto\:ohad.cohen@biu.ac.il)**

