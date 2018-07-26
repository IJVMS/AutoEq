# Polk Audio UltraFit 2000
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 6.0; 32 6.0; 35 6.0; 37 6.0; 40 6.0; 42 6.0; 45 6.0; 49 6.0; 52 6.0; 56 6.0; 59 5.9; 64 5.3; 68 5.0; 73 4.7; 78 4.2; 83 3.6; 89 2.5; 95 1.3; 102 0.2; 109 -0.4; 117 -0.9; 125 -1.6; 134 -2.2; 143 -2.6; 153 -2.7; 164 -2.8; 175 -2.5; 188 -2.3; 201 -2.1; 215 -1.9; 230 -1.6; 246 -1.4; 263 -1.1; 282 -0.8; 301 -0.2; 323 0.4; 345 0.7; 369 1.2; 395 1.7; 423 2.0; 452 2.4; 484 2.8; 518 3.1; 554 3.5; 593 4.0; 635 4.5; 679 5.0; 726 5.0; 777 4.7; 832 3.4; 890 1.7; 952 0.2; 1019 0.1; 1090 0.3; 1167 0.2; 1248 0.8; 1336 1.7; 1429 1.4; 1529 0.4; 1636 -0.2; 1751 -0.4; 1873 0.1; 2004 1.2; 2145 2.8; 2295 4.3; 2455 5.9; 2627 6.0; 2811 6.0; 3008 6.0; 3219 6.0; 3444 6.0; 3685 6.0; 3943 6.0; 4219 6.0; 4514 6.0; 4830 6.0; 5168 6.0; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 -0.4; 9502 -1.4; 10167 -0.4; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 6.0; 32 6.0; 35 6.0; 37 6.0; 40 6.0; 42 6.0; 45 6.0; 49 6.0; 52 6.0; 56 6.0; 59 5.9; 64 5.3; 68 5.0; 73 4.7; 78 4.2; 83 3.6; 89 2.5; 95 1.3; 102 0.2; 109 -0.4; 117 -0.9; 125 -1.6; 134 -2.2; 143 -2.6; 153 -2.7; 164 -2.8; 175 -2.5; 188 -2.3; 201 -2.1; 215 -1.9; 230 -1.6; 246 -1.4; 263 -1.1; 282 -0.8; 301 -0.2; 323 0.4; 345 0.7; 369 1.2; 395 1.7; 423 2.0; 452 2.4; 484 2.8; 518 3.1; 554 3.5; 593 4.0; 635 4.5; 679 5.0; 726 5.0; 777 4.7; 832 3.4; 890 1.7; 952 0.2; 1019 0.1; 1090 0.3; 1167 0.2; 1248 0.8; 1336 1.7; 1429 1.4; 1529 0.4; 1636 -0.2; 1751 -0.4; 1873 0.1; 2004 1.2; 2145 2.8; 2295 4.3; 2455 5.9; 2627 6.0; 2811 6.0; 3008 6.0; 3219 6.0; 3444 6.0; 3685 6.0; 3943 6.0; 4219 6.0; 4514 6.0; 4830 6.0; 5168 6.0; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 -0.4; 9502 -1.4; 10167 -0.4; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Sonoma%20Model%20One/headphoncecom/onear/Polk%20Audio%20UltraFit%202000/Polk%20Audio%20UltraFit%202000.png)