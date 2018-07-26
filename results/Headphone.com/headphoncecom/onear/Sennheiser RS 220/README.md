# Sennheiser RS 220
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 5.9; 25 5.7; 26 5.5; 28 5.0; 30 4.6; 32 4.3; 35 3.8; 37 3.5; 40 3.2; 42 2.9; 45 2.7; 49 2.4; 52 2.2; 56 1.9; 59 1.6; 64 1.6; 68 2.2; 73 2.2; 78 1.2; 83 0.5; 89 0.0; 95 -0.5; 102 -1.1; 109 -1.7; 117 -2.1; 125 -2.5; 134 -2.8; 143 -3.1; 153 -3.1; 164 -3.0; 175 -3.2; 188 -3.2; 201 -3.2; 215 -3.1; 230 -2.7; 246 -2.5; 263 -2.4; 282 -2.3; 301 -2.2; 323 -2.2; 345 -2.0; 369 -1.8; 395 -1.8; 423 -1.6; 452 -1.4; 484 -0.9; 518 -0.5; 554 -0.2; 593 -0.1; 635 0.1; 679 0.3; 726 0.4; 777 0.4; 832 0.3; 890 0.3; 952 0.2; 1019 -0.1; 1090 0.3; 1167 0.1; 1248 0.4; 1336 1.7; 1429 4.2; 1529 5.9; 1636 6.0; 1751 6.0; 1873 6.0; 2004 5.3; 2145 2.7; 2295 0.2; 2455 -0.8; 2627 -0.3; 2811 1.2; 3008 2.1; 3219 2.4; 3444 3.3; 3685 5.5; 3943 6.0; 4219 6.0; 4514 6.0; 4830 6.0; 5168 6.0; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.3; 7249 0.4; 7756 0.2; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 5.9; 25 5.7; 26 5.5; 28 5.0; 30 4.6; 32 4.3; 35 3.8; 37 3.5; 40 3.2; 42 2.9; 45 2.7; 49 2.4; 52 2.2; 56 1.9; 59 1.6; 64 1.6; 68 2.2; 73 2.2; 78 1.2; 83 0.5; 89 0.0; 95 -0.5; 102 -1.1; 109 -1.7; 117 -2.1; 125 -2.5; 134 -2.8; 143 -3.1; 153 -3.1; 164 -3.0; 175 -3.2; 188 -3.2; 201 -3.2; 215 -3.1; 230 -2.7; 246 -2.5; 263 -2.4; 282 -2.3; 301 -2.2; 323 -2.2; 345 -2.0; 369 -1.8; 395 -1.8; 423 -1.6; 452 -1.4; 484 -0.9; 518 -0.5; 554 -0.2; 593 -0.1; 635 0.1; 679 0.3; 726 0.4; 777 0.4; 832 0.3; 890 0.3; 952 0.2; 1019 -0.1; 1090 0.3; 1167 0.1; 1248 0.4; 1336 1.7; 1429 4.2; 1529 5.9; 1636 6.0; 1751 6.0; 1873 6.0; 2004 5.3; 2145 2.7; 2295 0.2; 2455 -0.8; 2627 -0.3; 2811 1.2; 3008 2.1; 3219 2.4; 3444 3.3; 3685 5.5; 3943 6.0; 4219 6.0; 4514 6.0; 4830 6.0; 5168 6.0; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.3; 7249 0.4; 7756 0.2; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Headphone.com/headphoncecom/onear/Sennheiser%20RS%20220/Sennheiser%20RS%20220.png)