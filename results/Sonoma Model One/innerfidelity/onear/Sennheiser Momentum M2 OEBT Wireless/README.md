# Sennheiser Momentum M2 OEBT Wireless
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 -0.9; 22 -1.3; 23 -1.5; 25 -1.9; 26 -2.1; 28 -2.4; 30 -2.7; 32 -2.9; 35 -3.2; 37 -3.4; 40 -3.8; 42 -4.0; 45 -4.2; 49 -4.5; 52 -4.6; 56 -4.8; 59 -4.9; 64 -2.1; 68 0.9; 73 -1.2; 78 -1.7; 83 -1.1; 89 -1.2; 95 -1.4; 102 -1.4; 109 -1.3; 117 -1.2; 125 -1.3; 134 -1.5; 143 -1.3; 153 -1.1; 164 -0.7; 175 -0.5; 188 -0.2; 201 -0.0; 215 0.3; 230 0.6; 246 1.2; 263 1.8; 282 2.4; 301 3.0; 323 3.5; 345 3.8; 369 3.7; 395 3.7; 423 3.8; 452 3.8; 484 3.7; 518 3.4; 554 3.2; 593 3.1; 635 3.0; 679 3.0; 726 3.0; 777 2.7; 832 2.0; 890 1.2; 952 0.4; 1019 -0.0; 1090 0.1; 1167 0.7; 1248 1.2; 1336 1.2; 1429 0.9; 1529 0.3; 1636 -0.9; 1751 -2.1; 1873 -3.1; 2004 -3.7; 2145 -3.9; 2295 -3.7; 2455 -2.9; 2627 -2.0; 2811 -0.9; 3008 0.6; 3219 2.0; 3444 3.2; 3685 3.9; 3943 5.5; 4219 6.0; 4514 5.9; 4830 4.3; 5168 1.5; 5530 0.8; 5917 1.3; 6331 1.7; 6775 1.0; 7249 0.6; 7756 -0.2; 8299 -1.7; 8880 -3.6; 9502 -4.7; 10167 -2.9; 10879 -0.1; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 -0.9; 22 -1.3; 23 -1.5; 25 -1.9; 26 -2.1; 28 -2.4; 30 -2.7; 32 -2.9; 35 -3.2; 37 -3.4; 40 -3.8; 42 -4.0; 45 -4.2; 49 -4.5; 52 -4.6; 56 -4.8; 59 -4.9; 64 -2.1; 68 0.9; 73 -1.2; 78 -1.7; 83 -1.1; 89 -1.2; 95 -1.4; 102 -1.4; 109 -1.3; 117 -1.2; 125 -1.3; 134 -1.5; 143 -1.3; 153 -1.1; 164 -0.7; 175 -0.5; 188 -0.2; 201 -0.0; 215 0.3; 230 0.6; 246 1.2; 263 1.8; 282 2.4; 301 3.0; 323 3.5; 345 3.8; 369 3.7; 395 3.7; 423 3.8; 452 3.8; 484 3.7; 518 3.4; 554 3.2; 593 3.1; 635 3.0; 679 3.0; 726 3.0; 777 2.7; 832 2.0; 890 1.2; 952 0.4; 1019 -0.0; 1090 0.1; 1167 0.7; 1248 1.2; 1336 1.2; 1429 0.9; 1529 0.3; 1636 -0.9; 1751 -2.1; 1873 -3.1; 2004 -3.7; 2145 -3.9; 2295 -3.7; 2455 -2.9; 2627 -2.0; 2811 -0.9; 3008 0.6; 3219 2.0; 3444 3.2; 3685 3.9; 3943 5.5; 4219 6.0; 4514 5.9; 4830 4.3; 5168 1.5; 5530 0.8; 5917 1.3; 6331 1.7; 6775 1.0; 7249 0.6; 7756 -0.2; 8299 -1.7; 8880 -3.6; 9502 -4.7; 10167 -2.9; 10879 -0.1; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Sonoma%20Model%20One/innerfidelity/onear/Sennheiser%20Momentum%20M2%20OEBT%20Wireless/Sennheiser%20Momentum%20M2%20OEBT%20Wireless.png)