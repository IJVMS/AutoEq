# Advanced Alpha Shallow Pads
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-39**.
```
GraphicEQ: 10 -84; 20 1.2; 22 1.2; 23 1.1; 25 1.1; 26 1.2; 28 1.2; 30 1.2; 32 1.3; 35 1.3; 37 1.3; 40 1.4; 42 1.4; 45 1.4; 49 1.4; 52 1.5; 56 1.5; 59 1.5; 64 1.5; 68 1.5; 73 1.5; 78 1.5; 83 1.4; 89 1.0; 95 0.5; 102 0.2; 109 -0.2; 117 -0.6; 125 -1.2; 134 -1.6; 143 -1.9; 153 -2.2; 164 -2.3; 175 -2.4; 188 -2.6; 201 -2.7; 215 -2.7; 230 -2.7; 246 -2.7; 263 -2.8; 282 -2.8; 301 -2.5; 323 -2.6; 345 -2.5; 369 -2.2; 395 -2.0; 423 -1.5; 452 -1.5; 484 -1.2; 518 -1.1; 554 -0.9; 593 -0.3; 635 -0.1; 679 0.1; 726 0.1; 777 0.2; 832 0.1; 890 -0.1; 952 -0.2; 1019 0.0; 1090 -0.2; 1167 -0.2; 1248 -0.6; 1336 0.0; 1429 0.9; 1529 0.2; 1636 -0.4; 1751 0.1; 1873 1.3; 2004 -0.6; 2145 -2.1; 2295 -3.6; 2455 -4.8; 2627 -5.8; 2811 -6.9; 3008 -7.0; 3219 -6.0; 3444 -4.8; 3685 -3.7; 3943 -1.3; 4219 2.1; 4514 3.2; 4830 -2.6; 5168 -3.1; 5530 -0.8; 5917 -0.2; 6331 -0.4; 6775 0.5; 7249 0.0; 7756 -0.8; 8299 -2.2; 8880 -3.1; 9502 -2.6; 10167 -0.6; 10879 0.0; 11640 0.0; 12455 0.0; 13327 -1.2; 14260 -4.3; 15258 -2.9; 16326 -0.0; 17469 0.0; 18692 0.0; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 1.2; 22 1.2; 23 1.1; 25 1.1; 26 1.2; 28 1.2; 30 1.2; 32 1.3; 35 1.3; 37 1.3; 40 1.4; 42 1.4; 45 1.4; 49 1.4; 52 1.5; 56 1.5; 59 1.5; 64 1.5; 68 1.5; 73 1.5; 78 1.5; 83 1.4; 89 1.0; 95 0.5; 102 0.2; 109 -0.2; 117 -0.6; 125 -1.2; 134 -1.6; 143 -1.9; 153 -2.2; 164 -2.3; 175 -2.4; 188 -2.6; 201 -2.7; 215 -2.7; 230 -2.7; 246 -2.7; 263 -2.8; 282 -2.8; 301 -2.5; 323 -2.6; 345 -2.5; 369 -2.2; 395 -2.0; 423 -1.5; 452 -1.5; 484 -1.2; 518 -1.1; 554 -0.9; 593 -0.3; 635 -0.1; 679 0.1; 726 0.1; 777 0.2; 832 0.1; 890 -0.1; 952 -0.2; 1019 0.0; 1090 -0.2; 1167 -0.2; 1248 -0.6; 1336 0.0; 1429 0.9; 1529 0.2; 1636 -0.4; 1751 0.1; 1873 1.3; 2004 -0.6; 2145 -2.1; 2295 -3.6; 2455 -4.8; 2627 -5.8; 2811 -6.9; 3008 -7.0; 3219 -6.0; 3444 -4.8; 3685 -3.7; 3943 -1.3; 4219 2.1; 4514 3.2; 4830 -2.6; 5168 -3.1; 5530 -0.8; 5917 -0.2; 6331 -0.4; 6775 0.5; 7249 0.0; 7756 -0.8; 8299 -2.2; 8880 -3.1; 9502 -2.6; 10167 -0.6; 10879 0.0; 11640 0.0; 12455 0.0; 13327 -1.2; 14260 -4.3; 15258 -2.9; 16326 -0.0; 17469 0.0; 18692 0.0; 20000 0.0
Copy: L=-3.9dB*l, R=-3.9dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/SBAF-Serious/innerfidelity/onear/Advanced%20Alpha%20Shallow%20Pads/Advanced%20Alpha%20Shallow%20Pads.png)