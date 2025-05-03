## LSTM-SCCM: Long Short-Term Memory Stream Cruise Control Method for Automated Drift Detection and Adaptation in Online Data Streams
LSTM-SCCM is an adaptive framework designed for robust online regression under concept drift. 

**LSTM-SCCM Objectives:**
1. Drift Detection
2. Magnitude Quantification & Categorization.
3. Short-term Adjustment Mechanism – For Hyperparameter Tuning.
4. Long-term Retraining – Deep adjustment if deemed necessary.


**Contributions:**
LSTM-SCCM: A Novel Framework for Online Drift Detection and Adaptation in Online Regression

1. **In-Memory Efficiency:** Proactively detects and addresses drift using real-time, in-memory processing.
2. **Holistic Drift Handling:** Integrates drift detection, magnitude quantification, adaptive hyperparameter tuning (SCCM), and long-term calibration for robust adaptability.
3. **Large Scale:** Operates on performance KPIs without assuming data distribution—ideal for high-dimensional, large-scale datasets.
4. **Dynamic Thresholding:** Accommodates diverse KPIs and adapts to evolving data distributions and variations.
5. **Plug-and-Play Architecture:** Seamlessly integrates with various online models for flexible drift detection and adaptation.

## Citation & Authorship

This repository is maintained by Mohammad Abu-Shaira, University of North Texas.

If you use this code, please cite the following:

Shaira et al, LSTM-SCCM: Long Short-Term Memory Stream Cruise Control Method for Adaptive Online Regression under Concept Drift, 2025.

BibTeX:
@misc{LSTM_SCCM_GIT,
  author       = {Mohammad Abu-Shaira and Weishi Shi},
  title        = {LSTM-SCCM: Long Short-Term Memory Stream Cruise Control Method},
  year         = {2025},
  howpublished = {\url{https://github.com/mabushaera/LSTM-SCCM}},
  note         = {GitHub repository}
}
