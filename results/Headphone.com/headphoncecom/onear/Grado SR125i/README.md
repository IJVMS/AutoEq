# Grado SR125i
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 6.0; 32 6.0; 35 6.0; 37 6.0; 40 6.0; 42 6.0; 45 6.0; 49 5.9; 52 5.5; 56 4.8; 59 4.2; 64 3.4; 68 2.7; 73 1.9; 78 1.3; 83 0.7; 89 0.0; 95 -0.5; 102 -1.2; 109 -1.7; 117 -2.1; 125 -2.4; 134 -2.5; 143 -2.5; 153 -2.5; 164 -2.5; 175 -2.4; 188 -2.3; 201 -2.1; 215 -1.9; 230 -1.8; 246 -1.5; 263 -1.3; 282 -0.7; 301 -0.9; 323 -1.8; 345 -1.7; 369 -1.3; 395 -1.2; 423 -1.0; 452 -0.7; 484 -0.5; 518 -0.2; 554 0.1; 593 0.2; 635 0.5; 679 0.5; 726 0.6; 777 0.6; 832 0.5; 890 0.3; 952 0.1; 1019 -0.0; 1090 -0.2; 1167 -0.3; 1248 -0.2; 1336 -0.2; 1429 -0.2; 1529 -0.4; 1636 -0.9; 1751 -1.5; 1873 -2.3; 2004 -2.7; 2145 -3.1; 2295 -3.1; 2455 -2.3; 2627 -1.8; 2811 -0.4; 3008 0.1; 3219 0.5; 3444 0.4; 3685 0.4; 3943 0.7; 4219 2.0; 4514 0.9; 4830 0.3; 5168 1.1; 5530 -3.1; 5917 -3.3; 6331 -3.9; 6775 -5.3; 7249 -5.0; 7756 -5.2; 8299 -6.8; 8880 -8.2; 9502 -7.1; 10167 -2.7; 10879 -0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 -1.4
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 6.0; 32 6.0; 35 6.0; 37 6.0; 40 6.0; 42 6.0; 45 6.0; 49 5.9; 52 5.5; 56 4.8; 59 4.2; 64 3.4; 68 2.7; 73 1.9; 78 1.3; 83 0.7; 89 0.0; 95 -0.5; 102 -1.2; 109 -1.7; 117 -2.1; 125 -2.4; 134 -2.5; 143 -2.5; 153 -2.5; 164 -2.5; 175 -2.4; 188 -2.3; 201 -2.1; 215 -1.9; 230 -1.8; 246 -1.5; 263 -1.3; 282 -0.7; 301 -0.9; 323 -1.8; 345 -1.7; 369 -1.3; 395 -1.2; 423 -1.0; 452 -0.7; 484 -0.5; 518 -0.2; 554 0.1; 593 0.2; 635 0.5; 679 0.5; 726 0.6; 777 0.6; 832 0.5; 890 0.3; 952 0.1; 1019 -0.0; 1090 -0.2; 1167 -0.3; 1248 -0.2; 1336 -0.2; 1429 -0.2; 1529 -0.4; 1636 -0.9; 1751 -1.5; 1873 -2.3; 2004 -2.7; 2145 -3.1; 2295 -3.1; 2455 -2.3; 2627 -1.8; 2811 -0.4; 3008 0.1; 3219 0.5; 3444 0.4; 3685 0.4; 3943 0.7; 4219 2.0; 4514 0.9; 4830 0.3; 5168 1.1; 5530 -3.1; 5917 -3.3; 6331 -3.9; 6775 -5.3; 7249 -5.0; 7756 -5.2; 8299 -6.8; 8880 -8.2; 9502 -7.1; 10167 -2.7; 10879 -0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 -1.4
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Headphone.com/headphoncecom/onear/Grado%20SR125i/Grado%20SR125i.png)