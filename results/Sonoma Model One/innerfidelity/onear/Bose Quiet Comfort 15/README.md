# Bose Quiet Comfort 15
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 1.2; 22 0.8; 23 0.6; 25 0.3; 26 0.2; 28 -0.0; 30 -0.2; 32 -0.4; 35 -0.5; 37 -0.6; 40 -0.7; 42 -0.9; 45 -1.0; 49 -1.2; 52 -1.3; 56 -1.3; 59 -1.2; 64 -0.8; 68 -0.4; 73 0.1; 78 0.3; 83 0.1; 89 -0.7; 95 -1.4; 102 -2.1; 109 -2.5; 117 -2.9; 125 -3.4; 134 -3.8; 143 -4.1; 153 -4.2; 164 -4.0; 175 -3.8; 188 -3.8; 201 -3.7; 215 -3.6; 230 -3.5; 246 -3.4; 263 -3.3; 282 -2.9; 301 -2.7; 323 -2.3; 345 -2.0; 369 -1.8; 395 -1.5; 423 -1.1; 452 -0.6; 484 -0.4; 518 -0.1; 554 0.1; 593 0.4; 635 1.0; 679 1.5; 726 2.0; 777 2.3; 832 1.8; 890 1.2; 952 0.4; 1019 -0.0; 1090 0.0; 1167 0.3; 1248 0.7; 1336 0.9; 1429 1.5; 1529 1.2; 1636 0.2; 1751 -1.1; 1873 -1.8; 2004 -1.7; 2145 -1.2; 2295 -1.1; 2455 -0.7; 2627 0.3; 2811 1.7; 3008 2.6; 3219 3.7; 3444 5.9; 3685 5.8; 3943 -0.8; 4219 -5.4; 4514 -4.4; 4830 -1.7; 5168 0.8; 5530 -1.5; 5917 -7.2; 6331 -6.4; 6775 -3.1; 7249 0.3; 7756 0.3; 8299 0.0; 8880 -0.0; 9502 -2.0; 10167 -3.1; 10879 -1.5; 11640 0.0; 12455 0.0; 13327 0.0; 14260 -0.3; 15258 -2.3; 16326 -1.1; 17469 0.0; 18692 0.0; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 1.2; 22 0.8; 23 0.6; 25 0.3; 26 0.2; 28 -0.0; 30 -0.2; 32 -0.4; 35 -0.5; 37 -0.6; 40 -0.7; 42 -0.9; 45 -1.0; 49 -1.2; 52 -1.3; 56 -1.3; 59 -1.2; 64 -0.8; 68 -0.4; 73 0.1; 78 0.3; 83 0.1; 89 -0.7; 95 -1.4; 102 -2.1; 109 -2.5; 117 -2.9; 125 -3.4; 134 -3.8; 143 -4.1; 153 -4.2; 164 -4.0; 175 -3.8; 188 -3.8; 201 -3.7; 215 -3.6; 230 -3.5; 246 -3.4; 263 -3.3; 282 -2.9; 301 -2.7; 323 -2.3; 345 -2.0; 369 -1.8; 395 -1.5; 423 -1.1; 452 -0.6; 484 -0.4; 518 -0.1; 554 0.1; 593 0.4; 635 1.0; 679 1.5; 726 2.0; 777 2.3; 832 1.8; 890 1.2; 952 0.4; 1019 -0.0; 1090 0.0; 1167 0.3; 1248 0.7; 1336 0.9; 1429 1.5; 1529 1.2; 1636 0.2; 1751 -1.1; 1873 -1.8; 2004 -1.7; 2145 -1.2; 2295 -1.1; 2455 -0.7; 2627 0.3; 2811 1.7; 3008 2.6; 3219 3.7; 3444 5.9; 3685 5.8; 3943 -0.8; 4219 -5.4; 4514 -4.4; 4830 -1.7; 5168 0.8; 5530 -1.5; 5917 -7.2; 6331 -6.4; 6775 -3.1; 7249 0.3; 7756 0.3; 8299 0.0; 8880 -0.0; 9502 -2.0; 10167 -3.1; 10879 -1.5; 11640 0.0; 12455 0.0; 13327 0.0; 14260 -0.3; 15258 -2.3; 16326 -1.1; 17469 0.0; 18692 0.0; 20000 0.0
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Sonoma%20Model%20One/innerfidelity/onear/Bose%20Quiet%20Comfort%2015/Bose%20Quiet%20Comfort%2015.png)