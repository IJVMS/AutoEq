# NVX XPT100
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 6.0; 22 5.5; 23 5.3; 25 4.9; 26 4.7; 28 4.4; 30 4.1; 32 3.8; 35 3.5; 37 3.4; 40 3.1; 42 3.0; 45 2.9; 49 2.8; 52 2.7; 56 2.5; 59 2.4; 64 2.3; 68 2.2; 73 2.0; 78 1.8; 83 1.6; 89 1.3; 95 0.9; 102 0.5; 109 0.3; 117 -0.2; 125 -0.9; 134 -1.7; 143 -2.2; 153 -2.6; 164 -2.1; 175 -1.9; 188 -2.5; 201 -2.4; 215 -2.0; 230 -1.3; 246 -0.1; 263 1.6; 282 3.4; 301 4.2; 323 3.7; 345 2.9; 369 2.1; 395 1.6; 423 1.3; 452 0.9; 484 0.6; 518 0.5; 554 0.5; 593 0.5; 635 0.5; 679 0.6; 726 0.6; 777 0.8; 832 1.0; 890 0.6; 952 0.2; 1019 -0.1; 1090 -0.3; 1167 -0.4; 1248 -0.3; 1336 -0.2; 1429 0.0; 1529 0.1; 1636 0.2; 1751 0.2; 1873 -0.1; 2004 0.1; 2145 0.3; 2295 0.8; 2455 1.3; 2627 1.8; 2811 2.2; 3008 4.2; 3219 5.7; 3444 3.4; 3685 2.6; 3943 3.2; 4219 5.0; 4514 6.0; 4830 6.0; 5168 6.0; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 6.0; 22 5.5; 23 5.3; 25 4.9; 26 4.7; 28 4.4; 30 4.1; 32 3.8; 35 3.5; 37 3.4; 40 3.1; 42 3.0; 45 2.9; 49 2.8; 52 2.7; 56 2.5; 59 2.4; 64 2.3; 68 2.2; 73 2.0; 78 1.8; 83 1.6; 89 1.3; 95 0.9; 102 0.5; 109 0.3; 117 -0.2; 125 -0.9; 134 -1.7; 143 -2.2; 153 -2.6; 164 -2.1; 175 -1.9; 188 -2.5; 201 -2.4; 215 -2.0; 230 -1.3; 246 -0.1; 263 1.6; 282 3.4; 301 4.2; 323 3.7; 345 2.9; 369 2.1; 395 1.6; 423 1.3; 452 0.9; 484 0.6; 518 0.5; 554 0.5; 593 0.5; 635 0.5; 679 0.6; 726 0.6; 777 0.8; 832 1.0; 890 0.6; 952 0.2; 1019 -0.1; 1090 -0.3; 1167 -0.4; 1248 -0.3; 1336 -0.2; 1429 0.0; 1529 0.1; 1636 0.2; 1751 0.2; 1873 -0.1; 2004 0.1; 2145 0.3; 2295 0.8; 2455 1.3; 2627 1.8; 2811 2.2; 3008 4.2; 3219 5.7; 3444 3.4; 3685 2.6; 3943 3.2; 4219 5.0; 4514 6.0; 4830 6.0; 5168 6.0; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Headphone.com/innerfidelity/onear/NVX%20XPT100/NVX%20XPT100.png)