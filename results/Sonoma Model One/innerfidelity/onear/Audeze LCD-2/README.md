# Audeze LCD-2
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 6.0; 32 6.0; 35 6.0; 37 6.0; 40 6.0; 42 6.0; 45 6.0; 49 6.0; 52 6.0; 56 6.0; 59 6.0; 64 6.0; 68 6.0; 73 6.0; 78 6.0; 83 6.0; 89 5.9; 95 5.2; 102 4.4; 109 3.9; 117 3.3; 125 2.6; 134 2.0; 143 1.6; 153 1.2; 164 1.0; 175 0.8; 188 0.6; 201 0.5; 215 0.5; 230 0.4; 246 0.2; 263 0.1; 282 0.2; 301 0.1; 323 0.0; 345 -0.0; 369 -0.1; 395 -0.2; 423 -0.1; 452 -0.1; 484 0.2; 518 0.5; 554 0.4; 593 0.4; 635 0.3; 679 0.5; 726 0.8; 777 0.7; 832 0.2; 890 -0.2; 952 -0.4; 1019 0.2; 1090 2.4; 1167 4.4; 1248 5.5; 1336 6.0; 1429 6.0; 1529 6.0; 1636 6.0; 1751 6.0; 1873 6.0; 2004 6.0; 2145 6.0; 2295 5.4; 2455 5.7; 2627 5.8; 2811 5.8; 3008 6.0; 3219 6.0; 3444 6.0; 3685 6.0; 3943 6.0; 4219 6.0; 4514 6.0; 4830 6.0; 5168 6.0; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 -0.7; 9502 -0.1; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 -1.5; 18692 -1.5; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 6.0; 32 6.0; 35 6.0; 37 6.0; 40 6.0; 42 6.0; 45 6.0; 49 6.0; 52 6.0; 56 6.0; 59 6.0; 64 6.0; 68 6.0; 73 6.0; 78 6.0; 83 6.0; 89 5.9; 95 5.2; 102 4.4; 109 3.9; 117 3.3; 125 2.6; 134 2.0; 143 1.6; 153 1.2; 164 1.0; 175 0.8; 188 0.6; 201 0.5; 215 0.5; 230 0.4; 246 0.2; 263 0.1; 282 0.2; 301 0.1; 323 0.0; 345 -0.0; 369 -0.1; 395 -0.2; 423 -0.1; 452 -0.1; 484 0.2; 518 0.5; 554 0.4; 593 0.4; 635 0.3; 679 0.5; 726 0.8; 777 0.7; 832 0.2; 890 -0.2; 952 -0.4; 1019 0.2; 1090 2.4; 1167 4.4; 1248 5.5; 1336 6.0; 1429 6.0; 1529 6.0; 1636 6.0; 1751 6.0; 1873 6.0; 2004 6.0; 2145 6.0; 2295 5.4; 2455 5.7; 2627 5.8; 2811 5.8; 3008 6.0; 3219 6.0; 3444 6.0; 3685 6.0; 3943 6.0; 4219 6.0; 4514 6.0; 4830 6.0; 5168 6.0; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 -0.7; 9502 -0.1; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 -1.5; 18692 -1.5; 20000 0.0
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Sonoma%20Model%20One/innerfidelity/onear/Audeze%20LCD-2/Audeze%20LCD-2.png)