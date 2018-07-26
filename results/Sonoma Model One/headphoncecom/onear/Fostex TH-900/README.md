# Fostex TH-900
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-50**.
```
GraphicEQ: 10 -84; 20 -2.0; 22 -2.2; 23 -2.3; 25 -2.4; 26 -2.5; 28 -2.5; 30 -2.5; 32 -2.6; 35 -2.6; 37 -2.7; 40 -2.7; 42 -2.8; 45 -2.8; 49 -2.4; 52 -2.1; 56 -2.4; 59 -3.0; 64 -3.3; 68 -3.0; 73 -2.4; 78 -2.1; 83 -2.1; 89 -2.4; 95 -3.2; 102 -3.9; 109 -4.2; 117 -4.6; 125 -5.2; 134 -5.7; 143 -6.0; 153 -6.0; 164 -5.8; 175 -5.6; 188 -5.6; 201 -5.3; 215 -5.1; 230 -4.8; 246 -4.6; 263 -4.3; 282 -3.8; 301 -3.4; 323 -2.9; 345 -2.3; 369 -1.8; 395 -1.1; 423 -0.2; 452 1.0; 484 2.3; 518 3.6; 554 4.7; 593 4.8; 635 3.8; 679 2.8; 726 3.2; 777 3.4; 832 1.9; 890 0.9; 952 0.3; 1019 0.1; 1090 0.5; 1167 1.3; 1248 2.1; 1336 2.9; 1429 3.2; 1529 2.9; 1636 1.9; 1751 0.8; 1873 0.6; 2004 2.1; 2145 4.0; 2295 4.5; 2455 3.6; 2627 3.6; 2811 2.9; 3008 2.6; 3219 2.6; 3444 2.7; 3685 2.6; 3943 2.4; 4219 0.7; 4514 -0.6; 4830 -1.2; 5168 -2.1; 5530 -4.6; 5917 -6.5; 6331 -4.9; 6775 -3.5; 7249 -3.2; 7756 -2.9; 8299 -1.3; 8880 -0.0; 9502 0.0; 10167 -1.8; 10879 -5.3; 11640 -5.4; 12455 -1.8; 13327 0.0; 14260 -1.1; 15258 -5.3; 16326 -7.5; 17469 -6.6; 18692 -6.0; 20000 -8.1
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 -2.0; 22 -2.2; 23 -2.3; 25 -2.4; 26 -2.5; 28 -2.5; 30 -2.5; 32 -2.6; 35 -2.6; 37 -2.7; 40 -2.7; 42 -2.8; 45 -2.8; 49 -2.4; 52 -2.1; 56 -2.4; 59 -3.0; 64 -3.3; 68 -3.0; 73 -2.4; 78 -2.1; 83 -2.1; 89 -2.4; 95 -3.2; 102 -3.9; 109 -4.2; 117 -4.6; 125 -5.2; 134 -5.7; 143 -6.0; 153 -6.0; 164 -5.8; 175 -5.6; 188 -5.6; 201 -5.3; 215 -5.1; 230 -4.8; 246 -4.6; 263 -4.3; 282 -3.8; 301 -3.4; 323 -2.9; 345 -2.3; 369 -1.8; 395 -1.1; 423 -0.2; 452 1.0; 484 2.3; 518 3.6; 554 4.7; 593 4.8; 635 3.8; 679 2.8; 726 3.2; 777 3.4; 832 1.9; 890 0.9; 952 0.3; 1019 0.1; 1090 0.5; 1167 1.3; 1248 2.1; 1336 2.9; 1429 3.2; 1529 2.9; 1636 1.9; 1751 0.8; 1873 0.6; 2004 2.1; 2145 4.0; 2295 4.5; 2455 3.6; 2627 3.6; 2811 2.9; 3008 2.6; 3219 2.6; 3444 2.7; 3685 2.6; 3943 2.4; 4219 0.7; 4514 -0.6; 4830 -1.2; 5168 -2.1; 5530 -4.6; 5917 -6.5; 6331 -4.9; 6775 -3.5; 7249 -3.2; 7756 -2.9; 8299 -1.3; 8880 -0.0; 9502 0.0; 10167 -1.8; 10879 -5.3; 11640 -5.4; 12455 -1.8; 13327 0.0; 14260 -1.1; 15258 -5.3; 16326 -7.5; 17469 -6.6; 18692 -6.0; 20000 -8.1
Copy: L=-5.0dB*l, R=-5.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Sonoma%20Model%20One/headphoncecom/onear/Fostex%20TH-900/Fostex%20TH-900.png)