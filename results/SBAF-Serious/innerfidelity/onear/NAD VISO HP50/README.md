# NAD VISO HP50
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-51**.
```
GraphicEQ: 10 -84; 20 -3.1; 22 -3.2; 23 -3.2; 25 -3.2; 26 -3.3; 28 -3.3; 30 -3.3; 32 -3.3; 35 -3.2; 37 -3.2; 40 -3.1; 42 -3.0; 45 -2.9; 49 -2.7; 52 -2.6; 56 -2.3; 59 -2.2; 64 -2.0; 68 -1.9; 73 -1.7; 78 -1.5; 83 -1.4; 89 -1.4; 95 -1.4; 102 -2.0; 109 -2.4; 117 -2.4; 125 -2.4; 134 -3.0; 143 -4.2; 153 -4.8; 164 -3.2; 175 -3.3; 188 -4.7; 201 -4.5; 215 -4.3; 230 -3.7; 246 -3.3; 263 -2.8; 282 -2.1; 301 -1.4; 323 -1.1; 345 -0.9; 369 -0.7; 395 -0.4; 423 -0.1; 452 0.0; 484 -0.1; 518 -0.1; 554 0.1; 593 0.3; 635 0.2; 679 0.1; 726 -0.1; 777 -0.1; 832 -0.1; 890 -0.1; 952 -0.0; 1019 -0.1; 1090 -0.3; 1167 -0.7; 1248 -1.5; 1336 -2.1; 1429 -2.4; 1529 -2.7; 1636 -2.8; 1751 -2.4; 1873 -1.9; 2004 -1.4; 2145 -0.7; 2295 0.1; 2455 1.0; 2627 1.8; 2811 2.2; 3008 2.3; 3219 2.2; 3444 1.9; 3685 1.2; 3943 0.7; 4219 0.2; 4514 -0.2; 4830 -1.3; 5168 1.4; 5530 4.0; 5917 5.0; 6331 5.1; 6775 3.8; 7249 1.3; 7756 -0.5; 8299 -1.4; 8880 -1.5; 9502 -0.8; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 -3.1; 22 -3.2; 23 -3.2; 25 -3.2; 26 -3.3; 28 -3.3; 30 -3.3; 32 -3.3; 35 -3.2; 37 -3.2; 40 -3.1; 42 -3.0; 45 -2.9; 49 -2.7; 52 -2.6; 56 -2.3; 59 -2.2; 64 -2.0; 68 -1.9; 73 -1.7; 78 -1.5; 83 -1.4; 89 -1.4; 95 -1.4; 102 -2.0; 109 -2.4; 117 -2.4; 125 -2.4; 134 -3.0; 143 -4.2; 153 -4.8; 164 -3.2; 175 -3.3; 188 -4.7; 201 -4.5; 215 -4.3; 230 -3.7; 246 -3.3; 263 -2.8; 282 -2.1; 301 -1.4; 323 -1.1; 345 -0.9; 369 -0.7; 395 -0.4; 423 -0.1; 452 0.0; 484 -0.1; 518 -0.1; 554 0.1; 593 0.3; 635 0.2; 679 0.1; 726 -0.1; 777 -0.1; 832 -0.1; 890 -0.1; 952 -0.0; 1019 -0.1; 1090 -0.3; 1167 -0.7; 1248 -1.5; 1336 -2.1; 1429 -2.4; 1529 -2.7; 1636 -2.8; 1751 -2.4; 1873 -1.9; 2004 -1.4; 2145 -0.7; 2295 0.1; 2455 1.0; 2627 1.8; 2811 2.2; 3008 2.3; 3219 2.2; 3444 1.9; 3685 1.2; 3943 0.7; 4219 0.2; 4514 -0.2; 4830 -1.3; 5168 1.4; 5530 4.0; 5917 5.0; 6331 5.1; 6775 3.8; 7249 1.3; 7756 -0.5; 8299 -1.4; 8880 -1.5; 9502 -0.8; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
Copy: L=-5.1dB*l, R=-5.1dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/SBAF-Serious/innerfidelity/onear/NAD%20VISO%20HP50/NAD%20VISO%20HP50.png)