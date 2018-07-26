# AKG K267 Tiesto Club Setting
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 1.0; 22 0.9; 23 0.9; 25 0.9; 26 1.0; 28 1.0; 30 1.0; 32 1.1; 35 1.2; 37 1.3; 40 1.4; 42 1.5; 45 1.7; 49 2.0; 52 2.2; 56 2.4; 59 2.5; 64 2.7; 68 3.0; 73 3.1; 78 3.1; 83 2.8; 89 1.8; 95 1.0; 102 0.6; 109 0.1; 117 -0.7; 125 -1.5; 134 -1.8; 143 -1.9; 153 -1.8; 164 -1.2; 175 -1.6; 188 -1.7; 201 -1.7; 215 -1.5; 230 -1.3; 246 -1.0; 263 -0.6; 282 0.2; 301 1.1; 323 2.0; 345 1.9; 369 1.6; 395 0.9; 423 0.3; 452 0.0; 484 -0.1; 518 0.0; 554 0.2; 593 0.3; 635 0.4; 679 0.6; 726 0.5; 777 0.6; 832 0.5; 890 0.3; 952 0.1; 1019 -0.1; 1090 -0.4; 1167 -0.6; 1248 -1.0; 1336 -1.6; 1429 -1.7; 1529 -0.7; 1636 0.4; 1751 1.5; 1873 2.1; 2004 2.7; 2145 3.3; 2295 4.0; 2455 5.0; 2627 5.3; 2811 5.2; 3008 5.4; 3219 5.3; 3444 5.6; 3685 6.0; 3943 6.0; 4219 6.0; 4514 6.0; 4830 6.0; 5168 6.0; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 1.0; 22 0.9; 23 0.9; 25 0.9; 26 1.0; 28 1.0; 30 1.0; 32 1.1; 35 1.2; 37 1.3; 40 1.4; 42 1.5; 45 1.7; 49 2.0; 52 2.2; 56 2.4; 59 2.5; 64 2.7; 68 3.0; 73 3.1; 78 3.1; 83 2.8; 89 1.8; 95 1.0; 102 0.6; 109 0.1; 117 -0.7; 125 -1.5; 134 -1.8; 143 -1.9; 153 -1.8; 164 -1.2; 175 -1.6; 188 -1.7; 201 -1.7; 215 -1.5; 230 -1.3; 246 -1.0; 263 -0.6; 282 0.2; 301 1.1; 323 2.0; 345 1.9; 369 1.6; 395 0.9; 423 0.3; 452 0.0; 484 -0.1; 518 0.0; 554 0.2; 593 0.3; 635 0.4; 679 0.6; 726 0.5; 777 0.6; 832 0.5; 890 0.3; 952 0.1; 1019 -0.1; 1090 -0.4; 1167 -0.6; 1248 -1.0; 1336 -1.6; 1429 -1.7; 1529 -0.7; 1636 0.4; 1751 1.5; 1873 2.1; 2004 2.7; 2145 3.3; 2295 4.0; 2455 5.0; 2627 5.3; 2811 5.2; 3008 5.4; 3219 5.3; 3444 5.6; 3685 6.0; 3943 6.0; 4219 6.0; 4514 6.0; 4830 6.0; 5168 6.0; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Headphone.com/innerfidelity/onear/AKG%20K267%20Tiesto%20Club%20Setting/AKG%20K267%20Tiesto%20Club%20Setting.png)