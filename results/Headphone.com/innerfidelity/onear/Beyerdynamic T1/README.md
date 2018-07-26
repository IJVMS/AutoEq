# Beyerdynamic T1
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-64**.
```
GraphicEQ: 10 -84; 20 6.4; 22 5.6; 23 5.3; 25 4.8; 26 4.5; 28 4.1; 30 3.8; 32 3.5; 35 3.1; 37 2.9; 40 2.7; 42 2.5; 45 2.3; 49 2.0; 52 2.0; 56 2.5; 59 2.7; 64 2.2; 68 1.6; 73 1.1; 78 0.7; 83 0.3; 89 -0.1; 95 -0.6; 102 -1.1; 109 -1.7; 117 -2.2; 125 -2.6; 134 -3.0; 143 -3.2; 153 -3.4; 164 -3.6; 175 -3.6; 188 -3.7; 201 -3.7; 215 -3.7; 230 -3.7; 246 -3.7; 263 -3.6; 282 -3.6; 301 -3.5; 323 -3.3; 345 -3.3; 369 -3.2; 395 -3.0; 423 -2.7; 452 -2.4; 484 -2.0; 518 -1.7; 554 -1.5; 593 -1.3; 635 -1.0; 679 -0.7; 726 -0.6; 777 -0.4; 832 -0.3; 890 -0.2; 952 -0.0; 1019 0.1; 1090 0.4; 1167 0.7; 1248 1.2; 1336 2.0; 1429 2.3; 1529 2.1; 1636 1.7; 1751 1.0; 1873 1.3; 2004 2.7; 2145 4.2; 2295 4.4; 2455 2.5; 2627 3.3; 2811 2.9; 3008 3.2; 3219 3.7; 3444 3.2; 3685 3.2; 3943 3.3; 4219 3.9; 4514 5.2; 4830 6.0; 5168 6.0; 5530 4.9; 5917 -1.1; 6331 -3.4; 6775 0.1; 7249 -3.3; 7756 -7.0; 8299 -10.2; 8880 -10.6; 9502 -6.9; 10167 -1.1; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 6.4; 22 5.6; 23 5.3; 25 4.8; 26 4.5; 28 4.1; 30 3.8; 32 3.5; 35 3.1; 37 2.9; 40 2.7; 42 2.5; 45 2.3; 49 2.0; 52 2.0; 56 2.5; 59 2.7; 64 2.2; 68 1.6; 73 1.1; 78 0.7; 83 0.3; 89 -0.1; 95 -0.6; 102 -1.1; 109 -1.7; 117 -2.2; 125 -2.6; 134 -3.0; 143 -3.2; 153 -3.4; 164 -3.6; 175 -3.6; 188 -3.7; 201 -3.7; 215 -3.7; 230 -3.7; 246 -3.7; 263 -3.6; 282 -3.6; 301 -3.5; 323 -3.3; 345 -3.3; 369 -3.2; 395 -3.0; 423 -2.7; 452 -2.4; 484 -2.0; 518 -1.7; 554 -1.5; 593 -1.3; 635 -1.0; 679 -0.7; 726 -0.6; 777 -0.4; 832 -0.3; 890 -0.2; 952 -0.0; 1019 0.1; 1090 0.4; 1167 0.7; 1248 1.2; 1336 2.0; 1429 2.3; 1529 2.1; 1636 1.7; 1751 1.0; 1873 1.3; 2004 2.7; 2145 4.2; 2295 4.4; 2455 2.5; 2627 3.3; 2811 2.9; 3008 3.2; 3219 3.7; 3444 3.2; 3685 3.2; 3943 3.3; 4219 3.9; 4514 5.2; 4830 6.0; 5168 6.0; 5530 4.9; 5917 -1.1; 6331 -3.4; 6775 0.1; 7249 -3.3; 7756 -7.0; 8299 -10.2; 8880 -10.6; 9502 -6.9; 10167 -1.1; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
Copy: L=-6.4dB*l, R=-6.4dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Headphone.com/innerfidelity/onear/Beyerdynamic%20T1/Beyerdynamic%20T1.png)