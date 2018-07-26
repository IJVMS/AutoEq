# AKG K267 Tiesto Studio Setting
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 3.1; 22 3.1; 23 3.2; 25 3.2; 26 3.2; 28 3.3; 30 3.4; 32 3.4; 35 3.6; 37 3.6; 40 3.8; 42 3.9; 45 4.1; 49 4.4; 52 4.6; 56 4.7; 59 4.7; 64 4.6; 68 4.5; 73 4.6; 78 4.7; 83 4.4; 89 3.4; 95 2.4; 102 1.4; 109 0.7; 117 -0.3; 125 -1.1; 134 -1.3; 143 -1.5; 153 -1.4; 164 -0.9; 175 -1.3; 188 -1.6; 201 -1.5; 215 -1.5; 230 -1.5; 246 -1.2; 263 -0.9; 282 -0.4; 301 0.4; 323 1.0; 345 0.9; 369 0.7; 395 0.2; 423 -0.2; 452 -0.4; 484 -0.4; 518 -0.3; 554 -0.0; 593 0.2; 635 0.3; 679 0.3; 726 0.4; 777 0.4; 832 0.3; 890 0.3; 952 0.1; 1019 -0.1; 1090 -0.1; 1167 -0.1; 1248 -0.5; 1336 -0.8; 1429 -0.6; 1529 0.5; 1636 1.5; 1751 2.4; 1873 2.9; 2004 3.5; 2145 4.1; 2295 4.9; 2455 5.9; 2627 6.0; 2811 6.0; 3008 6.0; 3219 6.0; 3444 6.0; 3685 6.0; 3943 6.0; 4219 6.0; 4514 6.0; 4830 6.0; 5168 6.0; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 3.1; 22 3.1; 23 3.2; 25 3.2; 26 3.2; 28 3.3; 30 3.4; 32 3.4; 35 3.6; 37 3.6; 40 3.8; 42 3.9; 45 4.1; 49 4.4; 52 4.6; 56 4.7; 59 4.7; 64 4.6; 68 4.5; 73 4.6; 78 4.7; 83 4.4; 89 3.4; 95 2.4; 102 1.4; 109 0.7; 117 -0.3; 125 -1.1; 134 -1.3; 143 -1.5; 153 -1.4; 164 -0.9; 175 -1.3; 188 -1.6; 201 -1.5; 215 -1.5; 230 -1.5; 246 -1.2; 263 -0.9; 282 -0.4; 301 0.4; 323 1.0; 345 0.9; 369 0.7; 395 0.2; 423 -0.2; 452 -0.4; 484 -0.4; 518 -0.3; 554 -0.0; 593 0.2; 635 0.3; 679 0.3; 726 0.4; 777 0.4; 832 0.3; 890 0.3; 952 0.1; 1019 -0.1; 1090 -0.1; 1167 -0.1; 1248 -0.5; 1336 -0.8; 1429 -0.6; 1529 0.5; 1636 1.5; 1751 2.4; 1873 2.9; 2004 3.5; 2145 4.1; 2295 4.9; 2455 5.9; 2627 6.0; 2811 6.0; 3008 6.0; 3219 6.0; 3444 6.0; 3685 6.0; 3943 6.0; 4219 6.0; 4514 6.0; 4830 6.0; 5168 6.0; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Headphone.com/innerfidelity/onear/AKG%20K267%20Tiesto%20Studio%20Setting/AKG%20K267%20Tiesto%20Studio%20Setting.png)