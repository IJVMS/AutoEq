# Sennheiser Momentum Wireless Wired Passive
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 2.6; 22 2.1; 23 1.9; 25 1.5; 26 1.4; 28 1.1; 30 0.9; 32 0.7; 35 0.5; 37 0.3; 40 0.2; 42 0.1; 45 -0.0; 49 -0.1; 52 -0.2; 56 -0.2; 59 -0.3; 64 -0.4; 68 -0.5; 73 -0.6; 78 -0.7; 83 -0.9; 89 -1.1; 95 -1.4; 102 -1.7; 109 -1.8; 117 -2.1; 125 -2.2; 134 -2.2; 143 -2.1; 153 -2.4; 164 -2.4; 175 -1.6; 188 -1.4; 201 -1.2; 215 -0.8; 230 -0.4; 246 0.1; 263 0.3; 282 0.9; 301 1.5; 323 2.0; 345 2.2; 369 2.0; 395 1.6; 423 1.4; 452 1.1; 484 0.8; 518 0.6; 554 0.5; 593 0.5; 635 0.5; 679 0.3; 726 0.3; 777 0.5; 832 0.4; 890 0.2; 952 -0.0; 1019 0.0; 1090 -0.1; 1167 -0.3; 1248 -0.5; 1336 -0.9; 1429 -1.4; 1529 -1.8; 1636 -1.9; 1751 -1.8; 1873 -2.1; 2004 -1.7; 2145 -1.1; 2295 -0.2; 2455 1.0; 2627 2.0; 2811 3.2; 3008 4.6; 3219 5.8; 3444 6.0; 3685 6.0; 3943 6.0; 4219 6.0; 4514 6.0; 4830 2.0; 5168 2.5; 5530 5.5; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 2.6; 22 2.1; 23 1.9; 25 1.5; 26 1.4; 28 1.1; 30 0.9; 32 0.7; 35 0.5; 37 0.3; 40 0.2; 42 0.1; 45 -0.0; 49 -0.1; 52 -0.2; 56 -0.2; 59 -0.3; 64 -0.4; 68 -0.5; 73 -0.6; 78 -0.7; 83 -0.9; 89 -1.1; 95 -1.4; 102 -1.7; 109 -1.8; 117 -2.1; 125 -2.2; 134 -2.2; 143 -2.1; 153 -2.4; 164 -2.4; 175 -1.6; 188 -1.4; 201 -1.2; 215 -0.8; 230 -0.4; 246 0.1; 263 0.3; 282 0.9; 301 1.5; 323 2.0; 345 2.2; 369 2.0; 395 1.6; 423 1.4; 452 1.1; 484 0.8; 518 0.6; 554 0.5; 593 0.5; 635 0.5; 679 0.3; 726 0.3; 777 0.5; 832 0.4; 890 0.2; 952 -0.0; 1019 0.0; 1090 -0.1; 1167 -0.3; 1248 -0.5; 1336 -0.9; 1429 -1.4; 1529 -1.8; 1636 -1.9; 1751 -1.8; 1873 -2.1; 2004 -1.7; 2145 -1.1; 2295 -0.2; 2455 1.0; 2627 2.0; 2811 3.2; 3008 4.6; 3219 5.8; 3444 6.0; 3685 6.0; 3943 6.0; 4219 6.0; 4514 6.0; 4830 2.0; 5168 2.5; 5530 5.5; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/SBAF-Serious/innerfidelity/onear/Sennheiser%20Momentum%20Wireless%20Wired%20Passive/Sennheiser%20Momentum%20Wireless%20Wired%20Passive.png)