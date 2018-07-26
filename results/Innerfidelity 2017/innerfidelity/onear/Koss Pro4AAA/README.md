# Koss Pro4AAA
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 0.8; 22 0.1; 23 -0.2; 25 -0.7; 26 -0.9; 28 -1.3; 30 -1.7; 32 -2.0; 35 -2.4; 37 -2.7; 40 -3.0; 42 -3.2; 45 -3.4; 49 -3.7; 52 -3.9; 56 -4.2; 59 -4.3; 64 -4.5; 68 -4.6; 73 -4.7; 78 -5.0; 83 -5.5; 89 -6.4; 95 -7.1; 102 -7.3; 109 -7.4; 117 -8.3; 125 -9.3; 134 -9.9; 143 -10.2; 153 -10.4; 164 -10.3; 175 -10.7; 188 -11.0; 201 -11.0; 215 -10.9; 230 -10.6; 246 -10.3; 263 -9.9; 282 -9.3; 301 -9.2; 323 -9.4; 345 -9.4; 369 -8.9; 395 -8.3; 423 -7.6; 452 -7.1; 484 -6.7; 518 -6.0; 554 -5.0; 593 -3.8; 635 -3.0; 679 -2.6; 726 -2.2; 777 -1.7; 832 -1.2; 890 -0.6; 952 -0.2; 1019 0.1; 1090 0.2; 1167 0.5; 1248 0.6; 1336 0.5; 1429 0.4; 1529 0.2; 1636 -0.1; 1751 -0.9; 1873 -1.5; 2004 -2.3; 2145 -3.2; 2295 -4.3; 2455 -4.8; 2627 -4.9; 2811 -5.2; 3008 -4.8; 3219 -3.0; 3444 -0.9; 3685 1.0; 3943 3.5; 4219 3.8; 4514 3.4; 4830 5.9; 5168 6.0; 5530 4.6; 5917 1.5; 6331 -0.6; 6775 2.3; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 0.8; 22 0.1; 23 -0.2; 25 -0.7; 26 -0.9; 28 -1.3; 30 -1.7; 32 -2.0; 35 -2.4; 37 -2.7; 40 -3.0; 42 -3.2; 45 -3.4; 49 -3.7; 52 -3.9; 56 -4.2; 59 -4.3; 64 -4.5; 68 -4.6; 73 -4.7; 78 -5.0; 83 -5.5; 89 -6.4; 95 -7.1; 102 -7.3; 109 -7.4; 117 -8.3; 125 -9.3; 134 -9.9; 143 -10.2; 153 -10.4; 164 -10.3; 175 -10.7; 188 -11.0; 201 -11.0; 215 -10.9; 230 -10.6; 246 -10.3; 263 -9.9; 282 -9.3; 301 -9.2; 323 -9.4; 345 -9.4; 369 -8.9; 395 -8.3; 423 -7.6; 452 -7.1; 484 -6.7; 518 -6.0; 554 -5.0; 593 -3.8; 635 -3.0; 679 -2.6; 726 -2.2; 777 -1.7; 832 -1.2; 890 -0.6; 952 -0.2; 1019 0.1; 1090 0.2; 1167 0.5; 1248 0.6; 1336 0.5; 1429 0.4; 1529 0.2; 1636 -0.1; 1751 -0.9; 1873 -1.5; 2004 -2.3; 2145 -3.2; 2295 -4.3; 2455 -4.8; 2627 -4.9; 2811 -5.2; 3008 -4.8; 3219 -3.0; 3444 -0.9; 3685 1.0; 3943 3.5; 4219 3.8; 4514 3.4; 4830 5.9; 5168 6.0; 5530 4.6; 5917 1.5; 6331 -0.6; 6775 2.3; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Innerfidelity%202017/innerfidelity/onear/Koss%20Pro4AAA/Koss%20Pro4AAA.png)