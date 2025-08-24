# ASR Super-Resolution and Audio Processing Repository

This repository contains notebooks and scripts for exploring and implementing audio super-resolution techniques aimed at improving Automatic Speech Recognition (ASR) performance. The project focuses on upsampling low-sampling-rate audio signals and enhancing speech representations using neural networks, interpolation methods, and bandwidth extension approaches.

---

## Project Overview

- **Input:** Low-resolution audio spectrograms at 2 kHz sampling rate  
- **Output:** Bandwidth-extended audio spectrograms at 16 kHz sampling rate to enhance ASR accuracy  
- **Core Architecture:** Custom neural network models including Conformer-based architectures designed for audio super-resolution  
- **Evaluation:** Comparison of learned models and classical interpolation techniques for audio upsampling effectiveness  

---

## Repository Structure

### 1. `all-models.ipynb`  
Implementation of multiple audio super-resolution models covering training and evaluation pipelines to convert low-frequency audio to higher frequency representations.

### 2. `dsp-nemo-conformer.ipynb`  
Application of Conformer models integrated with Digital Signal Processing (DSP) for improved ASR performance via audio enhancement.

### 3. `interpolation-methods.ipynb`  
Exploration of various interpolation algorithms for audio upsampling, benchmarking their impact on ASR.

### 4. `outputs-comp.ipynb`  
Comparison of outputs from different models and methods, supported by quantitative metrics and visualizations.

---

## Output Visualizations

- **Input Spectrogram (2 kHz sampling rate):**  
  ![Input Spectrogram](Images/2k%20Input%20spectrogram.png)  

- **Bandwidth-Extended Output Spectrogram (16 kHz sampling rate):**  
  ![16K Upsampled Spectrogram](Images/16K%20upsampled%20spectrogram.png)  

- **Model Architecture Diagram:**  
  ![Model Architecture](Images/Model%20Arch.png)  

---

## Installation

Install the necessary Python dependencies:

pip install torch torchaudio numpy matplotlib pandas librosa nemo_toolkit scipy

---

## Usage

1. Open and run the notebooks sequentially to explore data preprocessing, model training, interpolation, and output comparison.  
2. Inspect spectrogram visualizations in the `Images` folder to analyze input/output audio signals and model architecture.  
3. Use the `outputs-comp.ipynb` notebook for metric-based evaluation and visualization of super-resolution approaches.

---

## Contributing

Contributions, bug reports, and feature requests are welcome! Please feel free to open issues or submit pull requests for improvements or fixes.

---

## License

This repository is licensed under the MIT License. See the LICENSE file for details.

---

Thank you for exploring this project and your interest in advancing ASR through audio super-resolution!
