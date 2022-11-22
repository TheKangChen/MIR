# Music Information Retrieval Tasks
Demonstration of modern music information retrieval (MIR) tasks and analysis.

---
## 1. Instrument Classification
Analyze intrument classification performance of machine learning algorithms
- K Nearest Neighbor (KNN)
- Neural Networks

## 2. Onset Detection Comparison
Analyze performance of different Onset Detection algorithms
- Energy Based Detection
- Spectral Flux

## 3. Beat and Pitch Estimation
Analyze performance of beat and pitch tracking algorithms

Beat Tracking:
- Spectral Flux
- Recurrent Neural Network (RNN)

Pitch Tracking:
- Spectrogram argmax
- YIN
- Convolutional Neural Network (CNN)

## 4. Chord Estimation
Analyze performance of chord estimation algorithms
- Deep Chroma
- Template Matching

## 5. Audio Emotion Detection
Analyze and compare music emotion estimation performance using different machine learning architechtures
- Suppor Vector Machine (SVM)
- Neural Net (50, 4)
- Neural Net with Dropout (50, 4)
- Neural Net (50, 20, 4)
- K Nearest Neighbor (KNN)

## 6. Reference
- Instrument classification Medley-solos-DB: https://zenodo.org/record/3464194#.Y3wjCi-B30q
- Beat estimation GuitarSet: https://zenodo.org/record/3371780#.Y3wm4S-B30o
- Pitch estimation MedleyDB-Pitch: https://zenodo.org/record/2620624#.Y3w0qy-B30p
- Emotion recognition 4Q audio emotion dataset: http://mir.dei.uc.pt/downloads.html
- Python audio signal processing library madmom: https://github.com/CPJKU/madmom
- Python MIR evaluation library mir_eval: https://craffel.github.io/mir_eval/
- CREPE pitch tracker: https://github.com/marl/crepe
