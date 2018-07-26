# thinksound On1
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 2.7; 22 2.2; 23 1.9; 25 1.5; 26 1.3; 28 0.9; 30 0.6; 32 0.4; 35 -0.0; 37 -0.3; 40 -0.6; 42 -0.8; 45 -1.0; 49 -1.3; 52 -1.5; 56 -1.5; 59 -1.3; 64 -1.2; 68 -1.1; 73 -0.8; 78 -0.6; 83 -0.7; 89 -1.1; 95 -1.5; 102 -1.6; 109 -1.7; 117 -1.6; 125 -1.8; 134 -1.6; 143 -1.7; 153 -1.6; 164 -0.8; 175 -0.2; 188 -0.1; 201 0.6; 215 1.4; 230 2.2; 246 2.8; 263 2.9; 282 3.0; 301 2.7; 323 2.1; 345 1.8; 369 1.6; 395 1.3; 423 1.2; 452 1.1; 484 1.0; 518 0.8; 554 0.6; 593 0.7; 635 0.9; 679 1.2; 726 1.4; 777 1.4; 832 1.1; 890 0.6; 952 0.2; 1019 0.0; 1090 0.6; 1167 1.4; 1248 2.2; 1336 2.7; 1429 3.1; 1529 3.2; 1636 2.9; 1751 2.3; 1873 2.9; 2004 4.0; 2145 4.7; 2295 4.6; 2455 5.3; 2627 6.0; 2811 6.0; 3008 6.0; 3219 5.5; 3444 4.5; 3685 4.4; 3943 4.5; 4219 4.0; 4514 4.6; 4830 5.6; 5168 6.0; 5530 3.3; 5917 0.1; 6331 0.2; 6775 -0.3; 7249 -1.0; 7756 -1.4; 8299 -2.4; 8880 -2.7; 9502 -1.1; 10167 0.0; 10879 0.0; 11640 -0.2; 12455 -2.5; 13327 -3.7; 14260 -2.6; 15258 -0.7; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 2.7; 22 2.2; 23 1.9; 25 1.5; 26 1.3; 28 0.9; 30 0.6; 32 0.4; 35 -0.0; 37 -0.3; 40 -0.6; 42 -0.8; 45 -1.0; 49 -1.3; 52 -1.5; 56 -1.5; 59 -1.3; 64 -1.2; 68 -1.1; 73 -0.8; 78 -0.6; 83 -0.7; 89 -1.1; 95 -1.5; 102 -1.6; 109 -1.7; 117 -1.6; 125 -1.8; 134 -1.6; 143 -1.7; 153 -1.6; 164 -0.8; 175 -0.2; 188 -0.1; 201 0.6; 215 1.4; 230 2.2; 246 2.8; 263 2.9; 282 3.0; 301 2.7; 323 2.1; 345 1.8; 369 1.6; 395 1.3; 423 1.2; 452 1.1; 484 1.0; 518 0.8; 554 0.6; 593 0.7; 635 0.9; 679 1.2; 726 1.4; 777 1.4; 832 1.1; 890 0.6; 952 0.2; 1019 0.0; 1090 0.6; 1167 1.4; 1248 2.2; 1336 2.7; 1429 3.1; 1529 3.2; 1636 2.9; 1751 2.3; 1873 2.9; 2004 4.0; 2145 4.7; 2295 4.6; 2455 5.3; 2627 6.0; 2811 6.0; 3008 6.0; 3219 5.5; 3444 4.5; 3685 4.4; 3943 4.5; 4219 4.0; 4514 4.6; 4830 5.6; 5168 6.0; 5530 3.3; 5917 0.1; 6331 0.2; 6775 -0.3; 7249 -1.0; 7756 -1.4; 8299 -2.4; 8880 -2.7; 9502 -1.1; 10167 0.0; 10879 0.0; 11640 -0.2; 12455 -2.5; 13327 -3.7; 14260 -2.6; 15258 -0.7; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Sonoma%20Model%20One/innerfidelity/onear/thinksound%20On1/thinksound%20On1.png)