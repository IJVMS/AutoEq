# thinksound On1
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 -0.6; 22 -1.2; 23 -1.5; 25 -2.0; 26 -2.2; 28 -2.5; 30 -2.9; 32 -3.1; 35 -3.5; 37 -3.7; 40 -3.9; 42 -4.0; 45 -4.1; 49 -4.1; 52 -4.1; 56 -4.0; 59 -3.9; 64 -4.0; 68 -4.3; 73 -4.5; 78 -4.5; 83 -4.6; 89 -4.5; 95 -4.4; 102 -4.0; 109 -3.8; 117 -3.6; 125 -3.5; 134 -3.1; 143 -2.9; 153 -2.7; 164 -1.7; 175 -1.0; 188 -1.0; 201 -0.3; 215 0.5; 230 1.4; 246 1.9; 263 2.0; 282 2.0; 301 1.7; 323 1.0; 345 0.7; 369 0.4; 395 0.2; 423 -0.0; 452 -0.5; 484 -0.9; 518 -1.0; 554 -0.7; 593 -0.3; 635 -0.3; 679 -0.4; 726 -0.3; 777 -0.2; 832 -0.2; 890 -0.1; 952 -0.0; 1019 -0.0; 1090 0.0; 1167 0.0; 1248 0.1; 1336 0.2; 1429 0.4; 1529 0.6; 1636 0.7; 1751 0.8; 1873 1.7; 2004 3.0; 2145 3.6; 2295 3.6; 2455 4.3; 2627 5.7; 2811 6.0; 3008 5.9; 3219 4.9; 3444 4.3; 3685 5.2; 3943 6.0; 4219 6.0; 4514 6.0; 4830 6.0; 5168 6.0; 5530 5.7; 5917 3.3; 6331 2.5; 6775 0.6; 7249 -0.6; 7756 -1.1; 8299 -1.7; 8880 -1.2; 9502 -0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 -0.3; 13327 -0.1; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 -0.6; 22 -1.2; 23 -1.5; 25 -2.0; 26 -2.2; 28 -2.5; 30 -2.9; 32 -3.1; 35 -3.5; 37 -3.7; 40 -3.9; 42 -4.0; 45 -4.1; 49 -4.1; 52 -4.1; 56 -4.0; 59 -3.9; 64 -4.0; 68 -4.3; 73 -4.5; 78 -4.5; 83 -4.6; 89 -4.5; 95 -4.4; 102 -4.0; 109 -3.8; 117 -3.6; 125 -3.5; 134 -3.1; 143 -2.9; 153 -2.7; 164 -1.7; 175 -1.0; 188 -1.0; 201 -0.3; 215 0.5; 230 1.4; 246 1.9; 263 2.0; 282 2.0; 301 1.7; 323 1.0; 345 0.7; 369 0.4; 395 0.2; 423 -0.0; 452 -0.5; 484 -0.9; 518 -1.0; 554 -0.7; 593 -0.3; 635 -0.3; 679 -0.4; 726 -0.3; 777 -0.2; 832 -0.2; 890 -0.1; 952 -0.0; 1019 -0.0; 1090 0.0; 1167 0.0; 1248 0.1; 1336 0.2; 1429 0.4; 1529 0.6; 1636 0.7; 1751 0.8; 1873 1.7; 2004 3.0; 2145 3.6; 2295 3.6; 2455 4.3; 2627 5.7; 2811 6.0; 3008 5.9; 3219 4.9; 3444 4.3; 3685 5.2; 3943 6.0; 4219 6.0; 4514 6.0; 4830 6.0; 5168 6.0; 5530 5.7; 5917 3.3; 6331 2.5; 6775 0.6; 7249 -0.6; 7756 -1.1; 8299 -1.7; 8880 -1.2; 9502 -0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 -0.3; 13327 -0.1; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Innerfidelity%202017/innerfidelity/onear/thinksound%20On1/thinksound%20On1.png)