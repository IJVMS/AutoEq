# Sony MDR-Z7
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 2.5; 22 1.1; 23 0.4; 25 -0.7; 26 -1.2; 28 -2.0; 30 -2.6; 32 -3.1; 35 -3.6; 37 -3.9; 40 -4.1; 42 -4.1; 45 -4.1; 49 -4.0; 52 -3.9; 56 -3.8; 59 -3.7; 64 -3.5; 68 -3.3; 73 -3.2; 78 -3.0; 83 -2.8; 89 -2.9; 95 -3.3; 102 -4.2; 109 -4.8; 117 -5.1; 125 -4.9; 134 -5.4; 143 -6.2; 153 -7.1; 164 -6.8; 175 -6.1; 188 -6.3; 201 -6.0; 215 -5.7; 230 -5.4; 246 -4.9; 263 -4.5; 282 -4.0; 301 -3.5; 323 -3.0; 345 -2.6; 369 -2.2; 395 -1.7; 423 -1.1; 452 -0.7; 484 -0.5; 518 -0.2; 554 -0.1; 593 0.1; 635 0.1; 679 0.0; 726 -0.4; 777 -0.9; 832 -1.2; 890 -1.2; 952 -0.6; 1019 0.2; 1090 1.6; 1167 3.8; 1248 4.9; 1336 5.8; 1429 6.0; 1529 5.6; 1636 4.5; 1751 2.8; 1873 1.4; 2004 0.2; 2145 -0.6; 2295 -1.4; 2455 -1.7; 2627 -0.9; 2811 0.1; 3008 0.8; 3219 2.4; 3444 4.2; 3685 5.1; 3943 4.6; 4219 4.5; 4514 4.5; 4830 5.7; 5168 6.0; 5530 6.0; 5917 5.8; 6331 3.6; 6775 1.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 2.5; 22 1.1; 23 0.4; 25 -0.7; 26 -1.2; 28 -2.0; 30 -2.6; 32 -3.1; 35 -3.6; 37 -3.9; 40 -4.1; 42 -4.1; 45 -4.1; 49 -4.0; 52 -3.9; 56 -3.8; 59 -3.7; 64 -3.5; 68 -3.3; 73 -3.2; 78 -3.0; 83 -2.8; 89 -2.9; 95 -3.3; 102 -4.2; 109 -4.8; 117 -5.1; 125 -4.9; 134 -5.4; 143 -6.2; 153 -7.1; 164 -6.8; 175 -6.1; 188 -6.3; 201 -6.0; 215 -5.7; 230 -5.4; 246 -4.9; 263 -4.5; 282 -4.0; 301 -3.5; 323 -3.0; 345 -2.6; 369 -2.2; 395 -1.7; 423 -1.1; 452 -0.7; 484 -0.5; 518 -0.2; 554 -0.1; 593 0.1; 635 0.1; 679 0.0; 726 -0.4; 777 -0.9; 832 -1.2; 890 -1.2; 952 -0.6; 1019 0.2; 1090 1.6; 1167 3.8; 1248 4.9; 1336 5.8; 1429 6.0; 1529 5.6; 1636 4.5; 1751 2.8; 1873 1.4; 2004 0.2; 2145 -0.6; 2295 -1.4; 2455 -1.7; 2627 -0.9; 2811 0.1; 3008 0.8; 3219 2.4; 3444 4.2; 3685 5.1; 3943 4.6; 4219 4.5; 4514 4.5; 4830 5.7; 5168 6.0; 5530 6.0; 5917 5.8; 6331 3.6; 6775 1.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Headphone.com/innerfidelity/onear/Sony%20MDR-Z7/Sony%20MDR-Z7.png)