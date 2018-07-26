# MyST IzoPhones 60
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 6.0; 32 6.0; 35 6.0; 37 6.0; 40 6.0; 42 6.0; 45 6.0; 49 6.0; 52 5.6; 56 4.5; 59 3.7; 64 2.6; 68 1.9; 73 1.1; 78 0.5; 83 0.2; 89 -0.1; 95 -0.4; 102 -0.6; 109 -0.6; 117 -0.8; 125 -0.9; 134 -0.9; 143 -0.9; 153 -0.9; 164 -0.8; 175 -0.6; 188 -0.4; 201 -0.3; 215 -0.1; 230 0.2; 246 0.4; 263 0.6; 282 1.0; 301 1.3; 323 1.5; 345 1.0; 369 1.1; 395 1.0; 423 1.4; 452 1.2; 484 0.9; 518 1.0; 554 1.3; 593 1.8; 635 1.7; 679 1.3; 726 1.3; 777 1.4; 832 1.0; 890 0.6; 952 -0.1; 1019 0.2; 1090 0.5; 1167 -0.1; 1248 -0.1; 1336 -0.1; 1429 -0.6; 1529 -0.5; 1636 -0.8; 1751 0.8; 1873 1.6; 2004 2.6; 2145 2.8; 2295 3.1; 2455 4.0; 2627 4.3; 2811 3.4; 3008 2.3; 3219 1.8; 3444 1.1; 3685 0.2; 3943 -1.4; 4219 -3.4; 4514 -3.2; 4830 0.3; 5168 3.1; 5530 3.8; 5917 5.3; 6331 1.0; 6775 -3.0; 7249 -4.0; 7756 -4.6; 8299 -6.2; 8880 -7.5; 9502 -5.9; 10167 -1.2; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 -0.2; 17469 -0.8; 18692 -0.7; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 6.0; 32 6.0; 35 6.0; 37 6.0; 40 6.0; 42 6.0; 45 6.0; 49 6.0; 52 5.6; 56 4.5; 59 3.7; 64 2.6; 68 1.9; 73 1.1; 78 0.5; 83 0.2; 89 -0.1; 95 -0.4; 102 -0.6; 109 -0.6; 117 -0.8; 125 -0.9; 134 -0.9; 143 -0.9; 153 -0.9; 164 -0.8; 175 -0.6; 188 -0.4; 201 -0.3; 215 -0.1; 230 0.2; 246 0.4; 263 0.6; 282 1.0; 301 1.3; 323 1.5; 345 1.0; 369 1.1; 395 1.0; 423 1.4; 452 1.2; 484 0.9; 518 1.0; 554 1.3; 593 1.8; 635 1.7; 679 1.3; 726 1.3; 777 1.4; 832 1.0; 890 0.6; 952 -0.1; 1019 0.2; 1090 0.5; 1167 -0.1; 1248 -0.1; 1336 -0.1; 1429 -0.6; 1529 -0.5; 1636 -0.8; 1751 0.8; 1873 1.6; 2004 2.6; 2145 2.8; 2295 3.1; 2455 4.0; 2627 4.3; 2811 3.4; 3008 2.3; 3219 1.8; 3444 1.1; 3685 0.2; 3943 -1.4; 4219 -3.4; 4514 -3.2; 4830 0.3; 5168 3.1; 5530 3.8; 5917 5.3; 6331 1.0; 6775 -3.0; 7249 -4.0; 7756 -4.6; 8299 -6.2; 8880 -7.5; 9502 -5.9; 10167 -1.2; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 -0.2; 17469 -0.8; 18692 -0.7; 20000 0.0
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/SBAF-Serious/innerfidelity/onear/MyST%20IzoPhones%2060/MyST%20IzoPhones%2060.png)