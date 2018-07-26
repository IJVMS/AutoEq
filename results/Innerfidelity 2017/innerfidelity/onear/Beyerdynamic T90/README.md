# Beyerdynamic T90
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-55**.
```
GraphicEQ: 10 -84; 20 3.5; 22 3.2; 23 3.1; 25 2.8; 26 2.7; 28 2.4; 30 2.2; 32 2.0; 35 1.8; 37 1.7; 40 1.6; 42 1.6; 45 1.5; 49 1.3; 52 1.3; 56 1.7; 59 1.9; 64 1.4; 68 0.7; 73 0.1; 78 -0.3; 83 -0.6; 89 -1.0; 95 -1.5; 102 -2.1; 109 -2.6; 117 -3.0; 125 -3.7; 134 -4.1; 143 -4.3; 153 -4.5; 164 -4.6; 175 -4.7; 188 -4.9; 201 -5.0; 215 -5.0; 230 -5.1; 246 -5.2; 263 -5.1; 282 -5.0; 301 -5.1; 323 -5.0; 345 -4.8; 369 -4.6; 395 -4.5; 423 -4.4; 452 -4.2; 484 -4.2; 518 -3.8; 554 -3.1; 593 -2.2; 635 -1.7; 679 -1.3; 726 -1.0; 777 -0.5; 832 -0.3; 890 -0.1; 952 0.0; 1019 -0.1; 1090 -0.2; 1167 -0.2; 1248 -0.4; 1336 -0.7; 1429 -1.0; 1529 -1.4; 1636 -1.9; 1751 -2.5; 1873 -2.8; 2004 -3.1; 2145 -3.2; 2295 -3.2; 2455 -3.0; 2627 -3.2; 2811 -3.5; 3008 -3.6; 3219 -3.6; 3444 -2.9; 3685 -2.2; 3943 -1.2; 4219 -0.3; 4514 2.3; 4830 5.5; 5168 3.0; 5530 1.5; 5917 -1.0; 6331 -6.5; 6775 -9.6; 7249 -10.4; 7756 -11.5; 8299 -12.2; 8880 -12.1; 9502 -10.5; 10167 -8.5; 10879 -7.1; 11640 -6.1; 12455 -4.4; 13327 -1.7; 14260 -0.0; 15258 -0.0; 16326 -1.8; 17469 -4.3; 18692 -4.2; 20000 -0.1
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 3.5; 22 3.2; 23 3.1; 25 2.8; 26 2.7; 28 2.4; 30 2.2; 32 2.0; 35 1.8; 37 1.7; 40 1.6; 42 1.6; 45 1.5; 49 1.3; 52 1.3; 56 1.7; 59 1.9; 64 1.4; 68 0.7; 73 0.1; 78 -0.3; 83 -0.6; 89 -1.0; 95 -1.5; 102 -2.1; 109 -2.6; 117 -3.0; 125 -3.7; 134 -4.1; 143 -4.3; 153 -4.5; 164 -4.6; 175 -4.7; 188 -4.9; 201 -5.0; 215 -5.0; 230 -5.1; 246 -5.2; 263 -5.1; 282 -5.0; 301 -5.1; 323 -5.0; 345 -4.8; 369 -4.6; 395 -4.5; 423 -4.4; 452 -4.2; 484 -4.2; 518 -3.8; 554 -3.1; 593 -2.2; 635 -1.7; 679 -1.3; 726 -1.0; 777 -0.5; 832 -0.3; 890 -0.1; 952 0.0; 1019 -0.1; 1090 -0.2; 1167 -0.2; 1248 -0.4; 1336 -0.7; 1429 -1.0; 1529 -1.4; 1636 -1.9; 1751 -2.5; 1873 -2.8; 2004 -3.1; 2145 -3.2; 2295 -3.2; 2455 -3.0; 2627 -3.2; 2811 -3.5; 3008 -3.6; 3219 -3.6; 3444 -2.9; 3685 -2.2; 3943 -1.2; 4219 -0.3; 4514 2.3; 4830 5.5; 5168 3.0; 5530 1.5; 5917 -1.0; 6331 -6.5; 6775 -9.6; 7249 -10.4; 7756 -11.5; 8299 -12.2; 8880 -12.1; 9502 -10.5; 10167 -8.5; 10879 -7.1; 11640 -6.1; 12455 -4.4; 13327 -1.7; 14260 -0.0; 15258 -0.0; 16326 -1.8; 17469 -4.3; 18692 -4.2; 20000 -0.1
Copy: L=-5.5dB*l, R=-5.5dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Innerfidelity%202017/innerfidelity/onear/Beyerdynamic%20T90/Beyerdynamic%20T90.png)