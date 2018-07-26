# Sennheiser PX200
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 6.0; 32 6.0; 35 6.0; 37 6.0; 40 6.0; 42 6.0; 45 6.0; 49 6.0; 52 6.0; 56 6.0; 59 6.0; 64 6.0; 68 6.0; 73 6.0; 78 6.0; 83 6.0; 89 6.0; 95 6.0; 102 6.0; 109 6.0; 117 6.0; 125 6.0; 134 6.0; 143 6.0; 153 6.0; 164 6.0; 175 6.0; 188 6.0; 201 6.0; 215 6.0; 230 6.0; 246 6.0; 263 6.0; 282 5.9; 301 5.7; 323 5.4; 345 5.1; 369 4.9; 395 4.4; 423 4.4; 452 4.3; 484 3.6; 518 3.0; 554 2.5; 593 2.2; 635 1.7; 679 1.5; 726 1.5; 777 1.1; 832 0.7; 890 0.4; 952 0.1; 1019 0.1; 1090 0.6; 1167 1.5; 1248 2.2; 1336 2.5; 1429 2.6; 1529 2.4; 1636 1.6; 1751 0.7; 1873 0.0; 2004 -0.0; 2145 0.6; 2295 1.7; 2455 2.3; 2627 2.8; 2811 3.7; 3008 5.1; 3219 5.8; 3444 6.0; 3685 6.0; 3943 6.0; 4219 5.2; 4514 3.8; 4830 4.8; 5168 5.7; 5530 5.9; 5917 4.8; 6331 4.2; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 6.0; 32 6.0; 35 6.0; 37 6.0; 40 6.0; 42 6.0; 45 6.0; 49 6.0; 52 6.0; 56 6.0; 59 6.0; 64 6.0; 68 6.0; 73 6.0; 78 6.0; 83 6.0; 89 6.0; 95 6.0; 102 6.0; 109 6.0; 117 6.0; 125 6.0; 134 6.0; 143 6.0; 153 6.0; 164 6.0; 175 6.0; 188 6.0; 201 6.0; 215 6.0; 230 6.0; 246 6.0; 263 6.0; 282 5.9; 301 5.7; 323 5.4; 345 5.1; 369 4.9; 395 4.4; 423 4.4; 452 4.3; 484 3.6; 518 3.0; 554 2.5; 593 2.2; 635 1.7; 679 1.5; 726 1.5; 777 1.1; 832 0.7; 890 0.4; 952 0.1; 1019 0.1; 1090 0.6; 1167 1.5; 1248 2.2; 1336 2.5; 1429 2.6; 1529 2.4; 1636 1.6; 1751 0.7; 1873 0.0; 2004 -0.0; 2145 0.6; 2295 1.7; 2455 2.3; 2627 2.8; 2811 3.7; 3008 5.1; 3219 5.8; 3444 6.0; 3685 6.0; 3943 6.0; 4219 5.2; 4514 3.8; 4830 4.8; 5168 5.7; 5530 5.9; 5917 4.8; 6331 4.2; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Sonoma%20Model%20One/headphoncecom/onear/Sennheiser%20PX200/Sennheiser%20PX200.png)