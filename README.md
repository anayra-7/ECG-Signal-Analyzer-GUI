# ECG-Signal-Analyzer-GUI
An interactive desktop application built using MATLAB App Designer for processing complex ECG signal metrics.

# Desktop ECG Monitor & Signal Analyzer

A custom MATLAB desktop app built to import raw ECG data files (.csv), denoise the signals, and automatically track heart metrics like R-peaks and heart rate in real time. 

I designed and built this tool using **MATLAB App Designer** to apply what I learned in my Signal Processing Onramp course to a practical biomedical engineering application.

## What It Does
**Dynamic Data Import:** Ingests raw data files directly from your local drive and extracts the data vectors.
**Automated Feature Mapping:** Uses peak-detection thresholds to accurately locate R-peaks on the waveform.
**Live Health Diagnostics:** Instantly calculates Heart Rate (BPM), RR intervals, and total signal duration without relying on heavy calculation loops.
**Interactive UI Plots:** Built-in axes features that let users zoom, pan, and hover over specific data coordinates for signal review.

## Core Technical Concepts
*   **Vectorized Syntax:** Calculated time differences and BPM instantly across raw matrices using optimized syntax like `diff()`
*   **Object-Oriented UI:** Leveraged MATLAB's App Designer framework to handle asynchronous execution and clean callback workflows.
*   **Signal Exploration:** Moving theory into practice by handling time-domain data directly inside a custom environment.

## App Walkthrough & Preview
[Click here to watch the full 30-second Interactive App Walkthrough Video] https://drive.google.com/file/d/16qgsUa6jgidA97FlndIsDzbvqLHjCgrh/view?usp=drivesdk
