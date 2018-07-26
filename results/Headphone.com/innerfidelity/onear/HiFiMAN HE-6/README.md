# HiFiMAN HE-6
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 3.8; 22 3.4; 23 3.3; 25 3.0; 26 2.9; 28 2.8; 30 2.7; 32 2.6; 35 2.5; 37 2.5; 40 2.5; 42 2.5; 45 2.5; 49 2.4; 52 2.5; 56 2.5; 59 2.6; 64 2.8; 68 2.6; 73 2.3; 78 2.1; 83 2.0; 89 1.7; 95 1.3; 102 0.8; 109 0.4; 117 -0.0; 125 -0.3; 134 -0.7; 143 -0.9; 153 -1.0; 164 -1.0; 175 -1.0; 188 -1.0; 201 -1.0; 215 -0.9; 230 -0.8; 246 -0.9; 263 -0.9; 282 -0.9; 301 -0.9; 323 -1.0; 345 -1.2; 369 -1.2; 395 -1.1; 423 -1.0; 452 -0.7; 484 -0.6; 518 -0.4; 554 -0.2; 593 -0.0; 635 0.2; 679 0.2; 726 0.2; 777 0.2; 832 0.0; 890 -0.2; 952 -0.3; 1019 -0.0; 1090 0.7; 1167 1.3; 1248 1.4; 1336 2.3; 1429 3.2; 1529 4.4; 1636 5.0; 1751 5.6; 1873 6.0; 2004 5.9; 2145 5.5; 2295 5.5; 2455 5.7; 2627 5.3; 2811 4.6; 3008 3.6; 3219 2.4; 3444 2.2; 3685 1.9; 3943 0.9; 4219 2.2; 4514 3.5; 4830 5.7; 5168 4.2; 5530 -0.2; 5917 -2.0; 6331 -2.6; 6775 -3.0; 7249 -2.3; 7756 -2.4; 8299 -3.9; 8880 -5.3; 9502 -3.9; 10167 -0.3; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 3.8; 22 3.4; 23 3.3; 25 3.0; 26 2.9; 28 2.8; 30 2.7; 32 2.6; 35 2.5; 37 2.5; 40 2.5; 42 2.5; 45 2.5; 49 2.4; 52 2.5; 56 2.5; 59 2.6; 64 2.8; 68 2.6; 73 2.3; 78 2.1; 83 2.0; 89 1.7; 95 1.3; 102 0.8; 109 0.4; 117 -0.0; 125 -0.3; 134 -0.7; 143 -0.9; 153 -1.0; 164 -1.0; 175 -1.0; 188 -1.0; 201 -1.0; 215 -0.9; 230 -0.8; 246 -0.9; 263 -0.9; 282 -0.9; 301 -0.9; 323 -1.0; 345 -1.2; 369 -1.2; 395 -1.1; 423 -1.0; 452 -0.7; 484 -0.6; 518 -0.4; 554 -0.2; 593 -0.0; 635 0.2; 679 0.2; 726 0.2; 777 0.2; 832 0.0; 890 -0.2; 952 -0.3; 1019 -0.0; 1090 0.7; 1167 1.3; 1248 1.4; 1336 2.3; 1429 3.2; 1529 4.4; 1636 5.0; 1751 5.6; 1873 6.0; 2004 5.9; 2145 5.5; 2295 5.5; 2455 5.7; 2627 5.3; 2811 4.6; 3008 3.6; 3219 2.4; 3444 2.2; 3685 1.9; 3943 0.9; 4219 2.2; 4514 3.5; 4830 5.7; 5168 4.2; 5530 -0.2; 5917 -2.0; 6331 -2.6; 6775 -3.0; 7249 -2.3; 7756 -2.4; 8299 -3.9; 8880 -5.3; 9502 -3.9; 10167 -0.3; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Headphone.com/innerfidelity/onear/HiFiMAN%20HE-6/HiFiMAN%20HE-6.png)