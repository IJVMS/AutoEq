# Grado SR325
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 6.0; 32 6.0; 35 6.0; 37 6.0; 40 6.0; 42 5.7; 45 5.2; 49 4.2; 52 3.5; 56 2.8; 59 2.3; 64 1.7; 68 1.3; 73 0.8; 78 0.4; 83 0.1; 89 -0.2; 95 -0.6; 102 -0.9; 109 -1.1; 117 -1.3; 125 -1.6; 134 -1.8; 143 -1.9; 153 -2.0; 164 -1.9; 175 -1.8; 188 -1.8; 201 -1.9; 215 -1.9; 230 -1.8; 246 -1.7; 263 -1.8; 282 -1.7; 301 -1.7; 323 -1.6; 345 -1.5; 369 -1.4; 395 -1.4; 423 -1.3; 452 -1.4; 484 -1.8; 518 -1.6; 554 -1.1; 593 -0.6; 635 -0.4; 679 -0.4; 726 -0.3; 777 0.0; 832 0.1; 890 0.1; 952 0.1; 1019 -0.1; 1090 -0.3; 1167 -0.7; 1248 -1.1; 1336 -1.6; 1429 -2.1; 1529 -2.7; 1636 -3.4; 1751 -4.4; 1873 -6.3; 2004 -8.2; 2145 -8.3; 2295 -7.1; 2455 -5.9; 2627 -4.9; 2811 -3.6; 3008 -2.1; 3219 -1.0; 3444 -0.2; 3685 0.4; 3943 -0.6; 4219 -5.6; 4514 -9.3; 4830 -7.1; 5168 -4.8; 5530 -4.0; 5917 -3.9; 6331 -5.3; 6775 -6.6; 7249 -7.2; 7756 -8.0; 8299 -9.6; 8880 -11.3; 9502 -11.9; 10167 -11.5; 10879 -10.7; 11640 -9.0; 12455 -4.3; 13327 -0.1; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 6.0; 32 6.0; 35 6.0; 37 6.0; 40 6.0; 42 5.7; 45 5.2; 49 4.2; 52 3.5; 56 2.8; 59 2.3; 64 1.7; 68 1.3; 73 0.8; 78 0.4; 83 0.1; 89 -0.2; 95 -0.6; 102 -0.9; 109 -1.1; 117 -1.3; 125 -1.6; 134 -1.8; 143 -1.9; 153 -2.0; 164 -1.9; 175 -1.8; 188 -1.8; 201 -1.9; 215 -1.9; 230 -1.8; 246 -1.7; 263 -1.8; 282 -1.7; 301 -1.7; 323 -1.6; 345 -1.5; 369 -1.4; 395 -1.4; 423 -1.3; 452 -1.4; 484 -1.8; 518 -1.6; 554 -1.1; 593 -0.6; 635 -0.4; 679 -0.4; 726 -0.3; 777 0.0; 832 0.1; 890 0.1; 952 0.1; 1019 -0.1; 1090 -0.3; 1167 -0.7; 1248 -1.1; 1336 -1.6; 1429 -2.1; 1529 -2.7; 1636 -3.4; 1751 -4.4; 1873 -6.3; 2004 -8.2; 2145 -8.3; 2295 -7.1; 2455 -5.9; 2627 -4.9; 2811 -3.6; 3008 -2.1; 3219 -1.0; 3444 -0.2; 3685 0.4; 3943 -0.6; 4219 -5.6; 4514 -9.3; 4830 -7.1; 5168 -4.8; 5530 -4.0; 5917 -3.9; 6331 -5.3; 6775 -6.6; 7249 -7.2; 7756 -8.0; 8299 -9.6; 8880 -11.3; 9502 -11.9; 10167 -11.5; 10879 -10.7; 11640 -9.0; 12455 -4.3; 13327 -0.1; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Innerfidelity%202017/headphoncecom/onear/Grado%20SR325/Grado%20SR325.png)