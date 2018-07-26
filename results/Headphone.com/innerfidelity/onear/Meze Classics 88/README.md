# Meze Classics 88
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 4.2; 22 4.0; 23 3.9; 25 3.7; 26 3.6; 28 3.5; 30 3.3; 32 3.2; 35 3.1; 37 3.0; 40 2.9; 42 2.9; 45 2.9; 49 2.9; 52 2.9; 56 2.9; 59 2.9; 64 2.9; 68 2.9; 73 2.8; 78 2.7; 83 2.3; 89 1.7; 95 1.2; 102 0.9; 109 0.5; 117 -0.1; 125 -0.7; 134 -1.1; 143 -1.3; 153 -1.4; 164 -1.3; 175 -1.4; 188 -1.5; 201 -1.5; 215 -1.4; 230 -1.3; 246 -0.9; 263 -0.5; 282 -0.2; 301 -0.2; 323 -0.2; 345 -0.1; 369 0.3; 395 0.7; 423 1.5; 452 2.6; 484 3.8; 518 5.2; 554 6.0; 593 5.8; 635 5.0; 679 4.0; 726 3.1; 777 2.2; 832 1.3; 890 0.7; 952 -0.1; 1019 0.3; 1090 -0.0; 1167 -1.0; 1248 -1.0; 1336 -0.6; 1429 0.3; 1529 1.5; 1636 2.8; 1751 4.3; 1873 5.8; 2004 6.0; 2145 6.0; 2295 6.0; 2455 6.0; 2627 6.0; 2811 6.0; 3008 6.0; 3219 6.0; 3444 6.0; 3685 6.0; 3943 6.0; 4219 6.0; 4514 6.0; 4830 6.0; 5168 6.0; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 4.2; 22 4.0; 23 3.9; 25 3.7; 26 3.6; 28 3.5; 30 3.3; 32 3.2; 35 3.1; 37 3.0; 40 2.9; 42 2.9; 45 2.9; 49 2.9; 52 2.9; 56 2.9; 59 2.9; 64 2.9; 68 2.9; 73 2.8; 78 2.7; 83 2.3; 89 1.7; 95 1.2; 102 0.9; 109 0.5; 117 -0.1; 125 -0.7; 134 -1.1; 143 -1.3; 153 -1.4; 164 -1.3; 175 -1.4; 188 -1.5; 201 -1.5; 215 -1.4; 230 -1.3; 246 -0.9; 263 -0.5; 282 -0.2; 301 -0.2; 323 -0.2; 345 -0.1; 369 0.3; 395 0.7; 423 1.5; 452 2.6; 484 3.8; 518 5.2; 554 6.0; 593 5.8; 635 5.0; 679 4.0; 726 3.1; 777 2.2; 832 1.3; 890 0.7; 952 -0.1; 1019 0.3; 1090 -0.0; 1167 -1.0; 1248 -1.0; 1336 -0.6; 1429 0.3; 1529 1.5; 1636 2.8; 1751 4.3; 1873 5.8; 2004 6.0; 2145 6.0; 2295 6.0; 2455 6.0; 2627 6.0; 2811 6.0; 3008 6.0; 3219 6.0; 3444 6.0; 3685 6.0; 3943 6.0; 4219 6.0; 4514 6.0; 4830 6.0; 5168 6.0; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Headphone.com/innerfidelity/onear/Meze%20Classics%2088/Meze%20Classics%2088.png)