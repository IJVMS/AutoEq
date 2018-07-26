# Beyerdynamic Tesla T1
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 3.0; 22 2.5; 23 2.3; 25 1.9; 26 1.7; 28 1.4; 30 1.2; 32 0.9; 35 0.6; 37 0.4; 40 0.2; 42 0.1; 45 -0.1; 49 -0.4; 52 -0.5; 56 -0.5; 59 -0.5; 64 0.0; 68 0.3; 73 -0.5; 78 -1.1; 83 -1.6; 89 -2.1; 95 -2.4; 102 -2.9; 109 -3.5; 117 -3.9; 125 -4.3; 134 -4.7; 143 -5.1; 153 -5.3; 164 -5.2; 175 -5.2; 188 -5.3; 201 -5.3; 215 -5.3; 230 -5.3; 246 -5.4; 263 -5.1; 282 -5.0; 301 -5.0; 323 -4.8; 345 -4.7; 369 -4.4; 395 -4.1; 423 -3.9; 452 -3.6; 484 -3.2; 518 -2.6; 554 -2.2; 593 -2.1; 635 -1.7; 679 -1.2; 726 -0.9; 777 -0.5; 832 -0.5; 890 -0.4; 952 -0.2; 1019 0.1; 1090 0.5; 1167 1.1; 1248 1.9; 1336 2.9; 1429 3.1; 1529 3.0; 1636 2.2; 1751 1.6; 1873 1.0; 2004 1.0; 2145 1.9; 2295 2.9; 2455 3.4; 2627 3.5; 2811 2.6; 3008 1.9; 3219 2.3; 3444 2.7; 3685 2.3; 3943 2.3; 4219 3.0; 4514 5.2; 4830 6.0; 5168 6.0; 5530 5.5; 5917 4.5; 6331 5.2; 6775 3.3; 7249 0.9; 7756 -3.1; 8299 -6.7; 8880 -7.5; 9502 -4.6; 10167 -0.3; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 3.0; 22 2.5; 23 2.3; 25 1.9; 26 1.7; 28 1.4; 30 1.2; 32 0.9; 35 0.6; 37 0.4; 40 0.2; 42 0.1; 45 -0.1; 49 -0.4; 52 -0.5; 56 -0.5; 59 -0.5; 64 0.0; 68 0.3; 73 -0.5; 78 -1.1; 83 -1.6; 89 -2.1; 95 -2.4; 102 -2.9; 109 -3.5; 117 -3.9; 125 -4.3; 134 -4.7; 143 -5.1; 153 -5.3; 164 -5.2; 175 -5.2; 188 -5.3; 201 -5.3; 215 -5.3; 230 -5.3; 246 -5.4; 263 -5.1; 282 -5.0; 301 -5.0; 323 -4.8; 345 -4.7; 369 -4.4; 395 -4.1; 423 -3.9; 452 -3.6; 484 -3.2; 518 -2.6; 554 -2.2; 593 -2.1; 635 -1.7; 679 -1.2; 726 -0.9; 777 -0.5; 832 -0.5; 890 -0.4; 952 -0.2; 1019 0.1; 1090 0.5; 1167 1.1; 1248 1.9; 1336 2.9; 1429 3.1; 1529 3.0; 1636 2.2; 1751 1.6; 1873 1.0; 2004 1.0; 2145 1.9; 2295 2.9; 2455 3.4; 2627 3.5; 2811 2.6; 3008 1.9; 3219 2.3; 3444 2.7; 3685 2.3; 3943 2.3; 4219 3.0; 4514 5.2; 4830 6.0; 5168 6.0; 5530 5.5; 5917 4.5; 6331 5.2; 6775 3.3; 7249 0.9; 7756 -3.1; 8299 -6.7; 8880 -7.5; 9502 -4.6; 10167 -0.3; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Headphone.com/headphoncecom/onear/Beyerdynamic%20Tesla%20T1/Beyerdynamic%20Tesla%20T1.png)