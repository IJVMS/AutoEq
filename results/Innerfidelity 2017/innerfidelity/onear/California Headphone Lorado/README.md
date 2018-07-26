# California Headphone Lorado
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 6.0; 32 5.9; 35 5.4; 37 4.9; 40 4.0; 42 3.5; 45 2.7; 49 1.8; 52 1.3; 56 0.7; 59 0.2; 64 -0.5; 68 -0.7; 73 -0.7; 78 -0.9; 83 -1.6; 89 -2.5; 95 -3.0; 102 -2.8; 109 -2.7; 117 -3.1; 125 -3.8; 134 -4.2; 143 -4.4; 153 -4.6; 164 -3.9; 175 -4.1; 188 -4.7; 201 -5.2; 215 -4.9; 230 -4.5; 246 -4.3; 263 -4.0; 282 -3.4; 301 -2.9; 323 -2.4; 345 -2.1; 369 -1.8; 395 -1.7; 423 -1.6; 452 -1.8; 484 -1.9; 518 -1.6; 554 -1.1; 593 -0.5; 635 -0.2; 679 -0.1; 726 0.0; 777 0.4; 832 0.4; 890 0.2; 952 0.2; 1019 -0.1; 1090 -0.3; 1167 -0.6; 1248 -1.0; 1336 -1.8; 1429 -1.6; 1529 -1.7; 1636 -2.6; 1751 -2.8; 1873 -2.8; 2004 -2.2; 2145 -0.9; 2295 0.3; 2455 1.7; 2627 3.3; 2811 4.8; 3008 6.0; 3219 6.0; 3444 6.0; 3685 6.0; 3943 6.0; 4219 6.0; 4514 6.0; 4830 6.0; 5168 6.0; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 -0.6; 10167 -2.1; 10879 -1.8; 11640 -0.2; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 6.0; 32 5.9; 35 5.4; 37 4.9; 40 4.0; 42 3.5; 45 2.7; 49 1.8; 52 1.3; 56 0.7; 59 0.2; 64 -0.5; 68 -0.7; 73 -0.7; 78 -0.9; 83 -1.6; 89 -2.5; 95 -3.0; 102 -2.8; 109 -2.7; 117 -3.1; 125 -3.8; 134 -4.2; 143 -4.4; 153 -4.6; 164 -3.9; 175 -4.1; 188 -4.7; 201 -5.2; 215 -4.9; 230 -4.5; 246 -4.3; 263 -4.0; 282 -3.4; 301 -2.9; 323 -2.4; 345 -2.1; 369 -1.8; 395 -1.7; 423 -1.6; 452 -1.8; 484 -1.9; 518 -1.6; 554 -1.1; 593 -0.5; 635 -0.2; 679 -0.1; 726 0.0; 777 0.4; 832 0.4; 890 0.2; 952 0.2; 1019 -0.1; 1090 -0.3; 1167 -0.6; 1248 -1.0; 1336 -1.8; 1429 -1.6; 1529 -1.7; 1636 -2.6; 1751 -2.8; 1873 -2.8; 2004 -2.2; 2145 -0.9; 2295 0.3; 2455 1.7; 2627 3.3; 2811 4.8; 3008 6.0; 3219 6.0; 3444 6.0; 3685 6.0; 3943 6.0; 4219 6.0; 4514 6.0; 4830 6.0; 5168 6.0; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 -0.6; 10167 -2.1; 10879 -1.8; 11640 -0.2; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Innerfidelity%202017/innerfidelity/onear/California%20Headphone%20Lorado/California%20Headphone%20Lorado.png)