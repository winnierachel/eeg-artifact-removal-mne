# eeg-artifact-removal-mne
EEG Eye Blink Artifact Removal using ICA (MNE-Python)
# EEG Artifact Removal using ICA (MNE)

This project demonstrates removal of eye-blink artifacts from EEG signals using Independent Component Analysis (ICA).

## Steps:
1. Load EEG data
2. Filter signal (1–40 Hz)
3. Apply ICA
4. Detect eye-blink components using EOG
5. Remove artifacts
6. Compare before and after signals

## Results:
- Reduced low-frequency noise
- Improved EEG signal quality

## Tools:
- Python
- MNE-Python
- NumPy
- Matplotlib
