# V-Moda M-100
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 -2.4; 22 -2.7; 23 -2.8; 25 -3.0; 26 -3.1; 28 -3.2; 30 -3.4; 32 -3.4; 35 -3.5; 37 -3.5; 40 -3.6; 42 -3.7; 45 -3.7; 49 -3.7; 52 -3.8; 56 -3.8; 59 -3.8; 64 -3.8; 68 -3.7; 73 -3.4; 78 -3.4; 83 -4.0; 89 -4.4; 95 -4.2; 102 -4.0; 109 -4.3; 117 -5.1; 125 -5.6; 134 -5.6; 143 -5.6; 153 -5.5; 164 -4.8; 175 -4.5; 188 -4.3; 201 -3.6; 215 -2.8; 230 -2.1; 246 -1.3; 263 -0.3; 282 0.3; 301 0.3; 323 1.9; 345 2.9; 369 3.5; 395 3.7; 423 3.8; 452 3.7; 484 3.4; 518 3.2; 554 3.1; 593 2.9; 635 2.3; 679 1.6; 726 1.1; 777 0.9; 832 0.5; 890 0.1; 952 -0.0; 1019 -0.1; 1090 -0.1; 1167 0.0; 1248 0.3; 1336 0.4; 1429 0.4; 1529 0.5; 1636 0.4; 1751 0.6; 1873 0.7; 2004 0.5; 2145 -0.1; 2295 0.6; 2455 0.7; 2627 0.5; 2811 0.8; 3008 1.7; 3219 2.0; 3444 1.8; 3685 1.3; 3943 1.7; 4219 2.4; 4514 3.5; 4830 6.0; 5168 6.0; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 -0.1; 8880 -2.6; 9502 -4.1; 10167 -3.5; 10879 -0.6; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 -2.4; 22 -2.7; 23 -2.8; 25 -3.0; 26 -3.1; 28 -3.2; 30 -3.4; 32 -3.4; 35 -3.5; 37 -3.5; 40 -3.6; 42 -3.7; 45 -3.7; 49 -3.7; 52 -3.8; 56 -3.8; 59 -3.8; 64 -3.8; 68 -3.7; 73 -3.4; 78 -3.4; 83 -4.0; 89 -4.4; 95 -4.2; 102 -4.0; 109 -4.3; 117 -5.1; 125 -5.6; 134 -5.6; 143 -5.6; 153 -5.5; 164 -4.8; 175 -4.5; 188 -4.3; 201 -3.6; 215 -2.8; 230 -2.1; 246 -1.3; 263 -0.3; 282 0.3; 301 0.3; 323 1.9; 345 2.9; 369 3.5; 395 3.7; 423 3.8; 452 3.7; 484 3.4; 518 3.2; 554 3.1; 593 2.9; 635 2.3; 679 1.6; 726 1.1; 777 0.9; 832 0.5; 890 0.1; 952 -0.0; 1019 -0.1; 1090 -0.1; 1167 0.0; 1248 0.3; 1336 0.4; 1429 0.4; 1529 0.5; 1636 0.4; 1751 0.6; 1873 0.7; 2004 0.5; 2145 -0.1; 2295 0.6; 2455 0.7; 2627 0.5; 2811 0.8; 3008 1.7; 3219 2.0; 3444 1.8; 3685 1.3; 3943 1.7; 4219 2.4; 4514 3.5; 4830 6.0; 5168 6.0; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 -0.1; 8880 -2.6; 9502 -4.1; 10167 -3.5; 10879 -0.6; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/SBAF-Serious/headphoncecom/onear/V-Moda%20M-100/V-Moda%20M-100.png)