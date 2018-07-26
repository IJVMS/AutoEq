# Sony MDR-7520
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-66**.
```
GraphicEQ: 10 -84; 20 6.6; 22 5.4; 23 4.9; 25 3.9; 26 3.5; 28 2.6; 30 1.8; 32 1.1; 35 0.0; 37 -0.6; 40 -1.4; 42 -1.9; 45 -2.6; 49 -3.4; 52 -4.0; 56 -4.6; 59 -5.0; 64 -5.5; 68 -5.9; 73 -6.2; 78 -6.6; 83 -7.0; 89 -7.5; 95 -8.0; 102 -8.4; 109 -8.6; 117 -8.8; 125 -8.8; 134 -8.5; 143 -7.8; 153 -7.4; 164 -7.6; 175 -6.2; 188 -4.8; 201 -4.1; 215 -3.4; 230 -2.9; 246 -1.9; 263 -1.0; 282 -1.1; 301 -1.4; 323 -0.6; 345 -0.7; 369 -1.0; 395 -1.2; 423 -1.3; 452 -1.3; 484 -1.2; 518 -1.0; 554 -0.8; 593 -0.4; 635 -0.0; 679 0.3; 726 0.2; 777 0.2; 832 0.2; 890 0.2; 952 0.1; 1019 -0.0; 1090 -0.2; 1167 -0.2; 1248 -0.3; 1336 -0.3; 1429 -0.4; 1529 -0.9; 1636 -1.6; 1751 -2.6; 1873 -3.6; 2004 -4.9; 2145 -5.5; 2295 -5.2; 2455 -4.4; 2627 -3.7; 2811 -2.6; 3008 -1.4; 3219 -0.3; 3444 1.2; 3685 4.0; 3943 6.0; 4219 6.0; 4514 6.0; 4830 6.0; 5168 6.0; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 -0.4; 8299 -5.3; 8880 -8.6; 9502 -8.2; 10167 -4.2; 10879 -0.2; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 6.6; 22 5.4; 23 4.9; 25 3.9; 26 3.5; 28 2.6; 30 1.8; 32 1.1; 35 0.0; 37 -0.6; 40 -1.4; 42 -1.9; 45 -2.6; 49 -3.4; 52 -4.0; 56 -4.6; 59 -5.0; 64 -5.5; 68 -5.9; 73 -6.2; 78 -6.6; 83 -7.0; 89 -7.5; 95 -8.0; 102 -8.4; 109 -8.6; 117 -8.8; 125 -8.8; 134 -8.5; 143 -7.8; 153 -7.4; 164 -7.6; 175 -6.2; 188 -4.8; 201 -4.1; 215 -3.4; 230 -2.9; 246 -1.9; 263 -1.0; 282 -1.1; 301 -1.4; 323 -0.6; 345 -0.7; 369 -1.0; 395 -1.2; 423 -1.3; 452 -1.3; 484 -1.2; 518 -1.0; 554 -0.8; 593 -0.4; 635 -0.0; 679 0.3; 726 0.2; 777 0.2; 832 0.2; 890 0.2; 952 0.1; 1019 -0.0; 1090 -0.2; 1167 -0.2; 1248 -0.3; 1336 -0.3; 1429 -0.4; 1529 -0.9; 1636 -1.6; 1751 -2.6; 1873 -3.6; 2004 -4.9; 2145 -5.5; 2295 -5.2; 2455 -4.4; 2627 -3.7; 2811 -2.6; 3008 -1.4; 3219 -0.3; 3444 1.2; 3685 4.0; 3943 6.0; 4219 6.0; 4514 6.0; 4830 6.0; 5168 6.0; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 -0.4; 8299 -5.3; 8880 -8.6; 9502 -8.2; 10167 -4.2; 10879 -0.2; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
Copy: L=-6.6dB*l, R=-6.6dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Headphone.com/innerfidelity/onear/Sony%20MDR-7520/Sony%20MDR-7520.png)