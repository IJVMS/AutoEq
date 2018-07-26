# Sennheiser HD 800 S sn 01067
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 4.2; 22 3.7; 23 3.5; 25 3.1; 26 3.0; 28 2.7; 30 2.4; 32 2.2; 35 1.9; 37 1.7; 40 1.5; 42 1.4; 45 1.2; 49 1.1; 52 1.1; 56 1.0; 59 1.0; 64 1.0; 68 1.1; 73 0.9; 78 0.5; 83 0.2; 89 -0.1; 95 -0.7; 102 -1.5; 109 -2.0; 117 -2.6; 125 -3.2; 134 -3.4; 143 -3.7; 153 -3.9; 164 -3.9; 175 -4.0; 188 -4.1; 201 -4.2; 215 -4.2; 230 -4.2; 246 -4.2; 263 -4.1; 282 -3.9; 301 -3.9; 323 -3.8; 345 -3.8; 369 -3.6; 395 -3.4; 423 -3.1; 452 -2.8; 484 -2.5; 518 -2.2; 554 -1.9; 593 -1.6; 635 -1.4; 679 -1.1; 726 -0.8; 777 -0.6; 832 -0.5; 890 -0.3; 952 -0.1; 1019 0.1; 1090 0.5; 1167 0.7; 1248 1.5; 1336 2.4; 1429 3.5; 1529 4.3; 1636 4.5; 1751 4.5; 1873 4.3; 2004 4.6; 2145 4.6; 2295 4.7; 2455 5.1; 2627 5.6; 2811 5.0; 3008 4.4; 3219 4.5; 3444 4.1; 3685 2.5; 3943 2.1; 4219 3.2; 4514 4.8; 4830 5.9; 5168 5.4; 5530 3.4; 5917 1.7; 6331 -1.5; 6775 -2.4; 7249 -1.2; 7756 -0.2; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 4.2; 22 3.7; 23 3.5; 25 3.1; 26 3.0; 28 2.7; 30 2.4; 32 2.2; 35 1.9; 37 1.7; 40 1.5; 42 1.4; 45 1.2; 49 1.1; 52 1.1; 56 1.0; 59 1.0; 64 1.0; 68 1.1; 73 0.9; 78 0.5; 83 0.2; 89 -0.1; 95 -0.7; 102 -1.5; 109 -2.0; 117 -2.6; 125 -3.2; 134 -3.4; 143 -3.7; 153 -3.9; 164 -3.9; 175 -4.0; 188 -4.1; 201 -4.2; 215 -4.2; 230 -4.2; 246 -4.2; 263 -4.1; 282 -3.9; 301 -3.9; 323 -3.8; 345 -3.8; 369 -3.6; 395 -3.4; 423 -3.1; 452 -2.8; 484 -2.5; 518 -2.2; 554 -1.9; 593 -1.6; 635 -1.4; 679 -1.1; 726 -0.8; 777 -0.6; 832 -0.5; 890 -0.3; 952 -0.1; 1019 0.1; 1090 0.5; 1167 0.7; 1248 1.5; 1336 2.4; 1429 3.5; 1529 4.3; 1636 4.5; 1751 4.5; 1873 4.3; 2004 4.6; 2145 4.6; 2295 4.7; 2455 5.1; 2627 5.6; 2811 5.0; 3008 4.4; 3219 4.5; 3444 4.1; 3685 2.5; 3943 2.1; 4219 3.2; 4514 4.8; 4830 5.9; 5168 5.4; 5530 3.4; 5917 1.7; 6331 -1.5; 6775 -2.4; 7249 -1.2; 7756 -0.2; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Headphone.com/innerfidelity/onear/Sennheiser%20HD%20800%20S%20sn%2001067/Sennheiser%20HD%20800%20S%20sn%2001067.png)