# Noontec Zoro II Wireless Active
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 -0.3; 22 -0.9; 23 -1.1; 25 -1.6; 26 -1.8; 28 -2.1; 30 -2.4; 32 -2.6; 35 -2.9; 37 -3.0; 40 -3.2; 42 -3.4; 45 -3.5; 49 -3.5; 52 -3.6; 56 -3.8; 59 -3.8; 64 -3.7; 68 -3.8; 73 -3.9; 78 -4.2; 83 -4.5; 89 -5.0; 95 -5.3; 102 -5.7; 109 -6.1; 117 -6.6; 125 -7.0; 134 -7.4; 143 -7.8; 153 -7.9; 164 -7.8; 175 -7.8; 188 -8.0; 201 -8.0; 215 -7.8; 230 -7.6; 246 -7.5; 263 -7.2; 282 -6.7; 301 -6.4; 323 -6.3; 345 -6.0; 369 -5.8; 395 -5.8; 423 -5.7; 452 -5.6; 484 -5.5; 518 -4.9; 554 -4.2; 593 -3.2; 635 -2.5; 679 -2.1; 726 -1.5; 777 -0.9; 832 -0.5; 890 -0.3; 952 -0.1; 1019 -0.0; 1090 -0.1; 1167 -0.2; 1248 -0.7; 1336 -1.0; 1429 -1.2; 1529 -1.3; 1636 -1.4; 1751 -1.6; 1873 -1.4; 2004 -1.0; 2145 -0.3; 2295 0.2; 2455 0.9; 2627 1.5; 2811 2.1; 3008 2.5; 3219 2.4; 3444 2.7; 3685 4.2; 3943 6.0; 4219 6.0; 4514 6.0; 4830 5.8; 5168 3.7; 5530 2.7; 5917 2.3; 6331 0.1; 6775 -0.7; 7249 0.1; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 -0.3; 22 -0.9; 23 -1.1; 25 -1.6; 26 -1.8; 28 -2.1; 30 -2.4; 32 -2.6; 35 -2.9; 37 -3.0; 40 -3.2; 42 -3.4; 45 -3.5; 49 -3.5; 52 -3.6; 56 -3.8; 59 -3.8; 64 -3.7; 68 -3.8; 73 -3.9; 78 -4.2; 83 -4.5; 89 -5.0; 95 -5.3; 102 -5.7; 109 -6.1; 117 -6.6; 125 -7.0; 134 -7.4; 143 -7.8; 153 -7.9; 164 -7.8; 175 -7.8; 188 -8.0; 201 -8.0; 215 -7.8; 230 -7.6; 246 -7.5; 263 -7.2; 282 -6.7; 301 -6.4; 323 -6.3; 345 -6.0; 369 -5.8; 395 -5.8; 423 -5.7; 452 -5.6; 484 -5.5; 518 -4.9; 554 -4.2; 593 -3.2; 635 -2.5; 679 -2.1; 726 -1.5; 777 -0.9; 832 -0.5; 890 -0.3; 952 -0.1; 1019 -0.0; 1090 -0.1; 1167 -0.2; 1248 -0.7; 1336 -1.0; 1429 -1.2; 1529 -1.3; 1636 -1.4; 1751 -1.6; 1873 -1.4; 2004 -1.0; 2145 -0.3; 2295 0.2; 2455 0.9; 2627 1.5; 2811 2.1; 3008 2.5; 3219 2.4; 3444 2.7; 3685 4.2; 3943 6.0; 4219 6.0; 4514 6.0; 4830 5.8; 5168 3.7; 5530 2.7; 5917 2.3; 6331 0.1; 6775 -0.7; 7249 0.1; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Innerfidelity%202017/innerfidelity/onear/Noontec%20Zoro%20II%20Wireless%20Active/Noontec%20Zoro%20II%20Wireless%20Active.png)