# Sennheiser HD 471i
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 1.1; 22 0.7; 23 0.5; 25 0.3; 26 0.2; 28 -0.0; 30 -0.1; 32 -0.2; 35 -0.3; 37 -0.4; 40 -0.3; 42 -0.3; 45 -0.2; 49 -0.1; 52 0.0; 56 0.2; 59 0.4; 64 0.7; 68 0.9; 73 1.2; 78 1.4; 83 1.6; 89 1.7; 95 1.6; 102 2.0; 109 2.4; 117 2.8; 125 1.9; 134 -0.6; 143 -1.9; 153 -2.0; 164 -1.1; 175 -2.1; 188 -2.8; 201 -2.5; 215 -2.5; 230 -2.6; 246 -2.6; 263 -2.4; 282 -2.1; 301 -1.8; 323 -1.4; 345 -0.8; 369 -0.4; 395 -0.3; 423 -0.3; 452 -0.5; 484 -0.4; 518 -0.5; 554 -0.4; 593 -0.4; 635 -0.5; 679 -0.6; 726 -0.7; 777 -0.3; 832 -0.1; 890 -0.1; 952 -0.0; 1019 0.1; 1090 0.2; 1167 -0.2; 1248 -0.2; 1336 -0.3; 1429 -0.7; 1529 -1.1; 1636 -1.1; 1751 -0.9; 1873 -0.4; 2004 0.6; 2145 2.1; 2295 2.9; 2455 3.1; 2627 4.1; 2811 4.5; 3008 5.0; 3219 5.3; 3444 5.3; 3685 5.5; 3943 6.0; 4219 6.0; 4514 6.0; 4830 6.0; 5168 6.0; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 1.1; 22 0.7; 23 0.5; 25 0.3; 26 0.2; 28 -0.0; 30 -0.1; 32 -0.2; 35 -0.3; 37 -0.4; 40 -0.3; 42 -0.3; 45 -0.2; 49 -0.1; 52 0.0; 56 0.2; 59 0.4; 64 0.7; 68 0.9; 73 1.2; 78 1.4; 83 1.6; 89 1.7; 95 1.6; 102 2.0; 109 2.4; 117 2.8; 125 1.9; 134 -0.6; 143 -1.9; 153 -2.0; 164 -1.1; 175 -2.1; 188 -2.8; 201 -2.5; 215 -2.5; 230 -2.6; 246 -2.6; 263 -2.4; 282 -2.1; 301 -1.8; 323 -1.4; 345 -0.8; 369 -0.4; 395 -0.3; 423 -0.3; 452 -0.5; 484 -0.4; 518 -0.5; 554 -0.4; 593 -0.4; 635 -0.5; 679 -0.6; 726 -0.7; 777 -0.3; 832 -0.1; 890 -0.1; 952 -0.0; 1019 0.1; 1090 0.2; 1167 -0.2; 1248 -0.2; 1336 -0.3; 1429 -0.7; 1529 -1.1; 1636 -1.1; 1751 -0.9; 1873 -0.4; 2004 0.6; 2145 2.1; 2295 2.9; 2455 3.1; 2627 4.1; 2811 4.5; 3008 5.0; 3219 5.3; 3444 5.3; 3685 5.5; 3943 6.0; 4219 6.0; 4514 6.0; 4830 6.0; 5168 6.0; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/SBAF-Serious/innerfidelity/onear/Sennheiser%20HD%20471i/Sennheiser%20HD%20471i.png)