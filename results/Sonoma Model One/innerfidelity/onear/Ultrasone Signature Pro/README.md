# Ultrasone Signature Pro
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-62**.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 5.9; 25 5.6; 26 5.4; 28 4.9; 30 4.4; 32 3.9; 35 3.4; 37 3.1; 40 2.7; 42 2.4; 45 2.0; 49 1.6; 52 1.3; 56 1.1; 59 1.1; 64 1.4; 68 2.0; 73 3.2; 78 4.1; 83 3.9; 89 2.4; 95 1.0; 102 -0.1; 109 -0.1; 117 -0.0; 125 -1.0; 134 -2.2; 143 -2.9; 153 -3.3; 164 -2.8; 175 -2.9; 188 -3.5; 201 -3.4; 215 -3.4; 230 -3.3; 246 -3.2; 263 -2.8; 282 -2.4; 301 -2.0; 323 -1.7; 345 -1.5; 369 -1.4; 395 -1.5; 423 -1.4; 452 -1.4; 484 -1.4; 518 -1.6; 554 -1.7; 593 -1.7; 635 -1.3; 679 -0.9; 726 -0.4; 777 -0.1; 832 -0.2; 890 -0.4; 952 -0.3; 1019 0.2; 1090 1.3; 1167 2.3; 1248 2.8; 1336 3.0; 1429 3.2; 1529 3.8; 1636 4.5; 1751 4.4; 1873 4.3; 2004 4.8; 2145 5.7; 2295 6.0; 2455 6.0; 2627 6.0; 2811 6.0; 3008 6.0; 3219 6.0; 3444 6.0; 3685 6.0; 3943 5.7; 4219 5.6; 4514 6.1; 4830 6.0; 5168 6.0; 5530 6.0; 5917 5.9; 6331 4.4; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 -0.0; 9502 -2.8; 10167 -5.6; 10879 -7.0; 11640 -6.4; 12455 -4.5; 13327 -2.0; 14260 -0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 5.9; 25 5.6; 26 5.4; 28 4.9; 30 4.4; 32 3.9; 35 3.4; 37 3.1; 40 2.7; 42 2.4; 45 2.0; 49 1.6; 52 1.3; 56 1.1; 59 1.1; 64 1.4; 68 2.0; 73 3.2; 78 4.1; 83 3.9; 89 2.4; 95 1.0; 102 -0.1; 109 -0.1; 117 -0.0; 125 -1.0; 134 -2.2; 143 -2.9; 153 -3.3; 164 -2.8; 175 -2.9; 188 -3.5; 201 -3.4; 215 -3.4; 230 -3.3; 246 -3.2; 263 -2.8; 282 -2.4; 301 -2.0; 323 -1.7; 345 -1.5; 369 -1.4; 395 -1.5; 423 -1.4; 452 -1.4; 484 -1.4; 518 -1.6; 554 -1.7; 593 -1.7; 635 -1.3; 679 -0.9; 726 -0.4; 777 -0.1; 832 -0.2; 890 -0.4; 952 -0.3; 1019 0.2; 1090 1.3; 1167 2.3; 1248 2.8; 1336 3.0; 1429 3.2; 1529 3.8; 1636 4.5; 1751 4.4; 1873 4.3; 2004 4.8; 2145 5.7; 2295 6.0; 2455 6.0; 2627 6.0; 2811 6.0; 3008 6.0; 3219 6.0; 3444 6.0; 3685 6.0; 3943 5.7; 4219 5.6; 4514 6.1; 4830 6.0; 5168 6.0; 5530 6.0; 5917 5.9; 6331 4.4; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 -0.0; 9502 -2.8; 10167 -5.6; 10879 -7.0; 11640 -6.4; 12455 -4.5; 13327 -2.0; 14260 -0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
Copy: L=-6.2dB*l, R=-6.2dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Sonoma%20Model%20One/innerfidelity/onear/Ultrasone%20Signature%20Pro/Ultrasone%20Signature%20Pro.png)