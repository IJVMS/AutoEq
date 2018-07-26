# Sennheiser RS 170
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 5.7; 22 4.7; 23 4.3; 25 3.4; 26 3.0; 28 2.3; 30 1.6; 32 1.1; 35 0.4; 37 -0.1; 40 -0.7; 42 -1.1; 45 -1.5; 49 -2.1; 52 -2.4; 56 -2.8; 59 -2.9; 64 -3.2; 68 -3.5; 73 -3.9; 78 -4.1; 83 -3.9; 89 -3.8; 95 -3.6; 102 -3.6; 109 -4.2; 117 -5.1; 125 -6.1; 134 -6.8; 143 -7.1; 153 -7.3; 164 -7.1; 175 -6.8; 188 -7.4; 201 -7.2; 215 -6.5; 230 -5.7; 246 -5.3; 263 -5.0; 282 -4.8; 301 -4.3; 323 -3.7; 345 -3.3; 369 -3.0; 395 -3.2; 423 -3.4; 452 -3.7; 484 -3.8; 518 -3.2; 554 -2.3; 593 -1.2; 635 -0.6; 679 -0.4; 726 -0.1; 777 1.0; 832 2.2; 890 1.4; 952 0.3; 1019 -0.1; 1090 0.8; 1167 -0.2; 1248 -1.5; 1336 -2.2; 1429 -3.0; 1529 -3.8; 1636 -5.0; 1751 -4.0; 1873 -1.2; 2004 -3.2; 2145 -4.1; 2295 -4.5; 2455 -4.4; 2627 -4.1; 2811 -4.0; 3008 -3.1; 3219 -3.1; 3444 -2.7; 3685 -1.8; 3943 1.0; 4219 4.0; 4514 6.0; 4830 6.0; 5168 4.5; 5530 3.0; 5917 2.2; 6331 -0.0; 6775 -1.5; 7249 1.0; 7756 0.2; 8299 -1.7; 8880 -3.7; 9502 -4.5; 10167 -3.7; 10879 -1.9; 11640 -0.1; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 5.7; 22 4.7; 23 4.3; 25 3.4; 26 3.0; 28 2.3; 30 1.6; 32 1.1; 35 0.4; 37 -0.1; 40 -0.7; 42 -1.1; 45 -1.5; 49 -2.1; 52 -2.4; 56 -2.8; 59 -2.9; 64 -3.2; 68 -3.5; 73 -3.9; 78 -4.1; 83 -3.9; 89 -3.8; 95 -3.6; 102 -3.6; 109 -4.2; 117 -5.1; 125 -6.1; 134 -6.8; 143 -7.1; 153 -7.3; 164 -7.1; 175 -6.8; 188 -7.4; 201 -7.2; 215 -6.5; 230 -5.7; 246 -5.3; 263 -5.0; 282 -4.8; 301 -4.3; 323 -3.7; 345 -3.3; 369 -3.0; 395 -3.2; 423 -3.4; 452 -3.7; 484 -3.8; 518 -3.2; 554 -2.3; 593 -1.2; 635 -0.6; 679 -0.4; 726 -0.1; 777 1.0; 832 2.2; 890 1.4; 952 0.3; 1019 -0.1; 1090 0.8; 1167 -0.2; 1248 -1.5; 1336 -2.2; 1429 -3.0; 1529 -3.8; 1636 -5.0; 1751 -4.0; 1873 -1.2; 2004 -3.2; 2145 -4.1; 2295 -4.5; 2455 -4.4; 2627 -4.1; 2811 -4.0; 3008 -3.1; 3219 -3.1; 3444 -2.7; 3685 -1.8; 3943 1.0; 4219 4.0; 4514 6.0; 4830 6.0; 5168 4.5; 5530 3.0; 5917 2.2; 6331 -0.0; 6775 -1.5; 7249 1.0; 7756 0.2; 8299 -1.7; 8880 -3.7; 9502 -4.5; 10167 -3.7; 10879 -1.9; 11640 -0.1; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Innerfidelity%202017/headphoncecom/onear/Sennheiser%20RS%20170/Sennheiser%20RS%20170.png)