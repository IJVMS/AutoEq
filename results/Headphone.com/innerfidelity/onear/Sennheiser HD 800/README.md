# Sennheiser HD 800
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-56**.
```
GraphicEQ: 10 -84; 20 3.1; 22 2.7; 23 2.6; 25 2.3; 26 2.1; 28 1.9; 30 1.7; 32 1.5; 35 1.3; 37 1.2; 40 1.1; 42 1.1; 45 1.1; 49 1.2; 52 1.5; 56 1.7; 59 1.7; 64 1.3; 68 0.8; 73 0.2; 78 -0.2; 83 -0.6; 89 -1.0; 95 -1.5; 102 -2.0; 109 -2.5; 117 -2.9; 125 -3.4; 134 -3.7; 143 -4.0; 153 -4.2; 164 -4.2; 175 -4.3; 188 -4.4; 201 -4.4; 215 -4.4; 230 -4.3; 246 -4.4; 263 -4.3; 282 -4.1; 301 -4.1; 323 -4.0; 345 -3.9; 369 -3.7; 395 -3.5; 423 -3.2; 452 -2.9; 484 -2.6; 518 -2.2; 554 -1.9; 593 -1.7; 635 -1.4; 679 -1.2; 726 -1.0; 777 -0.7; 832 -0.6; 890 -0.4; 952 -0.1; 1019 0.1; 1090 0.6; 1167 1.2; 1248 2.0; 1336 2.9; 1429 3.6; 1529 4.3; 1636 4.4; 1751 4.2; 1873 4.1; 2004 4.5; 2145 4.6; 2295 4.6; 2455 5.0; 2627 5.6; 2811 5.1; 3008 4.5; 3219 4.5; 3444 4.1; 3685 2.9; 3943 2.2; 4219 2.0; 4514 2.2; 4830 2.9; 5168 2.5; 5530 0.8; 5917 -0.5; 6331 -2.7; 6775 -2.9; 7249 -2.0; 7756 -0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 3.1; 22 2.7; 23 2.6; 25 2.3; 26 2.1; 28 1.9; 30 1.7; 32 1.5; 35 1.3; 37 1.2; 40 1.1; 42 1.1; 45 1.1; 49 1.2; 52 1.5; 56 1.7; 59 1.7; 64 1.3; 68 0.8; 73 0.2; 78 -0.2; 83 -0.6; 89 -1.0; 95 -1.5; 102 -2.0; 109 -2.5; 117 -2.9; 125 -3.4; 134 -3.7; 143 -4.0; 153 -4.2; 164 -4.2; 175 -4.3; 188 -4.4; 201 -4.4; 215 -4.4; 230 -4.3; 246 -4.4; 263 -4.3; 282 -4.1; 301 -4.1; 323 -4.0; 345 -3.9; 369 -3.7; 395 -3.5; 423 -3.2; 452 -2.9; 484 -2.6; 518 -2.2; 554 -1.9; 593 -1.7; 635 -1.4; 679 -1.2; 726 -1.0; 777 -0.7; 832 -0.6; 890 -0.4; 952 -0.1; 1019 0.1; 1090 0.6; 1167 1.2; 1248 2.0; 1336 2.9; 1429 3.6; 1529 4.3; 1636 4.4; 1751 4.2; 1873 4.1; 2004 4.5; 2145 4.6; 2295 4.6; 2455 5.0; 2627 5.6; 2811 5.1; 3008 4.5; 3219 4.5; 3444 4.1; 3685 2.9; 3943 2.2; 4219 2.0; 4514 2.2; 4830 2.9; 5168 2.5; 5530 0.8; 5917 -0.5; 6331 -2.7; 6775 -2.9; 7249 -2.0; 7756 -0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
Copy: L=-5.6dB*l, R=-5.6dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Headphone.com/innerfidelity/onear/Sennheiser%20HD%20800/Sennheiser%20HD%20800.png)