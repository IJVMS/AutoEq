# Sennheiser HD 239
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 -1.0; 22 -1.5; 23 -1.7; 25 -2.1; 26 -2.2; 28 -2.5; 30 -2.8; 32 -2.9; 35 -3.2; 37 -3.3; 40 -3.5; 42 -3.6; 45 -3.7; 49 -3.9; 52 -4.0; 56 -4.1; 59 -4.2; 64 -4.2; 68 -4.3; 73 -4.3; 78 -4.4; 83 -4.5; 89 -4.6; 95 -4.7; 102 -4.5; 109 -4.5; 117 -4.9; 125 -5.6; 134 -5.7; 143 -5.9; 153 -5.9; 164 -6.0; 175 -5.9; 188 -5.8; 201 -5.8; 215 -5.6; 230 -5.4; 246 -5.3; 263 -5.0; 282 -4.7; 301 -4.4; 323 -4.3; 345 -4.0; 369 -3.7; 395 -3.5; 423 -3.3; 452 -3.2; 484 -3.4; 518 -3.0; 554 -2.4; 593 -1.8; 635 -1.4; 679 -1.3; 726 -1.1; 777 -0.6; 832 -0.3; 890 -0.2; 952 0.1; 1019 -0.0; 1090 -0.1; 1167 -0.2; 1248 -0.4; 1336 -0.5; 1429 0.5; 1529 0.0; 1636 0.3; 1751 0.7; 1873 1.6; 2004 3.3; 2145 4.8; 2295 5.9; 2455 6.0; 2627 6.0; 2811 6.0; 3008 5.4; 3219 4.3; 3444 5.4; 3685 6.0; 3943 6.0; 4219 6.0; 4514 5.4; 4830 5.8; 5168 6.0; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 -1.0; 22 -1.5; 23 -1.7; 25 -2.1; 26 -2.2; 28 -2.5; 30 -2.8; 32 -2.9; 35 -3.2; 37 -3.3; 40 -3.5; 42 -3.6; 45 -3.7; 49 -3.9; 52 -4.0; 56 -4.1; 59 -4.2; 64 -4.2; 68 -4.3; 73 -4.3; 78 -4.4; 83 -4.5; 89 -4.6; 95 -4.7; 102 -4.5; 109 -4.5; 117 -4.9; 125 -5.6; 134 -5.7; 143 -5.9; 153 -5.9; 164 -6.0; 175 -5.9; 188 -5.8; 201 -5.8; 215 -5.6; 230 -5.4; 246 -5.3; 263 -5.0; 282 -4.7; 301 -4.4; 323 -4.3; 345 -4.0; 369 -3.7; 395 -3.5; 423 -3.3; 452 -3.2; 484 -3.4; 518 -3.0; 554 -2.4; 593 -1.8; 635 -1.4; 679 -1.3; 726 -1.1; 777 -0.6; 832 -0.3; 890 -0.2; 952 0.1; 1019 -0.0; 1090 -0.1; 1167 -0.2; 1248 -0.4; 1336 -0.5; 1429 0.5; 1529 0.0; 1636 0.3; 1751 0.7; 1873 1.6; 2004 3.3; 2145 4.8; 2295 5.9; 2455 6.0; 2627 6.0; 2811 6.0; 3008 5.4; 3219 4.3; 3444 5.4; 3685 6.0; 3943 6.0; 4219 6.0; 4514 5.4; 4830 5.8; 5168 6.0; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Innerfidelity%202017/headphoncecom/onear/Sennheiser%20HD%20239/Sennheiser%20HD%20239.png)