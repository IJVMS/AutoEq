# Sennheiser HD 700
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-52**.
```
GraphicEQ: 10 -84; 20 4.8; 22 4.1; 23 3.8; 25 3.3; 26 3.0; 28 2.6; 30 2.1; 32 1.7; 35 1.3; 37 1.0; 40 0.6; 42 0.4; 45 0.1; 49 -0.2; 52 -0.4; 56 -0.7; 59 -0.8; 64 -1.1; 68 -1.2; 73 -1.3; 78 -1.5; 83 -1.7; 89 -2.0; 95 -2.5; 102 -3.1; 109 -3.6; 117 -3.9; 125 -4.4; 134 -4.8; 143 -5.2; 153 -5.4; 164 -5.5; 175 -5.5; 188 -5.7; 201 -5.7; 215 -5.7; 230 -5.7; 246 -5.7; 263 -5.7; 282 -5.6; 301 -5.5; 323 -5.4; 345 -5.2; 369 -5.1; 395 -5.0; 423 -4.8; 452 -4.7; 484 -4.8; 518 -4.5; 554 -3.8; 593 -3.1; 635 -2.7; 679 -2.6; 726 -2.2; 777 -1.6; 832 -1.3; 890 -0.9; 952 -0.4; 1019 0.1; 1090 0.4; 1167 0.6; 1248 1.2; 1336 1.7; 1429 2.5; 1529 3.3; 1636 3.4; 1751 3.8; 1873 4.2; 2004 4.4; 2145 4.2; 2295 3.7; 2455 3.4; 2627 3.1; 2811 2.8; 3008 3.0; 3219 3.2; 3444 3.9; 3685 4.9; 3943 4.8; 4219 3.1; 4514 2.0; 4830 -0.7; 5168 -2.9; 5530 -4.4; 5917 -7.0; 6331 -9.9; 6775 -7.3; 7249 -4.1; 7756 -2.0; 8299 -1.7; 8880 -2.1; 9502 -2.1; 10167 -2.1; 10879 -1.9; 11640 -0.2; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 -0.7; 18692 -3.9; 20000 -7.3
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 4.8; 22 4.1; 23 3.8; 25 3.3; 26 3.0; 28 2.6; 30 2.1; 32 1.7; 35 1.3; 37 1.0; 40 0.6; 42 0.4; 45 0.1; 49 -0.2; 52 -0.4; 56 -0.7; 59 -0.8; 64 -1.1; 68 -1.2; 73 -1.3; 78 -1.5; 83 -1.7; 89 -2.0; 95 -2.5; 102 -3.1; 109 -3.6; 117 -3.9; 125 -4.4; 134 -4.8; 143 -5.2; 153 -5.4; 164 -5.5; 175 -5.5; 188 -5.7; 201 -5.7; 215 -5.7; 230 -5.7; 246 -5.7; 263 -5.7; 282 -5.6; 301 -5.5; 323 -5.4; 345 -5.2; 369 -5.1; 395 -5.0; 423 -4.8; 452 -4.7; 484 -4.8; 518 -4.5; 554 -3.8; 593 -3.1; 635 -2.7; 679 -2.6; 726 -2.2; 777 -1.6; 832 -1.3; 890 -0.9; 952 -0.4; 1019 0.1; 1090 0.4; 1167 0.6; 1248 1.2; 1336 1.7; 1429 2.5; 1529 3.3; 1636 3.4; 1751 3.8; 1873 4.2; 2004 4.4; 2145 4.2; 2295 3.7; 2455 3.4; 2627 3.1; 2811 2.8; 3008 3.0; 3219 3.2; 3444 3.9; 3685 4.9; 3943 4.8; 4219 3.1; 4514 2.0; 4830 -0.7; 5168 -2.9; 5530 -4.4; 5917 -7.0; 6331 -9.9; 6775 -7.3; 7249 -4.1; 7756 -2.0; 8299 -1.7; 8880 -2.1; 9502 -2.1; 10167 -2.1; 10879 -1.9; 11640 -0.2; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 -0.7; 18692 -3.9; 20000 -7.3
Copy: L=-5.2dB*l, R=-5.2dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Innerfidelity%202017/innerfidelity/onear/Sennheiser%20HD%20700/Sennheiser%20HD%20700.png)