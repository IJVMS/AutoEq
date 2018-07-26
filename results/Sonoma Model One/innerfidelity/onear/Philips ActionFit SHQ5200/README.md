# Philips ActionFit SHQ5200
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 6.0; 32 5.9; 35 5.3; 37 4.8; 40 4.0; 42 3.5; 45 2.8; 49 1.9; 52 1.4; 56 0.8; 59 0.5; 64 0.4; 68 0.5; 73 0.7; 78 0.7; 83 0.4; 89 -0.3; 95 -1.2; 102 -1.9; 109 -2.3; 117 -2.9; 125 -3.5; 134 -4.0; 143 -4.4; 153 -4.6; 164 -4.7; 175 -4.5; 188 -4.5; 201 -4.4; 215 -4.3; 230 -4.1; 246 -3.9; 263 -3.6; 282 -3.3; 301 -3.1; 323 -2.5; 345 -1.7; 369 -0.8; 395 -0.9; 423 -2.7; 452 -2.8; 484 -2.2; 518 -1.9; 554 -1.6; 593 -1.1; 635 -0.5; 679 -0.0; 726 0.5; 777 0.8; 832 0.8; 890 0.5; 952 0.2; 1019 0.1; 1090 0.6; 1167 1.5; 1248 2.3; 1336 2.9; 1429 3.5; 1529 3.9; 1636 3.7; 1751 3.5; 1873 3.8; 2004 3.9; 2145 3.8; 2295 4.9; 2455 3.7; 2627 4.2; 2811 4.2; 3008 5.6; 3219 6.0; 3444 6.0; 3685 6.0; 3943 5.4; 4219 3.1; 4514 2.8; 4830 3.5; 5168 5.1; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 6.0; 32 5.9; 35 5.3; 37 4.8; 40 4.0; 42 3.5; 45 2.8; 49 1.9; 52 1.4; 56 0.8; 59 0.5; 64 0.4; 68 0.5; 73 0.7; 78 0.7; 83 0.4; 89 -0.3; 95 -1.2; 102 -1.9; 109 -2.3; 117 -2.9; 125 -3.5; 134 -4.0; 143 -4.4; 153 -4.6; 164 -4.7; 175 -4.5; 188 -4.5; 201 -4.4; 215 -4.3; 230 -4.1; 246 -3.9; 263 -3.6; 282 -3.3; 301 -3.1; 323 -2.5; 345 -1.7; 369 -0.8; 395 -0.9; 423 -2.7; 452 -2.8; 484 -2.2; 518 -1.9; 554 -1.6; 593 -1.1; 635 -0.5; 679 -0.0; 726 0.5; 777 0.8; 832 0.8; 890 0.5; 952 0.2; 1019 0.1; 1090 0.6; 1167 1.5; 1248 2.3; 1336 2.9; 1429 3.5; 1529 3.9; 1636 3.7; 1751 3.5; 1873 3.8; 2004 3.9; 2145 3.8; 2295 4.9; 2455 3.7; 2627 4.2; 2811 4.2; 3008 5.6; 3219 6.0; 3444 6.0; 3685 6.0; 3943 5.4; 4219 3.1; 4514 2.8; 4830 3.5; 5168 5.1; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Sonoma%20Model%20One/innerfidelity/onear/Philips%20ActionFit%20SHQ5200/Philips%20ActionFit%20SHQ5200.png)