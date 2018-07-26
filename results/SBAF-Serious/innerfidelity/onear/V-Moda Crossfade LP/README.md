# V-Moda Crossfade LP
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 4.1; 22 3.2; 23 2.7; 25 2.0; 26 1.7; 28 1.1; 30 0.5; 32 -0.1; 35 -0.8; 37 -1.2; 40 -1.7; 42 -2.0; 45 -2.3; 49 -2.6; 52 -2.7; 56 -2.8; 59 -2.8; 64 -2.7; 68 -2.8; 73 -3.1; 78 -3.3; 83 -3.2; 89 -3.2; 95 -3.6; 102 -4.1; 109 -4.4; 117 -4.8; 125 -5.1; 134 -5.4; 143 -5.6; 153 -5.7; 164 -5.5; 175 -5.5; 188 -5.4; 201 -5.1; 215 -4.6; 230 -3.8; 246 -2.9; 263 -2.6; 282 -1.4; 301 -0.2; 323 1.0; 345 2.1; 369 2.6; 395 3.1; 423 3.8; 452 4.2; 484 4.2; 518 4.0; 554 3.7; 593 3.2; 635 2.4; 679 1.4; 726 0.8; 777 0.6; 832 0.3; 890 0.1; 952 -0.0; 1019 0.0; 1090 -0.2; 1167 -0.4; 1248 -0.8; 1336 -1.5; 1429 -1.8; 1529 -2.1; 1636 -2.4; 1751 -2.3; 1873 -2.4; 2004 -2.6; 2145 -3.2; 2295 -3.5; 2455 -2.8; 2627 -2.3; 2811 -2.1; 3008 -1.4; 3219 -1.6; 3444 -1.2; 3685 0.1; 3943 2.0; 4219 3.0; 4514 4.5; 4830 6.0; 5168 6.0; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 -0.2; 10167 -0.7; 10879 -0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 4.1; 22 3.2; 23 2.7; 25 2.0; 26 1.7; 28 1.1; 30 0.5; 32 -0.1; 35 -0.8; 37 -1.2; 40 -1.7; 42 -2.0; 45 -2.3; 49 -2.6; 52 -2.7; 56 -2.8; 59 -2.8; 64 -2.7; 68 -2.8; 73 -3.1; 78 -3.3; 83 -3.2; 89 -3.2; 95 -3.6; 102 -4.1; 109 -4.4; 117 -4.8; 125 -5.1; 134 -5.4; 143 -5.6; 153 -5.7; 164 -5.5; 175 -5.5; 188 -5.4; 201 -5.1; 215 -4.6; 230 -3.8; 246 -2.9; 263 -2.6; 282 -1.4; 301 -0.2; 323 1.0; 345 2.1; 369 2.6; 395 3.1; 423 3.8; 452 4.2; 484 4.2; 518 4.0; 554 3.7; 593 3.2; 635 2.4; 679 1.4; 726 0.8; 777 0.6; 832 0.3; 890 0.1; 952 -0.0; 1019 0.0; 1090 -0.2; 1167 -0.4; 1248 -0.8; 1336 -1.5; 1429 -1.8; 1529 -2.1; 1636 -2.4; 1751 -2.3; 1873 -2.4; 2004 -2.6; 2145 -3.2; 2295 -3.5; 2455 -2.8; 2627 -2.3; 2811 -2.1; 3008 -1.4; 3219 -1.6; 3444 -1.2; 3685 0.1; 3943 2.0; 4219 3.0; 4514 4.5; 4830 6.0; 5168 6.0; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 -0.2; 10167 -0.7; 10879 -0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/SBAF-Serious/innerfidelity/onear/V-Moda%20Crossfade%20LP/V-Moda%20Crossfade%20LP.png)