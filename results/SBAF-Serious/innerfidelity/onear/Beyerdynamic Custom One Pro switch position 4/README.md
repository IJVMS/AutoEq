# Beyerdynamic Custom One Pro switch position 4
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 0.7; 22 0.2; 23 0.0; 25 -0.4; 26 -0.6; 28 -1.0; 30 -1.2; 32 -1.5; 35 -1.7; 37 -1.9; 40 -2.1; 42 -2.2; 45 -2.3; 49 -2.5; 52 -2.5; 56 -2.3; 59 -2.3; 64 -2.4; 68 -2.3; 73 -2.3; 78 -2.3; 83 -1.5; 89 -0.0; 95 1.1; 102 0.9; 109 -0.7; 117 -2.8; 125 -4.4; 134 -5.3; 143 -5.7; 153 -5.6; 164 -3.9; 175 -4.4; 188 -5.0; 201 -4.3; 215 -3.6; 230 -2.5; 246 -2.0; 263 -1.7; 282 -1.2; 301 -0.9; 323 -0.7; 345 -0.6; 369 -0.5; 395 -0.6; 423 -0.5; 452 -0.6; 484 -0.8; 518 -0.9; 554 -0.8; 593 -0.6; 635 -0.6; 679 -0.8; 726 -0.7; 777 0.1; 832 0.5; 890 0.2; 952 0.1; 1019 0.1; 1090 0.2; 1167 0.1; 1248 -0.1; 1336 -0.4; 1429 -0.9; 1529 -1.5; 1636 -2.1; 1751 -2.4; 1873 -2.5; 2004 -2.5; 2145 -2.1; 2295 -1.2; 2455 0.5; 2627 1.9; 2811 3.1; 3008 4.3; 3219 4.9; 3444 5.5; 3685 6.0; 3943 6.0; 4219 6.0; 4514 6.0; 4830 6.0; 5168 6.0; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 0.7; 22 0.2; 23 0.0; 25 -0.4; 26 -0.6; 28 -1.0; 30 -1.2; 32 -1.5; 35 -1.7; 37 -1.9; 40 -2.1; 42 -2.2; 45 -2.3; 49 -2.5; 52 -2.5; 56 -2.3; 59 -2.3; 64 -2.4; 68 -2.3; 73 -2.3; 78 -2.3; 83 -1.5; 89 -0.0; 95 1.1; 102 0.9; 109 -0.7; 117 -2.8; 125 -4.4; 134 -5.3; 143 -5.7; 153 -5.6; 164 -3.9; 175 -4.4; 188 -5.0; 201 -4.3; 215 -3.6; 230 -2.5; 246 -2.0; 263 -1.7; 282 -1.2; 301 -0.9; 323 -0.7; 345 -0.6; 369 -0.5; 395 -0.6; 423 -0.5; 452 -0.6; 484 -0.8; 518 -0.9; 554 -0.8; 593 -0.6; 635 -0.6; 679 -0.8; 726 -0.7; 777 0.1; 832 0.5; 890 0.2; 952 0.1; 1019 0.1; 1090 0.2; 1167 0.1; 1248 -0.1; 1336 -0.4; 1429 -0.9; 1529 -1.5; 1636 -2.1; 1751 -2.4; 1873 -2.5; 2004 -2.5; 2145 -2.1; 2295 -1.2; 2455 0.5; 2627 1.9; 2811 3.1; 3008 4.3; 3219 4.9; 3444 5.5; 3685 6.0; 3943 6.0; 4219 6.0; 4514 6.0; 4830 6.0; 5168 6.0; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/SBAF-Serious/innerfidelity/onear/Beyerdynamic%20Custom%20One%20Pro%20switch%20position%204/Beyerdynamic%20Custom%20One%20Pro%20switch%20position%204.png)