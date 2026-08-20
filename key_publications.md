# Applied Media Systems (AMS) – Key Publications

This is a **curated onboarding reading list** for the Applied Media Systems group at TU Ilmenau.  
It is intentionally selective rather than a complete bibliography.

- [AMS publication pages at TU Ilmenau](https://www.tu-ilmenau.de/universitaet/fakultaeten/fakultaet-elektrotechnik-und-informationstechnik/profil/institute-und-fachgebiete/fachgebiet-angewandte-mediensysteme/publikationen)
- [AMS GitHub organization](https://github.com/TUIlmenauAMS)

## 1. Books and broad background

### Multirate Signal Processing

**Gerald Schuller, _Multirate Signal Processing with Examples in Python_, Springer, 2026.**

A compact introduction to multirate systems, polyphase representations, filter banks, the MDCT, low-delay filter banks, filter-bank optimization, and neural-network connections.

- [Springer / DOI](https://doi.org/10.1007/978-3-032-17201-3)
- [MRSP tutorials and notebooks](https://github.com/TUIlmenauAMS/MRSP_Tutorials)

### Filter Banks and Audio Coding

**Gerald Schuller, _Filter Banks and Audio Coding: Compressing Audio Signals Using Python_, Springer, 2020.**

Core background for the group's work on filter banks, perceptual audio coding, psychoacoustics, predictive coding, and low-delay coding.

- [Springer / DOI](https://doi.org/10.1007/978-3-030-51249-1)
- [Audio Coding tutorials and notebooks](https://github.com/TUIlmenauAMS/AudioCoding_Tutorials)
- [Python Audio Coder](https://github.com/TUIlmenauAMS/Python-Audio-Coder)

German edition:

- [Gerald Schuller, _Filterbänke und Audiocodierung: Komprimierung von Audiosignalen mit Python_](https://doi.org/10.1007/978-3-031-19990-5)

---

## 2. Filter banks and low-delay audio coding

### New framework for modulated perfect-reconstruction filter banks

**Gerald D. T. Schuller and Mark J. T. Smith,  
“New Framework for Modulated Perfect Reconstruction Filter Banks,”  
IEEE Transactions on Signal Processing, 44(8), 1941–1954, 1996.**

A foundational paper on flexible modulated perfect-reconstruction filter banks with explicit control of system delay.

- [DOI](https://doi.org/10.1109/78.533715)

### Modulated filter banks with arbitrary system delay

**Gerald D. T. Schuller and Tanja Karp,  
“Modulated Filter Banks with Arbitrary System Delay: Efficient Implementations and the Time-Varying Case,”  
IEEE Transactions on Signal Processing, 48(3), 737–748, 2000.**

Important background for low-delay and time-varying filter-bank structures.

- [DOI](https://doi.org/10.1109/78.824669)
- [Full-text PDF at Fraunhofer IDMT](https://www.idmt.fraunhofer.de/content/dam/idmt/documents/IL/Personal%20Websites/Schuller/publications/tsp3-00.pdf)

### Efficient biorthogonal cosine-modulated filter banks

**Tanja Karp, Alfred Mertins, and Gerald Schuller,  
“Efficient Biorthogonal Cosine-Modulated Filter Banks,”  
Signal Processing, 81(5), 997–1016, 2001.**

Connects low-delay biorthogonal filter-bank design with efficient structured realizations.

- [DOI](https://doi.org/10.1016/S0165-1684(01)00019-6)

### Low-delay filter banks for Enhanced Low Delay AAC

**Markus Schnell, Ralf Geiger, Markus Schmidt, Markus Multrus, Michael Mellar, Jürgen Herre, and Gerald Schuller,  
“Low Delay Filterbanks for Enhanced Low Delay Audio Coding,”  
IEEE WASPAA, 2007.**

Connects dedicated low-delay filter banks directly to MPEG-4 Enhanced Low Delay AAC (AAC-ELD).

- [DOI](https://doi.org/10.1109/ASPAA.2007.4392985)
- [Full-text PDF](https://www.idmt.fraunhofer.de/content/dam/idmt/documents/IL/Personal%20Websites/Schuller/publications/WASPAA07_LDFB_for_ELD_0023.pdf)

### Perceptual audio coding with adaptive pre- and post-filters

**Gerald D. T. Schuller, Bin Yu, Dawei Huang, and Bernd Edler,  
“Perceptual Audio Coding Using Adaptive Pre- and Post-Filters and Lossless Compression,”  
IEEE Transactions on Speech and Audio Processing, 10(6), 379–390, 2002.**

A low-delay perceptual coding approach separating irrelevance reduction from redundancy reduction.

- [DOI](https://doi.org/10.1109/TSA.2002.803444)

---

## 3. Singing-voice and music source separation with deep learning

### Recurrent encoder-decoder with skip-filtering

**Stylianos Ioannis Mimilakis, Konstantinos Drossos, Tuomas Virtanen, and Gerald Schuller,  
“A Recurrent Encoder-Decoder Approach with Skip-Filtering Connections for Monaural Singing Voice Separation,”  
IEEE MLSP, 2017.**

A useful entry point into the group's deep-learning work on singing-voice separation.

- [DOI](https://doi.org/10.1109/MLSP.2017.8168117)
- [arXiv](https://arxiv.org/abs/1709.00611)

### Monaural singing-voice separation with recurrent mask inference

**Stylianos Ioannis Mimilakis, Konstantinos Drossos, João F. Santos, Gerald Schuller, Tuomas Virtanen, and Yoshua Bengio,  
“Monaural Singing Voice Separation with Skip-Filtering Connections and Recurrent Inference of Time-Frequency Mask,”  
IEEE ICASSP, 2018.**

Extends the skip-filtering approach with recurrent mask inference and learned denoising.

- [DOI](https://doi.org/10.1109/ICASSP.2018.8461822)
- [arXiv](https://arxiv.org/abs/1711.01437)

### Unsupervised interpretable representation learning for singing-voice separation

**Stylianos I. Mimilakis, Konstantinos Drossos, and Gerald Schuller,  
“Unsupervised Interpretable Representation Learning for Singing Voice Separation,”  
EUSIPCO, 2020.**

Introduces interpretable unsupervised representations learned directly from waveform signals.

- [Paper / author page](https://kdrossos.net/download.php?fen=publications%2Fpublications_0047_1536_1_en.pdf)
- [Support material on Zenodo](https://zenodo.org/record/3695332)

---

## 4. Low-delay multichannel source separation and Random Directions

### Random Directions for stereo audio source separation

**Oleg Golokolenko and Gerald Schuller,  
“The Method of Random Directions Optimization for Stereo Audio Source Separation,”  
INTERSPEECH, 2020.**

Introduces Random Directions optimization for low-complexity time-domain source separation.

- [ISCA Archive](https://www.isca-archive.org/interspeech_2020/golokolenko20_interspeech.html)
- [DOI](https://doi.org/10.21437/Interspeech.2020-1409)

### Low-latency time-domain multichannel source separation

**Gerald Schuller,  
“Low Latency Time Domain Multichannel Speech and Music Source Separation,”  
55th Asilomar Conference on Signals, Systems, and Computers, 2021.**

Extends the low-delay Random Directions approach to multichannel speech and music source separation.

- [DOI](https://doi.org/10.1109/IEEECONF53345.2021.9723106)
- [arXiv](https://arxiv.org/abs/2204.05609)
- [Demo repository](https://github.com/TUIlmenauAMS/LowDelayMultichannelSourceSeparation_Random-Directions_Demo)

### Fast black-box optimizers for low-delay audio source separation

**Gerald Schuller,  
“Fast Black-Box Optimizers for Low Delay Audio Source Separation,”  
HSCMA 2024 / SANE 2024.**

Compares derivative-free / zeroth-order optimizers for source separation and recurrent-neural-network applications, including Random Directions.

- [Paper, poster, software, and experiments](https://github.com/TUIlmenauAMS/BlackBoxOptimizerSPcomparison)
- [HSCMA 2024 program](https://sites.google.com/view/hscma2024)
- [SANE 2024](https://www.saneworkshop.org/sane2024/)

---

## 5. Perceptual loss functions and timbre

### Differentiable psychoacoustic loss

**Gerald Schuller and Muhammad Imran,  
“A Novel Perceptual Loss Function for Audio and Music Quality Differentiable in PyTorch,”  
58th Asilomar Conference on Signals, Systems, and Computers, 2024.**

A differentiable loss based on a psychoacoustic masking model, intended for audio quality assessment and neural-network training/fine-tuning.

- [DOI](https://doi.org/10.1109/IEEECONF60004.2024.10943044)
- [Code and examples](https://github.com/TUIlmenauAMS/PsychoacousticLoss)

### Instrumental timbre transfer

**Lin Ye, Gerald Schuller, and Muhammad Imran,  
“Instrumental Timbre Transfer Based on Disentangled Representation of Timbre and Pitch,”  
58th Asilomar Conference on Signals, Systems, and Computers, 2024.**

Uses a disentangled representation of pitch and timbre for many-to-many instrumental timbre transfer.

- [DOI](https://doi.org/10.1109/IEEECONF60004.2024.10943019)
- [Code and supporting material](https://github.com/TUIlmenauAMS/timbre-transfer)

---

## 6. Neural room-acoustics prediction

### Predicting energy-decay curves from room geometry

**Muhammad Imran and Gerald Schuller,  
“Deep Learning-Based Prediction of Energy Decay Curves from Room Geometry and Material Properties,” 2025.**

Predicts energy-decay curves (EDCs) directly from room geometry, source/receiver position, and frequency-dependent material absorption.

- [arXiv](https://arxiv.org/abs/2509.24769)

### Room impulse response prediction and perceptual validation

**Muhammad Imran and Gerald Schuller,  
“Room Impulse Response Prediction with Neural Networks: From Energy Decay Curves to Perceptual Validation,” 2025.**

Extends EDC prediction to room-impulse-response reconstruction and perceptual validation.

- [arXiv](https://arxiv.org/abs/2509.24834)

### From Numbers to Perception: Energy Decay Curves Prediction

**Muhammad Imran and Gerald Schuller,  
“From Numbers to Perception, Energy Decay Curves Prediction,”  
DAGA 2026, Dresden.**

A newer multi-band EDC-prediction approach with reduced model complexity and a physically motivated loss.

- [DAGA paper / DOI](https://doi.org/10.71568/daga2026.109)
- [arXiv](https://arxiv.org/abs/2605.20968)

---

## Suggested onboarding reading order

For a new member of the AMS group, a practical order is:

1. **Relevant textbook chapters** in _Multirate Signal Processing with Examples in Python_ and/or _Filter Banks and Audio Coding_.
2. **Schuller & Smith (1996)** and **Schuller & Karp (2000)** for the filter-bank foundation.
3. **Schnell et al. (2007)** for the link to Enhanced Low Delay AAC.
4. **Mimilakis et al. (2017/2018)** for deep-learning-based singing-voice separation.
5. **Golokolenko & Schuller (2020)** and **Schuller (2021)** for Random Directions and low-delay source separation.
6. **Schuller & Imran (2024)** for psychoacoustic loss functions.
7. **Imran & Schuller (2025/2026)** for current neural room-acoustics work.

---

_Last updated: August 2026._
