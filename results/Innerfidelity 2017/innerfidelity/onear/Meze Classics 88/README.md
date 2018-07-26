# Meze Classics 88
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 3.9; 22 3.6; 23 3.5; 25 3.3; 26 3.3; 28 3.1; 30 3.0; 32 2.9; 35 2.8; 37 2.8; 40 2.7; 42 2.6; 45 2.6; 49 2.6; 52 2.6; 56 2.6; 59 2.6; 64 2.6; 68 2.6; 73 2.6; 78 2.5; 83 2.2; 89 1.6; 95 1.2; 102 1.1; 109 0.8; 117 0.3; 125 -0.4; 134 -0.8; 143 -1.0; 153 -1.1; 164 -1.0; 175 -1.1; 188 -1.3; 201 -1.3; 215 -1.3; 230 -1.1; 246 -0.9; 263 -0.6; 282 -0.3; 301 -0.4; 323 -0.4; 345 -0.3; 369 -0.0; 395 0.2; 423 0.9; 452 1.7; 484 2.5; 518 3.8; 554 4.9; 593 5.1; 635 4.3; 679 3.1; 726 2.3; 777 1.7; 832 1.0; 890 0.4; 952 -0.1; 1019 0.3; 1090 -0.2; 1167 -1.4; 1248 -1.9; 1336 -2.0; 1429 -1.6; 1529 -0.8; 1636 0.2; 1751 1.6; 1873 3.0; 2004 4.3; 2145 5.6; 2295 6.0; 2455 6.0; 2627 6.0; 2811 6.0; 3008 6.0; 3219 6.0; 3444 6.0; 3685 6.0; 3943 6.0; 4219 6.0; 4514 6.0; 4830 6.0; 5168 6.0; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 3.9; 22 3.6; 23 3.5; 25 3.3; 26 3.3; 28 3.1; 30 3.0; 32 2.9; 35 2.8; 37 2.8; 40 2.7; 42 2.6; 45 2.6; 49 2.6; 52 2.6; 56 2.6; 59 2.6; 64 2.6; 68 2.6; 73 2.6; 78 2.5; 83 2.2; 89 1.6; 95 1.2; 102 1.1; 109 0.8; 117 0.3; 125 -0.4; 134 -0.8; 143 -1.0; 153 -1.1; 164 -1.0; 175 -1.1; 188 -1.3; 201 -1.3; 215 -1.3; 230 -1.1; 246 -0.9; 263 -0.6; 282 -0.3; 301 -0.4; 323 -0.4; 345 -0.3; 369 -0.0; 395 0.2; 423 0.9; 452 1.7; 484 2.5; 518 3.8; 554 4.9; 593 5.1; 635 4.3; 679 3.1; 726 2.3; 777 1.7; 832 1.0; 890 0.4; 952 -0.1; 1019 0.3; 1090 -0.2; 1167 -1.4; 1248 -1.9; 1336 -2.0; 1429 -1.6; 1529 -0.8; 1636 0.2; 1751 1.6; 1873 3.0; 2004 4.3; 2145 5.6; 2295 6.0; 2455 6.0; 2627 6.0; 2811 6.0; 3008 6.0; 3219 6.0; 3444 6.0; 3685 6.0; 3943 6.0; 4219 6.0; 4514 6.0; 4830 6.0; 5168 6.0; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Innerfidelity%202017/innerfidelity/onear/Meze%20Classics%2088/Meze%20Classics%2088.png)