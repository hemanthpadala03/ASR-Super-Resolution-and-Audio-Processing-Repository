# ASR Super-Resolution and Audio Processing Repository

This repository contains notebooks and scripts for exploring and implementing audio super-resolution techniques, focusing on improving Automatic Speech Recognition (ASR) performance. The project explores various methods including Conformer models, interpolation techniques, and comparisons of output results.

## Repository Files

### 1. **`all-models.ipynb`**
This notebook contains the implementation of multiple models for audio super-resolution tasks. It includes the training and evaluation pipelines for different neural network architectures designed for upsampling low-frequency audio to higher frequencies suitable for ASR tasks.

### 2. **`dsp-nemo-conformer.ipynb`**
This notebook focuses on applying Conformer models within the context of Digital Signal Processing (DSP) for ASR. The notebook provides detailed steps on how the Conformer architecture is used for improving audio resolution and recognition accuracy.

### 3. **`interpolation-methods.ipynb`**
In this notebook, various interpolation methods are explored to upscale low-sampling rate audio. The methods are tested in combination with ASR models to assess their impact on performance and accuracy.

### 4. **`outputs-comp.ipynb`**
This notebook compares the outputs of different models and interpolation methods used in the previous notebooks. It includes evaluation metrics and visualizations to highlight performance differences.

---

## Installation

To run these notebooks, you'll need the following Python libraries:

- `torch`
- `torchaudio`
- `numpy`
- `matplotlib`
- `pandas`
- `librosa`
- `nemo_toolkit` (for Nemo-based models)
- `scipy`

You can install these libraries using `pip`:

```bash
pip install torch torchaudio numpy matplotlib pandas librosa nemo_toolkit scipy
