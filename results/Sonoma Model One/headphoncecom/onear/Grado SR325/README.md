# Grado SR325
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 6.0; 32 6.0; 35 6.0; 37 6.0; 40 6.0; 42 6.0; 45 6.0; 49 6.0; 52 5.9; 56 5.3; 59 4.9; 64 4.5; 68 4.4; 73 4.5; 78 4.4; 83 4.0; 89 3.3; 95 2.3; 102 1.5; 109 1.1; 117 0.7; 125 0.1; 134 -0.3; 143 -0.6; 153 -0.9; 164 -1.0; 175 -0.9; 188 -0.9; 201 -1.0; 215 -1.1; 230 -0.9; 246 -0.9; 263 -0.9; 282 -0.8; 301 -0.7; 323 -0.5; 345 -0.3; 369 -0.3; 395 -0.2; 423 -0.0; 452 0.2; 484 0.1; 518 0.2; 554 0.2; 593 0.4; 635 0.8; 679 1.2; 726 1.5; 777 1.6; 832 1.3; 890 0.8; 952 0.3; 1019 -0.1; 1090 0.2; 1167 0.7; 1248 1.1; 1336 1.0; 1429 0.7; 1529 -0.0; 1636 -1.3; 1751 -2.8; 1873 -5.2; 2004 -7.2; 2145 -7.2; 2295 -6.0; 2455 -4.9; 2627 -3.8; 2811 -2.6; 3008 -1.3; 3219 -0.4; 3444 0.0; 3685 -0.5; 3943 -3.1; 4219 -9.3; 4514 -13.1; 4830 -10.0; 5168 -7.2; 5530 -6.9; 5917 -7.2; 6331 -7.6; 6775 -7.5; 7249 -7.5; 7756 -8.3; 8299 -10.3; 8880 -12.8; 9502 -14.5; 10167 -14.6; 10879 -13.4; 11640 -11.0; 12455 -6.6; 13327 -1.2; 14260 0.0; 15258 0.0; 16326 -1.5; 17469 -1.3; 18692 0.0; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 6.0; 32 6.0; 35 6.0; 37 6.0; 40 6.0; 42 6.0; 45 6.0; 49 6.0; 52 5.9; 56 5.3; 59 4.9; 64 4.5; 68 4.4; 73 4.5; 78 4.4; 83 4.0; 89 3.3; 95 2.3; 102 1.5; 109 1.1; 117 0.7; 125 0.1; 134 -0.3; 143 -0.6; 153 -0.9; 164 -1.0; 175 -0.9; 188 -0.9; 201 -1.0; 215 -1.1; 230 -0.9; 246 -0.9; 263 -0.9; 282 -0.8; 301 -0.7; 323 -0.5; 345 -0.3; 369 -0.3; 395 -0.2; 423 -0.0; 452 0.2; 484 0.1; 518 0.2; 554 0.2; 593 0.4; 635 0.8; 679 1.2; 726 1.5; 777 1.6; 832 1.3; 890 0.8; 952 0.3; 1019 -0.1; 1090 0.2; 1167 0.7; 1248 1.1; 1336 1.0; 1429 0.7; 1529 -0.0; 1636 -1.3; 1751 -2.8; 1873 -5.2; 2004 -7.2; 2145 -7.2; 2295 -6.0; 2455 -4.9; 2627 -3.8; 2811 -2.6; 3008 -1.3; 3219 -0.4; 3444 0.0; 3685 -0.5; 3943 -3.1; 4219 -9.3; 4514 -13.1; 4830 -10.0; 5168 -7.2; 5530 -6.9; 5917 -7.2; 6331 -7.6; 6775 -7.5; 7249 -7.5; 7756 -8.3; 8299 -10.3; 8880 -12.8; 9502 -14.5; 10167 -14.6; 10879 -13.4; 11640 -11.0; 12455 -6.6; 13327 -1.2; 14260 0.0; 15258 0.0; 16326 -1.5; 17469 -1.3; 18692 0.0; 20000 0.0
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Sonoma%20Model%20One/headphoncecom/onear/Grado%20SR325/Grado%20SR325.png)