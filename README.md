# 🧠 Cognitive Decline Pattern Detection

**Cognitive Decline Pattern Detection** is an AI/ML research pipeline designed to detect cognitive stress markers, speech disfluency, and speech pattern abnormalities using acoustic signal processing, NLP speech-to-text, and machine learning cluster analysis.

---

## 🌟 Key Features

- 🎧 **Audio Feature Extraction**: Acoustic property extraction including pitch variations, speech tempo, energy distribution, spectral features, and Mel-frequency cepstral coefficients (MFCCs) using `librosa`.
- 🗣️ **Speech-to-Text & Linguistic Analysis**: Automated transcription and text content analysis measuring vocabulary richness, pause frequencies, and linguistic disfluencies.
- ⚠️ **Anomaly & Outlier Detection**: Statistical outlier detection for identifying atypical speech patterns.
- 🔍 **Cluster Analysis & PCA**: K-Means clustering and Principal Component Analysis (PCA) to map feature spaces and identify cognitive stress states.
- 📊 **Visual Analytics**: Dynamic feature heatmaps, PCA scatter plots, and stress indicator distribution charts.

---

## 📁 Repository Structure

```
Cognitive-Decline-Pattern-Detection/
├── Cognitive_analysis.ipynb                # Main Jupyter Notebook pipeline
├── Cognitive Speech Analysis.pdf           # Technical research documentation & report
├── Flowchart-Cognitive-Speech-Analysis.png # System pipeline architecture flowchart
└── audio_samples/                          # Sample dataset audio files (.wav)
```

---

## 🧰 Prerequisites & Requirements

Ensure you have **Python 3.8+** installed along with the following packages:

```bash
pip install numpy pandas matplotlib scipy seaborn librosa SpeechRecognition scikit-learn
```

---

## 🚀 Execution & Usage

1. Open `Cognitive_analysis.ipynb` in **Jupyter Notebook** or **VS Code**:
   ```bash
   jupyter notebook Cognitive_analysis.ipynb
   ```
2. Execute the notebook cells sequentially to run audio feature extraction, clustering, anomaly detection, and report generation.

---

## 👨‍💻 Author & Contact

**Author**: Gagandeep Singh  
**GitHub**: [@random1619](https://github.com/random1619)

---

## 📄 License

Distributed under the MIT License.
