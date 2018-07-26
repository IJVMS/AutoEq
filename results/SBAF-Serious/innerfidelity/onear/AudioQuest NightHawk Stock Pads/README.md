# AudioQuest NightHawk Stock Pads
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-25**.
```
GraphicEQ: 10 -84; 20 -6.7; 22 -6.7; 23 -6.7; 25 -6.6; 26 -6.6; 28 -6.6; 30 -6.6; 32 -6.5; 35 -6.5; 37 -6.4; 40 -6.3; 42 -6.3; 45 -6.3; 49 -6.2; 52 -6.1; 56 -6.0; 59 -6.0; 64 -5.9; 68 -5.9; 73 -5.9; 78 -6.1; 83 -6.4; 89 -6.8; 95 -7.5; 102 -8.4; 109 -8.7; 117 -8.6; 125 -9.2; 134 -9.9; 143 -10.2; 153 -10.2; 164 -9.6; 175 -10.0; 188 -10.3; 201 -10.3; 215 -10.1; 230 -10.0; 246 -10.0; 263 -9.8; 282 -9.6; 301 -9.5; 323 -9.2; 345 -8.9; 369 -8.6; 395 -8.2; 423 -7.7; 452 -7.2; 484 -6.8; 518 -6.3; 554 -5.6; 593 -4.7; 635 -4.1; 679 -3.5; 726 -2.8; 777 -2.2; 832 -1.7; 890 -1.0; 952 -0.3; 1019 -0.1; 1090 -0.6; 1167 -0.9; 1248 -1.1; 1336 -2.2; 1429 -3.3; 1529 -4.1; 1636 -4.5; 1751 -4.4; 1873 -3.9; 2004 -3.2; 2145 -2.5; 2295 -1.8; 2455 -0.2; 2627 1.8; 2811 2.4; 3008 2.3; 3219 0.7; 3444 -0.4; 3685 0.4; 3943 2.1; 4219 2.0; 4514 2.1; 4830 2.4; 5168 2.4; 5530 0.8; 5917 -0.6; 6331 -0.8; 6775 -1.3; 7249 -2.5; 7756 -3.6; 8299 -4.6; 8880 -5.2; 9502 -4.8; 10167 -2.4; 10879 -0.1; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 -0.3; 16326 -0.9; 17469 -2.5; 18692 -4.7; 20000 -6.9
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 -6.7; 22 -6.7; 23 -6.7; 25 -6.6; 26 -6.6; 28 -6.6; 30 -6.6; 32 -6.5; 35 -6.5; 37 -6.4; 40 -6.3; 42 -6.3; 45 -6.3; 49 -6.2; 52 -6.1; 56 -6.0; 59 -6.0; 64 -5.9; 68 -5.9; 73 -5.9; 78 -6.1; 83 -6.4; 89 -6.8; 95 -7.5; 102 -8.4; 109 -8.7; 117 -8.6; 125 -9.2; 134 -9.9; 143 -10.2; 153 -10.2; 164 -9.6; 175 -10.0; 188 -10.3; 201 -10.3; 215 -10.1; 230 -10.0; 246 -10.0; 263 -9.8; 282 -9.6; 301 -9.5; 323 -9.2; 345 -8.9; 369 -8.6; 395 -8.2; 423 -7.7; 452 -7.2; 484 -6.8; 518 -6.3; 554 -5.6; 593 -4.7; 635 -4.1; 679 -3.5; 726 -2.8; 777 -2.2; 832 -1.7; 890 -1.0; 952 -0.3; 1019 -0.1; 1090 -0.6; 1167 -0.9; 1248 -1.1; 1336 -2.2; 1429 -3.3; 1529 -4.1; 1636 -4.5; 1751 -4.4; 1873 -3.9; 2004 -3.2; 2145 -2.5; 2295 -1.8; 2455 -0.2; 2627 1.8; 2811 2.4; 3008 2.3; 3219 0.7; 3444 -0.4; 3685 0.4; 3943 2.1; 4219 2.0; 4514 2.1; 4830 2.4; 5168 2.4; 5530 0.8; 5917 -0.6; 6331 -0.8; 6775 -1.3; 7249 -2.5; 7756 -3.6; 8299 -4.6; 8880 -5.2; 9502 -4.8; 10167 -2.4; 10879 -0.1; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 -0.3; 16326 -0.9; 17469 -2.5; 18692 -4.7; 20000 -6.9
Copy: L=-2.5dB*l, R=-2.5dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/SBAF-Serious/innerfidelity/onear/AudioQuest%20NightHawk%20Stock%20Pads/AudioQuest%20NightHawk%20Stock%20Pads.png)