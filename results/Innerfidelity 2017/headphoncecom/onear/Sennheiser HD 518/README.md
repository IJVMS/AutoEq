# Sennheiser HD 518
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-53**.
```
GraphicEQ: 10 -84; 20 5.3; 22 4.6; 23 4.3; 25 3.7; 26 3.4; 28 2.8; 30 2.3; 32 1.8; 35 1.2; 37 0.9; 40 0.4; 42 0.2; 45 -0.2; 49 -0.6; 52 -0.9; 56 -1.3; 59 -1.5; 64 -1.9; 68 -2.1; 73 -2.3; 78 -2.5; 83 -2.7; 89 -2.2; 95 -1.8; 102 -2.6; 109 -3.5; 117 -4.1; 125 -4.9; 134 -5.3; 143 -5.5; 153 -5.9; 164 -5.7; 175 -5.7; 188 -6.0; 201 -5.9; 215 -5.8; 230 -5.8; 246 -5.8; 263 -5.9; 282 -5.6; 301 -5.6; 323 -5.4; 345 -5.1; 369 -5.0; 395 -4.8; 423 -4.7; 452 -4.6; 484 -4.7; 518 -4.2; 554 -3.3; 593 -2.7; 635 -2.5; 679 -2.6; 726 -2.4; 777 -1.0; 832 -1.2; 890 -0.9; 952 -0.2; 1019 0.0; 1090 0.7; 1167 1.3; 1248 1.6; 1336 2.6; 1429 3.6; 1529 4.4; 1636 5.3; 1751 5.1; 1873 4.2; 2004 3.1; 2145 2.0; 2295 2.0; 2455 2.4; 2627 1.6; 2811 1.1; 3008 0.8; 3219 0.1; 3444 1.3; 3685 2.8; 3943 4.1; 4219 2.5; 4514 1.6; 4830 1.7; 5168 1.6; 5530 1.5; 5917 2.2; 6331 2.9; 6775 2.2; 7249 1.3; 7756 0.3; 8299 -0.8; 8880 -1.2; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 -0.0; 18692 -1.4; 20000 -1.2
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 5.3; 22 4.6; 23 4.3; 25 3.7; 26 3.4; 28 2.8; 30 2.3; 32 1.8; 35 1.2; 37 0.9; 40 0.4; 42 0.2; 45 -0.2; 49 -0.6; 52 -0.9; 56 -1.3; 59 -1.5; 64 -1.9; 68 -2.1; 73 -2.3; 78 -2.5; 83 -2.7; 89 -2.2; 95 -1.8; 102 -2.6; 109 -3.5; 117 -4.1; 125 -4.9; 134 -5.3; 143 -5.5; 153 -5.9; 164 -5.7; 175 -5.7; 188 -6.0; 201 -5.9; 215 -5.8; 230 -5.8; 246 -5.8; 263 -5.9; 282 -5.6; 301 -5.6; 323 -5.4; 345 -5.1; 369 -5.0; 395 -4.8; 423 -4.7; 452 -4.6; 484 -4.7; 518 -4.2; 554 -3.3; 593 -2.7; 635 -2.5; 679 -2.6; 726 -2.4; 777 -1.0; 832 -1.2; 890 -0.9; 952 -0.2; 1019 0.0; 1090 0.7; 1167 1.3; 1248 1.6; 1336 2.6; 1429 3.6; 1529 4.4; 1636 5.3; 1751 5.1; 1873 4.2; 2004 3.1; 2145 2.0; 2295 2.0; 2455 2.4; 2627 1.6; 2811 1.1; 3008 0.8; 3219 0.1; 3444 1.3; 3685 2.8; 3943 4.1; 4219 2.5; 4514 1.6; 4830 1.7; 5168 1.6; 5530 1.5; 5917 2.2; 6331 2.9; 6775 2.2; 7249 1.3; 7756 0.3; 8299 -0.8; 8880 -1.2; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 -0.0; 18692 -1.4; 20000 -1.2
Copy: L=-5.3dB*l, R=-5.3dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Innerfidelity%202017/headphoncecom/onear/Sennheiser%20HD%20518/Sennheiser%20HD%20518.png)