# Sony MDR-XB300
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 5.9; 25 5.6; 26 5.4; 28 4.7; 30 4.0; 32 3.3; 35 2.2; 37 1.6; 40 0.5; 42 -0.2; 45 -1.1; 49 -2.1; 52 -2.7; 56 -2.9; 59 -2.8; 64 -2.5; 68 -2.6; 73 -2.8; 78 -3.0; 83 -3.5; 89 -4.2; 95 -5.0; 102 -5.7; 109 -6.0; 117 -6.3; 125 -6.6; 134 -6.7; 143 -6.8; 153 -7.2; 164 -7.4; 175 -7.5; 188 -7.4; 201 -7.3; 215 -7.0; 230 -5.7; 246 -4.3; 263 -4.5; 282 -4.3; 301 -3.8; 323 -2.9; 345 -2.1; 369 -1.5; 395 -0.8; 423 0.1; 452 1.0; 484 1.6; 518 2.0; 554 2.5; 593 3.0; 635 3.6; 679 4.1; 726 4.6; 777 4.7; 832 3.9; 890 2.5; 952 0.9; 1019 -0.2; 1090 -0.8; 1167 -0.3; 1248 -0.1; 1336 -0.9; 1429 -0.9; 1529 -1.0; 1636 -1.6; 1751 -2.7; 1873 -3.4; 2004 -3.8; 2145 -4.0; 2295 -3.8; 2455 -3.0; 2627 -2.1; 2811 -0.9; 3008 0.9; 3219 2.1; 3444 3.1; 3685 3.7; 3943 4.2; 4219 4.0; 4514 5.3; 4830 6.0; 5168 6.0; 5530 6.0; 5917 1.1; 6331 -1.8; 6775 1.6; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 -0.2; 17469 -0.9; 18692 -0.6; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 5.9; 25 5.6; 26 5.4; 28 4.7; 30 4.0; 32 3.3; 35 2.2; 37 1.6; 40 0.5; 42 -0.2; 45 -1.1; 49 -2.1; 52 -2.7; 56 -2.9; 59 -2.8; 64 -2.5; 68 -2.6; 73 -2.8; 78 -3.0; 83 -3.5; 89 -4.2; 95 -5.0; 102 -5.7; 109 -6.0; 117 -6.3; 125 -6.6; 134 -6.7; 143 -6.8; 153 -7.2; 164 -7.4; 175 -7.5; 188 -7.4; 201 -7.3; 215 -7.0; 230 -5.7; 246 -4.3; 263 -4.5; 282 -4.3; 301 -3.8; 323 -2.9; 345 -2.1; 369 -1.5; 395 -0.8; 423 0.1; 452 1.0; 484 1.6; 518 2.0; 554 2.5; 593 3.0; 635 3.6; 679 4.1; 726 4.6; 777 4.7; 832 3.9; 890 2.5; 952 0.9; 1019 -0.2; 1090 -0.8; 1167 -0.3; 1248 -0.1; 1336 -0.9; 1429 -0.9; 1529 -1.0; 1636 -1.6; 1751 -2.7; 1873 -3.4; 2004 -3.8; 2145 -4.0; 2295 -3.8; 2455 -3.0; 2627 -2.1; 2811 -0.9; 3008 0.9; 3219 2.1; 3444 3.1; 3685 3.7; 3943 4.2; 4219 4.0; 4514 5.3; 4830 6.0; 5168 6.0; 5530 6.0; 5917 1.1; 6331 -1.8; 6775 1.6; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 -0.2; 17469 -0.9; 18692 -0.6; 20000 0.0
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Sonoma%20Model%20One/headphoncecom/onear/Sony%20MDR-XB300/Sony%20MDR-XB300.png)