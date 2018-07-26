# Ultrasone Signature Pro
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 4.4; 22 3.5; 23 3.1; 25 2.3; 26 2.0; 28 1.4; 30 0.9; 32 0.4; 35 -0.0; 37 -0.3; 40 -0.6; 42 -0.8; 45 -1.0; 49 -1.2; 52 -1.3; 56 -1.4; 59 -1.4; 64 -1.4; 68 -1.1; 73 -0.5; 78 0.2; 83 0.0; 89 -1.0; 95 -1.9; 102 -2.5; 109 -2.3; 117 -2.0; 125 -2.7; 134 -3.6; 143 -4.2; 153 -4.4; 164 -3.7; 175 -3.7; 188 -4.3; 201 -4.3; 215 -4.3; 230 -4.1; 246 -4.0; 263 -3.7; 282 -3.3; 301 -3.0; 323 -2.8; 345 -2.6; 369 -2.6; 395 -2.6; 423 -2.7; 452 -3.0; 484 -3.3; 518 -3.4; 554 -3.1; 593 -2.7; 635 -2.5; 679 -2.5; 726 -2.1; 777 -1.7; 832 -1.4; 890 -1.1; 952 -0.5; 1019 0.1; 1090 0.7; 1167 0.9; 1248 0.7; 1336 0.4; 1429 0.5; 1529 1.2; 1636 2.3; 1751 2.8; 1873 3.2; 2004 3.7; 2145 4.9; 2295 6.0; 2455 6.0; 2627 6.0; 2811 6.0; 3008 6.0; 3219 6.0; 3444 6.0; 3685 6.0; 3943 6.0; 4219 6.0; 4514 6.0; 4830 6.0; 5168 6.0; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 -0.4; 10167 -2.5; 10879 -4.2; 11640 -4.3; 12455 -2.2; 13327 -0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 4.4; 22 3.5; 23 3.1; 25 2.3; 26 2.0; 28 1.4; 30 0.9; 32 0.4; 35 -0.0; 37 -0.3; 40 -0.6; 42 -0.8; 45 -1.0; 49 -1.2; 52 -1.3; 56 -1.4; 59 -1.4; 64 -1.4; 68 -1.1; 73 -0.5; 78 0.2; 83 0.0; 89 -1.0; 95 -1.9; 102 -2.5; 109 -2.3; 117 -2.0; 125 -2.7; 134 -3.6; 143 -4.2; 153 -4.4; 164 -3.7; 175 -3.7; 188 -4.3; 201 -4.3; 215 -4.3; 230 -4.1; 246 -4.0; 263 -3.7; 282 -3.3; 301 -3.0; 323 -2.8; 345 -2.6; 369 -2.6; 395 -2.6; 423 -2.7; 452 -3.0; 484 -3.3; 518 -3.4; 554 -3.1; 593 -2.7; 635 -2.5; 679 -2.5; 726 -2.1; 777 -1.7; 832 -1.4; 890 -1.1; 952 -0.5; 1019 0.1; 1090 0.7; 1167 0.9; 1248 0.7; 1336 0.4; 1429 0.5; 1529 1.2; 1636 2.3; 1751 2.8; 1873 3.2; 2004 3.7; 2145 4.9; 2295 6.0; 2455 6.0; 2627 6.0; 2811 6.0; 3008 6.0; 3219 6.0; 3444 6.0; 3685 6.0; 3943 6.0; 4219 6.0; 4514 6.0; 4830 6.0; 5168 6.0; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 -0.4; 10167 -2.5; 10879 -4.2; 11640 -4.3; 12455 -2.2; 13327 -0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Innerfidelity%202017/innerfidelity/onear/Ultrasone%20Signature%20Pro/Ultrasone%20Signature%20Pro.png)