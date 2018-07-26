# Plantronics BackBeat 500 Wired
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 0.8; 22 0.7; 23 0.7; 25 0.6; 26 0.6; 28 0.6; 30 0.5; 32 0.5; 35 0.4; 37 0.3; 40 0.3; 42 0.3; 45 0.3; 49 -0.1; 52 -0.4; 56 -0.8; 59 -0.8; 64 -0.5; 68 -0.1; 73 0.4; 78 0.7; 83 0.8; 89 0.5; 95 -0.0; 102 -0.9; 109 -1.6; 117 -2.6; 125 -3.6; 134 -4.3; 143 -4.6; 153 -4.5; 164 -4.2; 175 -4.3; 188 -4.2; 201 -3.9; 215 -3.4; 230 -2.9; 246 -2.8; 263 -2.7; 282 -2.8; 301 -2.7; 323 -2.5; 345 -2.0; 369 -1.6; 395 -0.9; 423 -0.5; 452 -0.4; 484 -0.3; 518 -0.3; 554 -0.3; 593 -0.2; 635 0.1; 679 0.2; 726 0.3; 777 0.2; 832 -0.0; 890 -0.0; 952 0.1; 1019 0.0; 1090 0.3; 1167 1.4; 1248 2.1; 1336 2.2; 1429 2.1; 1529 1.5; 1636 0.4; 1751 -0.8; 1873 -1.1; 2004 -0.6; 2145 -0.0; 2295 0.8; 2455 2.3; 2627 3.8; 2811 3.8; 3008 4.8; 3219 5.1; 3444 5.1; 3685 5.0; 3943 5.5; 4219 5.8; 4514 6.0; 4830 6.0; 5168 5.4; 5530 3.8; 5917 4.6; 6331 4.9; 6775 3.2; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 -0.9; 16326 -2.6; 17469 -2.2; 18692 -0.4; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 0.8; 22 0.7; 23 0.7; 25 0.6; 26 0.6; 28 0.6; 30 0.5; 32 0.5; 35 0.4; 37 0.3; 40 0.3; 42 0.3; 45 0.3; 49 -0.1; 52 -0.4; 56 -0.8; 59 -0.8; 64 -0.5; 68 -0.1; 73 0.4; 78 0.7; 83 0.8; 89 0.5; 95 -0.0; 102 -0.9; 109 -1.6; 117 -2.6; 125 -3.6; 134 -4.3; 143 -4.6; 153 -4.5; 164 -4.2; 175 -4.3; 188 -4.2; 201 -3.9; 215 -3.4; 230 -2.9; 246 -2.8; 263 -2.7; 282 -2.8; 301 -2.7; 323 -2.5; 345 -2.0; 369 -1.6; 395 -0.9; 423 -0.5; 452 -0.4; 484 -0.3; 518 -0.3; 554 -0.3; 593 -0.2; 635 0.1; 679 0.2; 726 0.3; 777 0.2; 832 -0.0; 890 -0.0; 952 0.1; 1019 0.0; 1090 0.3; 1167 1.4; 1248 2.1; 1336 2.2; 1429 2.1; 1529 1.5; 1636 0.4; 1751 -0.8; 1873 -1.1; 2004 -0.6; 2145 -0.0; 2295 0.8; 2455 2.3; 2627 3.8; 2811 3.8; 3008 4.8; 3219 5.1; 3444 5.1; 3685 5.0; 3943 5.5; 4219 5.8; 4514 6.0; 4830 6.0; 5168 5.4; 5530 3.8; 5917 4.6; 6331 4.9; 6775 3.2; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 -0.9; 16326 -2.6; 17469 -2.2; 18692 -0.4; 20000 0.0
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Sonoma%20Model%20One/innerfidelity/onear/Plantronics%20BackBeat%20500%20Wired/Plantronics%20BackBeat%20500%20Wired.png)