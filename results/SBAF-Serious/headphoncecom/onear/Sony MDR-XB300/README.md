# Sony MDR-XB300
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-62**.
```
GraphicEQ: 10 -84; 20 6.2; 22 4.9; 23 4.4; 25 3.4; 26 2.9; 28 2.1; 30 1.3; 32 0.6; 35 -0.4; 37 -1.0; 40 -1.9; 42 -2.5; 45 -3.3; 49 -4.1; 52 -4.4; 56 -4.6; 59 -4.5; 64 -4.5; 68 -4.9; 73 -5.6; 78 -6.1; 83 -6.5; 89 -6.8; 95 -7.0; 102 -7.3; 109 -7.4; 117 -7.3; 125 -7.3; 134 -7.1; 143 -7.0; 153 -7.2; 164 -7.3; 175 -7.3; 188 -7.2; 201 -7.0; 215 -6.6; 230 -5.2; 246 -3.8; 263 -4.0; 282 -3.8; 301 -3.3; 323 -2.4; 345 -1.6; 369 -1.0; 395 -0.2; 423 0.6; 452 1.3; 484 1.8; 518 2.2; 554 2.7; 593 3.2; 635 3.5; 679 3.5; 726 3.6; 777 3.7; 832 3.1; 890 2.0; 952 0.8; 1019 -0.2; 1090 -1.3; 1167 -1.5; 1248 -2.0; 1336 -3.4; 1429 -3.8; 1529 -4.1; 1636 -4.2; 1751 -4.5; 1873 -4.6; 2004 -4.8; 2145 -5.0; 2295 -4.8; 2455 -4.0; 2627 -3.2; 2811 -2.1; 3008 -0.4; 3219 0.8; 3444 2.2; 3685 3.4; 3943 4.2; 4219 4.1; 4514 5.1; 4830 6.0; 5168 6.0; 5530 6.0; 5917 3.9; 6331 0.8; 6775 3.0; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 -1.2
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 6.2; 22 4.9; 23 4.4; 25 3.4; 26 2.9; 28 2.1; 30 1.3; 32 0.6; 35 -0.4; 37 -1.0; 40 -1.9; 42 -2.5; 45 -3.3; 49 -4.1; 52 -4.4; 56 -4.6; 59 -4.5; 64 -4.5; 68 -4.9; 73 -5.6; 78 -6.1; 83 -6.5; 89 -6.8; 95 -7.0; 102 -7.3; 109 -7.4; 117 -7.3; 125 -7.3; 134 -7.1; 143 -7.0; 153 -7.2; 164 -7.3; 175 -7.3; 188 -7.2; 201 -7.0; 215 -6.6; 230 -5.2; 246 -3.8; 263 -4.0; 282 -3.8; 301 -3.3; 323 -2.4; 345 -1.6; 369 -1.0; 395 -0.2; 423 0.6; 452 1.3; 484 1.8; 518 2.2; 554 2.7; 593 3.2; 635 3.5; 679 3.5; 726 3.6; 777 3.7; 832 3.1; 890 2.0; 952 0.8; 1019 -0.2; 1090 -1.3; 1167 -1.5; 1248 -2.0; 1336 -3.4; 1429 -3.8; 1529 -4.1; 1636 -4.2; 1751 -4.5; 1873 -4.6; 2004 -4.8; 2145 -5.0; 2295 -4.8; 2455 -4.0; 2627 -3.2; 2811 -2.1; 3008 -0.4; 3219 0.8; 3444 2.2; 3685 3.4; 3943 4.2; 4219 4.1; 4514 5.1; 4830 6.0; 5168 6.0; 5530 6.0; 5917 3.9; 6331 0.8; 6775 3.0; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 -1.2
Copy: L=-6.2dB*l, R=-6.2dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/SBAF-Serious/headphoncecom/onear/Sony%20MDR-XB300/Sony%20MDR-XB300.png)