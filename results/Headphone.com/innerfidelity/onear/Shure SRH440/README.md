# Shure SRH440
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 6.0; 32 6.0; 35 5.8; 37 5.4; 40 4.6; 42 4.1; 45 3.3; 49 2.4; 52 1.9; 56 1.2; 59 0.8; 64 0.0; 68 -0.4; 73 -0.7; 78 -0.8; 83 -0.6; 89 -0.3; 95 0.1; 102 -0.7; 109 -2.4; 117 -3.6; 125 -4.1; 134 -4.0; 143 -3.8; 153 -3.5; 164 -2.4; 175 -2.5; 188 -3.1; 201 -2.9; 215 -2.5; 230 -2.4; 246 -2.3; 263 -2.3; 282 -2.3; 301 -2.2; 323 -2.2; 345 -2.6; 369 -3.4; 395 -3.3; 423 -2.8; 452 -2.4; 484 -2.1; 518 -1.7; 554 -1.4; 593 -1.1; 635 -0.8; 679 -0.6; 726 -0.5; 777 -0.4; 832 -0.4; 890 -0.3; 952 -0.2; 1019 0.2; 1090 0.9; 1167 0.9; 1248 1.0; 1336 1.3; 1429 1.5; 1529 1.5; 1636 1.6; 1751 1.5; 1873 1.7; 2004 1.8; 2145 2.5; 2295 3.0; 2455 3.4; 2627 3.4; 2811 3.2; 3008 3.0; 3219 1.7; 3444 1.3; 3685 1.1; 3943 2.6; 4219 4.3; 4514 5.7; 4830 6.0; 5168 6.0; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.1; 8299 -2.1; 8880 -3.4; 9502 -3.5; 10167 -1.8; 10879 -0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 6.0; 32 6.0; 35 5.8; 37 5.4; 40 4.6; 42 4.1; 45 3.3; 49 2.4; 52 1.9; 56 1.2; 59 0.8; 64 0.0; 68 -0.4; 73 -0.7; 78 -0.8; 83 -0.6; 89 -0.3; 95 0.1; 102 -0.7; 109 -2.4; 117 -3.6; 125 -4.1; 134 -4.0; 143 -3.8; 153 -3.5; 164 -2.4; 175 -2.5; 188 -3.1; 201 -2.9; 215 -2.5; 230 -2.4; 246 -2.3; 263 -2.3; 282 -2.3; 301 -2.2; 323 -2.2; 345 -2.6; 369 -3.4; 395 -3.3; 423 -2.8; 452 -2.4; 484 -2.1; 518 -1.7; 554 -1.4; 593 -1.1; 635 -0.8; 679 -0.6; 726 -0.5; 777 -0.4; 832 -0.4; 890 -0.3; 952 -0.2; 1019 0.2; 1090 0.9; 1167 0.9; 1248 1.0; 1336 1.3; 1429 1.5; 1529 1.5; 1636 1.6; 1751 1.5; 1873 1.7; 2004 1.8; 2145 2.5; 2295 3.0; 2455 3.4; 2627 3.4; 2811 3.2; 3008 3.0; 3219 1.7; 3444 1.3; 3685 1.1; 3943 2.6; 4219 4.3; 4514 5.7; 4830 6.0; 5168 6.0; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.1; 8299 -2.1; 8880 -3.4; 9502 -3.5; 10167 -1.8; 10879 -0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Headphone.com/innerfidelity/onear/Shure%20SRH440/Shure%20SRH440.png)