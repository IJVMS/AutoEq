# Shure SRH840
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-69**.
```
GraphicEQ: 10 -84; 20 6.9; 22 5.4; 23 4.7; 25 3.6; 26 3.0; 28 2.1; 30 1.3; 32 0.7; 35 -0.1; 37 -0.7; 40 -1.6; 42 -2.3; 45 -3.2; 49 -3.9; 52 -4.0; 56 -3.8; 59 -3.6; 64 -3.5; 68 -4.0; 73 -4.9; 78 -5.8; 83 -6.5; 89 -7.2; 95 -7.7; 102 -8.2; 109 -8.3; 117 -8.5; 125 -8.5; 134 -8.5; 143 -8.4; 153 -7.9; 164 -6.9; 175 -6.7; 188 -6.1; 201 -5.2; 215 -4.6; 230 -4.1; 246 -4.0; 263 -3.7; 282 -3.8; 301 -5.9; 323 -6.0; 345 -5.2; 369 -4.9; 395 -4.5; 423 -4.3; 452 -4.2; 484 -4.2; 518 -3.9; 554 -3.2; 593 -2.4; 635 -1.9; 679 -1.7; 726 -1.3; 777 -0.6; 832 -0.3; 890 0.0; 952 0.1; 1019 -0.0; 1090 0.1; 1167 0.1; 1248 0.1; 1336 -0.0; 1429 -0.6; 1529 -1.2; 1636 -2.1; 1751 -3.1; 1873 -3.7; 2004 -4.2; 2145 -4.6; 2295 -4.5; 2455 -4.2; 2627 -3.2; 2811 -2.8; 3008 -1.9; 3219 -1.3; 3444 -0.8; 3685 0.2; 3943 1.7; 4219 2.1; 4514 0.8; 4830 0.6; 5168 1.6; 5530 3.2; 5917 3.8; 6331 3.3; 6775 3.0; 7249 1.3; 7756 -2.5; 8299 -7.4; 8880 -10.9; 9502 -9.9; 10167 -3.1; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 6.9; 22 5.4; 23 4.7; 25 3.6; 26 3.0; 28 2.1; 30 1.3; 32 0.7; 35 -0.1; 37 -0.7; 40 -1.6; 42 -2.3; 45 -3.2; 49 -3.9; 52 -4.0; 56 -3.8; 59 -3.6; 64 -3.5; 68 -4.0; 73 -4.9; 78 -5.8; 83 -6.5; 89 -7.2; 95 -7.7; 102 -8.2; 109 -8.3; 117 -8.5; 125 -8.5; 134 -8.5; 143 -8.4; 153 -7.9; 164 -6.9; 175 -6.7; 188 -6.1; 201 -5.2; 215 -4.6; 230 -4.1; 246 -4.0; 263 -3.7; 282 -3.8; 301 -5.9; 323 -6.0; 345 -5.2; 369 -4.9; 395 -4.5; 423 -4.3; 452 -4.2; 484 -4.2; 518 -3.9; 554 -3.2; 593 -2.4; 635 -1.9; 679 -1.7; 726 -1.3; 777 -0.6; 832 -0.3; 890 0.0; 952 0.1; 1019 -0.0; 1090 0.1; 1167 0.1; 1248 0.1; 1336 -0.0; 1429 -0.6; 1529 -1.2; 1636 -2.1; 1751 -3.1; 1873 -3.7; 2004 -4.2; 2145 -4.6; 2295 -4.5; 2455 -4.2; 2627 -3.2; 2811 -2.8; 3008 -1.9; 3219 -1.3; 3444 -0.8; 3685 0.2; 3943 1.7; 4219 2.1; 4514 0.8; 4830 0.6; 5168 1.6; 5530 3.2; 5917 3.8; 6331 3.3; 6775 3.0; 7249 1.3; 7756 -2.5; 8299 -7.4; 8880 -10.9; 9502 -9.9; 10167 -3.1; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
Copy: L=-6.9dB*l, R=-6.9dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Innerfidelity%202017/headphoncecom/onear/Shure%20SRH840/Shure%20SRH840.png)