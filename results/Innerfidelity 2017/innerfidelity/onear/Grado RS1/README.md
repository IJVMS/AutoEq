# Grado RS1
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 6.0; 32 6.0; 35 6.0; 37 6.0; 40 6.0; 42 5.8; 45 5.2; 49 4.2; 52 3.4; 56 2.5; 59 2.0; 64 1.1; 68 0.5; 73 -0.3; 78 -1.0; 83 -1.6; 89 -2.2; 95 -2.8; 102 -3.4; 109 -3.7; 117 -4.0; 125 -4.3; 134 -4.4; 143 -4.5; 153 -4.4; 164 -4.2; 175 -4.0; 188 -3.9; 201 -3.7; 215 -3.3; 230 -2.9; 246 -3.1; 263 -3.3; 282 -3.1; 301 -2.9; 323 -2.7; 345 -2.4; 369 -2.3; 395 -2.6; 423 -2.4; 452 -2.5; 484 -2.5; 518 -2.3; 554 -1.8; 593 -1.3; 635 -0.9; 679 -0.9; 726 -0.8; 777 -0.3; 832 -0.1; 890 -0.1; 952 -0.1; 1019 -0.1; 1090 -0.0; 1167 -0.4; 1248 -1.0; 1336 -1.5; 1429 -2.5; 1529 -3.5; 1636 -4.3; 1751 -6.3; 1873 -10.2; 2004 -8.8; 2145 -7.8; 2295 -6.6; 2455 -5.5; 2627 -4.7; 2811 -2.7; 3008 -1.2; 3219 -0.2; 3444 1.3; 3685 2.2; 3943 0.5; 4219 -4.0; 4514 -6.5; 4830 -4.1; 5168 -3.3; 5530 -4.1; 5917 -5.5; 6331 -8.3; 6775 -11.1; 7249 -10.5; 7756 -8.7; 8299 -8.4; 8880 -9.3; 9502 -8.0; 10167 -3.0; 10879 -0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 -1.5; 17469 -5.5; 18692 -3.8; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 6.0; 32 6.0; 35 6.0; 37 6.0; 40 6.0; 42 5.8; 45 5.2; 49 4.2; 52 3.4; 56 2.5; 59 2.0; 64 1.1; 68 0.5; 73 -0.3; 78 -1.0; 83 -1.6; 89 -2.2; 95 -2.8; 102 -3.4; 109 -3.7; 117 -4.0; 125 -4.3; 134 -4.4; 143 -4.5; 153 -4.4; 164 -4.2; 175 -4.0; 188 -3.9; 201 -3.7; 215 -3.3; 230 -2.9; 246 -3.1; 263 -3.3; 282 -3.1; 301 -2.9; 323 -2.7; 345 -2.4; 369 -2.3; 395 -2.6; 423 -2.4; 452 -2.5; 484 -2.5; 518 -2.3; 554 -1.8; 593 -1.3; 635 -0.9; 679 -0.9; 726 -0.8; 777 -0.3; 832 -0.1; 890 -0.1; 952 -0.1; 1019 -0.1; 1090 -0.0; 1167 -0.4; 1248 -1.0; 1336 -1.5; 1429 -2.5; 1529 -3.5; 1636 -4.3; 1751 -6.3; 1873 -10.2; 2004 -8.8; 2145 -7.8; 2295 -6.6; 2455 -5.5; 2627 -4.7; 2811 -2.7; 3008 -1.2; 3219 -0.2; 3444 1.3; 3685 2.2; 3943 0.5; 4219 -4.0; 4514 -6.5; 4830 -4.1; 5168 -3.3; 5530 -4.1; 5917 -5.5; 6331 -8.3; 6775 -11.1; 7249 -10.5; 7756 -8.7; 8299 -8.4; 8880 -9.3; 9502 -8.0; 10167 -3.0; 10879 -0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 -1.5; 17469 -5.5; 18692 -3.8; 20000 0.0
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Innerfidelity%202017/innerfidelity/onear/Grado%20RS1/Grado%20RS1.png)