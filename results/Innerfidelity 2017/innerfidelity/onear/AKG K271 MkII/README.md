# AKG K271 MkII
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-61**.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 6.0; 32 6.0; 35 5.7; 37 5.4; 40 4.8; 42 4.4; 45 3.9; 49 3.3; 52 3.0; 56 2.6; 59 2.5; 64 2.5; 68 2.8; 73 3.6; 78 4.5; 83 5.2; 89 6.0; 95 5.9; 102 3.9; 109 2.4; 117 1.7; 125 1.3; 134 0.3; 143 -0.3; 153 -0.0; 164 0.8; 175 0.0; 188 -0.2; 201 -0.1; 215 -0.4; 230 -1.1; 246 -1.6; 263 -1.9; 282 -2.0; 301 -2.2; 323 -2.3; 345 -2.3; 369 -2.4; 395 -2.6; 423 -2.7; 452 -2.9; 484 -3.3; 518 -3.4; 554 -3.3; 593 -3.2; 635 -3.7; 679 -3.2; 726 -0.7; 777 0.7; 832 0.5; 890 0.5; 952 0.4; 1019 -0.1; 1090 -0.4; 1167 -0.7; 1248 -1.1; 1336 -1.4; 1429 -1.8; 1529 -2.3; 1636 -2.8; 1751 -2.8; 1873 -2.1; 2004 -0.0; 2145 1.1; 2295 0.6; 2455 2.0; 2627 2.2; 2811 2.5; 3008 3.5; 3219 4.1; 3444 5.1; 3685 5.9; 3943 6.0; 4219 6.0; 4514 6.0; 4830 6.0; 5168 6.0; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 -1.2; 8299 -4.9; 8880 -6.9; 9502 -7.1; 10167 -5.3; 10879 -1.1; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 6.0; 32 6.0; 35 5.7; 37 5.4; 40 4.8; 42 4.4; 45 3.9; 49 3.3; 52 3.0; 56 2.6; 59 2.5; 64 2.5; 68 2.8; 73 3.6; 78 4.5; 83 5.2; 89 6.0; 95 5.9; 102 3.9; 109 2.4; 117 1.7; 125 1.3; 134 0.3; 143 -0.3; 153 -0.0; 164 0.8; 175 0.0; 188 -0.2; 201 -0.1; 215 -0.4; 230 -1.1; 246 -1.6; 263 -1.9; 282 -2.0; 301 -2.2; 323 -2.3; 345 -2.3; 369 -2.4; 395 -2.6; 423 -2.7; 452 -2.9; 484 -3.3; 518 -3.4; 554 -3.3; 593 -3.2; 635 -3.7; 679 -3.2; 726 -0.7; 777 0.7; 832 0.5; 890 0.5; 952 0.4; 1019 -0.1; 1090 -0.4; 1167 -0.7; 1248 -1.1; 1336 -1.4; 1429 -1.8; 1529 -2.3; 1636 -2.8; 1751 -2.8; 1873 -2.1; 2004 -0.0; 2145 1.1; 2295 0.6; 2455 2.0; 2627 2.2; 2811 2.5; 3008 3.5; 3219 4.1; 3444 5.1; 3685 5.9; 3943 6.0; 4219 6.0; 4514 6.0; 4830 6.0; 5168 6.0; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 -1.2; 8299 -4.9; 8880 -6.9; 9502 -7.1; 10167 -5.3; 10879 -1.1; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
Copy: L=-6.1dB*l, R=-6.1dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Innerfidelity%202017/innerfidelity/onear/AKG%20K271%20MkII/AKG%20K271%20MkII.png)