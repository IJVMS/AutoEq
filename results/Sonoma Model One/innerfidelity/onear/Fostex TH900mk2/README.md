# Fostex TH900mk2
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-48**.
```
GraphicEQ: 10 -84; 20 -0.1; 22 -0.4; 23 -0.5; 25 -0.7; 26 -0.8; 28 -0.9; 30 -1.0; 32 -1.2; 35 -1.4; 37 -1.5; 40 -1.6; 42 -1.7; 45 -1.8; 49 -2.0; 52 -2.1; 56 -2.2; 59 -2.1; 64 -1.6; 68 -1.1; 73 -0.5; 78 -0.3; 83 -0.6; 89 -1.2; 95 -1.9; 102 -2.6; 109 -2.9; 117 -3.3; 125 -3.8; 134 -4.1; 143 -4.4; 153 -4.4; 164 -4.2; 175 -4.1; 188 -3.9; 201 -3.7; 215 -3.4; 230 -3.1; 246 -2.9; 263 -2.5; 282 -2.1; 301 -1.7; 323 -1.1; 345 -0.6; 369 -0.1; 395 0.4; 423 1.1; 452 1.7; 484 2.0; 518 1.9; 554 1.7; 593 1.7; 635 1.6; 679 1.4; 726 1.3; 777 2.1; 832 1.8; 890 0.8; 952 0.2; 1019 0.1; 1090 0.8; 1167 2.0; 1248 3.1; 1336 3.8; 1429 4.3; 1529 4.4; 1636 4.0; 1751 3.2; 1873 2.7; 2004 2.6; 2145 2.6; 2295 3.1; 2455 4.2; 2627 4.8; 2811 4.1; 3008 2.9; 3219 1.6; 3444 2.1; 3685 2.4; 3943 1.7; 4219 0.4; 4514 -0.3; 4830 -1.0; 5168 -2.8; 5530 -6.9; 5917 -9.0; 6331 -6.0; 6775 -2.9; 7249 -3.5; 7756 -4.8; 8299 -3.9; 8880 -0.7; 9502 0.0; 10167 -0.3; 10879 -3.1; 11640 -3.4; 12455 -1.0; 13327 0.0; 14260 -0.9; 15258 -3.2; 16326 -4.9; 17469 -6.2; 18692 -6.9; 20000 -6.2
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 -0.1; 22 -0.4; 23 -0.5; 25 -0.7; 26 -0.8; 28 -0.9; 30 -1.0; 32 -1.2; 35 -1.4; 37 -1.5; 40 -1.6; 42 -1.7; 45 -1.8; 49 -2.0; 52 -2.1; 56 -2.2; 59 -2.1; 64 -1.6; 68 -1.1; 73 -0.5; 78 -0.3; 83 -0.6; 89 -1.2; 95 -1.9; 102 -2.6; 109 -2.9; 117 -3.3; 125 -3.8; 134 -4.1; 143 -4.4; 153 -4.4; 164 -4.2; 175 -4.1; 188 -3.9; 201 -3.7; 215 -3.4; 230 -3.1; 246 -2.9; 263 -2.5; 282 -2.1; 301 -1.7; 323 -1.1; 345 -0.6; 369 -0.1; 395 0.4; 423 1.1; 452 1.7; 484 2.0; 518 1.9; 554 1.7; 593 1.7; 635 1.6; 679 1.4; 726 1.3; 777 2.1; 832 1.8; 890 0.8; 952 0.2; 1019 0.1; 1090 0.8; 1167 2.0; 1248 3.1; 1336 3.8; 1429 4.3; 1529 4.4; 1636 4.0; 1751 3.2; 1873 2.7; 2004 2.6; 2145 2.6; 2295 3.1; 2455 4.2; 2627 4.8; 2811 4.1; 3008 2.9; 3219 1.6; 3444 2.1; 3685 2.4; 3943 1.7; 4219 0.4; 4514 -0.3; 4830 -1.0; 5168 -2.8; 5530 -6.9; 5917 -9.0; 6331 -6.0; 6775 -2.9; 7249 -3.5; 7756 -4.8; 8299 -3.9; 8880 -0.7; 9502 0.0; 10167 -0.3; 10879 -3.1; 11640 -3.4; 12455 -1.0; 13327 0.0; 14260 -0.9; 15258 -3.2; 16326 -4.9; 17469 -6.2; 18692 -6.9; 20000 -6.2
Copy: L=-4.8dB*l, R=-4.8dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Sonoma%20Model%20One/innerfidelity/onear/Fostex%20TH900mk2/Fostex%20TH900mk2.png)