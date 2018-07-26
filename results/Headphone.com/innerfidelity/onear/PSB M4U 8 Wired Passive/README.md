# PSB M4U 8 Wired Passive
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-51**.
```
GraphicEQ: 10 -84; 20 -6.0; 22 -6.1; 23 -6.0; 25 -6.0; 26 -6.0; 28 -5.9; 30 -5.9; 32 -5.8; 35 -5.7; 37 -5.6; 40 -5.4; 42 -5.3; 45 -5.1; 49 -4.8; 52 -4.8; 56 -4.9; 59 -5.0; 64 -5.0; 68 -4.9; 73 -4.7; 78 -4.5; 83 -4.3; 89 -4.3; 95 -4.5; 102 -5.5; 109 -6.5; 117 -7.0; 125 -7.6; 134 -8.5; 143 -8.5; 153 -8.1; 164 -6.9; 175 -7.5; 188 -7.7; 201 -7.1; 215 -6.7; 230 -6.0; 246 -5.4; 263 -4.8; 282 -4.4; 301 -4.3; 323 -3.8; 345 -3.2; 369 -2.6; 395 -1.9; 423 -1.3; 452 -0.7; 484 -0.3; 518 0.4; 554 0.8; 593 1.3; 635 1.6; 679 1.7; 726 1.6; 777 1.1; 832 0.6; 890 0.2; 952 0.1; 1019 -0.0; 1090 -0.2; 1167 -0.5; 1248 -0.4; 1336 0.2; 1429 0.8; 1529 1.3; 1636 1.6; 1751 1.8; 1873 2.1; 2004 2.8; 2145 2.5; 2295 2.6; 2455 2.5; 2627 2.6; 2811 2.3; 3008 1.7; 3219 1.0; 3444 0.3; 3685 -0.2; 3943 -0.3; 4219 0.9; 4514 3.0; 4830 4.6; 5168 5.0; 5530 4.2; 5917 3.9; 6331 2.5; 6775 1.6; 7249 0.7; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 -6.0; 22 -6.1; 23 -6.0; 25 -6.0; 26 -6.0; 28 -5.9; 30 -5.9; 32 -5.8; 35 -5.7; 37 -5.6; 40 -5.4; 42 -5.3; 45 -5.1; 49 -4.8; 52 -4.8; 56 -4.9; 59 -5.0; 64 -5.0; 68 -4.9; 73 -4.7; 78 -4.5; 83 -4.3; 89 -4.3; 95 -4.5; 102 -5.5; 109 -6.5; 117 -7.0; 125 -7.6; 134 -8.5; 143 -8.5; 153 -8.1; 164 -6.9; 175 -7.5; 188 -7.7; 201 -7.1; 215 -6.7; 230 -6.0; 246 -5.4; 263 -4.8; 282 -4.4; 301 -4.3; 323 -3.8; 345 -3.2; 369 -2.6; 395 -1.9; 423 -1.3; 452 -0.7; 484 -0.3; 518 0.4; 554 0.8; 593 1.3; 635 1.6; 679 1.7; 726 1.6; 777 1.1; 832 0.6; 890 0.2; 952 0.1; 1019 -0.0; 1090 -0.2; 1167 -0.5; 1248 -0.4; 1336 0.2; 1429 0.8; 1529 1.3; 1636 1.6; 1751 1.8; 1873 2.1; 2004 2.8; 2145 2.5; 2295 2.6; 2455 2.5; 2627 2.6; 2811 2.3; 3008 1.7; 3219 1.0; 3444 0.3; 3685 -0.2; 3943 -0.3; 4219 0.9; 4514 3.0; 4830 4.6; 5168 5.0; 5530 4.2; 5917 3.9; 6331 2.5; 6775 1.6; 7249 0.7; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
Copy: L=-5.1dB*l, R=-5.1dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Headphone.com/innerfidelity/onear/PSB%20M4U%208%20Wired%20Passive/PSB%20M4U%208%20Wired%20Passive.png)