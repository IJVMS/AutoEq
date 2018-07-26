# Polk UltraFit 2000
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 6.0; 32 6.0; 35 6.0; 37 6.0; 40 6.0; 42 6.0; 45 6.0; 49 6.0; 52 6.0; 56 6.0; 59 6.0; 64 5.9; 68 5.3; 73 4.3; 78 3.6; 83 3.0; 89 2.1; 95 1.4; 102 0.7; 109 0.3; 117 -0.1; 125 -0.5; 134 -0.7; 143 -0.8; 153 -0.8; 164 -0.6; 175 -0.3; 188 -0.1; 201 0.0; 215 0.4; 230 0.6; 246 0.9; 263 1.0; 282 1.4; 301 1.7; 323 2.5; 345 2.7; 369 3.0; 395 3.3; 423 3.9; 452 4.3; 484 4.5; 518 5.0; 554 5.9; 593 6.0; 635 6.0; 679 6.0; 726 6.0; 777 6.0; 832 6.0; 890 4.0; 952 1.6; 1019 -0.6; 1090 -1.7; 1167 -2.3; 1248 -2.8; 1336 -3.0; 1429 -2.9; 1529 -2.8; 1636 -3.0; 1751 -3.5; 1873 -3.9; 2004 -3.7; 2145 -3.1; 2295 -2.0; 2455 -0.3; 2627 1.2; 2811 2.6; 3008 4.1; 3219 4.3; 3444 3.9; 3685 3.5; 3943 4.5; 4219 5.9; 4514 6.0; 4830 6.0; 5168 6.0; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 -0.5; 8299 -3.6; 8880 -5.0; 9502 -4.3; 10167 -1.8; 10879 -0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 6.0; 32 6.0; 35 6.0; 37 6.0; 40 6.0; 42 6.0; 45 6.0; 49 6.0; 52 6.0; 56 6.0; 59 6.0; 64 5.9; 68 5.3; 73 4.3; 78 3.6; 83 3.0; 89 2.1; 95 1.4; 102 0.7; 109 0.3; 117 -0.1; 125 -0.5; 134 -0.7; 143 -0.8; 153 -0.8; 164 -0.6; 175 -0.3; 188 -0.1; 201 0.0; 215 0.4; 230 0.6; 246 0.9; 263 1.0; 282 1.4; 301 1.7; 323 2.5; 345 2.7; 369 3.0; 395 3.3; 423 3.9; 452 4.3; 484 4.5; 518 5.0; 554 5.9; 593 6.0; 635 6.0; 679 6.0; 726 6.0; 777 6.0; 832 6.0; 890 4.0; 952 1.6; 1019 -0.6; 1090 -1.7; 1167 -2.3; 1248 -2.8; 1336 -3.0; 1429 -2.9; 1529 -2.8; 1636 -3.0; 1751 -3.5; 1873 -3.9; 2004 -3.7; 2145 -3.1; 2295 -2.0; 2455 -0.3; 2627 1.2; 2811 2.6; 3008 4.1; 3219 4.3; 3444 3.9; 3685 3.5; 3943 4.5; 4219 5.9; 4514 6.0; 4830 6.0; 5168 6.0; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 -0.5; 8299 -3.6; 8880 -5.0; 9502 -4.3; 10167 -1.8; 10879 -0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Innerfidelity%202017/innerfidelity/onear/Polk%20UltraFit%202000/Polk%20UltraFit%202000.png)