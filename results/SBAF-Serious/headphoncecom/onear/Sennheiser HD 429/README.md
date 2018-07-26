# Sennheiser HD 429
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 -1.2; 22 -1.4; 23 -1.5; 25 -1.6; 26 -1.6; 28 -1.7; 30 -1.8; 32 -1.8; 35 -1.9; 37 -1.9; 40 -1.9; 42 -1.9; 45 -1.9; 49 -1.8; 52 -1.7; 56 -1.6; 59 -1.5; 64 -1.4; 68 -1.2; 73 -0.9; 78 -0.5; 83 -0.1; 89 0.7; 95 1.7; 102 1.4; 109 -0.5; 117 -1.3; 125 -2.0; 134 -2.4; 143 -2.6; 153 -2.2; 164 -1.9; 175 -2.5; 188 -2.4; 201 -2.3; 215 -2.4; 230 -2.2; 246 -1.8; 263 -1.1; 282 -0.2; 301 0.3; 323 0.5; 345 0.8; 369 0.7; 395 0.4; 423 0.4; 452 0.2; 484 -0.2; 518 -0.6; 554 -0.6; 593 -0.5; 635 -0.5; 679 -0.9; 726 -0.9; 777 -0.7; 832 -0.5; 890 -0.4; 952 -0.1; 1019 -0.1; 1090 -0.4; 1167 -1.0; 1248 -0.9; 1336 -0.4; 1429 -1.0; 1529 -1.2; 1636 -1.2; 1751 -0.8; 1873 0.0; 2004 0.7; 2145 1.8; 2295 3.0; 2455 4.1; 2627 3.8; 2811 4.3; 3008 4.9; 3219 5.1; 3444 5.1; 3685 5.0; 3943 6.0; 4219 6.0; 4514 6.0; 4830 6.0; 5168 6.0; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 -1.2; 22 -1.4; 23 -1.5; 25 -1.6; 26 -1.6; 28 -1.7; 30 -1.8; 32 -1.8; 35 -1.9; 37 -1.9; 40 -1.9; 42 -1.9; 45 -1.9; 49 -1.8; 52 -1.7; 56 -1.6; 59 -1.5; 64 -1.4; 68 -1.2; 73 -0.9; 78 -0.5; 83 -0.1; 89 0.7; 95 1.7; 102 1.4; 109 -0.5; 117 -1.3; 125 -2.0; 134 -2.4; 143 -2.6; 153 -2.2; 164 -1.9; 175 -2.5; 188 -2.4; 201 -2.3; 215 -2.4; 230 -2.2; 246 -1.8; 263 -1.1; 282 -0.2; 301 0.3; 323 0.5; 345 0.8; 369 0.7; 395 0.4; 423 0.4; 452 0.2; 484 -0.2; 518 -0.6; 554 -0.6; 593 -0.5; 635 -0.5; 679 -0.9; 726 -0.9; 777 -0.7; 832 -0.5; 890 -0.4; 952 -0.1; 1019 -0.1; 1090 -0.4; 1167 -1.0; 1248 -0.9; 1336 -0.4; 1429 -1.0; 1529 -1.2; 1636 -1.2; 1751 -0.8; 1873 0.0; 2004 0.7; 2145 1.8; 2295 3.0; 2455 4.1; 2627 3.8; 2811 4.3; 3008 4.9; 3219 5.1; 3444 5.1; 3685 5.0; 3943 6.0; 4219 6.0; 4514 6.0; 4830 6.0; 5168 6.0; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/SBAF-Serious/headphoncecom/onear/Sennheiser%20HD%20429/Sennheiser%20HD%20429.png)