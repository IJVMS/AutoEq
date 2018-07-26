# Sennheiser HD 4
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 6.0; 32 6.0; 35 6.0; 37 6.0; 40 5.7; 42 5.5; 45 5.1; 49 4.6; 52 4.2; 56 3.9; 59 3.7; 64 3.8; 68 4.0; 73 4.4; 78 4.4; 83 4.1; 89 3.5; 95 2.7; 102 1.9; 109 1.1; 117 0.8; 125 0.3; 134 -0.3; 143 -0.9; 153 -1.6; 164 -1.4; 175 -0.9; 188 -1.5; 201 -1.8; 215 -1.8; 230 -1.7; 246 -1.5; 263 -1.3; 282 -1.0; 301 -0.7; 323 -0.3; 345 0.0; 369 0.3; 395 0.4; 423 0.4; 452 0.3; 484 0.1; 518 0.0; 554 0.1; 593 0.4; 635 0.7; 679 1.0; 726 1.3; 777 1.5; 832 1.2; 890 0.7; 952 0.3; 1019 0.0; 1090 0.4; 1167 1.1; 1248 1.6; 1336 1.8; 1429 1.8; 1529 1.7; 1636 0.7; 1751 -0.2; 1873 -0.4; 2004 -0.2; 2145 0.0; 2295 0.7; 2455 1.9; 2627 3.2; 2811 4.5; 3008 5.8; 3219 6.0; 3444 6.0; 3685 6.0; 3943 6.0; 4219 6.0; 4514 5.9; 4830 1.5; 5168 0.1; 5530 0.8; 5917 1.0; 6331 3.4; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 6.0; 32 6.0; 35 6.0; 37 6.0; 40 5.7; 42 5.5; 45 5.1; 49 4.6; 52 4.2; 56 3.9; 59 3.7; 64 3.8; 68 4.0; 73 4.4; 78 4.4; 83 4.1; 89 3.5; 95 2.7; 102 1.9; 109 1.1; 117 0.8; 125 0.3; 134 -0.3; 143 -0.9; 153 -1.6; 164 -1.4; 175 -0.9; 188 -1.5; 201 -1.8; 215 -1.8; 230 -1.7; 246 -1.5; 263 -1.3; 282 -1.0; 301 -0.7; 323 -0.3; 345 0.0; 369 0.3; 395 0.4; 423 0.4; 452 0.3; 484 0.1; 518 0.0; 554 0.1; 593 0.4; 635 0.7; 679 1.0; 726 1.3; 777 1.5; 832 1.2; 890 0.7; 952 0.3; 1019 0.0; 1090 0.4; 1167 1.1; 1248 1.6; 1336 1.8; 1429 1.8; 1529 1.7; 1636 0.7; 1751 -0.2; 1873 -0.4; 2004 -0.2; 2145 0.0; 2295 0.7; 2455 1.9; 2627 3.2; 2811 4.5; 3008 5.8; 3219 6.0; 3444 6.0; 3685 6.0; 3943 6.0; 4219 6.0; 4514 5.9; 4830 1.5; 5168 0.1; 5530 0.8; 5917 1.0; 6331 3.4; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Sonoma%20Model%20One/innerfidelity/onear/Sennheiser%20HD%204/Sennheiser%20HD%204.png)