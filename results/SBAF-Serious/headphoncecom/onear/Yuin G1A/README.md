# Yuin G1A
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 6.0; 32 6.0; 35 6.0; 37 6.0; 40 6.0; 42 6.0; 45 6.0; 49 6.0; 52 5.6; 56 4.8; 59 4.3; 64 3.4; 68 2.9; 73 2.5; 78 2.3; 83 1.7; 89 0.9; 95 0.3; 102 -0.4; 109 -1.0; 117 -1.5; 125 -2.1; 134 -2.5; 143 -2.7; 153 -3.1; 164 -3.0; 175 -2.9; 188 -2.8; 201 -2.8; 215 -2.7; 230 -2.4; 246 -2.2; 263 -2.2; 282 -2.0; 301 -1.8; 323 -1.5; 345 -1.2; 369 -1.0; 395 -0.8; 423 -0.5; 452 -0.4; 484 -0.3; 518 -0.1; 554 0.1; 593 0.2; 635 0.3; 679 0.3; 726 0.4; 777 0.6; 832 0.5; 890 0.4; 952 0.2; 1019 -0.0; 1090 -0.4; 1167 -0.4; 1248 -0.5; 1336 -1.0; 1429 -0.8; 1529 -1.4; 1636 -2.5; 1751 -3.2; 1873 -3.7; 2004 -4.2; 2145 -4.2; 2295 -4.2; 2455 -3.6; 2627 -2.1; 2811 0.2; 3008 2.5; 3219 5.9; 3444 6.0; 3685 6.0; 3943 4.1; 4219 -0.9; 4514 -6.0; 4830 -8.5; 5168 -4.9; 5530 -1.4; 5917 2.1; 6331 5.2; 6775 2.9; 7249 0.8; 7756 -0.2; 8299 -1.3; 8880 -3.0; 9502 -4.0; 10167 -2.6; 10879 -0.1; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 6.0; 32 6.0; 35 6.0; 37 6.0; 40 6.0; 42 6.0; 45 6.0; 49 6.0; 52 5.6; 56 4.8; 59 4.3; 64 3.4; 68 2.9; 73 2.5; 78 2.3; 83 1.7; 89 0.9; 95 0.3; 102 -0.4; 109 -1.0; 117 -1.5; 125 -2.1; 134 -2.5; 143 -2.7; 153 -3.1; 164 -3.0; 175 -2.9; 188 -2.8; 201 -2.8; 215 -2.7; 230 -2.4; 246 -2.2; 263 -2.2; 282 -2.0; 301 -1.8; 323 -1.5; 345 -1.2; 369 -1.0; 395 -0.8; 423 -0.5; 452 -0.4; 484 -0.3; 518 -0.1; 554 0.1; 593 0.2; 635 0.3; 679 0.3; 726 0.4; 777 0.6; 832 0.5; 890 0.4; 952 0.2; 1019 -0.0; 1090 -0.4; 1167 -0.4; 1248 -0.5; 1336 -1.0; 1429 -0.8; 1529 -1.4; 1636 -2.5; 1751 -3.2; 1873 -3.7; 2004 -4.2; 2145 -4.2; 2295 -4.2; 2455 -3.6; 2627 -2.1; 2811 0.2; 3008 2.5; 3219 5.9; 3444 6.0; 3685 6.0; 3943 4.1; 4219 -0.9; 4514 -6.0; 4830 -8.5; 5168 -4.9; 5530 -1.4; 5917 2.1; 6331 5.2; 6775 2.9; 7249 0.8; 7756 -0.2; 8299 -1.3; 8880 -3.0; 9502 -4.0; 10167 -2.6; 10879 -0.1; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/SBAF-Serious/headphoncecom/onear/Yuin%20G1A/Yuin%20G1A.png)