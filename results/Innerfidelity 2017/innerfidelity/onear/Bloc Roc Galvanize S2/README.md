# Bloc Roc Galvanize S2
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 1.8; 22 0.9; 23 0.4; 25 -0.5; 26 -0.9; 28 -1.7; 30 -2.5; 32 -3.2; 35 -4.1; 37 -4.6; 40 -5.4; 42 -5.8; 45 -6.4; 49 -7.0; 52 -7.3; 56 -7.6; 59 -7.8; 64 -7.8; 68 -7.8; 73 -7.9; 78 -7.8; 83 -7.4; 89 -7.2; 95 -7.2; 102 -7.5; 109 -7.8; 117 -8.0; 125 -8.2; 134 -8.4; 143 -8.4; 153 -8.3; 164 -7.9; 175 -7.9; 188 -7.7; 201 -7.5; 215 -7.2; 230 -6.8; 246 -6.4; 263 -6.0; 282 -5.5; 301 -5.9; 323 -5.9; 345 -5.6; 369 -5.2; 395 -5.0; 423 -4.6; 452 -4.7; 484 -4.5; 518 -3.9; 554 -2.9; 593 -1.6; 635 -0.5; 679 0.1; 726 0.5; 777 0.6; 832 0.6; 890 0.5; 952 0.2; 1019 -0.1; 1090 -0.7; 1167 -1.2; 1248 -1.6; 1336 -2.4; 1429 -2.9; 1529 -3.8; 1636 -4.3; 1751 -4.7; 1873 -4.4; 2004 -4.3; 2145 -3.6; 2295 -2.9; 2455 -1.8; 2627 -0.4; 2811 1.1; 3008 1.8; 3219 1.3; 3444 3.0; 3685 4.8; 3943 5.9; 4219 6.0; 4514 4.4; 4830 1.4; 5168 0.4; 5530 -0.8; 5917 -0.1; 6331 -0.7; 6775 -1.5; 7249 0.5; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 1.8; 22 0.9; 23 0.4; 25 -0.5; 26 -0.9; 28 -1.7; 30 -2.5; 32 -3.2; 35 -4.1; 37 -4.6; 40 -5.4; 42 -5.8; 45 -6.4; 49 -7.0; 52 -7.3; 56 -7.6; 59 -7.8; 64 -7.8; 68 -7.8; 73 -7.9; 78 -7.8; 83 -7.4; 89 -7.2; 95 -7.2; 102 -7.5; 109 -7.8; 117 -8.0; 125 -8.2; 134 -8.4; 143 -8.4; 153 -8.3; 164 -7.9; 175 -7.9; 188 -7.7; 201 -7.5; 215 -7.2; 230 -6.8; 246 -6.4; 263 -6.0; 282 -5.5; 301 -5.9; 323 -5.9; 345 -5.6; 369 -5.2; 395 -5.0; 423 -4.6; 452 -4.7; 484 -4.5; 518 -3.9; 554 -2.9; 593 -1.6; 635 -0.5; 679 0.1; 726 0.5; 777 0.6; 832 0.6; 890 0.5; 952 0.2; 1019 -0.1; 1090 -0.7; 1167 -1.2; 1248 -1.6; 1336 -2.4; 1429 -2.9; 1529 -3.8; 1636 -4.3; 1751 -4.7; 1873 -4.4; 2004 -4.3; 2145 -3.6; 2295 -2.9; 2455 -1.8; 2627 -0.4; 2811 1.1; 3008 1.8; 3219 1.3; 3444 3.0; 3685 4.8; 3943 5.9; 4219 6.0; 4514 4.4; 4830 1.4; 5168 0.4; 5530 -0.8; 5917 -0.1; 6331 -0.7; 6775 -1.5; 7249 0.5; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Innerfidelity%202017/innerfidelity/onear/Bloc%20Roc%20Galvanize%20S2/Bloc%20Roc%20Galvanize%20S2.png)