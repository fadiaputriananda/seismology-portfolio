# Earthquake Waveform Analysis using ObsPy
The workflow includes:
- Retrieving earthquake event catalogs
- Downloading seismic waveform data
- Signal filtering and preprocessing
- Waveform visualization
- Basic waveform interpretation

## Tools and Libraries
- Python
- ObsPy
- Matplotlib
- NumPy
- Jupyter Notebook

## Workflow

### 1. Retrieve Earthquake Catalog
Earthquake event catalogs were retrieved using the IRIS FDSN web service through ObsPy.

### 2. Download Waveform Data
Waveform data were downloaded from seismic stations located closer to Indonesia to improve signal visibility.

### 3. Signal Processing
Bandpass filtering was applied to reduce noise and improve waveform clarity.

### 4. Visualization
Raw and filtered waveforms were visualized using ObsPy and Matplotlib.

## Example Visualization
<img width="3078" height="1232" alt="waveform_example" src="https://github.com/user-attachments/assets/2fa602b8-e3b3-4c4f-91a4-5b4b4008bd23" />

## Key Learning Points
- Basic seismic waveform processing workflow
- Seismic signal filtering
- Earthquake metadata extraction
- Waveform visualization using Python
- Introduction to computational seismology workflows

## Future Improvements
Possible future developments include:
- Phase picking
- Event detection
- Spectral analysis
- SeisBench integration
- Indonesian seismicity analysis

## Data Source
Seismic waveform and earthquake catalog data were retrieved from the IRIS FDSN web service using ObsPy.

## Author
Fadia Putri Ananda
