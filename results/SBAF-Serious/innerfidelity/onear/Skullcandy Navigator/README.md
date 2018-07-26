# Skullcandy Navigator
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 -2.4; 22 -2.4; 23 -2.4; 25 -2.5; 26 -2.5; 28 -2.5; 30 -2.5; 32 -2.5; 35 -2.4; 37 -2.4; 40 -2.4; 42 -2.4; 45 -2.3; 49 -2.3; 52 -2.3; 56 -2.3; 59 -2.3; 64 -2.3; 68 -2.3; 73 -2.3; 78 -2.4; 83 -2.6; 89 -2.8; 95 -3.0; 102 -3.3; 109 -3.5; 117 -3.9; 125 -4.3; 134 -4.5; 143 -4.6; 153 -4.5; 164 -4.6; 175 -4.2; 188 -4.1; 201 -4.4; 215 -4.6; 230 -4.4; 246 -4.3; 263 -4.1; 282 -3.7; 301 -3.4; 323 -3.2; 345 -2.8; 369 -2.6; 395 -2.2; 423 -1.5; 452 -1.2; 484 -0.8; 518 -0.3; 554 0.2; 593 0.7; 635 0.9; 679 1.0; 726 1.3; 777 1.6; 832 1.1; 890 0.7; 952 0.3; 1019 0.1; 1090 0.2; 1167 0.1; 1248 -0.1; 1336 -0.1; 1429 -0.1; 1529 -0.3; 1636 0.3; 1751 0.6; 1873 1.0; 2004 1.5; 2145 2.1; 2295 2.7; 2455 3.4; 2627 3.9; 2811 4.0; 3008 4.4; 3219 4.8; 3444 5.2; 3685 5.5; 3943 6.0; 4219 6.0; 4514 6.0; 4830 6.0; 5168 6.0; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 -2.4; 22 -2.4; 23 -2.4; 25 -2.5; 26 -2.5; 28 -2.5; 30 -2.5; 32 -2.5; 35 -2.4; 37 -2.4; 40 -2.4; 42 -2.4; 45 -2.3; 49 -2.3; 52 -2.3; 56 -2.3; 59 -2.3; 64 -2.3; 68 -2.3; 73 -2.3; 78 -2.4; 83 -2.6; 89 -2.8; 95 -3.0; 102 -3.3; 109 -3.5; 117 -3.9; 125 -4.3; 134 -4.5; 143 -4.6; 153 -4.5; 164 -4.6; 175 -4.2; 188 -4.1; 201 -4.4; 215 -4.6; 230 -4.4; 246 -4.3; 263 -4.1; 282 -3.7; 301 -3.4; 323 -3.2; 345 -2.8; 369 -2.6; 395 -2.2; 423 -1.5; 452 -1.2; 484 -0.8; 518 -0.3; 554 0.2; 593 0.7; 635 0.9; 679 1.0; 726 1.3; 777 1.6; 832 1.1; 890 0.7; 952 0.3; 1019 0.1; 1090 0.2; 1167 0.1; 1248 -0.1; 1336 -0.1; 1429 -0.1; 1529 -0.3; 1636 0.3; 1751 0.6; 1873 1.0; 2004 1.5; 2145 2.1; 2295 2.7; 2455 3.4; 2627 3.9; 2811 4.0; 3008 4.4; 3219 4.8; 3444 5.2; 3685 5.5; 3943 6.0; 4219 6.0; 4514 6.0; 4830 6.0; 5168 6.0; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/SBAF-Serious/innerfidelity/onear/Skullcandy%20Navigator/Skullcandy%20Navigator.png)