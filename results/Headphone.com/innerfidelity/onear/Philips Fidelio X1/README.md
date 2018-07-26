# Philips Fidelio X1
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-41**.
```
GraphicEQ: 10 -84; 20 4.1; 22 3.0; 23 2.4; 25 1.5; 26 1.0; 28 0.2; 30 -0.6; 32 -1.4; 35 -2.5; 37 -3.1; 40 -4.0; 42 -4.5; 45 -5.2; 49 -6.0; 52 -6.5; 56 -7.0; 59 -7.2; 64 -7.4; 68 -7.4; 73 -7.4; 78 -7.4; 83 -7.3; 89 -7.4; 95 -7.6; 102 -7.6; 109 -7.5; 117 -7.6; 125 -7.6; 134 -7.6; 143 -7.6; 153 -7.4; 164 -7.1; 175 -7.1; 188 -7.8; 201 -7.5; 215 -6.9; 230 -6.5; 246 -6.1; 263 -5.8; 282 -5.5; 301 -5.3; 323 -5.0; 345 -4.7; 369 -4.4; 395 -4.1; 423 -3.8; 452 -3.5; 484 -3.3; 518 -2.9; 554 -2.5; 593 -2.3; 635 -2.1; 679 -1.7; 726 -1.6; 777 -1.5; 832 -1.3; 890 -0.5; 952 -0.2; 1019 0.1; 1090 0.2; 1167 0.8; 1248 1.2; 1336 0.8; 1429 0.3; 1529 -0.0; 1636 -0.2; 1751 -0.1; 1873 -0.1; 2004 -0.2; 2145 0.1; 2295 0.2; 2455 0.3; 2627 1.2; 2811 3.7; 3008 3.4; 3219 1.9; 3444 0.6; 3685 0.3; 3943 0.5; 4219 1.0; 4514 1.5; 4830 2.3; 5168 2.6; 5530 1.2; 5917 -0.2; 6331 -0.2; 6775 0.0; 7249 -1.4; 7756 -2.8; 8299 -4.4; 8880 -4.8; 9502 -2.6; 10167 -0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 4.1; 22 3.0; 23 2.4; 25 1.5; 26 1.0; 28 0.2; 30 -0.6; 32 -1.4; 35 -2.5; 37 -3.1; 40 -4.0; 42 -4.5; 45 -5.2; 49 -6.0; 52 -6.5; 56 -7.0; 59 -7.2; 64 -7.4; 68 -7.4; 73 -7.4; 78 -7.4; 83 -7.3; 89 -7.4; 95 -7.6; 102 -7.6; 109 -7.5; 117 -7.6; 125 -7.6; 134 -7.6; 143 -7.6; 153 -7.4; 164 -7.1; 175 -7.1; 188 -7.8; 201 -7.5; 215 -6.9; 230 -6.5; 246 -6.1; 263 -5.8; 282 -5.5; 301 -5.3; 323 -5.0; 345 -4.7; 369 -4.4; 395 -4.1; 423 -3.8; 452 -3.5; 484 -3.3; 518 -2.9; 554 -2.5; 593 -2.3; 635 -2.1; 679 -1.7; 726 -1.6; 777 -1.5; 832 -1.3; 890 -0.5; 952 -0.2; 1019 0.1; 1090 0.2; 1167 0.8; 1248 1.2; 1336 0.8; 1429 0.3; 1529 -0.0; 1636 -0.2; 1751 -0.1; 1873 -0.1; 2004 -0.2; 2145 0.1; 2295 0.2; 2455 0.3; 2627 1.2; 2811 3.7; 3008 3.4; 3219 1.9; 3444 0.6; 3685 0.3; 3943 0.5; 4219 1.0; 4514 1.5; 4830 2.3; 5168 2.6; 5530 1.2; 5917 -0.2; 6331 -0.2; 6775 0.0; 7249 -1.4; 7756 -2.8; 8299 -4.4; 8880 -4.8; 9502 -2.6; 10167 -0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
Copy: L=-4.1dB*l, R=-4.1dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Headphone.com/innerfidelity/onear/Philips%20Fidelio%20X1/Philips%20Fidelio%20X1.png)