# IsNyquistSatisfied
Confirm if a proposed sampling rate is high enough to avoid aliasing when sampling.

Function written by Eleni Christoforidou in MATLAB R2022b.

This function confirms if a proposed sampling rate, Fs, is high enough to avoid aliasing when sampling a signal that is known to contain no frequency greater than fmax. The function takes as input fmax and Fs, and it outputs a logical value of true if aliasing will be avoided and false otherwise. A second output, Fs_min, contains the Nyquist sampling rate.
