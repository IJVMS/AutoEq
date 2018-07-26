# Superlux HD 681
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 6.0; 32 6.0; 35 6.0; 37 6.0; 40 6.0; 42 6.0; 45 6.0; 49 6.0; 52 6.0; 56 6.0; 59 6.0; 64 6.0; 68 6.0; 73 6.0; 78 6.0; 83 6.0; 89 6.0; 95 5.8; 102 4.9; 109 4.3; 117 3.6; 125 3.0; 134 2.2; 143 1.6; 153 1.4; 164 1.3; 175 1.9; 188 1.8; 201 1.4; 215 1.2; 230 1.3; 246 1.2; 263 1.2; 282 1.3; 301 1.6; 323 1.9; 345 2.2; 369 2.1; 395 2.0; 423 2.2; 452 2.3; 484 2.2; 518 1.9; 554 1.6; 593 1.9; 635 2.3; 679 2.3; 726 2.5; 777 2.4; 832 1.7; 890 1.1; 952 0.3; 1019 -0.1; 1090 0.1; 1167 0.4; 1248 0.6; 1336 0.4; 1429 -0.0; 1529 -0.4; 1636 -1.1; 1751 -2.0; 1873 -3.6; 2004 -4.2; 2145 -4.4; 2295 -4.4; 2455 -4.2; 2627 -3.3; 2811 -2.6; 3008 -1.4; 3219 -0.5; 3444 0.4; 3685 0.9; 3943 0.2; 4219 -1.2; 4514 -3.4; 4830 -4.4; 5168 -2.6; 5530 -6.6; 5917 -7.7; 6331 -4.7; 6775 -0.7; 7249 -3.7; 7756 -8.0; 8299 -11.0; 8880 -11.6; 9502 -11.1; 10167 -9.8; 10879 -6.6; 11640 -1.8; 12455 0.0; 13327 -1.9; 14260 -5.6; 15258 -5.4; 16326 -2.5; 17469 -0.9; 18692 -1.7; 20000 -3.5
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 6.0; 32 6.0; 35 6.0; 37 6.0; 40 6.0; 42 6.0; 45 6.0; 49 6.0; 52 6.0; 56 6.0; 59 6.0; 64 6.0; 68 6.0; 73 6.0; 78 6.0; 83 6.0; 89 6.0; 95 5.8; 102 4.9; 109 4.3; 117 3.6; 125 3.0; 134 2.2; 143 1.6; 153 1.4; 164 1.3; 175 1.9; 188 1.8; 201 1.4; 215 1.2; 230 1.3; 246 1.2; 263 1.2; 282 1.3; 301 1.6; 323 1.9; 345 2.2; 369 2.1; 395 2.0; 423 2.2; 452 2.3; 484 2.2; 518 1.9; 554 1.6; 593 1.9; 635 2.3; 679 2.3; 726 2.5; 777 2.4; 832 1.7; 890 1.1; 952 0.3; 1019 -0.1; 1090 0.1; 1167 0.4; 1248 0.6; 1336 0.4; 1429 -0.0; 1529 -0.4; 1636 -1.1; 1751 -2.0; 1873 -3.6; 2004 -4.2; 2145 -4.4; 2295 -4.4; 2455 -4.2; 2627 -3.3; 2811 -2.6; 3008 -1.4; 3219 -0.5; 3444 0.4; 3685 0.9; 3943 0.2; 4219 -1.2; 4514 -3.4; 4830 -4.4; 5168 -2.6; 5530 -6.6; 5917 -7.7; 6331 -4.7; 6775 -0.7; 7249 -3.7; 7756 -8.0; 8299 -11.0; 8880 -11.6; 9502 -11.1; 10167 -9.8; 10879 -6.6; 11640 -1.8; 12455 0.0; 13327 -1.9; 14260 -5.6; 15258 -5.4; 16326 -2.5; 17469 -0.9; 18692 -1.7; 20000 -3.5
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Sonoma%20Model%20One/headphoncecom/onear/Superlux%20HD%20681/Superlux%20HD%20681.png)