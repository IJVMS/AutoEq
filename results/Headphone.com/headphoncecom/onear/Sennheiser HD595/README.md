# Sennheiser HD595
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 6.0; 32 6.0; 35 5.8; 37 5.5; 40 5.0; 42 4.7; 45 4.2; 49 3.8; 52 3.7; 56 3.8; 59 3.7; 64 3.2; 68 3.7; 73 4.2; 78 2.9; 83 2.0; 89 1.3; 95 0.7; 102 0.1; 109 -0.5; 117 -1.0; 125 -1.6; 134 -2.0; 143 -2.4; 153 -2.5; 164 -2.4; 175 -2.7; 188 -2.8; 201 -2.8; 215 -2.8; 230 -2.7; 246 -2.8; 263 -2.8; 282 -2.8; 301 -2.7; 323 -2.6; 345 -2.3; 369 -2.0; 395 -1.8; 423 -1.3; 452 -1.0; 484 -1.0; 518 -0.9; 554 -0.8; 593 -0.7; 635 -0.6; 679 0.7; 726 0.3; 777 0.2; 832 0.2; 890 0.2; 952 0.0; 1019 0.0; 1090 0.3; 1167 0.8; 1248 1.4; 1336 2.4; 1429 3.4; 1529 4.1; 1636 4.6; 1751 4.7; 1873 4.4; 2004 3.9; 2145 3.6; 2295 3.5; 2455 4.0; 2627 4.7; 2811 4.7; 3008 4.0; 3219 3.3; 3444 3.3; 3685 3.9; 3943 5.0; 4219 6.0; 4514 6.0; 4830 6.0; 5168 6.0; 5530 6.0; 5917 5.9; 6331 5.5; 6775 2.3; 7249 1.2; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 6.0; 32 6.0; 35 5.8; 37 5.5; 40 5.0; 42 4.7; 45 4.2; 49 3.8; 52 3.7; 56 3.8; 59 3.7; 64 3.2; 68 3.7; 73 4.2; 78 2.9; 83 2.0; 89 1.3; 95 0.7; 102 0.1; 109 -0.5; 117 -1.0; 125 -1.6; 134 -2.0; 143 -2.4; 153 -2.5; 164 -2.4; 175 -2.7; 188 -2.8; 201 -2.8; 215 -2.8; 230 -2.7; 246 -2.8; 263 -2.8; 282 -2.8; 301 -2.7; 323 -2.6; 345 -2.3; 369 -2.0; 395 -1.8; 423 -1.3; 452 -1.0; 484 -1.0; 518 -0.9; 554 -0.8; 593 -0.7; 635 -0.6; 679 0.7; 726 0.3; 777 0.2; 832 0.2; 890 0.2; 952 0.0; 1019 0.0; 1090 0.3; 1167 0.8; 1248 1.4; 1336 2.4; 1429 3.4; 1529 4.1; 1636 4.6; 1751 4.7; 1873 4.4; 2004 3.9; 2145 3.6; 2295 3.5; 2455 4.0; 2627 4.7; 2811 4.7; 3008 4.0; 3219 3.3; 3444 3.3; 3685 3.9; 3943 5.0; 4219 6.0; 4514 6.0; 4830 6.0; 5168 6.0; 5530 6.0; 5917 5.9; 6331 5.5; 6775 2.3; 7249 1.2; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Headphone.com/headphoncecom/onear/Sennheiser%20HD595/Sennheiser%20HD595.png)