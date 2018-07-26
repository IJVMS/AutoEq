# Onkyo ES-FC300
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 -1.9; 22 -2.0; 23 -2.1; 25 -2.2; 26 -2.3; 28 -2.4; 30 -2.4; 32 -2.3; 35 -2.3; 37 -2.3; 40 -2.5; 42 -2.7; 45 -3.0; 49 -3.3; 52 -3.4; 56 -3.3; 59 -3.0; 64 -2.3; 68 -1.4; 73 -0.5; 78 -0.7; 83 -1.5; 89 -2.4; 95 -3.1; 102 -3.3; 109 -3.5; 117 -4.3; 125 -5.1; 134 -5.5; 143 -5.8; 153 -5.7; 164 -5.1; 175 -5.0; 188 -4.5; 201 -3.4; 215 -2.7; 230 -1.9; 246 -1.0; 263 -0.6; 282 -1.0; 301 -1.9; 323 -2.6; 345 -3.0; 369 -3.4; 395 -3.6; 423 -3.4; 452 -3.1; 484 -2.8; 518 -2.6; 554 -2.4; 593 -2.0; 635 -1.5; 679 -0.9; 726 -0.2; 777 0.2; 832 0.2; 890 0.1; 952 0.0; 1019 0.1; 1090 0.7; 1167 1.8; 1248 2.7; 1336 3.2; 1429 3.5; 1529 3.3; 1636 2.7; 1751 1.9; 1873 1.4; 2004 1.5; 2145 1.6; 2295 1.7; 2455 2.0; 2627 1.9; 2811 1.8; 3008 2.6; 3219 3.0; 3444 2.8; 3685 3.3; 3943 5.3; 4219 5.4; 4514 5.5; 4830 6.0; 5168 6.0; 5530 5.8; 5917 3.8; 6331 4.5; 6775 3.9; 7249 1.3; 7756 0.1; 8299 -1.0; 8880 -1.2; 9502 -1.4; 10167 -1.2; 10879 -0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 -1.9; 22 -2.0; 23 -2.1; 25 -2.2; 26 -2.3; 28 -2.4; 30 -2.4; 32 -2.3; 35 -2.3; 37 -2.3; 40 -2.5; 42 -2.7; 45 -3.0; 49 -3.3; 52 -3.4; 56 -3.3; 59 -3.0; 64 -2.3; 68 -1.4; 73 -0.5; 78 -0.7; 83 -1.5; 89 -2.4; 95 -3.1; 102 -3.3; 109 -3.5; 117 -4.3; 125 -5.1; 134 -5.5; 143 -5.8; 153 -5.7; 164 -5.1; 175 -5.0; 188 -4.5; 201 -3.4; 215 -2.7; 230 -1.9; 246 -1.0; 263 -0.6; 282 -1.0; 301 -1.9; 323 -2.6; 345 -3.0; 369 -3.4; 395 -3.6; 423 -3.4; 452 -3.1; 484 -2.8; 518 -2.6; 554 -2.4; 593 -2.0; 635 -1.5; 679 -0.9; 726 -0.2; 777 0.2; 832 0.2; 890 0.1; 952 0.0; 1019 0.1; 1090 0.7; 1167 1.8; 1248 2.7; 1336 3.2; 1429 3.5; 1529 3.3; 1636 2.7; 1751 1.9; 1873 1.4; 2004 1.5; 2145 1.6; 2295 1.7; 2455 2.0; 2627 1.9; 2811 1.8; 3008 2.6; 3219 3.0; 3444 2.8; 3685 3.3; 3943 5.3; 4219 5.4; 4514 5.5; 4830 6.0; 5168 6.0; 5530 5.8; 5917 3.8; 6331 4.5; 6775 3.9; 7249 1.3; 7756 0.1; 8299 -1.0; 8880 -1.2; 9502 -1.4; 10167 -1.2; 10879 -0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Sonoma%20Model%20One/innerfidelity/onear/Onkyo%20ES-FC300/Onkyo%20ES-FC300.png)