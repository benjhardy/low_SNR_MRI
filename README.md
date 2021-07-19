# low_SNR_MRI
## Explanation 
SNR is typically measured with magnitude images of complex data. 
This notebook demonstrates that noise will be underestimated if considered to be normally distributed when SNR is relatively low. 
although the noise of the real and imaginary parts of the noise is normally distributed, the magnitude of the image's noise will be rayleigh in it's distribution.
Therefore, when calculating SNR of a magnitude image, there is a correction factor that must be applied.
###
##
## Benjamin M. Hardy 
## 7-19-2021
## benjamin.m.hardy (AT) vanderbilt (dot) edu
### Key References:
### 1. https://web.stanford.edu/class/rad229/Notes/Lecture-07/Rad229_2020_Lecture07A_SingleChannelSNR.pdf
### 2. https://onlinelibrary.wiley.com/doi/abs/10.1002/mrm.1910360327?sid=nlm%3Apubmed
### 3. https://aapm.onlinelibrary.wiley.com/doi/abs/10.1118/1.595711
### 4. Erratum for 3, https://aapm.onlinelibrary.wiley.com/doi/10.1118/1.595860
