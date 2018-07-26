# Koss Pro4AAA
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 1.1; 22 0.5; 23 0.2; 25 -0.3; 26 -0.6; 28 -1.0; 30 -1.4; 32 -1.7; 35 -2.1; 37 -2.4; 40 -2.8; 42 -2.9; 45 -3.2; 49 -3.4; 52 -3.6; 56 -3.9; 59 -4.1; 64 -4.2; 68 -4.4; 73 -4.5; 78 -4.8; 83 -5.3; 89 -6.4; 95 -7.1; 102 -7.5; 109 -7.7; 117 -8.7; 125 -9.7; 134 -10.2; 143 -10.5; 153 -10.7; 164 -10.6; 175 -11.0; 188 -11.2; 201 -11.2; 215 -11.1; 230 -10.8; 246 -10.4; 263 -9.8; 282 -9.2; 301 -9.0; 323 -9.2; 345 -9.2; 369 -8.6; 395 -7.8; 423 -7.0; 452 -6.2; 484 -5.4; 518 -4.5; 554 -3.8; 593 -3.0; 635 -2.2; 679 -1.7; 726 -1.3; 777 -1.2; 832 -0.9; 890 -0.4; 952 -0.1; 1019 0.1; 1090 0.4; 1167 0.9; 1248 1.4; 1336 1.9; 1429 2.3; 1529 2.5; 1636 2.4; 1751 1.9; 1873 1.3; 2004 0.7; 2145 -0.1; 2295 -1.2; 2455 -1.8; 2627 -1.9; 2811 -2.5; 3008 -2.8; 3219 -1.3; 3444 0.5; 3685 1.8; 3943 3.4; 4219 3.8; 4514 4.1; 4830 6.0; 5168 6.0; 5530 6.0; 5917 4.8; 6331 1.9; 6775 3.4; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 1.1; 22 0.5; 23 0.2; 25 -0.3; 26 -0.6; 28 -1.0; 30 -1.4; 32 -1.7; 35 -2.1; 37 -2.4; 40 -2.8; 42 -2.9; 45 -3.2; 49 -3.4; 52 -3.6; 56 -3.9; 59 -4.1; 64 -4.2; 68 -4.4; 73 -4.5; 78 -4.8; 83 -5.3; 89 -6.4; 95 -7.1; 102 -7.5; 109 -7.7; 117 -8.7; 125 -9.7; 134 -10.2; 143 -10.5; 153 -10.7; 164 -10.6; 175 -11.0; 188 -11.2; 201 -11.2; 215 -11.1; 230 -10.8; 246 -10.4; 263 -9.8; 282 -9.2; 301 -9.0; 323 -9.2; 345 -9.2; 369 -8.6; 395 -7.8; 423 -7.0; 452 -6.2; 484 -5.4; 518 -4.5; 554 -3.8; 593 -3.0; 635 -2.2; 679 -1.7; 726 -1.3; 777 -1.2; 832 -0.9; 890 -0.4; 952 -0.1; 1019 0.1; 1090 0.4; 1167 0.9; 1248 1.4; 1336 1.9; 1429 2.3; 1529 2.5; 1636 2.4; 1751 1.9; 1873 1.3; 2004 0.7; 2145 -0.1; 2295 -1.2; 2455 -1.8; 2627 -1.9; 2811 -2.5; 3008 -2.8; 3219 -1.3; 3444 0.5; 3685 1.8; 3943 3.4; 4219 3.8; 4514 4.1; 4830 6.0; 5168 6.0; 5530 6.0; 5917 4.8; 6331 1.9; 6775 3.4; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Headphone.com/innerfidelity/onear/Koss%20Pro4AAA/Koss%20Pro4AAA.png)