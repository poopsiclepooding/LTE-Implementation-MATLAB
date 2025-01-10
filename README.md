# LTE PSS And SSS MatLab Implementation

Code contains PSS and SSS signal generation, applying noise and channel effects and detecting PSS and SSS in LTE frame.
Channel Effects added are:
1. Gaussian Random Noise
2. Rayleigh Fading
3. Timing Offset
4. Frequency Offset

Using PSS and SSS timing offset is corrected and using cyclic prefix correlation frequency offset is corrected.
Detection of PSS and SSS is performed after it.

Reference : 
1. [PSS](https://www.sharetechnote.com/html/Handbook_LTE_PSS.html)
2. [SSS](https://www.sharetechnote.com/html/Handbook_LTE_SSS.html)

PSS and SSS Making and Detection :
```
PSSandSSS.mlx
```
