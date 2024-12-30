# Electrical-Stethescope
Ahmet Tüfek-Ertuğrul Uysal


# Signal Processing App

This is a MATLAB App Designer project for real-time signal processing and analysis. The app receives data from a serial port, applies various filters, performs FFT analysis, and calculates BPM (Beats Per Minute). It provides a user-friendly interface for visualizing raw and filtered signals, as well as their frequency spectra.

## Features
- **Real-time data acquisition** from a serial port.
- **Signal processing** using Butterworth filters (high-pass and band-pass).
- **FFT Analysis** for frequency-domain visualization.
- **BPM Calculation** based on detected peaks in the signal.
- **Interactive GUI** to adjust filter parameters and start/stop data processing.

---

## User Interface Overview
The app interface includes the following components:
1. **Raw Signal Plot**: Displays the raw data collected from the serial port.
2. **Filtered Signal Plot**: Displays the filtered version of the signal.
3. **FFT of Raw Signal**: Frequency spectrum of the raw data.
4. **FFT of Filtered Signal**: Frequency spectrum of the filtered data.
5. **Parameter Controls**:
   - `High pass fc`: Adjust the cutoff frequency for the high-pass filter.
   - `Low pass fc`: Adjust the cutoff frequency for the low-pass filter.
   - `Edit Order`: Modify the filter order.
6. **Start/Stop Buttons**: Control the data acquisition process.
7. **BPM Display**: Shows the calculated Beats Per Minute (BPM).

---

## Installation and Setup

### Prerequisites
- MATLAB R2021b or later (with App Designer support).
- A compatible serial device for data acquisition.

### Steps to Use the App
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/SignalProcessingApp.git
   cd SignalProcessingApp
