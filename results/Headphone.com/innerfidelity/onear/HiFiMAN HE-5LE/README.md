# HiFiMAN HE-5LE
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 4.1; 22 2.7; 23 2.1; 25 1.2; 26 0.8; 28 0.4; 30 0.3; 32 0.3; 35 0.5; 37 0.6; 40 0.7; 42 0.9; 45 1.0; 49 1.3; 52 1.4; 56 1.6; 59 1.5; 64 1.4; 68 1.4; 73 1.4; 78 1.4; 83 1.2; 89 0.9; 95 0.5; 102 0.1; 109 -0.3; 117 -0.9; 125 -1.6; 134 -2.3; 143 -2.9; 153 -3.5; 164 -3.9; 175 -4.1; 188 -4.2; 201 -4.2; 215 -4.3; 230 -4.3; 246 -4.4; 263 -4.5; 282 -4.5; 301 -4.5; 323 -4.4; 345 -4.5; 369 -4.4; 395 -4.2; 423 -4.1; 452 -3.9; 484 -3.6; 518 -3.4; 554 -3.6; 593 -3.2; 635 -1.6; 679 -0.7; 726 0.7; 777 1.4; 832 1.1; 890 0.6; 952 0.1; 1019 -0.1; 1090 0.5; 1167 1.4; 1248 2.4; 1336 3.7; 1429 5.3; 1529 6.0; 1636 6.0; 1751 6.0; 1873 6.0; 2004 6.0; 2145 6.0; 2295 6.0; 2455 6.0; 2627 6.0; 2811 5.9; 3008 5.3; 3219 4.6; 3444 4.4; 3685 4.4; 3943 3.3; 4219 2.7; 4514 4.2; 4830 2.2; 5168 5.0; 5530 5.4; 5917 0.6; 6331 -1.5; 6775 -2.1; 7249 -2.1; 7756 -2.7; 8299 -4.1; 8880 -5.4; 9502 -4.4; 10167 -0.9; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 4.1; 22 2.7; 23 2.1; 25 1.2; 26 0.8; 28 0.4; 30 0.3; 32 0.3; 35 0.5; 37 0.6; 40 0.7; 42 0.9; 45 1.0; 49 1.3; 52 1.4; 56 1.6; 59 1.5; 64 1.4; 68 1.4; 73 1.4; 78 1.4; 83 1.2; 89 0.9; 95 0.5; 102 0.1; 109 -0.3; 117 -0.9; 125 -1.6; 134 -2.3; 143 -2.9; 153 -3.5; 164 -3.9; 175 -4.1; 188 -4.2; 201 -4.2; 215 -4.3; 230 -4.3; 246 -4.4; 263 -4.5; 282 -4.5; 301 -4.5; 323 -4.4; 345 -4.5; 369 -4.4; 395 -4.2; 423 -4.1; 452 -3.9; 484 -3.6; 518 -3.4; 554 -3.6; 593 -3.2; 635 -1.6; 679 -0.7; 726 0.7; 777 1.4; 832 1.1; 890 0.6; 952 0.1; 1019 -0.1; 1090 0.5; 1167 1.4; 1248 2.4; 1336 3.7; 1429 5.3; 1529 6.0; 1636 6.0; 1751 6.0; 1873 6.0; 2004 6.0; 2145 6.0; 2295 6.0; 2455 6.0; 2627 6.0; 2811 5.9; 3008 5.3; 3219 4.6; 3444 4.4; 3685 4.4; 3943 3.3; 4219 2.7; 4514 4.2; 4830 2.2; 5168 5.0; 5530 5.4; 5917 0.6; 6331 -1.5; 6775 -2.1; 7249 -2.1; 7756 -2.7; 8299 -4.1; 8880 -5.4; 9502 -4.4; 10167 -0.9; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Headphone.com/innerfidelity/onear/HiFiMAN%20HE-5LE/HiFiMAN%20HE-5LE.png)