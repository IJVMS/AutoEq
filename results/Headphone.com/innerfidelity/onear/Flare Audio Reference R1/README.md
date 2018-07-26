# Flare Audio Reference R1
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 6.0; 32 6.0; 35 6.0; 37 6.0; 40 6.0; 42 6.0; 45 6.0; 49 5.9; 52 5.3; 56 4.2; 59 3.3; 64 2.1; 68 1.2; 73 0.1; 78 -0.8; 83 -1.5; 89 -2.3; 95 -3.0; 102 -4.1; 109 -4.8; 117 -5.5; 125 -6.0; 134 -6.4; 143 -6.6; 153 -6.8; 164 -6.9; 175 -6.9; 188 -6.9; 201 -7.0; 215 -7.0; 230 -7.1; 246 -7.1; 263 -7.1; 282 -7.1; 301 -7.2; 323 -7.1; 345 -7.0; 369 -7.0; 395 -7.0; 423 -6.9; 452 -7.1; 484 -7.3; 518 -7.5; 554 -7.7; 593 -7.8; 635 -7.7; 679 -7.5; 726 -6.9; 777 -6.2; 832 -5.1; 890 -3.4; 952 -1.6; 1019 0.7; 1090 3.1; 1167 5.6; 1248 6.0; 1336 6.0; 1429 6.0; 1529 6.0; 1636 5.5; 1751 1.5; 1873 -1.4; 2004 -1.7; 2145 1.2; 2295 3.9; 2455 5.8; 2627 6.0; 2811 6.0; 3008 6.0; 3219 6.0; 3444 6.0; 3685 6.0; 3943 6.0; 4219 6.0; 4514 6.0; 4830 6.0; 5168 6.0; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 6.0; 32 6.0; 35 6.0; 37 6.0; 40 6.0; 42 6.0; 45 6.0; 49 5.9; 52 5.3; 56 4.2; 59 3.3; 64 2.1; 68 1.2; 73 0.1; 78 -0.8; 83 -1.5; 89 -2.3; 95 -3.0; 102 -4.1; 109 -4.8; 117 -5.5; 125 -6.0; 134 -6.4; 143 -6.6; 153 -6.8; 164 -6.9; 175 -6.9; 188 -6.9; 201 -7.0; 215 -7.0; 230 -7.1; 246 -7.1; 263 -7.1; 282 -7.1; 301 -7.2; 323 -7.1; 345 -7.0; 369 -7.0; 395 -7.0; 423 -6.9; 452 -7.1; 484 -7.3; 518 -7.5; 554 -7.7; 593 -7.8; 635 -7.7; 679 -7.5; 726 -6.9; 777 -6.2; 832 -5.1; 890 -3.4; 952 -1.6; 1019 0.7; 1090 3.1; 1167 5.6; 1248 6.0; 1336 6.0; 1429 6.0; 1529 6.0; 1636 5.5; 1751 1.5; 1873 -1.4; 2004 -1.7; 2145 1.2; 2295 3.9; 2455 5.8; 2627 6.0; 2811 6.0; 3008 6.0; 3219 6.0; 3444 6.0; 3685 6.0; 3943 6.0; 4219 6.0; 4514 6.0; 4830 6.0; 5168 6.0; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Headphone.com/innerfidelity/onear/Flare%20Audio%20Reference%20R1/Flare%20Audio%20Reference%20R1.png)