# Bang Olufsen H6 2nd Gen
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 4.7; 22 3.8; 23 3.4; 25 2.6; 26 2.3; 28 1.7; 30 1.2; 32 0.8; 35 0.2; 37 -0.1; 40 -0.4; 42 -0.6; 45 -0.8; 49 -1.0; 52 -1.1; 56 -1.1; 59 -1.1; 64 -1.0; 68 -0.8; 73 -0.6; 78 -0.4; 83 -0.3; 89 -0.1; 95 0.3; 102 0.9; 109 1.1; 117 0.8; 125 -0.2; 134 -0.9; 143 -0.5; 153 1.1; 164 3.5; 175 4.0; 188 3.6; 201 4.1; 215 4.8; 230 5.6; 246 5.3; 263 4.6; 282 3.8; 301 3.1; 323 2.4; 345 1.9; 369 1.5; 395 1.1; 423 0.8; 452 0.3; 484 -0.2; 518 -0.4; 554 -0.1; 593 0.3; 635 0.3; 679 0.1; 726 -0.0; 777 0.0; 832 -0.1; 890 -0.0; 952 0.0; 1019 -0.0; 1090 -0.0; 1167 0.0; 1248 0.1; 1336 0.0; 1429 0.1; 1529 0.1; 1636 0.0; 1751 -0.2; 1873 -0.1; 2004 0.2; 2145 0.7; 2295 1.6; 2455 2.9; 2627 4.4; 2811 5.6; 3008 6.0; 3219 6.0; 3444 6.0; 3685 6.0; 3943 6.0; 4219 6.0; 4514 6.0; 4830 6.0; 5168 6.0; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 -0.6; 8880 -1.7; 9502 -1.8; 10167 -0.3; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 4.7; 22 3.8; 23 3.4; 25 2.6; 26 2.3; 28 1.7; 30 1.2; 32 0.8; 35 0.2; 37 -0.1; 40 -0.4; 42 -0.6; 45 -0.8; 49 -1.0; 52 -1.1; 56 -1.1; 59 -1.1; 64 -1.0; 68 -0.8; 73 -0.6; 78 -0.4; 83 -0.3; 89 -0.1; 95 0.3; 102 0.9; 109 1.1; 117 0.8; 125 -0.2; 134 -0.9; 143 -0.5; 153 1.1; 164 3.5; 175 4.0; 188 3.6; 201 4.1; 215 4.8; 230 5.6; 246 5.3; 263 4.6; 282 3.8; 301 3.1; 323 2.4; 345 1.9; 369 1.5; 395 1.1; 423 0.8; 452 0.3; 484 -0.2; 518 -0.4; 554 -0.1; 593 0.3; 635 0.3; 679 0.1; 726 -0.0; 777 0.0; 832 -0.1; 890 -0.0; 952 0.0; 1019 -0.0; 1090 -0.0; 1167 0.0; 1248 0.1; 1336 0.0; 1429 0.1; 1529 0.1; 1636 0.0; 1751 -0.2; 1873 -0.1; 2004 0.2; 2145 0.7; 2295 1.6; 2455 2.9; 2627 4.4; 2811 5.6; 3008 6.0; 3219 6.0; 3444 6.0; 3685 6.0; 3943 6.0; 4219 6.0; 4514 6.0; 4830 6.0; 5168 6.0; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 -0.6; 8880 -1.7; 9502 -1.8; 10167 -0.3; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Innerfidelity%202017/innerfidelity/onear/Bang%20Olufsen%20H6%202nd%20Gen/Bang%20Olufsen%20H6%202nd%20Gen.png)