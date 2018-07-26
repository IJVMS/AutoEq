# Audez'e LCD-3 #2312454
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-58**.
```
GraphicEQ: 10 -84; 20 2.9; 22 3.0; 23 3.1; 25 3.1; 26 3.2; 28 3.2; 30 3.1; 32 2.9; 35 2.7; 37 2.7; 40 2.7; 42 2.8; 45 3.0; 49 2.7; 52 2.0; 56 1.4; 59 1.3; 64 1.5; 68 1.5; 73 1.5; 78 1.5; 83 1.3; 89 1.0; 95 0.7; 102 0.4; 109 0.1; 117 -0.3; 125 -0.7; 134 -1.0; 143 -1.2; 153 -1.3; 164 -1.5; 175 -1.6; 188 -1.7; 201 -1.8; 215 -1.8; 230 -1.7; 246 -1.8; 263 -1.8; 282 -1.8; 301 -1.9; 323 -2.0; 345 -2.0; 369 -1.9; 395 -1.9; 423 -1.7; 452 -1.6; 484 -1.5; 518 -1.5; 554 -1.5; 593 -1.5; 635 -1.7; 679 -1.8; 726 -1.8; 777 -1.4; 832 -1.3; 890 -0.8; 952 -0.2; 1019 0.1; 1090 0.3; 1167 0.4; 1248 0.7; 1336 0.4; 1429 0.3; 1529 -0.0; 1636 0.1; 1751 0.6; 1873 1.0; 2004 1.2; 2145 0.9; 2295 1.0; 2455 1.1; 2627 1.0; 2811 0.7; 3008 1.0; 3219 1.3; 3444 2.1; 3685 2.5; 3943 2.5; 4219 2.5; 4514 4.6; 4830 5.5; 5168 5.5; 5530 4.1; 5917 5.1; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 -0.3; 16326 -2.5; 17469 -5.6; 18692 -6.6; 20000 -3.3
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 2.9; 22 3.0; 23 3.1; 25 3.1; 26 3.2; 28 3.2; 30 3.1; 32 2.9; 35 2.7; 37 2.7; 40 2.7; 42 2.8; 45 3.0; 49 2.7; 52 2.0; 56 1.4; 59 1.3; 64 1.5; 68 1.5; 73 1.5; 78 1.5; 83 1.3; 89 1.0; 95 0.7; 102 0.4; 109 0.1; 117 -0.3; 125 -0.7; 134 -1.0; 143 -1.2; 153 -1.3; 164 -1.5; 175 -1.6; 188 -1.7; 201 -1.8; 215 -1.8; 230 -1.7; 246 -1.8; 263 -1.8; 282 -1.8; 301 -1.9; 323 -2.0; 345 -2.0; 369 -1.9; 395 -1.9; 423 -1.7; 452 -1.6; 484 -1.5; 518 -1.5; 554 -1.5; 593 -1.5; 635 -1.7; 679 -1.8; 726 -1.8; 777 -1.4; 832 -1.3; 890 -0.8; 952 -0.2; 1019 0.1; 1090 0.3; 1167 0.4; 1248 0.7; 1336 0.4; 1429 0.3; 1529 -0.0; 1636 0.1; 1751 0.6; 1873 1.0; 2004 1.2; 2145 0.9; 2295 1.0; 2455 1.1; 2627 1.0; 2811 0.7; 3008 1.0; 3219 1.3; 3444 2.1; 3685 2.5; 3943 2.5; 4219 2.5; 4514 4.6; 4830 5.5; 5168 5.5; 5530 4.1; 5917 5.1; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 -0.3; 16326 -2.5; 17469 -5.6; 18692 -6.6; 20000 -3.3
Copy: L=-5.8dB*l, R=-5.8dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/SBAF-Serious/innerfidelity/onear/Audez'e%20LCD-3%20#2312454/Audez'e%20LCD-3%20#2312454.png)