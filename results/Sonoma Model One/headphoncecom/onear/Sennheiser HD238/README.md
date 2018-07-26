# Sennheiser HD238
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 6.0; 22 5.9; 23 5.8; 25 5.3; 26 5.1; 28 4.6; 30 4.1; 32 3.7; 35 3.2; 37 2.8; 40 2.4; 42 2.2; 45 1.8; 49 1.2; 52 0.7; 56 0.3; 59 0.2; 64 0.5; 68 0.8; 73 1.0; 78 0.9; 83 0.6; 89 -0.1; 95 -0.9; 102 -1.9; 109 -2.4; 117 -3.0; 125 -3.7; 134 -4.1; 143 -4.4; 153 -4.6; 164 -4.9; 175 -4.9; 188 -4.8; 201 -4.9; 215 -4.7; 230 -4.6; 246 -4.5; 263 -4.4; 282 -4.1; 301 -3.9; 323 -3.5; 345 -3.2; 369 -2.9; 395 -2.7; 423 -2.3; 452 -2.1; 484 -1.7; 518 -1.6; 554 -1.3; 593 -0.9; 635 -0.3; 679 0.2; 726 0.7; 777 1.0; 832 0.9; 890 0.6; 952 0.2; 1019 0.0; 1090 0.4; 1167 1.0; 1248 1.4; 1336 1.5; 1429 1.3; 1529 1.0; 1636 1.2; 1751 0.3; 1873 0.0; 2004 0.5; 2145 1.7; 2295 2.6; 2455 3.2; 2627 2.3; 2811 0.6; 3008 -0.8; 3219 -2.4; 3444 -1.3; 3685 1.3; 3943 1.5; 4219 -2.4; 4514 -4.0; 4830 -1.6; 5168 -0.2; 5530 -2.0; 5917 -4.6; 6331 -4.5; 6775 -2.7; 7249 -1.8; 7756 -1.4; 8299 -2.5; 8880 -4.2; 9502 -4.2; 10167 -1.5; 10879 0.0; 11640 0.0; 12455 0.0; 13327 -0.1; 14260 -3.5; 15258 -6.6; 16326 -6.6; 17469 -4.0; 18692 -0.5; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 6.0; 22 5.9; 23 5.8; 25 5.3; 26 5.1; 28 4.6; 30 4.1; 32 3.7; 35 3.2; 37 2.8; 40 2.4; 42 2.2; 45 1.8; 49 1.2; 52 0.7; 56 0.3; 59 0.2; 64 0.5; 68 0.8; 73 1.0; 78 0.9; 83 0.6; 89 -0.1; 95 -0.9; 102 -1.9; 109 -2.4; 117 -3.0; 125 -3.7; 134 -4.1; 143 -4.4; 153 -4.6; 164 -4.9; 175 -4.9; 188 -4.8; 201 -4.9; 215 -4.7; 230 -4.6; 246 -4.5; 263 -4.4; 282 -4.1; 301 -3.9; 323 -3.5; 345 -3.2; 369 -2.9; 395 -2.7; 423 -2.3; 452 -2.1; 484 -1.7; 518 -1.6; 554 -1.3; 593 -0.9; 635 -0.3; 679 0.2; 726 0.7; 777 1.0; 832 0.9; 890 0.6; 952 0.2; 1019 0.0; 1090 0.4; 1167 1.0; 1248 1.4; 1336 1.5; 1429 1.3; 1529 1.0; 1636 1.2; 1751 0.3; 1873 0.0; 2004 0.5; 2145 1.7; 2295 2.6; 2455 3.2; 2627 2.3; 2811 0.6; 3008 -0.8; 3219 -2.4; 3444 -1.3; 3685 1.3; 3943 1.5; 4219 -2.4; 4514 -4.0; 4830 -1.6; 5168 -0.2; 5530 -2.0; 5917 -4.6; 6331 -4.5; 6775 -2.7; 7249 -1.8; 7756 -1.4; 8299 -2.5; 8880 -4.2; 9502 -4.2; 10167 -1.5; 10879 0.0; 11640 0.0; 12455 0.0; 13327 -0.1; 14260 -3.5; 15258 -6.6; 16326 -6.6; 17469 -4.0; 18692 -0.5; 20000 0.0
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Sonoma%20Model%20One/headphoncecom/onear/Sennheiser%20HD238/Sennheiser%20HD238.png)