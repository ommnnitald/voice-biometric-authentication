# voice-biometric-authentication
# Speaker Verification Project

This project aims to perform speaker verification using recorded and re-recorded audio words. It compares the MFCC (Mel-frequency cepstral coefficients) features of the two audio clips using dynamic time warping (DTW) to verify whether the speaker matches or not.

## Prerequisites

Before running the project, you need to install the following Python libraries:

- NumPy
- SciPy
- Matplotlib
- Librosa

You can install these libraries using the following command:

```bash
pip install numpy scipy matplotlib librosa
Project Structure

The project contains the following files and directories:

    README.md: This file provides an overview of the project and instructions on how to use it.
    main.ipynb: The Jupyter Notebook file containing the code for speaker verification.
    recordPath/: A directory containing the recorded audio words in WAV format.
    RerecordPath/: A directory containing the re-recorded audio words in WAV format.
