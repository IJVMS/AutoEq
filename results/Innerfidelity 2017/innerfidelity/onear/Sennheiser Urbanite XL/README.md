# Sennheiser Urbanite XL
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 0.1; 22 -0.5; 23 -0.9; 25 -1.4; 26 -1.6; 28 -2.0; 30 -2.4; 32 -2.7; 35 -3.1; 37 -3.4; 40 -3.7; 42 -3.9; 45 -4.2; 49 -4.4; 52 -4.6; 56 -4.8; 59 -4.9; 64 -5.2; 68 -5.3; 73 -5.4; 78 -5.7; 83 -5.9; 89 -6.3; 95 -6.6; 102 -6.8; 109 -6.9; 117 -6.9; 125 -7.1; 134 -7.3; 143 -8.0; 153 -8.5; 164 -7.7; 175 -7.2; 188 -7.6; 201 -7.4; 215 -7.1; 230 -6.5; 246 -6.3; 263 -6.2; 282 -6.6; 301 -6.9; 323 -7.1; 345 -7.0; 369 -6.6; 395 -5.9; 423 -5.2; 452 -5.1; 484 -5.1; 518 -4.6; 554 -3.6; 593 -2.7; 635 -2.2; 679 -2.2; 726 -1.9; 777 -1.4; 832 -1.0; 890 -0.7; 952 -0.3; 1019 0.1; 1090 -0.0; 1167 -0.3; 1248 -0.6; 1336 -0.8; 1429 -0.9; 1529 -1.1; 1636 -1.4; 1751 -1.8; 1873 -2.2; 2004 -2.2; 2145 -1.8; 2295 -0.7; 2455 0.3; 2627 0.8; 2811 1.8; 3008 3.0; 3219 3.2; 3444 3.9; 3685 5.3; 3943 6.0; 4219 6.0; 4514 6.0; 4830 3.3; 5168 1.0; 5530 3.2; 5917 4.8; 6331 4.8; 6775 3.3; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 0.1; 22 -0.5; 23 -0.9; 25 -1.4; 26 -1.6; 28 -2.0; 30 -2.4; 32 -2.7; 35 -3.1; 37 -3.4; 40 -3.7; 42 -3.9; 45 -4.2; 49 -4.4; 52 -4.6; 56 -4.8; 59 -4.9; 64 -5.2; 68 -5.3; 73 -5.4; 78 -5.7; 83 -5.9; 89 -6.3; 95 -6.6; 102 -6.8; 109 -6.9; 117 -6.9; 125 -7.1; 134 -7.3; 143 -8.0; 153 -8.5; 164 -7.7; 175 -7.2; 188 -7.6; 201 -7.4; 215 -7.1; 230 -6.5; 246 -6.3; 263 -6.2; 282 -6.6; 301 -6.9; 323 -7.1; 345 -7.0; 369 -6.6; 395 -5.9; 423 -5.2; 452 -5.1; 484 -5.1; 518 -4.6; 554 -3.6; 593 -2.7; 635 -2.2; 679 -2.2; 726 -1.9; 777 -1.4; 832 -1.0; 890 -0.7; 952 -0.3; 1019 0.1; 1090 -0.0; 1167 -0.3; 1248 -0.6; 1336 -0.8; 1429 -0.9; 1529 -1.1; 1636 -1.4; 1751 -1.8; 1873 -2.2; 2004 -2.2; 2145 -1.8; 2295 -0.7; 2455 0.3; 2627 0.8; 2811 1.8; 3008 3.0; 3219 3.2; 3444 3.9; 3685 5.3; 3943 6.0; 4219 6.0; 4514 6.0; 4830 3.3; 5168 1.0; 5530 3.2; 5917 4.8; 6331 4.8; 6775 3.3; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Innerfidelity%202017/innerfidelity/onear/Sennheiser%20Urbanite%20XL/Sennheiser%20Urbanite%20XL.png)