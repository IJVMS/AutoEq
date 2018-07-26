# AKG K712
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 3.0; 22 2.6; 23 2.4; 25 2.1; 26 1.9; 28 1.7; 30 1.4; 32 1.2; 35 0.9; 37 0.7; 40 0.4; 42 0.1; 45 -0.2; 49 -0.6; 52 -0.9; 56 -1.2; 59 -1.2; 64 -1.0; 68 -0.7; 73 -0.2; 78 -0.0; 83 -0.2; 89 -0.9; 95 -1.9; 102 -2.8; 109 -3.3; 117 -3.7; 125 -4.4; 134 -5.2; 143 -5.6; 153 -6.0; 164 -6.1; 175 -5.9; 188 -6.3; 201 -6.5; 215 -6.7; 230 -6.8; 246 -6.8; 263 -6.8; 282 -6.7; 301 -6.6; 323 -6.4; 345 -6.0; 369 -6.0; 395 -5.9; 423 -5.7; 452 -5.3; 484 -5.0; 518 -4.7; 554 -3.9; 593 -3.7; 635 -3.5; 679 -2.8; 726 -1.8; 777 -1.2; 832 -0.9; 890 -0.6; 952 -0.4; 1019 0.3; 1090 1.7; 1167 2.9; 1248 3.5; 1336 3.9; 1429 3.3; 1529 2.8; 1636 1.2; 1751 -0.4; 1873 -2.5; 2004 -4.5; 2145 -4.8; 2295 -3.0; 2455 -0.7; 2627 2.1; 2811 5.2; 3008 5.9; 3219 4.3; 3444 2.5; 3685 1.2; 3943 -0.2; 4219 -2.4; 4514 -2.9; 4830 -1.6; 5168 -2.7; 5530 -4.7; 5917 -6.6; 6331 -6.7; 6775 -7.9; 7249 -8.4; 7756 -7.5; 8299 -6.4; 8880 -5.4; 9502 -5.4; 10167 -6.6; 10879 -7.1; 11640 -4.2; 12455 -0.2; 13327 0.0; 14260 0.0; 15258 -1.3; 16326 -5.1; 17469 -6.3; 18692 -5.0; 20000 -2.2
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 3.0; 22 2.6; 23 2.4; 25 2.1; 26 1.9; 28 1.7; 30 1.4; 32 1.2; 35 0.9; 37 0.7; 40 0.4; 42 0.1; 45 -0.2; 49 -0.6; 52 -0.9; 56 -1.2; 59 -1.2; 64 -1.0; 68 -0.7; 73 -0.2; 78 -0.0; 83 -0.2; 89 -0.9; 95 -1.9; 102 -2.8; 109 -3.3; 117 -3.7; 125 -4.4; 134 -5.2; 143 -5.6; 153 -6.0; 164 -6.1; 175 -5.9; 188 -6.3; 201 -6.5; 215 -6.7; 230 -6.8; 246 -6.8; 263 -6.8; 282 -6.7; 301 -6.6; 323 -6.4; 345 -6.0; 369 -6.0; 395 -5.9; 423 -5.7; 452 -5.3; 484 -5.0; 518 -4.7; 554 -3.9; 593 -3.7; 635 -3.5; 679 -2.8; 726 -1.8; 777 -1.2; 832 -0.9; 890 -0.6; 952 -0.4; 1019 0.3; 1090 1.7; 1167 2.9; 1248 3.5; 1336 3.9; 1429 3.3; 1529 2.8; 1636 1.2; 1751 -0.4; 1873 -2.5; 2004 -4.5; 2145 -4.8; 2295 -3.0; 2455 -0.7; 2627 2.1; 2811 5.2; 3008 5.9; 3219 4.3; 3444 2.5; 3685 1.2; 3943 -0.2; 4219 -2.4; 4514 -2.9; 4830 -1.6; 5168 -2.7; 5530 -4.7; 5917 -6.6; 6331 -6.7; 6775 -7.9; 7249 -8.4; 7756 -7.5; 8299 -6.4; 8880 -5.4; 9502 -5.4; 10167 -6.6; 10879 -7.1; 11640 -4.2; 12455 -0.2; 13327 0.0; 14260 0.0; 15258 -1.3; 16326 -5.1; 17469 -6.3; 18692 -5.0; 20000 -2.2
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Sonoma%20Model%20One/headphoncecom/onear/AKG%20K712/AKG%20K712.png)