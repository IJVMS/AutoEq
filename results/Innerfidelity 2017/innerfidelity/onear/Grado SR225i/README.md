# Grado SR225i
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 6.0; 32 6.0; 35 5.5; 37 5.0; 40 4.2; 42 3.7; 45 3.0; 49 2.2; 52 1.8; 56 1.3; 59 0.9; 64 0.4; 68 -0.0; 73 -0.5; 78 -0.9; 83 -1.2; 89 -1.6; 95 -1.9; 102 -2.3; 109 -2.5; 117 -2.7; 125 -3.0; 134 -3.2; 143 -3.3; 153 -3.2; 164 -3.2; 175 -2.9; 188 -2.9; 201 -2.8; 215 -2.6; 230 -2.3; 246 -2.2; 263 -2.1; 282 -1.9; 301 -2.0; 323 -2.1; 345 -1.8; 369 -1.8; 395 -2.0; 423 -1.9; 452 -1.9; 484 -2.0; 518 -1.9; 554 -1.4; 593 -0.9; 635 -0.6; 679 -0.6; 726 -0.5; 777 -0.1; 832 -0.0; 890 -0.0; 952 0.0; 1019 -0.0; 1090 -0.1; 1167 -0.5; 1248 -0.9; 1336 -1.3; 1429 -2.0; 1529 -2.6; 1636 -3.4; 1751 -4.0; 1873 -6.4; 2004 -8.4; 2145 -8.7; 2295 -6.8; 2455 -5.5; 2627 -4.5; 2811 -3.3; 3008 -2.9; 3219 -1.7; 3444 -1.9; 3685 -2.2; 3943 -0.0; 4219 2.8; 4514 3.9; 4830 2.7; 5168 -0.0; 5530 -0.8; 5917 -1.2; 6331 -2.8; 6775 -5.3; 7249 -6.8; 7756 -6.7; 8299 -7.2; 8880 -8.6; 9502 -8.7; 10167 -5.7; 10879 -1.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 6.0; 32 6.0; 35 5.5; 37 5.0; 40 4.2; 42 3.7; 45 3.0; 49 2.2; 52 1.8; 56 1.3; 59 0.9; 64 0.4; 68 -0.0; 73 -0.5; 78 -0.9; 83 -1.2; 89 -1.6; 95 -1.9; 102 -2.3; 109 -2.5; 117 -2.7; 125 -3.0; 134 -3.2; 143 -3.3; 153 -3.2; 164 -3.2; 175 -2.9; 188 -2.9; 201 -2.8; 215 -2.6; 230 -2.3; 246 -2.2; 263 -2.1; 282 -1.9; 301 -2.0; 323 -2.1; 345 -1.8; 369 -1.8; 395 -2.0; 423 -1.9; 452 -1.9; 484 -2.0; 518 -1.9; 554 -1.4; 593 -0.9; 635 -0.6; 679 -0.6; 726 -0.5; 777 -0.1; 832 -0.0; 890 -0.0; 952 0.0; 1019 -0.0; 1090 -0.1; 1167 -0.5; 1248 -0.9; 1336 -1.3; 1429 -2.0; 1529 -2.6; 1636 -3.4; 1751 -4.0; 1873 -6.4; 2004 -8.4; 2145 -8.7; 2295 -6.8; 2455 -5.5; 2627 -4.5; 2811 -3.3; 3008 -2.9; 3219 -1.7; 3444 -1.9; 3685 -2.2; 3943 -0.0; 4219 2.8; 4514 3.9; 4830 2.7; 5168 -0.0; 5530 -0.8; 5917 -1.2; 6331 -2.8; 6775 -5.3; 7249 -6.8; 7756 -6.7; 8299 -7.2; 8880 -8.6; 9502 -8.7; 10167 -5.7; 10879 -1.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Innerfidelity%202017/innerfidelity/onear/Grado%20SR225i/Grado%20SR225i.png)