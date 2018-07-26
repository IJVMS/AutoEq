# Yamaha Pro500
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 6.0; 22 5.8; 23 5.7; 25 5.3; 26 5.1; 28 4.6; 30 4.2; 32 3.9; 35 3.6; 37 3.4; 40 3.1; 42 2.9; 45 2.6; 49 2.3; 52 2.2; 56 2.0; 59 1.8; 64 1.7; 68 2.0; 73 2.6; 78 2.0; 83 1.2; 89 0.6; 95 0.9; 102 0.7; 109 -0.5; 117 -1.2; 125 -1.9; 134 -2.4; 143 -2.8; 153 -3.0; 164 -2.8; 175 -3.0; 188 -3.3; 201 -3.4; 215 -3.4; 230 -3.1; 246 -2.7; 263 -2.3; 282 -1.8; 301 -1.3; 323 -0.3; 345 0.7; 369 1.4; 395 2.0; 423 2.8; 452 2.8; 484 2.2; 518 2.2; 554 2.3; 593 2.1; 635 1.8; 679 1.3; 726 0.9; 777 0.8; 832 0.3; 890 0.3; 952 0.6; 1019 -0.0; 1090 -0.2; 1167 -0.5; 1248 -0.6; 1336 -0.9; 1429 -1.2; 1529 -1.2; 1636 -1.1; 1751 -0.8; 1873 0.0; 2004 0.8; 2145 1.6; 2295 2.7; 2455 4.0; 2627 5.3; 2811 6.0; 3008 6.0; 3219 5.7; 3444 4.4; 3685 4.8; 3943 6.0; 4219 6.0; 4514 6.0; 4830 6.0; 5168 6.0; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 6.0; 22 5.8; 23 5.7; 25 5.3; 26 5.1; 28 4.6; 30 4.2; 32 3.9; 35 3.6; 37 3.4; 40 3.1; 42 2.9; 45 2.6; 49 2.3; 52 2.2; 56 2.0; 59 1.8; 64 1.7; 68 2.0; 73 2.6; 78 2.0; 83 1.2; 89 0.6; 95 0.9; 102 0.7; 109 -0.5; 117 -1.2; 125 -1.9; 134 -2.4; 143 -2.8; 153 -3.0; 164 -2.8; 175 -3.0; 188 -3.3; 201 -3.4; 215 -3.4; 230 -3.1; 246 -2.7; 263 -2.3; 282 -1.8; 301 -1.3; 323 -0.3; 345 0.7; 369 1.4; 395 2.0; 423 2.8; 452 2.8; 484 2.2; 518 2.2; 554 2.3; 593 2.1; 635 1.8; 679 1.3; 726 0.9; 777 0.8; 832 0.3; 890 0.3; 952 0.6; 1019 -0.0; 1090 -0.2; 1167 -0.5; 1248 -0.6; 1336 -0.9; 1429 -1.2; 1529 -1.2; 1636 -1.1; 1751 -0.8; 1873 0.0; 2004 0.8; 2145 1.6; 2295 2.7; 2455 4.0; 2627 5.3; 2811 6.0; 3008 6.0; 3219 5.7; 3444 4.4; 3685 4.8; 3943 6.0; 4219 6.0; 4514 6.0; 4830 6.0; 5168 6.0; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Innerfidelity%202017/innerfidelity/onear/Yamaha%20Pro500/Yamaha%20Pro500.png)