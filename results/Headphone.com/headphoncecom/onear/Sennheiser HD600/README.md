# Sennheiser HD600
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 6.0; 32 5.8; 35 5.3; 37 4.9; 40 4.4; 42 4.1; 45 3.7; 49 3.3; 52 3.2; 56 3.4; 59 3.4; 64 2.3; 68 1.5; 73 1.0; 78 0.6; 83 0.3; 89 -0.2; 95 -0.6; 102 -1.3; 109 -1.7; 117 -2.2; 125 -2.8; 134 -2.9; 143 -3.0; 153 -3.2; 164 -3.3; 175 -3.4; 188 -3.2; 201 -3.2; 215 -3.0; 230 -2.9; 246 -2.9; 263 -2.7; 282 -2.5; 301 -2.2; 323 -2.1; 345 -2.0; 369 -1.6; 395 -1.4; 423 -1.0; 452 -0.7; 484 -0.5; 518 -0.3; 554 -0.1; 593 0.2; 635 0.5; 679 0.7; 726 0.9; 777 0.8; 832 0.6; 890 0.4; 952 0.1; 1019 0.2; 1090 0.5; 1167 0.5; 1248 0.8; 1336 1.2; 1429 1.7; 1529 2.2; 1636 2.3; 1751 2.4; 1873 2.2; 2004 2.3; 2145 2.1; 2295 1.7; 2455 1.5; 2627 1.2; 2811 0.7; 3008 -0.0; 3219 -1.2; 3444 -2.1; 3685 -2.4; 3943 -1.6; 4219 -0.7; 4514 0.1; 4830 1.3; 5168 3.2; 5530 5.6; 5917 5.9; 6331 4.1; 6775 2.6; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 6.0; 32 5.8; 35 5.3; 37 4.9; 40 4.4; 42 4.1; 45 3.7; 49 3.3; 52 3.2; 56 3.4; 59 3.4; 64 2.3; 68 1.5; 73 1.0; 78 0.6; 83 0.3; 89 -0.2; 95 -0.6; 102 -1.3; 109 -1.7; 117 -2.2; 125 -2.8; 134 -2.9; 143 -3.0; 153 -3.2; 164 -3.3; 175 -3.4; 188 -3.2; 201 -3.2; 215 -3.0; 230 -2.9; 246 -2.9; 263 -2.7; 282 -2.5; 301 -2.2; 323 -2.1; 345 -2.0; 369 -1.6; 395 -1.4; 423 -1.0; 452 -0.7; 484 -0.5; 518 -0.3; 554 -0.1; 593 0.2; 635 0.5; 679 0.7; 726 0.9; 777 0.8; 832 0.6; 890 0.4; 952 0.1; 1019 0.2; 1090 0.5; 1167 0.5; 1248 0.8; 1336 1.2; 1429 1.7; 1529 2.2; 1636 2.3; 1751 2.4; 1873 2.2; 2004 2.3; 2145 2.1; 2295 1.7; 2455 1.5; 2627 1.2; 2811 0.7; 3008 -0.0; 3219 -1.2; 3444 -2.1; 3685 -2.4; 3943 -1.6; 4219 -0.7; 4514 0.1; 4830 1.3; 5168 3.2; 5530 5.6; 5917 5.9; 6331 4.1; 6775 2.6; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Headphone.com/headphoncecom/onear/Sennheiser%20HD600/Sennheiser%20HD600.png)