
# Bimodal Emotion Recognition (Face + Speech)

**Report (PDF):** [Bimodal_Emotion_Recognition_Face_Speech.pdf](./Bimodal_Emotion_Recognition_Face_Speech.pdf)

## Overview
A multimodal emotion recognition project that combines **facial expressions** and **speech** to classify six basic emotions (happiness, sadness, anger, fear, disgust, surprise). It evaluates multiple classifiers and fusion strategies to improve robustness over single‑modality systems.

## Methods
- **Speech features:** MFCCs (plus prosodic/spectral statistics).
- **Face features:** Wavelet coefficients and **Hu moments** (shape descriptors).
- **Classifiers:** SVM, Naive Bayes, K‑Nearest Neighbors.
- **Fusion:** Feature‑level fusion and match‑score (decision‑level) fusion.

## Results (summary)
- Fusion improves accuracy compared to single-modality models.
- **Feature‑level fusion** performs better than score-level fusion in this setup.
- Includes UI screenshots (data upload, preprocessing, accuracy graphs, sample predictions).

## Tech & Tools
- **Python 3.7** on Windows
- TensorFlow • NumPy • Pandas • Matplotlib • scikit‑learn

## Repository Structure
```
emotion-recognition-bimodal/
├─ Bimodal_Emotion_Recognition_Face_Speech.pdf   # Full report
└─ README.md
```

## Future Work
- Larger, more diverse dataset; noise‑robust audio preprocessing.
- Real‑time webcam/mic capture and inference pipeline.
- Data augmentation and cross‑validation by subject.
