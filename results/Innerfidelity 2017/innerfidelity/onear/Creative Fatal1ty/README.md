# Creative Fatal1ty
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 0.9; 22 0.1; 23 -0.3; 25 -0.9; 26 -1.1; 28 -1.6; 30 -2.0; 32 -2.4; 35 -2.9; 37 -3.2; 40 -3.5; 42 -3.7; 45 -3.9; 49 -4.1; 52 -4.2; 56 -4.3; 59 -4.4; 64 -4.4; 68 -4.4; 73 -4.4; 78 -4.5; 83 -4.6; 89 -4.7; 95 -4.7; 102 -4.7; 109 -4.8; 117 -5.0; 125 -5.3; 134 -5.4; 143 -5.5; 153 -5.4; 164 -5.1; 175 -4.9; 188 -4.7; 201 -4.5; 215 -4.2; 230 -3.7; 246 -3.3; 263 -3.1; 282 -2.6; 301 -2.0; 323 -1.6; 345 -1.0; 369 -0.5; 395 -0.3; 423 0.1; 452 0.3; 484 0.1; 518 -0.1; 554 0.0; 593 0.1; 635 -0.2; 679 -0.7; 726 -0.7; 777 -0.2; 832 -0.3; 890 -0.3; 952 -0.2; 1019 0.0; 1090 0.2; 1167 0.3; 1248 0.3; 1336 0.3; 1429 0.5; 1529 0.9; 1636 1.4; 1751 1.8; 1873 2.5; 2004 3.4; 2145 4.4; 2295 5.4; 2455 6.0; 2627 6.0; 2811 6.0; 3008 6.0; 3219 6.0; 3444 6.0; 3685 6.0; 3943 6.0; 4219 6.0; 4514 6.0; 4830 6.0; 5168 6.0; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 0.9; 22 0.1; 23 -0.3; 25 -0.9; 26 -1.1; 28 -1.6; 30 -2.0; 32 -2.4; 35 -2.9; 37 -3.2; 40 -3.5; 42 -3.7; 45 -3.9; 49 -4.1; 52 -4.2; 56 -4.3; 59 -4.4; 64 -4.4; 68 -4.4; 73 -4.4; 78 -4.5; 83 -4.6; 89 -4.7; 95 -4.7; 102 -4.7; 109 -4.8; 117 -5.0; 125 -5.3; 134 -5.4; 143 -5.5; 153 -5.4; 164 -5.1; 175 -4.9; 188 -4.7; 201 -4.5; 215 -4.2; 230 -3.7; 246 -3.3; 263 -3.1; 282 -2.6; 301 -2.0; 323 -1.6; 345 -1.0; 369 -0.5; 395 -0.3; 423 0.1; 452 0.3; 484 0.1; 518 -0.1; 554 0.0; 593 0.1; 635 -0.2; 679 -0.7; 726 -0.7; 777 -0.2; 832 -0.3; 890 -0.3; 952 -0.2; 1019 0.0; 1090 0.2; 1167 0.3; 1248 0.3; 1336 0.3; 1429 0.5; 1529 0.9; 1636 1.4; 1751 1.8; 1873 2.5; 2004 3.4; 2145 4.4; 2295 5.4; 2455 6.0; 2627 6.0; 2811 6.0; 3008 6.0; 3219 6.0; 3444 6.0; 3685 6.0; 3943 6.0; 4219 6.0; 4514 6.0; 4830 6.0; 5168 6.0; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Innerfidelity%202017/innerfidelity/onear/Creative%20Fatal1ty/Creative%20Fatal1ty.png)