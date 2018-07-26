# Massdrop x EMu Purpleheart
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 -2.5; 22 -3.0; 23 -3.2; 25 -3.5; 26 -3.6; 28 -3.9; 30 -4.1; 32 -4.2; 35 -4.5; 37 -4.6; 40 -4.8; 42 -4.9; 45 -5.0; 49 -5.1; 52 -5.2; 56 -5.3; 59 -5.3; 64 -5.3; 68 -5.4; 73 -5.5; 78 -5.6; 83 -5.8; 89 -6.0; 95 -6.4; 102 -6.8; 109 -7.2; 117 -7.5; 125 -7.8; 134 -8.0; 143 -8.1; 153 -8.1; 164 -7.9; 175 -7.7; 188 -7.6; 201 -7.4; 215 -7.1; 230 -6.8; 246 -6.5; 263 -6.1; 282 -5.8; 301 -5.6; 323 -5.4; 345 -5.0; 369 -4.6; 395 -4.2; 423 -3.8; 452 -3.4; 484 -3.1; 518 -2.7; 554 -2.3; 593 -1.9; 635 -1.6; 679 -1.3; 726 -1.1; 777 -1.0; 832 -1.2; 890 -0.6; 952 0.0; 1019 -0.0; 1090 -0.2; 1167 -0.2; 1248 -0.0; 1336 0.5; 1429 0.9; 1529 1.4; 1636 1.7; 1751 2.0; 1873 2.3; 2004 2.8; 2145 3.4; 2295 4.0; 2455 4.5; 2627 4.4; 2811 2.9; 3008 1.7; 3219 1.2; 3444 1.8; 3685 3.5; 3943 4.1; 4219 2.2; 4514 3.8; 4830 5.9; 5168 6.0; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 -0.5; 9502 -0.2; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 -2.5; 22 -3.0; 23 -3.2; 25 -3.5; 26 -3.6; 28 -3.9; 30 -4.1; 32 -4.2; 35 -4.5; 37 -4.6; 40 -4.8; 42 -4.9; 45 -5.0; 49 -5.1; 52 -5.2; 56 -5.3; 59 -5.3; 64 -5.3; 68 -5.4; 73 -5.5; 78 -5.6; 83 -5.8; 89 -6.0; 95 -6.4; 102 -6.8; 109 -7.2; 117 -7.5; 125 -7.8; 134 -8.0; 143 -8.1; 153 -8.1; 164 -7.9; 175 -7.7; 188 -7.6; 201 -7.4; 215 -7.1; 230 -6.8; 246 -6.5; 263 -6.1; 282 -5.8; 301 -5.6; 323 -5.4; 345 -5.0; 369 -4.6; 395 -4.2; 423 -3.8; 452 -3.4; 484 -3.1; 518 -2.7; 554 -2.3; 593 -1.9; 635 -1.6; 679 -1.3; 726 -1.1; 777 -1.0; 832 -1.2; 890 -0.6; 952 0.0; 1019 -0.0; 1090 -0.2; 1167 -0.2; 1248 -0.0; 1336 0.5; 1429 0.9; 1529 1.4; 1636 1.7; 1751 2.0; 1873 2.3; 2004 2.8; 2145 3.4; 2295 4.0; 2455 4.5; 2627 4.4; 2811 2.9; 3008 1.7; 3219 1.2; 3444 1.8; 3685 3.5; 3943 4.1; 4219 2.2; 4514 3.8; 4830 5.9; 5168 6.0; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 -0.5; 9502 -0.2; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Headphone.com/innerfidelity/onear/Massdrop%20x%20EMu%20Purpleheart/Massdrop%20x%20EMu%20Purpleheart.png)