# Polk Melee
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 -1.5; 22 -1.9; 23 -2.1; 25 -2.4; 26 -2.5; 28 -2.7; 30 -2.9; 32 -3.0; 35 -3.1; 37 -3.2; 40 -3.3; 42 -3.3; 45 -3.4; 49 -3.3; 52 -3.4; 56 -3.4; 59 -3.3; 64 -3.2; 68 -3.1; 73 -2.9; 78 -2.9; 83 -3.2; 89 -4.1; 95 -4.7; 102 -4.8; 109 -4.7; 117 -4.9; 125 -5.7; 134 -6.5; 143 -7.2; 153 -7.1; 164 -6.1; 175 -6.7; 188 -7.1; 201 -6.9; 215 -6.7; 230 -6.4; 246 -6.1; 263 -5.6; 282 -5.0; 301 -4.6; 323 -4.6; 345 -4.7; 369 -4.3; 395 -3.8; 423 -3.3; 452 -2.9; 484 -2.5; 518 -2.0; 554 -1.6; 593 -1.3; 635 -0.9; 679 -0.7; 726 -0.6; 777 -0.5; 832 -0.4; 890 -0.3; 952 -0.1; 1019 0.1; 1090 0.4; 1167 0.9; 1248 1.6; 1336 2.4; 1429 3.2; 1529 4.1; 1636 5.0; 1751 5.9; 1873 6.0; 2004 6.0; 2145 6.0; 2295 6.0; 2455 6.0; 2627 6.0; 2811 6.0; 3008 6.0; 3219 6.0; 3444 6.0; 3685 6.0; 3943 6.0; 4219 6.0; 4514 6.0; 4830 6.0; 5168 6.0; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 -1.5; 22 -1.9; 23 -2.1; 25 -2.4; 26 -2.5; 28 -2.7; 30 -2.9; 32 -3.0; 35 -3.1; 37 -3.2; 40 -3.3; 42 -3.3; 45 -3.4; 49 -3.3; 52 -3.4; 56 -3.4; 59 -3.3; 64 -3.2; 68 -3.1; 73 -2.9; 78 -2.9; 83 -3.2; 89 -4.1; 95 -4.7; 102 -4.8; 109 -4.7; 117 -4.9; 125 -5.7; 134 -6.5; 143 -7.2; 153 -7.1; 164 -6.1; 175 -6.7; 188 -7.1; 201 -6.9; 215 -6.7; 230 -6.4; 246 -6.1; 263 -5.6; 282 -5.0; 301 -4.6; 323 -4.6; 345 -4.7; 369 -4.3; 395 -3.8; 423 -3.3; 452 -2.9; 484 -2.5; 518 -2.0; 554 -1.6; 593 -1.3; 635 -0.9; 679 -0.7; 726 -0.6; 777 -0.5; 832 -0.4; 890 -0.3; 952 -0.1; 1019 0.1; 1090 0.4; 1167 0.9; 1248 1.6; 1336 2.4; 1429 3.2; 1529 4.1; 1636 5.0; 1751 5.9; 1873 6.0; 2004 6.0; 2145 6.0; 2295 6.0; 2455 6.0; 2627 6.0; 2811 6.0; 3008 6.0; 3219 6.0; 3444 6.0; 3685 6.0; 3943 6.0; 4219 6.0; 4514 6.0; 4830 6.0; 5168 6.0; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Headphone.com/innerfidelity/onear/Polk%20Melee/Polk%20Melee.png)