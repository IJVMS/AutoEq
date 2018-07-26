# Yamaha HPH MT220
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 2.8; 22 2.2; 23 2.0; 25 1.5; 26 1.4; 28 1.1; 30 0.8; 32 0.7; 35 0.5; 37 0.5; 40 0.4; 42 0.4; 45 0.4; 49 0.5; 52 0.6; 56 0.8; 59 0.9; 64 0.9; 68 0.9; 73 1.0; 78 1.1; 83 1.2; 89 1.1; 95 1.1; 102 1.2; 109 1.4; 117 1.7; 125 2.0; 134 2.1; 143 1.5; 153 0.7; 164 1.7; 175 2.6; 188 1.8; 201 1.7; 215 1.9; 230 2.3; 246 2.7; 263 3.1; 282 3.7; 301 4.0; 323 3.8; 345 3.7; 369 3.9; 395 3.9; 423 3.8; 452 3.4; 484 2.8; 518 2.3; 554 2.0; 593 1.7; 635 1.3; 679 0.8; 726 0.4; 777 0.3; 832 0.1; 890 -0.0; 952 -0.0; 1019 0.0; 1090 0.2; 1167 0.6; 1248 1.0; 1336 0.9; 1429 0.8; 1529 1.2; 1636 1.8; 1751 2.9; 1873 4.1; 2004 5.4; 2145 6.0; 2295 6.0; 2455 6.0; 2627 6.0; 2811 6.0; 3008 6.0; 3219 6.0; 3444 6.0; 3685 6.0; 3943 5.7; 4219 3.5; 4514 4.1; 4830 5.9; 5168 6.0; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 2.8; 22 2.2; 23 2.0; 25 1.5; 26 1.4; 28 1.1; 30 0.8; 32 0.7; 35 0.5; 37 0.5; 40 0.4; 42 0.4; 45 0.4; 49 0.5; 52 0.6; 56 0.8; 59 0.9; 64 0.9; 68 0.9; 73 1.0; 78 1.1; 83 1.2; 89 1.1; 95 1.1; 102 1.2; 109 1.4; 117 1.7; 125 2.0; 134 2.1; 143 1.5; 153 0.7; 164 1.7; 175 2.6; 188 1.8; 201 1.7; 215 1.9; 230 2.3; 246 2.7; 263 3.1; 282 3.7; 301 4.0; 323 3.8; 345 3.7; 369 3.9; 395 3.9; 423 3.8; 452 3.4; 484 2.8; 518 2.3; 554 2.0; 593 1.7; 635 1.3; 679 0.8; 726 0.4; 777 0.3; 832 0.1; 890 -0.0; 952 -0.0; 1019 0.0; 1090 0.2; 1167 0.6; 1248 1.0; 1336 0.9; 1429 0.8; 1529 1.2; 1636 1.8; 1751 2.9; 1873 4.1; 2004 5.4; 2145 6.0; 2295 6.0; 2455 6.0; 2627 6.0; 2811 6.0; 3008 6.0; 3219 6.0; 3444 6.0; 3685 6.0; 3943 5.7; 4219 3.5; 4514 4.1; 4830 5.9; 5168 6.0; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/SBAF-Serious/innerfidelity/onear/Yamaha%20HPH%20MT220/Yamaha%20HPH%20MT220.png)