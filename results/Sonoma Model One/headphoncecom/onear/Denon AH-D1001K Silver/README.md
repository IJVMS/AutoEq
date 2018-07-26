# Denon AH-D1001K Silver
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 6.0; 32 6.0; 35 6.0; 37 6.0; 40 6.0; 42 6.0; 45 6.0; 49 6.0; 52 6.0; 56 6.0; 59 6.0; 64 6.0; 68 6.0; 73 6.0; 78 6.0; 83 5.8; 89 5.1; 95 4.3; 102 3.3; 109 2.8; 117 2.4; 125 1.8; 134 1.6; 143 1.4; 153 1.2; 164 1.1; 175 1.1; 188 1.4; 201 1.6; 215 1.7; 230 1.7; 246 1.6; 263 1.7; 282 2.0; 301 2.1; 323 2.4; 345 2.7; 369 2.9; 395 3.1; 423 3.4; 452 3.6; 484 3.8; 518 3.8; 554 3.7; 593 3.6; 635 3.4; 679 3.2; 726 2.6; 777 2.0; 832 1.3; 890 0.5; 952 0.1; 1019 0.0; 1090 0.8; 1167 2.0; 1248 2.8; 1336 3.4; 1429 3.9; 1529 4.2; 1636 3.9; 1751 3.5; 1873 3.5; 2004 4.0; 2145 4.6; 2295 5.3; 2455 5.8; 2627 5.6; 2811 5.0; 3008 4.7; 3219 3.8; 3444 3.2; 3685 5.7; 3943 3.6; 4219 -0.0; 4514 -0.2; 4830 0.8; 5168 2.7; 5530 4.3; 5917 4.7; 6331 3.3; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 -1.4; 9502 -4.9; 10167 -6.2; 10879 -3.5; 11640 -0.1; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 -0.8; 17469 -2.8; 18692 -0.1; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 6.0; 32 6.0; 35 6.0; 37 6.0; 40 6.0; 42 6.0; 45 6.0; 49 6.0; 52 6.0; 56 6.0; 59 6.0; 64 6.0; 68 6.0; 73 6.0; 78 6.0; 83 5.8; 89 5.1; 95 4.3; 102 3.3; 109 2.8; 117 2.4; 125 1.8; 134 1.6; 143 1.4; 153 1.2; 164 1.1; 175 1.1; 188 1.4; 201 1.6; 215 1.7; 230 1.7; 246 1.6; 263 1.7; 282 2.0; 301 2.1; 323 2.4; 345 2.7; 369 2.9; 395 3.1; 423 3.4; 452 3.6; 484 3.8; 518 3.8; 554 3.7; 593 3.6; 635 3.4; 679 3.2; 726 2.6; 777 2.0; 832 1.3; 890 0.5; 952 0.1; 1019 0.0; 1090 0.8; 1167 2.0; 1248 2.8; 1336 3.4; 1429 3.9; 1529 4.2; 1636 3.9; 1751 3.5; 1873 3.5; 2004 4.0; 2145 4.6; 2295 5.3; 2455 5.8; 2627 5.6; 2811 5.0; 3008 4.7; 3219 3.8; 3444 3.2; 3685 5.7; 3943 3.6; 4219 -0.0; 4514 -0.2; 4830 0.8; 5168 2.7; 5530 4.3; 5917 4.7; 6331 3.3; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 -1.4; 9502 -4.9; 10167 -6.2; 10879 -3.5; 11640 -0.1; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 -0.8; 17469 -2.8; 18692 -0.1; 20000 0.0
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Sonoma%20Model%20One/headphoncecom/onear/Denon%20AH-D1001K%20Silver/Denon%20AH-D1001K%20Silver.png)