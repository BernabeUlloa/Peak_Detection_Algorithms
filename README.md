# Peak_Detection_Algorithms
Accurate detection of R-peak is essential for the diagnosis of arrhythmias such as premature atrial contraction, tachycardia and bradycardia. However, effective detection of R-peak remains difficult in a dynamic and noisy environment due to variable waveform morphology. This is even more difficult when the ECG signal is affected by noise. That is why it is important to choose a proper algorithm for the type of signal to be processed.
## Pan and Tompkins
The Pan and Tompkins algorithm [1] is a method based on low complexity thresholds, so it is relatively simple and has a low computational cost, adaptable, accurate and reliable, making it one of the most widely used. The algorithm is sensitive to inter- and intra-subject variability such as amplitude and shape of R peaks. Sensitive to changes in heart rate. Need for parameter adjustment.
## Peak algorithm
The Peaks algorithm [2] is good for R-peak detection in portable ECG devices as it is a thresholding method considered to be one of the most computationally efficient. It can be classified as pattern recognition. It is also sensitive to inter- and intra-subject variability and changes in heart rate, however this algorithm is much more affected by signal quality.
## Peak + Wavelet algorithm
Wavelet-based Multiresolution Analysis is applied to enhance ECG signal representation by filtering the frequency range of interest for interferences such as baseline drift and motion artifacts as all noises considerably influence the thresholding operation. The adaptive thresholding of the Peak algorithm excludes false R peaks in the reconstructed signal. Attempts to improve signal quality but incorrect selection of the filter or filter parameters may adversely affect the quality and accuracy of the ECG signal processing.
## Reference
>[1] Data available in a publicly accessible repository. The data presented in this work are openly available in Physiobank ATM: https://archive.physionet.org/cgi-bin/atm/ATM (accessed on 1 July 2023).
>[2] PAN.J, TOMPKINS. W.J,"A Real-Time QRS Detection Algorithm" IEEE TRANSACTIONS ON BIOMEDICAL ENGINEERING, VOL. BME-32, NO. 3, MARCH 1985.
>[3] Pino E, Ohno-Machado L, Wiechmann E, Curtis D. "Real-time ECG algorithms for ambulatory patient monitoring". AMIA Annu Symp Proc. 2005;2005:604-8. PMID: 16779111; PMCID: PMC1560458.
