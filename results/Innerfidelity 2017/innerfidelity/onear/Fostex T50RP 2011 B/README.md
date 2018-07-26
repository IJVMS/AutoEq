# Fostex T50RP 2011 B
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 6.0; 32 6.0; 35 6.0; 37 6.0; 40 6.0; 42 6.0; 45 6.0; 49 6.0; 52 6.0; 56 6.0; 59 6.0; 64 6.0; 68 6.0; 73 6.0; 78 6.0; 83 6.0; 89 6.0; 95 5.3; 102 4.2; 109 3.5; 117 2.6; 125 1.7; 134 0.9; 143 0.4; 153 -0.1; 164 -0.1; 175 -0.6; 188 -1.0; 201 -1.2; 215 -1.4; 230 -1.4; 246 -1.6; 263 -1.6; 282 -1.6; 301 -1.7; 323 -1.6; 345 -1.1; 369 -0.9; 395 -1.2; 423 -1.4; 452 -1.6; 484 -1.9; 518 -1.6; 554 -1.1; 593 -0.7; 635 -0.2; 679 -0.6; 726 -0.8; 777 -0.3; 832 -0.5; 890 -0.9; 952 -0.4; 1019 0.2; 1090 0.2; 1167 -0.1; 1248 -0.4; 1336 -0.4; 1429 -0.5; 1529 -0.9; 1636 -0.5; 1751 -0.1; 1873 0.3; 2004 1.1; 2145 2.2; 2295 3.5; 2455 5.1; 2627 6.0; 2811 6.0; 3008 6.0; 3219 6.0; 3444 6.0; 3685 6.0; 3943 6.0; 4219 6.0; 4514 6.0; 4830 6.0; 5168 6.0; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 6.0; 32 6.0; 35 6.0; 37 6.0; 40 6.0; 42 6.0; 45 6.0; 49 6.0; 52 6.0; 56 6.0; 59 6.0; 64 6.0; 68 6.0; 73 6.0; 78 6.0; 83 6.0; 89 6.0; 95 5.3; 102 4.2; 109 3.5; 117 2.6; 125 1.7; 134 0.9; 143 0.4; 153 -0.1; 164 -0.1; 175 -0.6; 188 -1.0; 201 -1.2; 215 -1.4; 230 -1.4; 246 -1.6; 263 -1.6; 282 -1.6; 301 -1.7; 323 -1.6; 345 -1.1; 369 -0.9; 395 -1.2; 423 -1.4; 452 -1.6; 484 -1.9; 518 -1.6; 554 -1.1; 593 -0.7; 635 -0.2; 679 -0.6; 726 -0.8; 777 -0.3; 832 -0.5; 890 -0.9; 952 -0.4; 1019 0.2; 1090 0.2; 1167 -0.1; 1248 -0.4; 1336 -0.4; 1429 -0.5; 1529 -0.9; 1636 -0.5; 1751 -0.1; 1873 0.3; 2004 1.1; 2145 2.2; 2295 3.5; 2455 5.1; 2627 6.0; 2811 6.0; 3008 6.0; 3219 6.0; 3444 6.0; 3685 6.0; 3943 6.0; 4219 6.0; 4514 6.0; 4830 6.0; 5168 6.0; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Innerfidelity%202017/innerfidelity/onear/Fostex%20T50RP%202011%20B/Fostex%20T50RP%202011%20B.png)