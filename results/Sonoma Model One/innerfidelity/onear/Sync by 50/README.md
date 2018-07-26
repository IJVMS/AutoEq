# Sync by 50
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-44**.
```
GraphicEQ: 10 -84; 20 1.3; 22 0.5; 23 0.1; 25 -0.6; 26 -0.9; 28 -1.5; 30 -2.0; 32 -2.5; 35 -3.1; 37 -3.5; 40 -4.1; 42 -4.4; 45 -4.9; 49 -5.4; 52 -5.8; 56 -6.1; 59 -6.2; 64 -6.1; 68 -5.8; 73 -5.4; 78 -5.2; 83 -5.5; 89 -6.2; 95 -7.0; 102 -7.8; 109 -8.2; 117 -8.7; 125 -9.3; 134 -9.8; 143 -10.1; 153 -10.3; 164 -10.3; 175 -10.2; 188 -10.1; 201 -9.9; 215 -9.5; 230 -9.3; 246 -9.2; 263 -9.2; 282 -9.7; 301 -9.5; 323 -9.3; 345 -9.1; 369 -8.8; 395 -8.7; 423 -8.6; 452 -8.2; 484 -7.8; 518 -6.9; 554 -5.5; 593 -3.2; 635 -0.6; 679 1.3; 726 2.8; 777 3.3; 832 2.7; 890 1.6; 952 0.6; 1019 -0.2; 1090 -0.2; 1167 0.4; 1248 1.4; 1336 2.6; 1429 3.1; 1529 2.1; 1636 0.4; 1751 -1.0; 1873 -2.0; 2004 -2.2; 2145 -1.7; 2295 -1.1; 2455 -0.2; 2627 1.1; 2811 1.9; 3008 2.6; 3219 2.7; 3444 2.0; 3685 1.1; 3943 -0.3; 4219 -0.7; 4514 1.5; 4830 3.7; 5168 4.3; 5530 1.1; 5917 0.2; 6331 3.3; 6775 -0.7; 7249 -1.8; 7756 0.1; 8299 0.0; 8880 0.0; 9502 0.0; 10167 -1.4; 10879 -1.7; 11640 -0.1; 12455 0.0; 13327 0.0; 14260 -0.6; 15258 -1.5; 16326 -0.2; 17469 0.0; 18692 0.0; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 1.3; 22 0.5; 23 0.1; 25 -0.6; 26 -0.9; 28 -1.5; 30 -2.0; 32 -2.5; 35 -3.1; 37 -3.5; 40 -4.1; 42 -4.4; 45 -4.9; 49 -5.4; 52 -5.8; 56 -6.1; 59 -6.2; 64 -6.1; 68 -5.8; 73 -5.4; 78 -5.2; 83 -5.5; 89 -6.2; 95 -7.0; 102 -7.8; 109 -8.2; 117 -8.7; 125 -9.3; 134 -9.8; 143 -10.1; 153 -10.3; 164 -10.3; 175 -10.2; 188 -10.1; 201 -9.9; 215 -9.5; 230 -9.3; 246 -9.2; 263 -9.2; 282 -9.7; 301 -9.5; 323 -9.3; 345 -9.1; 369 -8.8; 395 -8.7; 423 -8.6; 452 -8.2; 484 -7.8; 518 -6.9; 554 -5.5; 593 -3.2; 635 -0.6; 679 1.3; 726 2.8; 777 3.3; 832 2.7; 890 1.6; 952 0.6; 1019 -0.2; 1090 -0.2; 1167 0.4; 1248 1.4; 1336 2.6; 1429 3.1; 1529 2.1; 1636 0.4; 1751 -1.0; 1873 -2.0; 2004 -2.2; 2145 -1.7; 2295 -1.1; 2455 -0.2; 2627 1.1; 2811 1.9; 3008 2.6; 3219 2.7; 3444 2.0; 3685 1.1; 3943 -0.3; 4219 -0.7; 4514 1.5; 4830 3.7; 5168 4.3; 5530 1.1; 5917 0.2; 6331 3.3; 6775 -0.7; 7249 -1.8; 7756 0.1; 8299 0.0; 8880 0.0; 9502 0.0; 10167 -1.4; 10879 -1.7; 11640 -0.1; 12455 0.0; 13327 0.0; 14260 -0.6; 15258 -1.5; 16326 -0.2; 17469 0.0; 18692 0.0; 20000 0.0
Copy: L=-4.4dB*l, R=-4.4dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Sonoma%20Model%20One/innerfidelity/onear/Sync%20by%2050/Sync%20by%2050.png)