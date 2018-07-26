# Grado SR60
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 6.0; 32 6.0; 35 6.0; 37 5.7; 40 5.1; 42 4.6; 45 4.0; 49 3.2; 52 2.7; 56 2.2; 59 2.0; 64 2.0; 68 2.5; 73 2.9; 78 2.9; 83 2.6; 89 1.9; 95 1.3; 102 0.6; 109 0.2; 117 -0.2; 125 -0.7; 134 -0.9; 143 -1.0; 153 -1.2; 164 -1.5; 175 -1.5; 188 -1.4; 201 -1.1; 215 -0.8; 230 -1.3; 246 -2.0; 263 -2.0; 282 -1.7; 301 -1.6; 323 -1.2; 345 -1.0; 369 -1.0; 395 -0.8; 423 -0.5; 452 -0.2; 484 -0.1; 518 -0.0; 554 -0.0; 593 0.2; 635 0.7; 679 1.0; 726 1.4; 777 1.5; 832 1.3; 890 0.7; 952 0.2; 1019 -0.1; 1090 0.2; 1167 0.7; 1248 1.1; 1336 1.1; 1429 0.8; 1529 0.2; 1636 -1.0; 1751 -2.5; 1873 -3.5; 2004 -4.3; 2145 -4.6; 2295 -4.9; 2455 -4.6; 2627 -3.9; 2811 -2.5; 3008 -0.3; 3219 1.1; 3444 1.7; 3685 1.9; 3943 0.3; 4219 -2.0; 4514 -5.8; 4830 -7.0; 5168 -4.6; 5530 -5.7; 5917 -5.1; 6331 -3.2; 6775 -3.6; 7249 -5.2; 7756 -7.0; 8299 -9.0; 8880 -9.8; 9502 -7.7; 10167 -3.3; 10879 -0.1; 11640 0.0; 12455 0.0; 13327 -0.2; 14260 -3.5; 15258 -6.1; 16326 -6.3; 17469 -4.9; 18692 -2.9; 20000 -0.7
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 6.0; 32 6.0; 35 6.0; 37 5.7; 40 5.1; 42 4.6; 45 4.0; 49 3.2; 52 2.7; 56 2.2; 59 2.0; 64 2.0; 68 2.5; 73 2.9; 78 2.9; 83 2.6; 89 1.9; 95 1.3; 102 0.6; 109 0.2; 117 -0.2; 125 -0.7; 134 -0.9; 143 -1.0; 153 -1.2; 164 -1.5; 175 -1.5; 188 -1.4; 201 -1.1; 215 -0.8; 230 -1.3; 246 -2.0; 263 -2.0; 282 -1.7; 301 -1.6; 323 -1.2; 345 -1.0; 369 -1.0; 395 -0.8; 423 -0.5; 452 -0.2; 484 -0.1; 518 -0.0; 554 -0.0; 593 0.2; 635 0.7; 679 1.0; 726 1.4; 777 1.5; 832 1.3; 890 0.7; 952 0.2; 1019 -0.1; 1090 0.2; 1167 0.7; 1248 1.1; 1336 1.1; 1429 0.8; 1529 0.2; 1636 -1.0; 1751 -2.5; 1873 -3.5; 2004 -4.3; 2145 -4.6; 2295 -4.9; 2455 -4.6; 2627 -3.9; 2811 -2.5; 3008 -0.3; 3219 1.1; 3444 1.7; 3685 1.9; 3943 0.3; 4219 -2.0; 4514 -5.8; 4830 -7.0; 5168 -4.6; 5530 -5.7; 5917 -5.1; 6331 -3.2; 6775 -3.6; 7249 -5.2; 7756 -7.0; 8299 -9.0; 8880 -9.8; 9502 -7.7; 10167 -3.3; 10879 -0.1; 11640 0.0; 12455 0.0; 13327 -0.2; 14260 -3.5; 15258 -6.1; 16326 -6.3; 17469 -4.9; 18692 -2.9; 20000 -0.7
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Sonoma%20Model%20One/headphoncecom/onear/Grado%20SR60/Grado%20SR60.png)