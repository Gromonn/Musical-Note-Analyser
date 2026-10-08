# Musical Note Analyser:

A Python-based audio analysis project that detects musical notes from a WAV file using **Fourier Transform (FFT)** and **Harmonic Product Spectrum (HPS)**.

## Features:

- Loads and normalizes WAV audio files
- Converts stereo audio to mono
- Applies FFT to convert audio from the time domain to the frequency domain
- Uses HPS to improve fundamental-frequency detection
- Maps detected frequencies to the closest musical note
- Estimates note start and end times
- Displays an audio spectrogram
- Displays the frequency spectrum

## Tools Used:

- Python
- NumPy
- SciPy
- Matplotlib
- Fourier Transform (FFT)
- Harmonic Product Spectrum (HPS)

## Project Structure:

```text
musical-note-analyser/
│
├── audio/
│   └── Voice_035.wav
│
├── src/
│   └── project.py
│
├── notebooks/
│   └── Musical_Note_Analyser.ipynb
│
├── README.md
└── requirements.txt
