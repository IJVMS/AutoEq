# AKG N90Q Nominal
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-56**.
```
GraphicEQ: 10 -84; 20 -0.8; 22 -0.7; 23 -0.6; 25 -0.5; 26 -0.5; 28 -0.4; 30 -0.2; 32 -0.1; 35 0.1; 37 0.3; 40 0.5; 42 0.6; 45 0.8; 49 1.1; 52 1.3; 56 1.5; 59 1.6; 64 1.6; 68 1.5; 73 1.3; 78 1.1; 83 0.8; 89 0.5; 95 0.1; 102 -0.4; 109 -0.8; 117 -1.2; 125 -1.6; 134 -2.0; 143 -2.2; 153 -2.2; 164 -2.3; 175 -2.3; 188 -2.3; 201 -2.2; 215 -2.2; 230 -2.1; 246 -2.1; 263 -2.0; 282 -1.9; 301 -2.0; 323 -1.9; 345 -1.9; 369 -1.8; 395 -1.9; 423 -1.8; 452 -1.8; 484 -1.7; 518 -1.6; 554 -1.4; 593 -1.0; 635 -0.3; 679 -0.3; 726 -1.0; 777 -0.9; 832 -0.7; 890 -0.4; 952 -0.1; 1019 0.0; 1090 0.2; 1167 0.6; 1248 1.2; 1336 1.7; 1429 2.1; 1529 2.3; 1636 2.7; 1751 2.4; 1873 2.0; 2004 2.0; 2145 1.1; 2295 0.4; 2455 -0.5; 2627 -0.6; 2811 -0.4; 3008 -1.2; 3219 -2.1; 3444 -2.5; 3685 -2.5; 3943 -2.7; 4219 -1.9; 4514 0.6; 4830 3.2; 5168 5.3; 5530 5.2; 5917 3.8; 6331 5.1; 6775 3.9; 7249 1.3; 7756 0.3; 8299 -1.0; 8880 -3.0; 9502 -3.0; 10167 -0.8; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 -0.8; 22 -0.7; 23 -0.6; 25 -0.5; 26 -0.5; 28 -0.4; 30 -0.2; 32 -0.1; 35 0.1; 37 0.3; 40 0.5; 42 0.6; 45 0.8; 49 1.1; 52 1.3; 56 1.5; 59 1.6; 64 1.6; 68 1.5; 73 1.3; 78 1.1; 83 0.8; 89 0.5; 95 0.1; 102 -0.4; 109 -0.8; 117 -1.2; 125 -1.6; 134 -2.0; 143 -2.2; 153 -2.2; 164 -2.3; 175 -2.3; 188 -2.3; 201 -2.2; 215 -2.2; 230 -2.1; 246 -2.1; 263 -2.0; 282 -1.9; 301 -2.0; 323 -1.9; 345 -1.9; 369 -1.8; 395 -1.9; 423 -1.8; 452 -1.8; 484 -1.7; 518 -1.6; 554 -1.4; 593 -1.0; 635 -0.3; 679 -0.3; 726 -1.0; 777 -0.9; 832 -0.7; 890 -0.4; 952 -0.1; 1019 0.0; 1090 0.2; 1167 0.6; 1248 1.2; 1336 1.7; 1429 2.1; 1529 2.3; 1636 2.7; 1751 2.4; 1873 2.0; 2004 2.0; 2145 1.1; 2295 0.4; 2455 -0.5; 2627 -0.6; 2811 -0.4; 3008 -1.2; 3219 -2.1; 3444 -2.5; 3685 -2.5; 3943 -2.7; 4219 -1.9; 4514 0.6; 4830 3.2; 5168 5.3; 5530 5.2; 5917 3.8; 6331 5.1; 6775 3.9; 7249 1.3; 7756 0.3; 8299 -1.0; 8880 -3.0; 9502 -3.0; 10167 -0.8; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
Copy: L=-5.6dB*l, R=-5.6dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Headphone.com/innerfidelity/onear/AKG%20N90Q%20Nominal/AKG%20N90Q%20Nominal.png)