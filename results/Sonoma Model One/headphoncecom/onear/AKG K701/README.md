# AKG K701
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 6.0; 32 6.0; 35 6.0; 37 6.0; 40 6.0; 42 6.0; 45 6.0; 49 6.0; 52 5.8; 56 5.4; 59 5.5; 64 6.0; 68 6.0; 73 6.0; 78 5.7; 83 5.2; 89 4.4; 95 3.5; 102 2.6; 109 1.9; 117 1.2; 125 0.2; 134 -0.4; 143 -0.9; 153 -1.2; 164 -1.4; 175 -1.6; 188 -1.9; 201 -1.8; 215 -1.8; 230 -2.0; 246 -2.0; 263 -1.9; 282 -1.7; 301 -1.6; 323 -1.4; 345 -1.3; 369 -1.2; 395 -1.2; 423 -0.8; 452 -0.5; 484 -0.3; 518 -0.3; 554 0.9; 593 1.6; 635 1.2; 679 1.6; 726 1.9; 777 1.8; 832 1.3; 890 0.7; 952 0.1; 1019 -0.0; 1090 0.2; 1167 0.7; 1248 1.2; 1336 1.9; 1429 1.8; 1529 1.5; 1636 0.7; 1751 -0.7; 1873 -2.2; 2004 -3.2; 2145 -3.8; 2295 -3.6; 2455 -3.0; 2627 -2.1; 2811 -1.5; 3008 -1.1; 3219 -0.9; 3444 -1.2; 3685 -1.6; 3943 -2.2; 4219 -2.9; 4514 -2.7; 4830 -1.4; 5168 -2.2; 5530 -5.9; 5917 -8.9; 6331 -7.8; 6775 -5.3; 7249 -5.2; 7756 -5.5; 8299 -5.3; 8880 -4.8; 9502 -4.2; 10167 -3.6; 10879 -2.3; 11640 -0.4; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 6.0; 32 6.0; 35 6.0; 37 6.0; 40 6.0; 42 6.0; 45 6.0; 49 6.0; 52 5.8; 56 5.4; 59 5.5; 64 6.0; 68 6.0; 73 6.0; 78 5.7; 83 5.2; 89 4.4; 95 3.5; 102 2.6; 109 1.9; 117 1.2; 125 0.2; 134 -0.4; 143 -0.9; 153 -1.2; 164 -1.4; 175 -1.6; 188 -1.9; 201 -1.8; 215 -1.8; 230 -2.0; 246 -2.0; 263 -1.9; 282 -1.7; 301 -1.6; 323 -1.4; 345 -1.3; 369 -1.2; 395 -1.2; 423 -0.8; 452 -0.5; 484 -0.3; 518 -0.3; 554 0.9; 593 1.6; 635 1.2; 679 1.6; 726 1.9; 777 1.8; 832 1.3; 890 0.7; 952 0.1; 1019 -0.0; 1090 0.2; 1167 0.7; 1248 1.2; 1336 1.9; 1429 1.8; 1529 1.5; 1636 0.7; 1751 -0.7; 1873 -2.2; 2004 -3.2; 2145 -3.8; 2295 -3.6; 2455 -3.0; 2627 -2.1; 2811 -1.5; 3008 -1.1; 3219 -0.9; 3444 -1.2; 3685 -1.6; 3943 -2.2; 4219 -2.9; 4514 -2.7; 4830 -1.4; 5168 -2.2; 5530 -5.9; 5917 -8.9; 6331 -7.8; 6775 -5.3; 7249 -5.2; 7756 -5.5; 8299 -5.3; 8880 -4.8; 9502 -4.2; 10167 -3.6; 10879 -2.3; 11640 -0.4; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Sonoma%20Model%20One/headphoncecom/onear/AKG%20K701/AKG%20K701.png)