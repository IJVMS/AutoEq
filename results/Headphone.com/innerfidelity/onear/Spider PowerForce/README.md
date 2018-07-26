# Spider PowerForce
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 -1.3; 22 -2.1; 23 -2.5; 25 -3.1; 26 -3.4; 28 -4.0; 30 -4.5; 32 -4.9; 35 -5.5; 37 -5.9; 40 -6.3; 42 -6.6; 45 -7.0; 49 -7.3; 52 -7.5; 56 -7.8; 59 -8.0; 64 -8.1; 68 -8.2; 73 -8.3; 78 -8.5; 83 -8.6; 89 -8.8; 95 -9.0; 102 -9.3; 109 -9.6; 117 -9.9; 125 -10.2; 134 -10.3; 143 -10.4; 153 -10.3; 164 -9.9; 175 -9.4; 188 -8.9; 201 -8.2; 215 -7.3; 230 -6.6; 246 -4.9; 263 -3.5; 282 -3.2; 301 -3.7; 323 -3.9; 345 -4.2; 369 -4.1; 395 -4.2; 423 -4.3; 452 -4.1; 484 -3.8; 518 -3.4; 554 -3.0; 593 -2.4; 635 -1.9; 679 -0.8; 726 0.1; 777 -0.3; 832 -0.2; 890 -0.2; 952 -0.1; 1019 0.1; 1090 0.3; 1167 0.7; 1248 1.1; 1336 1.5; 1429 2.1; 1529 2.5; 1636 2.4; 1751 2.3; 1873 2.1; 2004 2.1; 2145 2.0; 2295 2.1; 2455 2.4; 2627 2.9; 2811 3.5; 3008 3.7; 3219 4.0; 3444 5.1; 3685 6.0; 3943 6.0; 4219 6.0; 4514 6.0; 4830 3.3; 5168 5.1; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 -1.3; 22 -2.1; 23 -2.5; 25 -3.1; 26 -3.4; 28 -4.0; 30 -4.5; 32 -4.9; 35 -5.5; 37 -5.9; 40 -6.3; 42 -6.6; 45 -7.0; 49 -7.3; 52 -7.5; 56 -7.8; 59 -8.0; 64 -8.1; 68 -8.2; 73 -8.3; 78 -8.5; 83 -8.6; 89 -8.8; 95 -9.0; 102 -9.3; 109 -9.6; 117 -9.9; 125 -10.2; 134 -10.3; 143 -10.4; 153 -10.3; 164 -9.9; 175 -9.4; 188 -8.9; 201 -8.2; 215 -7.3; 230 -6.6; 246 -4.9; 263 -3.5; 282 -3.2; 301 -3.7; 323 -3.9; 345 -4.2; 369 -4.1; 395 -4.2; 423 -4.3; 452 -4.1; 484 -3.8; 518 -3.4; 554 -3.0; 593 -2.4; 635 -1.9; 679 -0.8; 726 0.1; 777 -0.3; 832 -0.2; 890 -0.2; 952 -0.1; 1019 0.1; 1090 0.3; 1167 0.7; 1248 1.1; 1336 1.5; 1429 2.1; 1529 2.5; 1636 2.4; 1751 2.3; 1873 2.1; 2004 2.1; 2145 2.0; 2295 2.1; 2455 2.4; 2627 2.9; 2811 3.5; 3008 3.7; 3219 4.0; 3444 5.1; 3685 6.0; 3943 6.0; 4219 6.0; 4514 6.0; 4830 3.3; 5168 5.1; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Headphone.com/innerfidelity/onear/Spider%20PowerForce/Spider%20PowerForce.png)