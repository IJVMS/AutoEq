# Grado SR125i
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 5.8; 30 5.4; 32 4.9; 35 4.0; 37 3.5; 40 2.7; 42 2.3; 45 1.7; 49 1.0; 52 0.6; 56 0.1; 59 -0.2; 64 -0.7; 68 -0.9; 73 -1.2; 78 -1.5; 83 -1.7; 89 -2.0; 95 -2.4; 102 -2.6; 109 -2.8; 117 -3.0; 125 -3.4; 134 -3.5; 143 -3.6; 153 -3.6; 164 -3.5; 175 -3.3; 188 -3.2; 201 -3.1; 215 -2.8; 230 -2.6; 246 -2.4; 263 -2.3; 282 -2.0; 301 -1.7; 323 -2.1; 345 -2.4; 369 -2.4; 395 -2.5; 423 -2.3; 452 -2.3; 484 -2.4; 518 -2.2; 554 -1.7; 593 -1.0; 635 -0.8; 679 -0.8; 726 -0.6; 777 -0.2; 832 -0.1; 890 -0.1; 952 0.0; 1019 -0.0; 1090 -0.1; 1167 -0.3; 1248 -0.7; 1336 -1.1; 1429 -1.7; 1529 -2.5; 1636 -3.0; 1751 -3.7; 1873 -6.7; 2004 -10.0; 2145 -9.8; 2295 -8.1; 2455 -6.0; 2627 -4.5; 2811 -2.5; 3008 -1.3; 3219 0.2; 3444 -0.4; 3685 -0.6; 3943 0.8; 4219 3.5; 4514 4.2; 4830 3.3; 5168 1.5; 5530 0.4; 5917 1.8; 6331 1.3; 6775 -1.5; 7249 -3.9; 7756 -4.4; 8299 -4.5; 8880 -4.1; 9502 -2.6; 10167 -0.2; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 5.8; 30 5.4; 32 4.9; 35 4.0; 37 3.5; 40 2.7; 42 2.3; 45 1.7; 49 1.0; 52 0.6; 56 0.1; 59 -0.2; 64 -0.7; 68 -0.9; 73 -1.2; 78 -1.5; 83 -1.7; 89 -2.0; 95 -2.4; 102 -2.6; 109 -2.8; 117 -3.0; 125 -3.4; 134 -3.5; 143 -3.6; 153 -3.6; 164 -3.5; 175 -3.3; 188 -3.2; 201 -3.1; 215 -2.8; 230 -2.6; 246 -2.4; 263 -2.3; 282 -2.0; 301 -1.7; 323 -2.1; 345 -2.4; 369 -2.4; 395 -2.5; 423 -2.3; 452 -2.3; 484 -2.4; 518 -2.2; 554 -1.7; 593 -1.0; 635 -0.8; 679 -0.8; 726 -0.6; 777 -0.2; 832 -0.1; 890 -0.1; 952 0.0; 1019 -0.0; 1090 -0.1; 1167 -0.3; 1248 -0.7; 1336 -1.1; 1429 -1.7; 1529 -2.5; 1636 -3.0; 1751 -3.7; 1873 -6.7; 2004 -10.0; 2145 -9.8; 2295 -8.1; 2455 -6.0; 2627 -4.5; 2811 -2.5; 3008 -1.3; 3219 0.2; 3444 -0.4; 3685 -0.6; 3943 0.8; 4219 3.5; 4514 4.2; 4830 3.3; 5168 1.5; 5530 0.4; 5917 1.8; 6331 1.3; 6775 -1.5; 7249 -3.9; 7756 -4.4; 8299 -4.5; 8880 -4.1; 9502 -2.6; 10167 -0.2; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Innerfidelity%202017/innerfidelity/onear/Grado%20SR125i/Grado%20SR125i.png)