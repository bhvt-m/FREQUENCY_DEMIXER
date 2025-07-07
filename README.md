# Frequency De-mixer: Unwanted Solo

## Overview
This project demonstrates audio frequency analysis and filtering techniques to remove unwanted piccolo frequencies from a music track while preserving overall sound quality. Using frequency domain analysis and targeted band-stop filtering, the project cleans the audio for enhanced clarity.

## Contents
- **Frequency_De-mixer.ipynb**: Jupyter/Colab notebook containing:
  - Audio file upload and inspection
  - Power Spectral Density (PSD) analysis
  - Spectrogram visualization
  - Bode plots and Pole-Zero plots for filter analysis
  - Multi-band band-stop filtering for unwanted frequency removal
  - Export of cleaned audio
- **REPORT_ON_Frequency_De-mixer.pdf**: Detailed lab report with:
  - Theory and background on audio frequency analysis
  - Implementation steps with analysis and figures
  - Observations and conclusions
  - What If? analysis for alternative methods
- **result_audio/**: Cleaned audio files for reference.
- **result_figures/**: Spectrograms, PSD plots, and pole-zero diagrams.

## Requirements
- Python 3.x
- Libraries:
  - `numpy`
  - `scipy`
  - `matplotlib`
  - `librosa`
  - `IPython.display` (for audio playback in notebooks)
- Recommended: Google Colab for smooth execution.

## Running the Notebook
1. Open `Frequency_De-mixer.ipynb` in Google Colab.
2. Upload your input audio file when prompted, or use the provided test file.
3. Run through the cells to:
   - Visualize PSD and spectrogram to identify unwanted frequency bands.
   - Analyze Bode and pole-zero plots to understand filter design.
   - Apply targeted band-stop filters to remove piccolo frequencies.
   - Listen to and export the cleaned audio.
4. Compare before/after spectrograms to confirm effectiveness.

## Results
- Cleaned audio preserving musical quality with reduced piccolo interference.
- Before/after spectrograms showing effective removal of targeted frequencies.
- Plots demonstrating filter design and implementation.

## License
This project is for **educational and demonstration purposes only.**

---

