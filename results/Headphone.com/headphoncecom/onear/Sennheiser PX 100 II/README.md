# Sennheiser PX 100 II
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-65**.
```
GraphicEQ: 10 -84; 20 6.5; 22 5.7; 23 5.3; 25 4.7; 26 4.3; 28 3.8; 30 3.2; 32 2.8; 35 2.2; 37 1.9; 40 1.4; 42 1.1; 45 0.8; 49 0.3; 52 0.0; 56 -0.3; 59 -0.5; 64 -0.8; 68 -1.1; 73 -1.4; 78 -1.7; 83 -2.0; 89 -2.4; 95 -2.6; 102 -2.8; 109 -3.3; 117 -3.9; 125 -4.3; 134 -4.7; 143 -5.0; 153 -5.1; 164 -5.2; 175 -5.2; 188 -5.0; 201 -5.0; 215 -4.8; 230 -4.7; 246 -4.5; 263 -4.3; 282 -3.9; 301 -3.6; 323 -3.5; 345 -3.2; 369 -2.8; 395 -2.4; 423 -2.1; 452 -1.9; 484 -1.6; 518 -1.2; 554 -0.8; 593 -0.5; 635 -0.2; 679 0.0; 726 0.2; 777 0.2; 832 0.2; 890 0.2; 952 0.1; 1019 -0.0; 1090 -0.1; 1167 -0.0; 1248 0.2; 1336 0.5; 1429 0.6; 1529 0.7; 1636 0.3; 1751 0.0; 1873 -0.1; 2004 0.4; 2145 1.7; 2295 3.5; 2455 5.5; 2627 6.0; 2811 6.0; 3008 5.9; 3219 4.4; 3444 5.0; 3685 6.0; 3943 5.4; 4219 2.2; 4514 1.5; 4830 5.0; 5168 6.0; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 6.5; 22 5.7; 23 5.3; 25 4.7; 26 4.3; 28 3.8; 30 3.2; 32 2.8; 35 2.2; 37 1.9; 40 1.4; 42 1.1; 45 0.8; 49 0.3; 52 0.0; 56 -0.3; 59 -0.5; 64 -0.8; 68 -1.1; 73 -1.4; 78 -1.7; 83 -2.0; 89 -2.4; 95 -2.6; 102 -2.8; 109 -3.3; 117 -3.9; 125 -4.3; 134 -4.7; 143 -5.0; 153 -5.1; 164 -5.2; 175 -5.2; 188 -5.0; 201 -5.0; 215 -4.8; 230 -4.7; 246 -4.5; 263 -4.3; 282 -3.9; 301 -3.6; 323 -3.5; 345 -3.2; 369 -2.8; 395 -2.4; 423 -2.1; 452 -1.9; 484 -1.6; 518 -1.2; 554 -0.8; 593 -0.5; 635 -0.2; 679 0.0; 726 0.2; 777 0.2; 832 0.2; 890 0.2; 952 0.1; 1019 -0.0; 1090 -0.1; 1167 -0.0; 1248 0.2; 1336 0.5; 1429 0.6; 1529 0.7; 1636 0.3; 1751 0.0; 1873 -0.1; 2004 0.4; 2145 1.7; 2295 3.5; 2455 5.5; 2627 6.0; 2811 6.0; 3008 5.9; 3219 4.4; 3444 5.0; 3685 6.0; 3943 5.4; 4219 2.2; 4514 1.5; 4830 5.0; 5168 6.0; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
Copy: L=-6.5dB*l, R=-6.5dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Headphone.com/headphoncecom/onear/Sennheiser%20PX%20100%20II/Sennheiser%20PX%20100%20II.png)