# Compressor_Fault_Detection_App
A MATLAB App Designer application that uses a trained SVM model  to classify air compressor faults from audio recordings.

# Compressor Fault Detection App
A MATLAB App Designer application that uses a trained SVM model 
to classify air compressor faults from audio recordings.

## Features
- Audio waveform visualisation
- Real-time fault classification (Bearing, Piston, LOV, LIV etc.)
- Extracted feature display (RMS Energy, Spectral Centroid, Spectral Energy)
- Traffic light fault indicator system

## How to Run
1. Open CompressorFaultApp.mlapp in MATLAB App Designer
2. Click Run
3. Load a .wav file from the UnknownRecordings folder
4. Click Classify

## Model Performance
- SVM model achieving 90.4% test accuracy across 8 fault classes
- Trained on 1776 audio recordings
