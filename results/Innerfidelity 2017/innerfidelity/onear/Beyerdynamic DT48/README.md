# Beyerdynamic DT48
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 6.0; 32 6.0; 35 6.0; 37 6.0; 40 6.0; 42 6.0; 45 6.0; 49 6.0; 52 6.0; 56 6.0; 59 6.0; 64 6.0; 68 4.0; 73 -2.3; 78 -7.0; 83 -7.3; 89 -5.4; 95 -3.9; 102 -3.7; 109 -4.1; 117 -4.0; 125 -3.8; 134 -3.5; 143 -3.2; 153 -2.7; 164 -2.5; 175 -3.6; 188 -3.1; 201 -2.8; 215 -2.4; 230 -2.0; 246 -1.7; 263 -1.3; 282 -0.8; 301 -0.4; 323 -0.1; 345 0.2; 369 0.5; 395 0.8; 423 1.5; 452 2.0; 484 2.6; 518 3.4; 554 4.6; 593 5.5; 635 5.1; 679 4.2; 726 2.9; 777 2.7; 832 2.8; 890 1.9; 952 0.8; 1019 -0.3; 1090 -1.7; 1167 -3.0; 1248 -3.8; 1336 -4.1; 1429 -4.5; 1529 -5.0; 1636 -5.8; 1751 -6.4; 1873 -6.9; 2004 -6.8; 2145 -6.2; 2295 -5.3; 2455 -2.9; 2627 -0.7; 2811 1.2; 3008 2.4; 3219 2.7; 3444 4.0; 3685 5.7; 3943 6.0; 4219 6.0; 4514 6.0; 4830 6.0; 5168 6.0; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 -0.5; 7756 -5.9; 8299 -9.4; 8880 -8.9; 9502 -4.7; 10167 -0.5; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 -1.5; 16326 -5.7; 17469 -8.5; 18692 -7.5; 20000 -1.3
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 6.0; 32 6.0; 35 6.0; 37 6.0; 40 6.0; 42 6.0; 45 6.0; 49 6.0; 52 6.0; 56 6.0; 59 6.0; 64 6.0; 68 4.0; 73 -2.3; 78 -7.0; 83 -7.3; 89 -5.4; 95 -3.9; 102 -3.7; 109 -4.1; 117 -4.0; 125 -3.8; 134 -3.5; 143 -3.2; 153 -2.7; 164 -2.5; 175 -3.6; 188 -3.1; 201 -2.8; 215 -2.4; 230 -2.0; 246 -1.7; 263 -1.3; 282 -0.8; 301 -0.4; 323 -0.1; 345 0.2; 369 0.5; 395 0.8; 423 1.5; 452 2.0; 484 2.6; 518 3.4; 554 4.6; 593 5.5; 635 5.1; 679 4.2; 726 2.9; 777 2.7; 832 2.8; 890 1.9; 952 0.8; 1019 -0.3; 1090 -1.7; 1167 -3.0; 1248 -3.8; 1336 -4.1; 1429 -4.5; 1529 -5.0; 1636 -5.8; 1751 -6.4; 1873 -6.9; 2004 -6.8; 2145 -6.2; 2295 -5.3; 2455 -2.9; 2627 -0.7; 2811 1.2; 3008 2.4; 3219 2.7; 3444 4.0; 3685 5.7; 3943 6.0; 4219 6.0; 4514 6.0; 4830 6.0; 5168 6.0; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 -0.5; 7756 -5.9; 8299 -9.4; 8880 -8.9; 9502 -4.7; 10167 -0.5; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 -1.5; 16326 -5.7; 17469 -8.5; 18692 -7.5; 20000 -1.3
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Innerfidelity%202017/innerfidelity/onear/Beyerdynamic%20DT48/Beyerdynamic%20DT48.png)