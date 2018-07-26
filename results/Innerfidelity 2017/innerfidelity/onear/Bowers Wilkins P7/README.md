# Bowers Wilkins P7
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-52**.
```
GraphicEQ: 10 -84; 20 0.1; 22 -0.3; 23 -0.5; 25 -0.8; 26 -1.0; 28 -1.2; 30 -1.4; 32 -1.7; 35 -1.9; 37 -2.0; 40 -2.0; 42 -2.0; 45 -2.1; 49 -2.2; 52 -2.1; 56 -1.8; 59 -1.9; 64 -2.3; 68 -2.5; 73 -2.6; 78 -2.6; 83 -2.4; 89 -2.5; 95 -2.3; 102 -1.6; 109 -1.4; 117 -1.3; 125 -2.0; 134 -2.6; 143 -3.4; 153 -3.5; 164 -2.3; 175 -2.4; 188 -2.7; 201 -2.3; 215 -2.0; 230 -1.5; 246 -1.0; 263 -0.6; 282 -0.2; 301 0.1; 323 0.2; 345 0.3; 369 0.4; 395 0.3; 423 0.3; 452 0.3; 484 0.0; 518 0.0; 554 0.5; 593 0.9; 635 1.0; 679 0.7; 726 0.4; 777 0.1; 832 -0.3; 890 -0.2; 952 0.1; 1019 -0.1; 1090 -0.5; 1167 -1.0; 1248 -1.6; 1336 -2.3; 1429 -2.8; 1529 -3.3; 1636 -3.8; 1751 -4.1; 1873 -4.2; 2004 -4.0; 2145 -3.6; 2295 -2.9; 2455 -1.4; 2627 1.1; 2811 3.3; 3008 4.6; 3219 4.6; 3444 3.6; 3685 2.3; 3943 2.5; 4219 3.7; 4514 4.4; 4830 4.8; 5168 4.7; 5530 3.2; 5917 2.1; 6331 5.0; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 0.1; 22 -0.3; 23 -0.5; 25 -0.8; 26 -1.0; 28 -1.2; 30 -1.4; 32 -1.7; 35 -1.9; 37 -2.0; 40 -2.0; 42 -2.0; 45 -2.1; 49 -2.2; 52 -2.1; 56 -1.8; 59 -1.9; 64 -2.3; 68 -2.5; 73 -2.6; 78 -2.6; 83 -2.4; 89 -2.5; 95 -2.3; 102 -1.6; 109 -1.4; 117 -1.3; 125 -2.0; 134 -2.6; 143 -3.4; 153 -3.5; 164 -2.3; 175 -2.4; 188 -2.7; 201 -2.3; 215 -2.0; 230 -1.5; 246 -1.0; 263 -0.6; 282 -0.2; 301 0.1; 323 0.2; 345 0.3; 369 0.4; 395 0.3; 423 0.3; 452 0.3; 484 0.0; 518 0.0; 554 0.5; 593 0.9; 635 1.0; 679 0.7; 726 0.4; 777 0.1; 832 -0.3; 890 -0.2; 952 0.1; 1019 -0.1; 1090 -0.5; 1167 -1.0; 1248 -1.6; 1336 -2.3; 1429 -2.8; 1529 -3.3; 1636 -3.8; 1751 -4.1; 1873 -4.2; 2004 -4.0; 2145 -3.6; 2295 -2.9; 2455 -1.4; 2627 1.1; 2811 3.3; 3008 4.6; 3219 4.6; 3444 3.6; 3685 2.3; 3943 2.5; 4219 3.7; 4514 4.4; 4830 4.8; 5168 4.7; 5530 3.2; 5917 2.1; 6331 5.0; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
Copy: L=-5.2dB*l, R=-5.2dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Innerfidelity%202017/innerfidelity/onear/Bowers%20Wilkins%20P7/Bowers%20Wilkins%20P7.png)