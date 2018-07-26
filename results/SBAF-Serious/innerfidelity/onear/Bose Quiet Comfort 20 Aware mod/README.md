# Bose Quiet Comfort 20 Aware mod
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 4.8; 22 3.1; 23 2.4; 25 1.3; 26 0.8; 28 0.2; 30 -0.2; 32 -0.4; 35 -0.5; 37 -0.4; 40 -0.3; 42 -0.1; 45 0.1; 49 0.3; 52 0.5; 56 0.6; 59 0.6; 64 0.6; 68 0.4; 73 0.2; 78 -0.1; 83 -0.5; 89 -0.9; 95 -1.4; 102 -1.7; 109 -2.0; 117 -2.2; 125 -2.4; 134 -2.6; 143 -2.6; 153 -2.6; 164 -2.6; 175 -2.6; 188 -2.6; 201 -2.6; 215 -2.5; 230 -2.4; 246 -2.3; 263 -2.1; 282 -2.0; 301 -1.8; 323 -1.8; 345 -1.7; 369 -1.6; 395 -1.7; 423 -1.7; 452 -1.6; 484 -1.7; 518 -1.5; 554 -1.1; 593 -0.7; 635 -0.7; 679 -0.9; 726 -0.7; 777 -0.2; 832 0.2; 890 0.4; 952 0.3; 1019 -0.1; 1090 -0.7; 1167 -1.3; 1248 -2.2; 1336 -3.2; 1429 -4.4; 1529 -5.5; 1636 -6.1; 1751 -5.8; 1873 -4.8; 2004 -3.7; 2145 -2.9; 2295 -2.3; 2455 -1.5; 2627 -1.1; 2811 -0.3; 3008 1.2; 3219 2.2; 3444 2.5; 3685 1.6; 3943 -0.1; 4219 -2.0; 4514 -1.1; 4830 2.0; 5168 5.5; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.8; 7249 -1.5; 7756 -3.7; 8299 -2.6; 8880 -1.0; 9502 -0.9; 10167 -0.5; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 4.8; 22 3.1; 23 2.4; 25 1.3; 26 0.8; 28 0.2; 30 -0.2; 32 -0.4; 35 -0.5; 37 -0.4; 40 -0.3; 42 -0.1; 45 0.1; 49 0.3; 52 0.5; 56 0.6; 59 0.6; 64 0.6; 68 0.4; 73 0.2; 78 -0.1; 83 -0.5; 89 -0.9; 95 -1.4; 102 -1.7; 109 -2.0; 117 -2.2; 125 -2.4; 134 -2.6; 143 -2.6; 153 -2.6; 164 -2.6; 175 -2.6; 188 -2.6; 201 -2.6; 215 -2.5; 230 -2.4; 246 -2.3; 263 -2.1; 282 -2.0; 301 -1.8; 323 -1.8; 345 -1.7; 369 -1.6; 395 -1.7; 423 -1.7; 452 -1.6; 484 -1.7; 518 -1.5; 554 -1.1; 593 -0.7; 635 -0.7; 679 -0.9; 726 -0.7; 777 -0.2; 832 0.2; 890 0.4; 952 0.3; 1019 -0.1; 1090 -0.7; 1167 -1.3; 1248 -2.2; 1336 -3.2; 1429 -4.4; 1529 -5.5; 1636 -6.1; 1751 -5.8; 1873 -4.8; 2004 -3.7; 2145 -2.9; 2295 -2.3; 2455 -1.5; 2627 -1.1; 2811 -0.3; 3008 1.2; 3219 2.2; 3444 2.5; 3685 1.6; 3943 -0.1; 4219 -2.0; 4514 -1.1; 4830 2.0; 5168 5.5; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.8; 7249 -1.5; 7756 -3.7; 8299 -2.6; 8880 -1.0; 9502 -0.9; 10167 -0.5; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/SBAF-Serious/innerfidelity/onear/Bose%20Quiet%20Comfort%2020%20Aware%20mod/Bose%20Quiet%20Comfort%2020%20Aware%20mod.png)