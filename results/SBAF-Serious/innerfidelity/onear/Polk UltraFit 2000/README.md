# Polk UltraFit 2000
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 6.0; 32 6.0; 35 6.0; 37 6.0; 40 6.0; 42 6.0; 45 6.0; 49 6.0; 52 6.0; 56 6.0; 59 6.0; 64 6.0; 68 5.9; 73 5.2; 78 4.5; 83 3.8; 89 3.0; 95 2.3; 102 1.6; 109 1.2; 117 0.8; 125 0.4; 134 0.3; 143 0.2; 153 0.3; 164 0.4; 175 0.8; 188 1.0; 201 1.2; 215 1.6; 230 1.9; 246 2.2; 263 2.5; 282 2.9; 301 3.2; 323 4.1; 345 4.3; 369 4.6; 395 5.0; 423 5.7; 452 6.0; 484 6.0; 518 6.0; 554 6.0; 593 6.0; 635 6.0; 679 6.0; 726 6.0; 777 6.0; 832 6.0; 890 4.2; 952 1.7; 1019 -0.6; 1090 -1.7; 1167 -2.1; 1248 -2.6; 1336 -3.0; 1429 -3.1; 1529 -3.2; 1636 -3.4; 1751 -3.8; 1873 -3.9; 2004 -3.7; 2145 -3.1; 2295 -1.9; 2455 -0.3; 2627 1.2; 2811 2.4; 3008 3.6; 3219 3.7; 3444 3.2; 3685 2.2; 3943 2.0; 4219 2.7; 4514 4.1; 4830 5.8; 5168 6.0; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 -0.0; 8299 -3.2; 8880 -5.1; 9502 -4.7; 10167 -1.6; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 -1.4
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 6.0; 32 6.0; 35 6.0; 37 6.0; 40 6.0; 42 6.0; 45 6.0; 49 6.0; 52 6.0; 56 6.0; 59 6.0; 64 6.0; 68 5.9; 73 5.2; 78 4.5; 83 3.8; 89 3.0; 95 2.3; 102 1.6; 109 1.2; 117 0.8; 125 0.4; 134 0.3; 143 0.2; 153 0.3; 164 0.4; 175 0.8; 188 1.0; 201 1.2; 215 1.6; 230 1.9; 246 2.2; 263 2.5; 282 2.9; 301 3.2; 323 4.1; 345 4.3; 369 4.6; 395 5.0; 423 5.7; 452 6.0; 484 6.0; 518 6.0; 554 6.0; 593 6.0; 635 6.0; 679 6.0; 726 6.0; 777 6.0; 832 6.0; 890 4.2; 952 1.7; 1019 -0.6; 1090 -1.7; 1167 -2.1; 1248 -2.6; 1336 -3.0; 1429 -3.1; 1529 -3.2; 1636 -3.4; 1751 -3.8; 1873 -3.9; 2004 -3.7; 2145 -3.1; 2295 -1.9; 2455 -0.3; 2627 1.2; 2811 2.4; 3008 3.6; 3219 3.7; 3444 3.2; 3685 2.2; 3943 2.0; 4219 2.7; 4514 4.1; 4830 5.8; 5168 6.0; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 -0.0; 8299 -3.2; 8880 -5.1; 9502 -4.7; 10167 -1.6; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 -1.4
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/SBAF-Serious/innerfidelity/onear/Polk%20UltraFit%202000/Polk%20UltraFit%202000.png)