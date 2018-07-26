# AKG K702
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-18**.
```
GraphicEQ: 10 -84; 20 1.8; 22 1.2; 23 0.9; 25 0.4; 26 0.2; 28 -0.2; 30 -0.5; 32 -0.8; 35 -1.2; 37 -1.4; 40 -1.7; 42 -1.9; 45 -2.1; 49 -2.3; 52 -2.5; 56 -2.6; 59 -2.7; 64 -2.9; 68 -3.0; 73 -3.0; 78 -2.8; 83 -2.7; 89 -3.1; 95 -3.4; 102 -3.6; 109 -3.7; 117 -4.3; 125 -5.1; 134 -5.7; 143 -6.1; 153 -6.2; 164 -6.0; 175 -6.0; 188 -6.2; 201 -6.3; 215 -6.1; 230 -6.1; 246 -6.1; 263 -6.1; 282 -6.0; 301 -5.8; 323 -5.6; 345 -5.4; 369 -5.2; 395 -5.0; 423 -4.7; 452 -4.5; 484 -4.4; 518 -3.5; 554 -1.6; 593 -1.1; 635 -0.6; 679 -0.1; 726 0.3; 777 0.6; 832 0.4; 890 0.3; 952 0.2; 1019 -0.1; 1090 -0.7; 1167 -0.8; 1248 -0.7; 1336 -1.0; 1429 -1.4; 1529 -2.0; 1636 -2.6; 1751 -3.6; 1873 -4.1; 2004 -5.3; 2145 -5.6; 2295 -5.4; 2455 -4.7; 2627 -3.3; 2811 -2.0; 3008 -0.4; 3219 0.8; 3444 1.0; 3685 1.2; 3943 1.6; 4219 1.0; 4514 0.6; 4830 0.0; 5168 -0.5; 5530 -1.8; 5917 -4.5; 6331 -6.2; 6775 -7.0; 7249 -7.3; 7756 -7.4; 8299 -7.5; 8880 -6.1; 9502 -2.8; 10167 -0.1; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 -0.2; 17469 -2.8; 18692 -3.8; 20000 -1.8
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 1.8; 22 1.2; 23 0.9; 25 0.4; 26 0.2; 28 -0.2; 30 -0.5; 32 -0.8; 35 -1.2; 37 -1.4; 40 -1.7; 42 -1.9; 45 -2.1; 49 -2.3; 52 -2.5; 56 -2.6; 59 -2.7; 64 -2.9; 68 -3.0; 73 -3.0; 78 -2.8; 83 -2.7; 89 -3.1; 95 -3.4; 102 -3.6; 109 -3.7; 117 -4.3; 125 -5.1; 134 -5.7; 143 -6.1; 153 -6.2; 164 -6.0; 175 -6.0; 188 -6.2; 201 -6.3; 215 -6.1; 230 -6.1; 246 -6.1; 263 -6.1; 282 -6.0; 301 -5.8; 323 -5.6; 345 -5.4; 369 -5.2; 395 -5.0; 423 -4.7; 452 -4.5; 484 -4.4; 518 -3.5; 554 -1.6; 593 -1.1; 635 -0.6; 679 -0.1; 726 0.3; 777 0.6; 832 0.4; 890 0.3; 952 0.2; 1019 -0.1; 1090 -0.7; 1167 -0.8; 1248 -0.7; 1336 -1.0; 1429 -1.4; 1529 -2.0; 1636 -2.6; 1751 -3.6; 1873 -4.1; 2004 -5.3; 2145 -5.6; 2295 -5.4; 2455 -4.7; 2627 -3.3; 2811 -2.0; 3008 -0.4; 3219 0.8; 3444 1.0; 3685 1.2; 3943 1.6; 4219 1.0; 4514 0.6; 4830 0.0; 5168 -0.5; 5530 -1.8; 5917 -4.5; 6331 -6.2; 6775 -7.0; 7249 -7.3; 7756 -7.4; 8299 -7.5; 8880 -6.1; 9502 -2.8; 10167 -0.1; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 -0.2; 17469 -2.8; 18692 -3.8; 20000 -1.8
Copy: L=-1.8dB*l, R=-1.8dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Innerfidelity%202017/innerfidelity/onear/AKG%20K702/AKG%20K702.png)