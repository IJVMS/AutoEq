# Sennheiser HD 650
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 5.8; 26 5.6; 28 5.2; 30 4.7; 32 4.3; 35 3.7; 37 3.3; 40 2.9; 42 2.7; 45 2.4; 49 2.1; 52 2.1; 56 1.9; 59 1.6; 64 1.2; 68 1.3; 73 1.6; 78 1.1; 83 0.2; 89 -0.5; 95 -1.1; 102 -1.7; 109 -2.2; 117 -2.7; 125 -3.2; 134 -3.5; 143 -3.8; 153 -3.9; 164 -3.8; 175 -3.9; 188 -4.0; 201 -4.1; 215 -3.9; 230 -3.8; 246 -3.7; 263 -3.6; 282 -3.4; 301 -3.3; 323 -3.2; 345 -3.0; 369 -2.8; 395 -2.7; 423 -2.4; 452 -2.1; 484 -1.7; 518 -1.5; 554 -1.3; 593 -1.0; 635 -0.7; 679 -0.5; 726 -0.3; 777 -0.3; 832 -0.4; 890 -0.6; 952 -0.4; 1019 -0.1; 1090 -0.4; 1167 -0.6; 1248 -0.3; 1336 0.2; 1429 0.9; 1529 1.4; 1636 1.5; 1751 1.5; 1873 1.5; 2004 2.1; 2145 2.3; 2295 2.5; 2455 2.7; 2627 3.1; 2811 2.8; 3008 1.9; 3219 1.2; 3444 1.1; 3685 1.5; 3943 2.4; 4219 3.6; 4514 4.7; 4830 5.9; 5168 6.0; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 5.8; 26 5.6; 28 5.2; 30 4.7; 32 4.3; 35 3.7; 37 3.3; 40 2.9; 42 2.7; 45 2.4; 49 2.1; 52 2.1; 56 1.9; 59 1.6; 64 1.2; 68 1.3; 73 1.6; 78 1.1; 83 0.2; 89 -0.5; 95 -1.1; 102 -1.7; 109 -2.2; 117 -2.7; 125 -3.2; 134 -3.5; 143 -3.8; 153 -3.9; 164 -3.8; 175 -3.9; 188 -4.0; 201 -4.1; 215 -3.9; 230 -3.8; 246 -3.7; 263 -3.6; 282 -3.4; 301 -3.3; 323 -3.2; 345 -3.0; 369 -2.8; 395 -2.7; 423 -2.4; 452 -2.1; 484 -1.7; 518 -1.5; 554 -1.3; 593 -1.0; 635 -0.7; 679 -0.5; 726 -0.3; 777 -0.3; 832 -0.4; 890 -0.6; 952 -0.4; 1019 -0.1; 1090 -0.4; 1167 -0.6; 1248 -0.3; 1336 0.2; 1429 0.9; 1529 1.4; 1636 1.5; 1751 1.5; 1873 1.5; 2004 2.1; 2145 2.3; 2295 2.5; 2455 2.7; 2627 3.1; 2811 2.8; 3008 1.9; 3219 1.2; 3444 1.1; 3685 1.5; 3943 2.4; 4219 3.6; 4514 4.7; 4830 5.9; 5168 6.0; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Headphone.com/innerfidelity/onear/Sennheiser%20HD%20650/Sennheiser%20HD%20650.png)