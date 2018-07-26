# Stax SR-007
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 6.0; 32 6.0; 35 6.0; 37 6.0; 40 6.0; 42 6.0; 45 6.0; 49 5.0; 52 3.4; 56 2.2; 59 2.5; 64 3.3; 68 3.6; 73 3.8; 78 3.9; 83 3.8; 89 3.5; 95 3.2; 102 2.8; 109 2.5; 117 2.1; 125 1.7; 134 1.3; 143 1.1; 153 0.9; 164 0.7; 175 0.7; 188 0.6; 201 0.5; 215 0.4; 230 0.4; 246 0.3; 263 0.3; 282 0.2; 301 0.1; 323 0.0; 345 -0.1; 369 -0.1; 395 -0.1; 423 0.1; 452 0.4; 484 1.3; 518 2.1; 554 1.6; 593 1.0; 635 0.4; 679 0.2; 726 0.4; 777 0.5; 832 0.5; 890 0.4; 952 0.2; 1019 0.2; 1090 1.3; 1167 2.6; 1248 4.6; 1336 3.0; 1429 1.4; 1529 1.8; 1636 2.4; 1751 3.7; 1873 5.1; 2004 6.0; 2145 6.0; 2295 6.0; 2455 6.0; 2627 6.0; 2811 6.0; 3008 6.0; 3219 6.0; 3444 6.0; 3685 6.0; 3943 6.0; 4219 6.0; 4514 6.0; 4830 6.0; 5168 6.0; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 6.0; 32 6.0; 35 6.0; 37 6.0; 40 6.0; 42 6.0; 45 6.0; 49 5.0; 52 3.4; 56 2.2; 59 2.5; 64 3.3; 68 3.6; 73 3.8; 78 3.9; 83 3.8; 89 3.5; 95 3.2; 102 2.8; 109 2.5; 117 2.1; 125 1.7; 134 1.3; 143 1.1; 153 0.9; 164 0.7; 175 0.7; 188 0.6; 201 0.5; 215 0.4; 230 0.4; 246 0.3; 263 0.3; 282 0.2; 301 0.1; 323 0.0; 345 -0.1; 369 -0.1; 395 -0.1; 423 0.1; 452 0.4; 484 1.3; 518 2.1; 554 1.6; 593 1.0; 635 0.4; 679 0.2; 726 0.4; 777 0.5; 832 0.5; 890 0.4; 952 0.2; 1019 0.2; 1090 1.3; 1167 2.6; 1248 4.6; 1336 3.0; 1429 1.4; 1529 1.8; 1636 2.4; 1751 3.7; 1873 5.1; 2004 6.0; 2145 6.0; 2295 6.0; 2455 6.0; 2627 6.0; 2811 6.0; 3008 6.0; 3219 6.0; 3444 6.0; 3685 6.0; 3943 6.0; 4219 6.0; 4514 6.0; 4830 6.0; 5168 6.0; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Headphone.com/innerfidelity/onear/Stax%20SR-007/Stax%20SR-007.png)