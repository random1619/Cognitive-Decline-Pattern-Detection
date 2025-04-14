# 🧠 Cognitive Stress Detection in Speech

## 📝 Overview
This repository contains a comprehensive Python-based cognitive analysis tool designed to detect stress patterns and abnormalities in speech.  
The system uses a **multi-modal approach** combining acoustic feature extraction, speech-to-text analysis, and machine learning to identify potential cognitive stress markers in audio samples.

## 🌟 Features
- 🎧 **Audio Feature Extraction**  
  Analyzes acoustic properties: pitch, speech rate, energy levels, spectral features, MFCCs (Mel-frequency cepstral coefficients)

- 🗣️ **Speech-to-Text Processing**  
  Converts speech to text for linguistic analysis

- ✍️ **Text Content Analysis**  
  Analyzes vocabulary richness, hesitation patterns, disfluencies

- ⚠️ **Anomaly Detection**  
  Identifies outliers and abnormal speech patterns

- 🔍 **Cluster Analysis**  
  Groups similar speech patterns to detect cognitive states

- 📊 **Visualization Tools**  
  Charts and plots for detected patterns and anomalies

- 📋 **Detailed Risk Analysis**  
  Generates stress indicator reports with confidence metrics

## 🧰 Requirements
Ensure you have **Python 3.6+** and the following libraries installed:

```
text
numpy
pandas
matplotlib
scipy
seaborn
librosa
SpeechRecognition
scikit-learn
```

## ⚙️ Installation

Clone the repository:

```
git clone https://github.com/yourusername/cognitive-stress-detection.git
cd cognitive-stress-detection
```

Install the dependencies:

```
pip install -r requirements.txt
```

## ▶️ Usage

🎵 Place `.wav` or `.mp3` files into the `audio_samples` directory.

Run the analysis pipeline:

```
python cognitive_analysis.py
```

Or launch the Jupyter Notebook:

```
jupyter notebook Cognitive_analysis.ipynb
```

## 🔄 Pipeline Workflow

1. 📂 **Audio Loading** — Load audio from directory  
2. 🔍 **Feature Extraction** — Extract pitch, MFCCs, etc.  
3. 🗣️ **Speech-to-Text** — Transcribe speech using Google's API  
4. ✍️ **Text Analysis** — Extract linguistic markers  
5. 🧮 **Feature Normalization** — Standardize features  
6. 📌 **Clustering** — Group similar patterns using K-means  
7. ⚠️ **Anomaly Detection** — Detect cognitive stress markers  
8. 📊 **Visualization** — Display charts and visualizations  
9. 📋 **Risk Analysis** — Generate comprehensive assessment reports

## 📈 Example Output

The pipeline provides:

- 🔵 PCA plots of feature clusters  
- ⚠️ Highlighted anomalies & risk samples  
- 🔥 Feature deviation heatmaps  
- 📄 Report with:
  - Total samples analyzed
  - Cluster breakdown
  - Risk sample insights
  - Key features and markers
  - Suggested follow-ups

## 🧪 Applications

- 🏥 **Clinical Assessment** — Early cognitive disorder detection  
- 🧘 **Mental Health Monitoring** — Track stress over time  
- 💬 **Human-AI Interaction** — More responsive virtual assistants  
- 📱 **Personal Well-being** — Self-monitor stress levels  
- 📚 **Research** — Cognitive pattern studies across populations

## ⚠️ Limitations

- 🎙️ Clear audio needed for best results  
- 🌐 Supports **English only** for now  
- 📉 Statistical analysis should be interpreted by professionals  
- 🚫 Not a substitute for medical diagnosis

