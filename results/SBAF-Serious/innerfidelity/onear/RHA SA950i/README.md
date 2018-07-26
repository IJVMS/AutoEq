# RHA SA950i
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 -5.2; 22 -5.7; 23 -5.9; 25 -6.2; 26 -6.4; 28 -6.6; 30 -6.7; 32 -6.8; 35 -6.8; 37 -6.8; 40 -6.8; 42 -6.8; 45 -6.8; 49 -6.6; 52 -6.5; 56 -6.4; 59 -6.4; 64 -6.3; 68 -6.2; 73 -6.1; 78 -6.1; 83 -6.2; 89 -6.0; 95 -6.0; 102 -6.3; 109 -6.6; 117 -6.7; 125 -6.9; 134 -7.4; 143 -7.7; 153 -7.9; 164 -7.8; 175 -7.8; 188 -7.9; 201 -7.9; 215 -7.6; 230 -7.3; 246 -7.3; 263 -7.3; 282 -7.2; 301 -7.3; 323 -7.6; 345 -7.8; 369 -7.9; 395 -7.9; 423 -7.7; 452 -7.6; 484 -7.6; 518 -7.4; 554 -6.9; 593 -6.2; 635 -5.7; 679 -4.9; 726 -3.8; 777 -2.7; 832 -1.6; 890 -1.0; 952 -0.5; 1019 0.1; 1090 -0.5; 1167 -1.4; 1248 -2.9; 1336 -4.4; 1429 -5.6; 1529 -5.9; 1636 -5.8; 1751 -5.1; 1873 -3.8; 2004 -2.3; 2145 -1.0; 2295 -0.2; 2455 1.1; 2627 2.1; 2811 2.6; 3008 3.3; 3219 4.4; 3444 4.3; 3685 4.5; 3943 5.8; 4219 6.0; 4514 6.0; 4830 1.5; 5168 -1.7; 5530 -1.4; 5917 3.0; 6331 5.4; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 -5.2; 22 -5.7; 23 -5.9; 25 -6.2; 26 -6.4; 28 -6.6; 30 -6.7; 32 -6.8; 35 -6.8; 37 -6.8; 40 -6.8; 42 -6.8; 45 -6.8; 49 -6.6; 52 -6.5; 56 -6.4; 59 -6.4; 64 -6.3; 68 -6.2; 73 -6.1; 78 -6.1; 83 -6.2; 89 -6.0; 95 -6.0; 102 -6.3; 109 -6.6; 117 -6.7; 125 -6.9; 134 -7.4; 143 -7.7; 153 -7.9; 164 -7.8; 175 -7.8; 188 -7.9; 201 -7.9; 215 -7.6; 230 -7.3; 246 -7.3; 263 -7.3; 282 -7.2; 301 -7.3; 323 -7.6; 345 -7.8; 369 -7.9; 395 -7.9; 423 -7.7; 452 -7.6; 484 -7.6; 518 -7.4; 554 -6.9; 593 -6.2; 635 -5.7; 679 -4.9; 726 -3.8; 777 -2.7; 832 -1.6; 890 -1.0; 952 -0.5; 1019 0.1; 1090 -0.5; 1167 -1.4; 1248 -2.9; 1336 -4.4; 1429 -5.6; 1529 -5.9; 1636 -5.8; 1751 -5.1; 1873 -3.8; 2004 -2.3; 2145 -1.0; 2295 -0.2; 2455 1.1; 2627 2.1; 2811 2.6; 3008 3.3; 3219 4.4; 3444 4.3; 3685 4.5; 3943 5.8; 4219 6.0; 4514 6.0; 4830 1.5; 5168 -1.7; 5530 -1.4; 5917 3.0; 6331 5.4; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/SBAF-Serious/innerfidelity/onear/RHA%20SA950i/RHA%20SA950i.png)