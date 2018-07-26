# Audeze LCD-3
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 0.8; 22 1.4; 23 1.5; 25 1.5; 26 1.3; 28 0.9; 30 0.6; 32 0.6; 35 0.8; 37 0.8; 40 0.4; 42 0.2; 45 -0.1; 49 -0.7; 52 -0.7; 56 -0.4; 59 -0.3; 64 -0.4; 68 -0.4; 73 -0.5; 78 -0.6; 83 -0.7; 89 -0.8; 95 -1.1; 102 -1.4; 109 -1.6; 117 -1.9; 125 -2.4; 134 -2.7; 143 -2.9; 153 -3.0; 164 -3.2; 175 -3.4; 188 -3.5; 201 -3.7; 215 -3.6; 230 -3.7; 246 -3.8; 263 -3.8; 282 -3.5; 301 -2.8; 323 -2.3; 345 -2.1; 369 -2.0; 395 -2.3; 423 -2.7; 452 -3.0; 484 -3.1; 518 -2.8; 554 -2.6; 593 -2.3; 635 -2.4; 679 -2.4; 726 -2.1; 777 -2.2; 832 -2.5; 890 -1.7; 952 -0.6; 1019 0.2; 1090 0.9; 1167 0.8; 1248 -0.2; 1336 -0.3; 1429 -0.5; 1529 -0.8; 1636 -0.3; 1751 0.4; 1873 1.4; 2004 2.4; 2145 1.9; 2295 0.7; 2455 1.8; 2627 1.6; 2811 1.5; 3008 1.3; 3219 1.8; 3444 3.4; 3685 5.8; 3943 6.0; 4219 6.0; 4514 5.5; 4830 3.8; 5168 2.1; 5530 0.7; 5917 1.3; 6331 2.3; 6775 3.2; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 -0.2; 15258 -2.6; 16326 -5.7; 17469 -7.7; 18692 -7.7; 20000 -5.3
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 0.8; 22 1.4; 23 1.5; 25 1.5; 26 1.3; 28 0.9; 30 0.6; 32 0.6; 35 0.8; 37 0.8; 40 0.4; 42 0.2; 45 -0.1; 49 -0.7; 52 -0.7; 56 -0.4; 59 -0.3; 64 -0.4; 68 -0.4; 73 -0.5; 78 -0.6; 83 -0.7; 89 -0.8; 95 -1.1; 102 -1.4; 109 -1.6; 117 -1.9; 125 -2.4; 134 -2.7; 143 -2.9; 153 -3.0; 164 -3.2; 175 -3.4; 188 -3.5; 201 -3.7; 215 -3.6; 230 -3.7; 246 -3.8; 263 -3.8; 282 -3.5; 301 -2.8; 323 -2.3; 345 -2.1; 369 -2.0; 395 -2.3; 423 -2.7; 452 -3.0; 484 -3.1; 518 -2.8; 554 -2.6; 593 -2.3; 635 -2.4; 679 -2.4; 726 -2.1; 777 -2.2; 832 -2.5; 890 -1.7; 952 -0.6; 1019 0.2; 1090 0.9; 1167 0.8; 1248 -0.2; 1336 -0.3; 1429 -0.5; 1529 -0.8; 1636 -0.3; 1751 0.4; 1873 1.4; 2004 2.4; 2145 1.9; 2295 0.7; 2455 1.8; 2627 1.6; 2811 1.5; 3008 1.3; 3219 1.8; 3444 3.4; 3685 5.8; 3943 6.0; 4219 6.0; 4514 5.5; 4830 3.8; 5168 2.1; 5530 0.7; 5917 1.3; 6331 2.3; 6775 3.2; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 -0.2; 15258 -2.6; 16326 -5.7; 17469 -7.7; 18692 -7.7; 20000 -5.3
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/SBAF-Serious/headphoncecom/onear/Audeze%20LCD-3/Audeze%20LCD-3.png)