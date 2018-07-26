# Sennheiser HD25-SP
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 2.8; 22 2.1; 23 1.7; 25 1.1; 26 0.8; 28 0.3; 30 -0.2; 32 -0.6; 35 -0.8; 37 -0.8; 40 -1.1; 42 -1.6; 45 -2.5; 49 -3.1; 52 -3.3; 56 -3.5; 59 -3.6; 64 -3.6; 68 -3.8; 73 -3.9; 78 -3.6; 83 -3.2; 89 -3.3; 95 -4.7; 102 -6.1; 109 -6.7; 117 -6.8; 125 -6.9; 134 -6.5; 143 -6.1; 153 -5.5; 164 -5.3; 175 -6.1; 188 -6.7; 201 -6.8; 215 -6.4; 230 -5.9; 246 -5.1; 263 -4.4; 282 -3.8; 301 -2.9; 323 -1.7; 345 -0.6; 369 0.1; 395 0.8; 423 1.2; 452 1.2; 484 1.2; 518 1.3; 554 1.3; 593 1.5; 635 1.4; 679 1.1; 726 1.0; 777 1.0; 832 0.7; 890 0.5; 952 0.2; 1019 -0.1; 1090 -0.4; 1167 -0.8; 1248 -1.3; 1336 -2.1; 1429 -2.7; 1529 -3.3; 1636 -4.1; 1751 -4.6; 1873 -4.7; 2004 -4.7; 2145 -4.3; 2295 -3.8; 2455 -3.5; 2627 -3.1; 2811 -1.8; 3008 -0.0; 3219 0.6; 3444 1.1; 3685 1.4; 3943 0.7; 4219 0.7; 4514 0.8; 4830 0.6; 5168 2.0; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 -4.2; 8880 -9.0; 9502 -8.3; 10167 -4.7; 10879 -1.5; 11640 -0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 2.8; 22 2.1; 23 1.7; 25 1.1; 26 0.8; 28 0.3; 30 -0.2; 32 -0.6; 35 -0.8; 37 -0.8; 40 -1.1; 42 -1.6; 45 -2.5; 49 -3.1; 52 -3.3; 56 -3.5; 59 -3.6; 64 -3.6; 68 -3.8; 73 -3.9; 78 -3.6; 83 -3.2; 89 -3.3; 95 -4.7; 102 -6.1; 109 -6.7; 117 -6.8; 125 -6.9; 134 -6.5; 143 -6.1; 153 -5.5; 164 -5.3; 175 -6.1; 188 -6.7; 201 -6.8; 215 -6.4; 230 -5.9; 246 -5.1; 263 -4.4; 282 -3.8; 301 -2.9; 323 -1.7; 345 -0.6; 369 0.1; 395 0.8; 423 1.2; 452 1.2; 484 1.2; 518 1.3; 554 1.3; 593 1.5; 635 1.4; 679 1.1; 726 1.0; 777 1.0; 832 0.7; 890 0.5; 952 0.2; 1019 -0.1; 1090 -0.4; 1167 -0.8; 1248 -1.3; 1336 -2.1; 1429 -2.7; 1529 -3.3; 1636 -4.1; 1751 -4.6; 1873 -4.7; 2004 -4.7; 2145 -4.3; 2295 -3.8; 2455 -3.5; 2627 -3.1; 2811 -1.8; 3008 -0.0; 3219 0.6; 3444 1.1; 3685 1.4; 3943 0.7; 4219 0.7; 4514 0.8; 4830 0.6; 5168 2.0; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 -4.2; 8880 -9.0; 9502 -8.3; 10167 -4.7; 10879 -1.5; 11640 -0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/SBAF-Serious/headphoncecom/onear/Sennheiser%20HD25-SP/Sennheiser%20HD25-SP.png)