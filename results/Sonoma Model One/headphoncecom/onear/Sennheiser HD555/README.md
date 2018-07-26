# Sennheiser HD555
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 6.0; 32 6.0; 35 6.0; 37 6.0; 40 6.0; 42 6.0; 45 6.0; 49 5.8; 52 5.5; 56 5.4; 59 5.3; 64 5.5; 68 6.0; 73 6.0; 78 6.0; 83 5.5; 89 4.6; 95 3.6; 102 2.6; 109 1.9; 117 1.4; 125 0.7; 134 -0.1; 143 -0.6; 153 -1.0; 164 -1.0; 175 -1.3; 188 -1.4; 201 -1.6; 215 -1.7; 230 -1.7; 246 -1.8; 263 -1.8; 282 -1.7; 301 -1.6; 323 -1.4; 345 -1.3; 369 -1.2; 395 -1.1; 423 -0.7; 452 -0.5; 484 -0.3; 518 -0.3; 554 -0.3; 593 0.3; 635 0.6; 679 0.9; 726 1.3; 777 1.3; 832 1.2; 890 0.8; 952 0.2; 1019 0.1; 1090 0.6; 1167 1.5; 1248 2.5; 1336 3.4; 1429 4.1; 1529 4.5; 1636 4.4; 1751 3.1; 1873 2.0; 2004 1.7; 2145 1.5; 2295 1.2; 2455 1.5; 2627 1.9; 2811 2.1; 3008 1.5; 3219 0.5; 3444 0.2; 3685 0.3; 3943 2.0; 4219 3.3; 4514 0.8; 4830 0.4; 5168 2.0; 5530 3.3; 5917 3.5; 6331 1.7; 6775 2.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 -1.3; 9502 -1.3; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 -0.5; 16326 -3.4; 17469 -6.0; 18692 -5.8; 20000 -1.5
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 6.0; 32 6.0; 35 6.0; 37 6.0; 40 6.0; 42 6.0; 45 6.0; 49 5.8; 52 5.5; 56 5.4; 59 5.3; 64 5.5; 68 6.0; 73 6.0; 78 6.0; 83 5.5; 89 4.6; 95 3.6; 102 2.6; 109 1.9; 117 1.4; 125 0.7; 134 -0.1; 143 -0.6; 153 -1.0; 164 -1.0; 175 -1.3; 188 -1.4; 201 -1.6; 215 -1.7; 230 -1.7; 246 -1.8; 263 -1.8; 282 -1.7; 301 -1.6; 323 -1.4; 345 -1.3; 369 -1.2; 395 -1.1; 423 -0.7; 452 -0.5; 484 -0.3; 518 -0.3; 554 -0.3; 593 0.3; 635 0.6; 679 0.9; 726 1.3; 777 1.3; 832 1.2; 890 0.8; 952 0.2; 1019 0.1; 1090 0.6; 1167 1.5; 1248 2.5; 1336 3.4; 1429 4.1; 1529 4.5; 1636 4.4; 1751 3.1; 1873 2.0; 2004 1.7; 2145 1.5; 2295 1.2; 2455 1.5; 2627 1.9; 2811 2.1; 3008 1.5; 3219 0.5; 3444 0.2; 3685 0.3; 3943 2.0; 4219 3.3; 4514 0.8; 4830 0.4; 5168 2.0; 5530 3.3; 5917 3.5; 6331 1.7; 6775 2.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 -1.3; 9502 -1.3; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 -0.5; 16326 -3.4; 17469 -6.0; 18692 -5.8; 20000 -1.5
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Sonoma%20Model%20One/headphoncecom/onear/Sennheiser%20HD555/Sennheiser%20HD555.png)