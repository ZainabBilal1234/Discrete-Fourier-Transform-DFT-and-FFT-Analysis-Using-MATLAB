Discrete Fourier Transform (DFT) and FFT Analysis

This project demonstrates the implementation and analysis of the Discrete Fourier Transform (DFT) and Fast Fourier Transform (FFT) using MATLAB. A discrete-time signal of length N = 16 is generated, and its frequency spectrum is computed using both a manually constructed DFT matrix and MATLAB’s built-in FFT function. The project validates the equivalence of DFT and FFT while highlighting the computational advantages of FFT.

The analysis explores important frequency-domain concepts such as zero-padding, spectral leakage, and windowing. Zero-padding is applied to improve spectral resolution for visualization, while signals with integer and non-integer frequencies are used to demonstrate the effects of spectral leakage. A Hamming window is then applied to reduce leakage and smooth discontinuities at signal boundaries.

The simulation generates multiple plots to compare FFT and manual DFT results, visualize the impact of zero-padding, and study leakage behavior before and after windowing. Performance comparisons between DFT and FFT are also included, showing the difference in computational complexity (O(N²) vs O(N log N)).

Technologies Used
MATLAB
Discrete Fourier Transform (DFT)
Fast Fourier Transform (FFT)
Matrix-Based Computation
Signal Processing Techniques
Hamming Windowing
Frequency Spectrum Analysis
