# MrSpeakers AEON PreProduction
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 0.8; 22 0.7; 23 0.6; 25 0.5; 26 0.4; 28 0.4; 30 0.3; 32 0.3; 35 0.2; 37 0.2; 40 0.2; 42 0.2; 45 0.2; 49 0.3; 52 0.2; 56 0.1; 59 0.2; 64 0.5; 68 0.5; 73 0.5; 78 0.4; 83 -0.1; 89 -0.6; 95 -1.5; 102 -2.4; 109 -3.0; 117 -3.3; 125 -3.4; 134 -3.1; 143 -2.6; 153 -1.8; 164 -1.0; 175 -1.8; 188 -1.5; 201 -1.2; 215 -1.2; 230 -1.2; 246 -1.2; 263 -1.2; 282 -1.3; 301 -1.3; 323 -1.5; 345 -1.5; 369 -1.6; 395 -1.5; 423 -1.2; 452 -0.9; 484 -0.6; 518 -0.3; 554 -0.2; 593 -0.1; 635 0.1; 679 0.3; 726 0.5; 777 0.5; 832 0.9; 890 0.4; 952 -0.0; 1019 -0.2; 1090 -0.5; 1167 -0.4; 1248 -0.1; 1336 0.3; 1429 0.8; 1529 1.0; 1636 1.0; 1751 1.0; 1873 1.5; 2004 2.4; 2145 2.7; 2295 3.5; 2455 3.6; 2627 4.7; 2811 5.9; 3008 5.5; 3219 5.1; 3444 4.2; 3685 3.4; 3943 3.2; 4219 4.5; 4514 5.6; 4830 6.0; 5168 6.0; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 -0.4; 8880 -1.3; 9502 -0.5; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 0.8; 22 0.7; 23 0.6; 25 0.5; 26 0.4; 28 0.4; 30 0.3; 32 0.3; 35 0.2; 37 0.2; 40 0.2; 42 0.2; 45 0.2; 49 0.3; 52 0.2; 56 0.1; 59 0.2; 64 0.5; 68 0.5; 73 0.5; 78 0.4; 83 -0.1; 89 -0.6; 95 -1.5; 102 -2.4; 109 -3.0; 117 -3.3; 125 -3.4; 134 -3.1; 143 -2.6; 153 -1.8; 164 -1.0; 175 -1.8; 188 -1.5; 201 -1.2; 215 -1.2; 230 -1.2; 246 -1.2; 263 -1.2; 282 -1.3; 301 -1.3; 323 -1.5; 345 -1.5; 369 -1.6; 395 -1.5; 423 -1.2; 452 -0.9; 484 -0.6; 518 -0.3; 554 -0.2; 593 -0.1; 635 0.1; 679 0.3; 726 0.5; 777 0.5; 832 0.9; 890 0.4; 952 -0.0; 1019 -0.2; 1090 -0.5; 1167 -0.4; 1248 -0.1; 1336 0.3; 1429 0.8; 1529 1.0; 1636 1.0; 1751 1.0; 1873 1.5; 2004 2.4; 2145 2.7; 2295 3.5; 2455 3.6; 2627 4.7; 2811 5.9; 3008 5.5; 3219 5.1; 3444 4.2; 3685 3.4; 3943 3.2; 4219 4.5; 4514 5.6; 4830 6.0; 5168 6.0; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 -0.4; 8880 -1.3; 9502 -0.5; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Headphone.com/innerfidelity/onear/MrSpeakers%20AEON%20PreProduction/MrSpeakers%20AEON%20PreProduction.png)