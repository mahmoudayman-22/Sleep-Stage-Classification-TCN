# Sleep Stage Classification using TCN

An end-to-end signal processing and deep learning project utilizing a **Temporal Convolutional Network (TCN)** to classify sleep stages from single-channel EEG signals (**PhysioNet** dataset).

---

##  Project Overview
Automated sleep stage scoring is critical for diagnosing sleep disorders. This project processes raw EEG signals and models long-term temporal dependencies across 5 sleep stages (**Wake, N1, N2, N3, REM**) using causal and dilated convolutions.

---

##  Key Features
- **Temporal Convolutional Network (TCN):** Leveraged causal and dilated convolutions to capture sequence-based physiological pattern progression over time.
- **EEG Preprocessing:** Segmented raw signals into 30-second epochs, applied signal normalization, and filtered out physiological artifacts.
- **Comprehensive Evaluation:** Assessed temporal sequence modeling using Precision, Recall, **Macro F1-score**, and Confusion Matrices to analyze state transition accuracy.

---

##  Tech Stack & Tools
- **Framework:** PyTorch
- **Signal Processing:** SciPy, MNE, NumPy, Pandas, Matplotlib
- **Dataset:** PhysioNet Sleep EEG
- **Language:** Python

---

##  Author
**Mahmoud Ayman Zaki**
- **Email:** mahmoudayman340@gmail.com
- **GitHub:** [@mahmoudayman-22](https://github.com/mahmoudayman-22)
