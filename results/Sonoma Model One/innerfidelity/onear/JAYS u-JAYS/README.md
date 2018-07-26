# JAYS u-JAYS
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-63**.
```
GraphicEQ: 10 -84; 20 6.3; 22 6.0; 23 5.8; 25 5.5; 26 5.4; 28 5.2; 30 5.0; 32 4.9; 35 4.7; 37 4.5; 40 4.3; 42 4.1; 45 3.9; 49 3.7; 52 3.6; 56 3.4; 59 3.3; 64 3.4; 68 3.8; 73 4.2; 78 4.4; 83 4.3; 89 3.8; 95 3.1; 102 2.5; 109 2.3; 117 1.9; 125 1.4; 134 0.7; 143 0.1; 153 -0.1; 164 0.1; 175 0.2; 188 -0.0; 201 0.1; 215 0.3; 230 0.5; 246 0.7; 263 1.2; 282 2.0; 301 2.6; 323 3.1; 345 3.3; 369 3.1; 395 2.9; 423 2.7; 452 2.6; 484 2.3; 518 2.1; 554 1.9; 593 1.9; 635 1.9; 679 2.0; 726 2.1; 777 2.0; 832 1.5; 890 0.9; 952 0.3; 1019 0.0; 1090 0.5; 1167 1.3; 1248 2.0; 1336 2.6; 1429 2.8; 1529 2.8; 1636 2.3; 1751 1.9; 1873 1.9; 2004 2.2; 2145 2.8; 2295 3.4; 2455 4.4; 2627 5.1; 2811 5.4; 3008 5.5; 3219 5.0; 3444 4.9; 3685 5.2; 3943 5.9; 4219 5.8; 4514 5.3; 4830 6.0; 5168 5.1; 5530 1.2; 5917 -0.2; 6331 -0.3; 6775 -0.3; 7249 0.1; 7756 0.2; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 -1.3; 18692 -0.5; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 6.3; 22 6.0; 23 5.8; 25 5.5; 26 5.4; 28 5.2; 30 5.0; 32 4.9; 35 4.7; 37 4.5; 40 4.3; 42 4.1; 45 3.9; 49 3.7; 52 3.6; 56 3.4; 59 3.3; 64 3.4; 68 3.8; 73 4.2; 78 4.4; 83 4.3; 89 3.8; 95 3.1; 102 2.5; 109 2.3; 117 1.9; 125 1.4; 134 0.7; 143 0.1; 153 -0.1; 164 0.1; 175 0.2; 188 -0.0; 201 0.1; 215 0.3; 230 0.5; 246 0.7; 263 1.2; 282 2.0; 301 2.6; 323 3.1; 345 3.3; 369 3.1; 395 2.9; 423 2.7; 452 2.6; 484 2.3; 518 2.1; 554 1.9; 593 1.9; 635 1.9; 679 2.0; 726 2.1; 777 2.0; 832 1.5; 890 0.9; 952 0.3; 1019 0.0; 1090 0.5; 1167 1.3; 1248 2.0; 1336 2.6; 1429 2.8; 1529 2.8; 1636 2.3; 1751 1.9; 1873 1.9; 2004 2.2; 2145 2.8; 2295 3.4; 2455 4.4; 2627 5.1; 2811 5.4; 3008 5.5; 3219 5.0; 3444 4.9; 3685 5.2; 3943 5.9; 4219 5.8; 4514 5.3; 4830 6.0; 5168 5.1; 5530 1.2; 5917 -0.2; 6331 -0.3; 6775 -0.3; 7249 0.1; 7756 0.2; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 -1.3; 18692 -0.5; 20000 0.0
Copy: L=-6.3dB*l, R=-6.3dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Sonoma%20Model%20One/innerfidelity/onear/JAYS%20u-JAYS/JAYS%20u-JAYS.png)