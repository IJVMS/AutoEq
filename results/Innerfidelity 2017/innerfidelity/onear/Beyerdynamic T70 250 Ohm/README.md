# Beyerdynamic T70 250 Ohm
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 4.3; 22 4.1; 23 4.0; 25 3.8; 26 3.8; 28 3.6; 30 3.4; 32 3.3; 35 3.2; 37 3.1; 40 3.0; 42 2.9; 45 2.9; 49 3.0; 52 3.0; 56 3.1; 59 3.2; 64 3.3; 68 3.3; 73 3.2; 78 2.7; 83 2.2; 89 1.5; 95 0.9; 102 0.1; 109 -0.4; 117 -0.9; 125 -1.6; 134 -2.1; 143 -2.3; 153 -2.1; 164 -1.6; 175 -2.1; 188 -2.2; 201 -2.2; 215 -2.0; 230 -1.8; 246 -1.9; 263 -1.9; 282 -2.0; 301 -2.2; 323 -2.5; 345 -2.7; 369 -3.0; 395 -3.3; 423 -3.5; 452 -3.7; 484 -3.2; 518 -2.1; 554 -1.6; 593 -1.2; 635 -1.0; 679 -1.0; 726 -0.9; 777 -0.6; 832 -0.5; 890 -0.3; 952 -0.1; 1019 -0.0; 1090 -0.1; 1167 -0.1; 1248 -0.1; 1336 -0.1; 1429 -0.1; 1529 -0.1; 1636 -0.2; 1751 -0.2; 1873 -0.1; 2004 0.5; 2145 2.0; 2295 3.7; 2455 4.0; 2627 3.6; 2811 3.0; 3008 2.7; 3219 2.6; 3444 2.6; 3685 3.0; 3943 6.0; 4219 6.0; 4514 5.6; 4830 5.2; 5168 5.8; 5530 6.0; 5917 5.1; 6331 2.1; 6775 -0.1; 7249 -4.7; 7756 -7.3; 8299 -8.9; 8880 -9.0; 9502 -7.9; 10167 -5.4; 10879 -1.6; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 4.3; 22 4.1; 23 4.0; 25 3.8; 26 3.8; 28 3.6; 30 3.4; 32 3.3; 35 3.2; 37 3.1; 40 3.0; 42 2.9; 45 2.9; 49 3.0; 52 3.0; 56 3.1; 59 3.2; 64 3.3; 68 3.3; 73 3.2; 78 2.7; 83 2.2; 89 1.5; 95 0.9; 102 0.1; 109 -0.4; 117 -0.9; 125 -1.6; 134 -2.1; 143 -2.3; 153 -2.1; 164 -1.6; 175 -2.1; 188 -2.2; 201 -2.2; 215 -2.0; 230 -1.8; 246 -1.9; 263 -1.9; 282 -2.0; 301 -2.2; 323 -2.5; 345 -2.7; 369 -3.0; 395 -3.3; 423 -3.5; 452 -3.7; 484 -3.2; 518 -2.1; 554 -1.6; 593 -1.2; 635 -1.0; 679 -1.0; 726 -0.9; 777 -0.6; 832 -0.5; 890 -0.3; 952 -0.1; 1019 -0.0; 1090 -0.1; 1167 -0.1; 1248 -0.1; 1336 -0.1; 1429 -0.1; 1529 -0.1; 1636 -0.2; 1751 -0.2; 1873 -0.1; 2004 0.5; 2145 2.0; 2295 3.7; 2455 4.0; 2627 3.6; 2811 3.0; 3008 2.7; 3219 2.6; 3444 2.6; 3685 3.0; 3943 6.0; 4219 6.0; 4514 5.6; 4830 5.2; 5168 5.8; 5530 6.0; 5917 5.1; 6331 2.1; 6775 -0.1; 7249 -4.7; 7756 -7.3; 8299 -8.9; 8880 -9.0; 9502 -7.9; 10167 -5.4; 10879 -1.6; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Innerfidelity%202017/innerfidelity/onear/Beyerdynamic%20T70%20250%20Ohm/Beyerdynamic%20T70%20250%20Ohm.png)