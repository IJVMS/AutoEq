# Shure SRH1540
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-5**.
```
GraphicEQ: 10 -84; 20 -3.8; 22 -4.5; 23 -4.8; 25 -5.3; 26 -5.5; 28 -6.0; 30 -6.3; 32 -6.6; 35 -7.0; 37 -7.3; 40 -7.6; 42 -7.7; 45 -7.9; 49 -8.0; 52 -8.0; 56 -8.0; 59 -8.0; 64 -7.8; 68 -7.7; 73 -7.4; 78 -7.1; 83 -6.8; 89 -6.6; 95 -6.4; 102 -6.5; 109 -6.7; 117 -6.9; 125 -7.0; 134 -7.0; 143 -6.6; 153 -6.0; 164 -4.7; 175 -4.7; 188 -4.8; 201 -4.4; 215 -4.0; 230 -3.8; 246 -3.8; 263 -3.7; 282 -3.6; 301 -3.9; 323 -4.1; 345 -4.0; 369 -3.8; 395 -3.6; 423 -3.1; 452 -2.8; 484 -2.5; 518 -2.2; 554 -1.6; 593 -1.1; 635 -0.8; 679 -0.6; 726 -0.2; 777 0.0; 832 0.1; 890 0.2; 952 0.2; 1019 -0.0; 1090 -0.1; 1167 0.1; 1248 0.2; 1336 -0.1; 1429 -0.6; 1529 -1.2; 1636 -1.9; 1751 -2.7; 1873 -3.2; 2004 -3.4; 2145 -3.1; 2295 -3.1; 2455 -2.8; 2627 -2.2; 2811 -1.6; 3008 -1.3; 3219 -1.5; 3444 -1.2; 3685 -1.2; 3943 -1.0; 4219 -0.9; 4514 -0.9; 4830 -0.4; 5168 0.4; 5530 -0.2; 5917 -3.0; 6331 -3.9; 6775 -2.3; 7249 -1.0; 7756 -0.5; 8299 -1.8; 8880 -3.6; 9502 -3.6; 10167 -1.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 -3.8; 22 -4.5; 23 -4.8; 25 -5.3; 26 -5.5; 28 -6.0; 30 -6.3; 32 -6.6; 35 -7.0; 37 -7.3; 40 -7.6; 42 -7.7; 45 -7.9; 49 -8.0; 52 -8.0; 56 -8.0; 59 -8.0; 64 -7.8; 68 -7.7; 73 -7.4; 78 -7.1; 83 -6.8; 89 -6.6; 95 -6.4; 102 -6.5; 109 -6.7; 117 -6.9; 125 -7.0; 134 -7.0; 143 -6.6; 153 -6.0; 164 -4.7; 175 -4.7; 188 -4.8; 201 -4.4; 215 -4.0; 230 -3.8; 246 -3.8; 263 -3.7; 282 -3.6; 301 -3.9; 323 -4.1; 345 -4.0; 369 -3.8; 395 -3.6; 423 -3.1; 452 -2.8; 484 -2.5; 518 -2.2; 554 -1.6; 593 -1.1; 635 -0.8; 679 -0.6; 726 -0.2; 777 0.0; 832 0.1; 890 0.2; 952 0.2; 1019 -0.0; 1090 -0.1; 1167 0.1; 1248 0.2; 1336 -0.1; 1429 -0.6; 1529 -1.2; 1636 -1.9; 1751 -2.7; 1873 -3.2; 2004 -3.4; 2145 -3.1; 2295 -3.1; 2455 -2.8; 2627 -2.2; 2811 -1.6; 3008 -1.3; 3219 -1.5; 3444 -1.2; 3685 -1.2; 3943 -1.0; 4219 -0.9; 4514 -0.9; 4830 -0.4; 5168 0.4; 5530 -0.2; 5917 -3.0; 6331 -3.9; 6775 -2.3; 7249 -1.0; 7756 -0.5; 8299 -1.8; 8880 -3.6; 9502 -3.6; 10167 -1.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
Copy: L=-0.5dB*l, R=-0.5dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/SBAF-Serious/innerfidelity/onear/Shure%20SRH1540/Shure%20SRH1540.png)