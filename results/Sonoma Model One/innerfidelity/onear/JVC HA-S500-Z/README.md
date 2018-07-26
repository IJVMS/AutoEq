# JVC HA-S500-Z
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 5.9; 28 5.5; 30 5.1; 32 4.7; 35 4.1; 37 3.8; 40 3.3; 42 3.1; 45 2.7; 49 2.3; 52 2.0; 56 1.8; 59 1.8; 64 2.0; 68 2.3; 73 2.7; 78 2.9; 83 2.6; 89 2.1; 95 1.4; 102 0.7; 109 0.3; 117 -0.3; 125 -1.0; 134 -1.6; 143 -2.1; 153 -2.5; 164 -2.6; 175 -2.4; 188 -2.5; 201 -2.6; 215 -2.7; 230 -2.6; 246 -2.6; 263 -3.1; 282 -3.7; 301 -3.8; 323 -3.2; 345 -2.5; 369 -1.8; 395 -1.0; 423 0.3; 452 1.5; 484 3.0; 518 4.3; 554 4.6; 593 4.0; 635 3.5; 679 2.9; 726 2.6; 777 2.3; 832 1.6; 890 0.9; 952 0.3; 1019 0.0; 1090 0.4; 1167 1.4; 1248 2.1; 1336 2.6; 1429 3.2; 1529 3.7; 1636 3.6; 1751 3.7; 1873 3.7; 2004 4.6; 2145 5.7; 2295 6.0; 2455 6.0; 2627 6.0; 2811 6.0; 3008 6.0; 3219 6.0; 3444 6.0; 3685 6.0; 3943 6.0; 4219 5.9; 4514 5.5; 4830 5.9; 5168 6.0; 5530 6.0; 5917 5.9; 6331 5.5; 6775 2.6; 7249 -1.1; 7756 -0.7; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 5.9; 28 5.5; 30 5.1; 32 4.7; 35 4.1; 37 3.8; 40 3.3; 42 3.1; 45 2.7; 49 2.3; 52 2.0; 56 1.8; 59 1.8; 64 2.0; 68 2.3; 73 2.7; 78 2.9; 83 2.6; 89 2.1; 95 1.4; 102 0.7; 109 0.3; 117 -0.3; 125 -1.0; 134 -1.6; 143 -2.1; 153 -2.5; 164 -2.6; 175 -2.4; 188 -2.5; 201 -2.6; 215 -2.7; 230 -2.6; 246 -2.6; 263 -3.1; 282 -3.7; 301 -3.8; 323 -3.2; 345 -2.5; 369 -1.8; 395 -1.0; 423 0.3; 452 1.5; 484 3.0; 518 4.3; 554 4.6; 593 4.0; 635 3.5; 679 2.9; 726 2.6; 777 2.3; 832 1.6; 890 0.9; 952 0.3; 1019 0.0; 1090 0.4; 1167 1.4; 1248 2.1; 1336 2.6; 1429 3.2; 1529 3.7; 1636 3.6; 1751 3.7; 1873 3.7; 2004 4.6; 2145 5.7; 2295 6.0; 2455 6.0; 2627 6.0; 2811 6.0; 3008 6.0; 3219 6.0; 3444 6.0; 3685 6.0; 3943 6.0; 4219 5.9; 4514 5.5; 4830 5.9; 5168 6.0; 5530 6.0; 5917 5.9; 6331 5.5; 6775 2.6; 7249 -1.1; 7756 -0.7; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Sonoma%20Model%20One/innerfidelity/onear/JVC%20HA-S500-Z/JVC%20HA-S500-Z.png)