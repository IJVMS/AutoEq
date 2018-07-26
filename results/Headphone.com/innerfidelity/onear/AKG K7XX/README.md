# AKG K7XX
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 0.4; 22 -0.1; 23 -0.3; 25 -0.7; 26 -0.9; 28 -1.3; 30 -1.6; 32 -1.8; 35 -2.2; 37 -2.3; 40 -2.5; 42 -2.7; 45 -2.8; 49 -3.0; 52 -3.1; 56 -3.2; 59 -3.3; 64 -3.4; 68 -3.5; 73 -3.6; 78 -3.9; 83 -4.1; 89 -4.5; 95 -4.9; 102 -5.3; 109 -5.7; 117 -6.1; 125 -6.5; 134 -6.7; 143 -6.8; 153 -6.9; 164 -7.1; 175 -6.9; 188 -6.6; 201 -6.6; 215 -6.6; 230 -6.6; 246 -6.5; 263 -6.4; 282 -6.4; 301 -6.3; 323 -6.1; 345 -5.9; 369 -5.6; 395 -5.3; 423 -4.9; 452 -4.4; 484 -3.8; 518 -3.3; 554 -2.8; 593 -2.1; 635 -1.6; 679 -1.0; 726 -0.3; 777 0.1; 832 0.4; 890 0.6; 952 0.2; 1019 0.1; 1090 -0.2; 1167 -0.4; 1248 -0.3; 1336 -0.2; 1429 -0.4; 1529 -0.9; 1636 -1.7; 1751 -2.3; 1873 -2.7; 2004 -2.7; 2145 -2.0; 2295 -0.7; 2455 1.5; 2627 3.6; 2811 5.5; 3008 6.0; 3219 5.9; 3444 5.0; 3685 3.3; 3943 2.4; 4219 2.7; 4514 3.4; 4830 4.9; 5168 6.0; 5530 6.0; 5917 4.6; 6331 2.4; 6775 -0.4; 7249 -1.8; 7756 -2.2; 8299 -2.8; 8880 -2.7; 9502 -0.5; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 0.4; 22 -0.1; 23 -0.3; 25 -0.7; 26 -0.9; 28 -1.3; 30 -1.6; 32 -1.8; 35 -2.2; 37 -2.3; 40 -2.5; 42 -2.7; 45 -2.8; 49 -3.0; 52 -3.1; 56 -3.2; 59 -3.3; 64 -3.4; 68 -3.5; 73 -3.6; 78 -3.9; 83 -4.1; 89 -4.5; 95 -4.9; 102 -5.3; 109 -5.7; 117 -6.1; 125 -6.5; 134 -6.7; 143 -6.8; 153 -6.9; 164 -7.1; 175 -6.9; 188 -6.6; 201 -6.6; 215 -6.6; 230 -6.6; 246 -6.5; 263 -6.4; 282 -6.4; 301 -6.3; 323 -6.1; 345 -5.9; 369 -5.6; 395 -5.3; 423 -4.9; 452 -4.4; 484 -3.8; 518 -3.3; 554 -2.8; 593 -2.1; 635 -1.6; 679 -1.0; 726 -0.3; 777 0.1; 832 0.4; 890 0.6; 952 0.2; 1019 0.1; 1090 -0.2; 1167 -0.4; 1248 -0.3; 1336 -0.2; 1429 -0.4; 1529 -0.9; 1636 -1.7; 1751 -2.3; 1873 -2.7; 2004 -2.7; 2145 -2.0; 2295 -0.7; 2455 1.5; 2627 3.6; 2811 5.5; 3008 6.0; 3219 5.9; 3444 5.0; 3685 3.3; 3943 2.4; 4219 2.7; 4514 3.4; 4830 4.9; 5168 6.0; 5530 6.0; 5917 4.6; 6331 2.4; 6775 -0.4; 7249 -1.8; 7756 -2.2; 8299 -2.8; 8880 -2.7; 9502 -0.5; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Headphone.com/innerfidelity/onear/AKG%20K7XX/AKG%20K7XX.png)