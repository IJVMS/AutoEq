# Koss KSC75
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 6.0; 32 6.0; 35 6.0; 37 6.0; 40 5.7; 42 5.3; 45 4.6; 49 3.7; 52 3.0; 56 2.3; 59 1.7; 64 0.9; 68 0.3; 73 -0.3; 78 -0.9; 83 -1.4; 89 -2.0; 95 -2.6; 102 -3.2; 109 -3.5; 117 -3.9; 125 -4.3; 134 -4.6; 143 -4.6; 153 -4.8; 164 -4.6; 175 -4.4; 188 -4.3; 201 -4.3; 215 -4.2; 230 -4.0; 246 -3.9; 263 -3.8; 282 -3.6; 301 -3.4; 323 -3.2; 345 -3.0; 369 -2.9; 395 -2.7; 423 -2.5; 452 -2.5; 484 -2.5; 518 -2.3; 554 -1.7; 593 -1.1; 635 -0.9; 679 -0.8; 726 -0.5; 777 -0.2; 832 -0.0; 890 -0.0; 952 0.0; 1019 -0.0; 1090 -0.1; 1167 -0.4; 1248 -0.7; 1336 -1.0; 1429 -1.5; 1529 -2.1; 1636 -2.7; 1751 -3.4; 1873 -4.4; 2004 -4.9; 2145 -5.4; 2295 -5.9; 2455 -5.6; 2627 -4.6; 2811 -3.3; 3008 -2.4; 3219 -2.3; 3444 0.7; 3685 6.0; 3943 6.0; 4219 3.0; 4514 -3.2; 4830 -5.7; 5168 -2.0; 5530 0.7; 5917 2.0; 6331 1.4; 6775 1.4; 7249 0.6; 7756 -1.0; 8299 -3.4; 8880 -5.5; 9502 -6.3; 10167 -5.4; 10879 -2.6; 11640 -0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 -0.3
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 6.0; 32 6.0; 35 6.0; 37 6.0; 40 5.7; 42 5.3; 45 4.6; 49 3.7; 52 3.0; 56 2.3; 59 1.7; 64 0.9; 68 0.3; 73 -0.3; 78 -0.9; 83 -1.4; 89 -2.0; 95 -2.6; 102 -3.2; 109 -3.5; 117 -3.9; 125 -4.3; 134 -4.6; 143 -4.6; 153 -4.8; 164 -4.6; 175 -4.4; 188 -4.3; 201 -4.3; 215 -4.2; 230 -4.0; 246 -3.9; 263 -3.8; 282 -3.6; 301 -3.4; 323 -3.2; 345 -3.0; 369 -2.9; 395 -2.7; 423 -2.5; 452 -2.5; 484 -2.5; 518 -2.3; 554 -1.7; 593 -1.1; 635 -0.9; 679 -0.8; 726 -0.5; 777 -0.2; 832 -0.0; 890 -0.0; 952 0.0; 1019 -0.0; 1090 -0.1; 1167 -0.4; 1248 -0.7; 1336 -1.0; 1429 -1.5; 1529 -2.1; 1636 -2.7; 1751 -3.4; 1873 -4.4; 2004 -4.9; 2145 -5.4; 2295 -5.9; 2455 -5.6; 2627 -4.6; 2811 -3.3; 3008 -2.4; 3219 -2.3; 3444 0.7; 3685 6.0; 3943 6.0; 4219 3.0; 4514 -3.2; 4830 -5.7; 5168 -2.0; 5530 0.7; 5917 2.0; 6331 1.4; 6775 1.4; 7249 0.6; 7756 -1.0; 8299 -3.4; 8880 -5.5; 9502 -6.3; 10167 -5.4; 10879 -2.6; 11640 -0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 -0.3
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Innerfidelity%202017/innerfidelity/onear/Koss%20KSC75/Koss%20KSC75.png)