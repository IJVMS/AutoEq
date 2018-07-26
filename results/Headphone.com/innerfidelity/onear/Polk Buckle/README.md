# Polk Buckle
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 -7.3; 22 -7.4; 23 -7.4; 25 -7.5; 26 -7.5; 28 -7.5; 30 -7.5; 32 -7.4; 35 -7.3; 37 -7.2; 40 -7.1; 42 -7.0; 45 -6.8; 49 -6.5; 52 -6.3; 56 -6.0; 59 -5.8; 64 -5.4; 68 -5.0; 73 -4.4; 78 -4.0; 83 -3.9; 89 -4.3; 95 -4.9; 102 -5.5; 109 -5.9; 117 -6.1; 125 -6.2; 134 -6.3; 143 -6.3; 153 -6.2; 164 -5.6; 175 -5.6; 188 -5.8; 201 -5.8; 215 -5.6; 230 -5.5; 246 -5.4; 263 -4.9; 282 -3.9; 301 -2.7; 323 -2.6; 345 -2.1; 369 -1.6; 395 -1.3; 423 -1.1; 452 -0.7; 484 -0.2; 518 0.3; 554 0.7; 593 0.9; 635 1.3; 679 1.7; 726 1.3; 777 0.6; 832 -0.0; 890 -0.1; 952 -0.0; 1019 0.0; 1090 0.3; 1167 0.9; 1248 1.7; 1336 2.7; 1429 3.7; 1529 4.6; 1636 5.3; 1751 5.8; 1873 6.0; 2004 6.0; 2145 6.0; 2295 6.0; 2455 6.0; 2627 6.0; 2811 6.0; 3008 6.0; 3219 6.0; 3444 6.0; 3685 6.0; 3943 6.0; 4219 6.0; 4514 6.0; 4830 6.0; 5168 6.0; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 -7.3; 22 -7.4; 23 -7.4; 25 -7.5; 26 -7.5; 28 -7.5; 30 -7.5; 32 -7.4; 35 -7.3; 37 -7.2; 40 -7.1; 42 -7.0; 45 -6.8; 49 -6.5; 52 -6.3; 56 -6.0; 59 -5.8; 64 -5.4; 68 -5.0; 73 -4.4; 78 -4.0; 83 -3.9; 89 -4.3; 95 -4.9; 102 -5.5; 109 -5.9; 117 -6.1; 125 -6.2; 134 -6.3; 143 -6.3; 153 -6.2; 164 -5.6; 175 -5.6; 188 -5.8; 201 -5.8; 215 -5.6; 230 -5.5; 246 -5.4; 263 -4.9; 282 -3.9; 301 -2.7; 323 -2.6; 345 -2.1; 369 -1.6; 395 -1.3; 423 -1.1; 452 -0.7; 484 -0.2; 518 0.3; 554 0.7; 593 0.9; 635 1.3; 679 1.7; 726 1.3; 777 0.6; 832 -0.0; 890 -0.1; 952 -0.0; 1019 0.0; 1090 0.3; 1167 0.9; 1248 1.7; 1336 2.7; 1429 3.7; 1529 4.6; 1636 5.3; 1751 5.8; 1873 6.0; 2004 6.0; 2145 6.0; 2295 6.0; 2455 6.0; 2627 6.0; 2811 6.0; 3008 6.0; 3219 6.0; 3444 6.0; 3685 6.0; 3943 6.0; 4219 6.0; 4514 6.0; 4830 6.0; 5168 6.0; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Headphone.com/innerfidelity/onear/Polk%20Buckle/Polk%20Buckle.png)