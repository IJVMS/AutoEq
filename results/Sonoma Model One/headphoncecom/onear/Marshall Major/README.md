# Marshall Major
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 6.0; 32 6.0; 35 6.0; 37 6.0; 40 6.0; 42 6.0; 45 6.0; 49 6.0; 52 6.0; 56 6.0; 59 6.0; 64 6.0; 68 6.0; 73 6.0; 78 6.0; 83 6.0; 89 6.0; 95 6.0; 102 6.0; 109 6.0; 117 6.0; 125 5.4; 134 4.6; 143 4.0; 153 3.4; 164 3.1; 175 2.8; 188 2.5; 201 2.3; 215 2.1; 230 2.0; 246 2.0; 263 2.2; 282 2.2; 301 1.7; 323 1.5; 345 1.8; 369 1.7; 395 1.5; 423 1.5; 452 1.6; 484 2.0; 518 2.3; 554 2.9; 593 3.4; 635 3.8; 679 4.2; 726 4.4; 777 4.3; 832 3.5; 890 2.4; 952 1.1; 1019 -0.1; 1090 -0.2; 1167 0.4; 1248 -0.1; 1336 -1.5; 1429 -2.9; 1529 -4.2; 1636 -5.2; 1751 -6.8; 1873 -6.9; 2004 -5.8; 2145 -3.9; 2295 -1.7; 2455 0.5; 2627 2.5; 2811 4.1; 3008 5.5; 3219 5.9; 3444 5.7; 3685 5.8; 3943 6.0; 4219 6.0; 4514 6.0; 4830 6.0; 5168 6.0; 5530 5.2; 5917 1.0; 6331 -1.1; 6775 -3.3; 7249 -4.2; 7756 -3.1; 8299 -2.6; 8880 -3.7; 9502 -5.1; 10167 -3.6; 10879 -0.1; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 -0.6; 17469 -1.4; 18692 -0.3; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 6.0; 32 6.0; 35 6.0; 37 6.0; 40 6.0; 42 6.0; 45 6.0; 49 6.0; 52 6.0; 56 6.0; 59 6.0; 64 6.0; 68 6.0; 73 6.0; 78 6.0; 83 6.0; 89 6.0; 95 6.0; 102 6.0; 109 6.0; 117 6.0; 125 5.4; 134 4.6; 143 4.0; 153 3.4; 164 3.1; 175 2.8; 188 2.5; 201 2.3; 215 2.1; 230 2.0; 246 2.0; 263 2.2; 282 2.2; 301 1.7; 323 1.5; 345 1.8; 369 1.7; 395 1.5; 423 1.5; 452 1.6; 484 2.0; 518 2.3; 554 2.9; 593 3.4; 635 3.8; 679 4.2; 726 4.4; 777 4.3; 832 3.5; 890 2.4; 952 1.1; 1019 -0.1; 1090 -0.2; 1167 0.4; 1248 -0.1; 1336 -1.5; 1429 -2.9; 1529 -4.2; 1636 -5.2; 1751 -6.8; 1873 -6.9; 2004 -5.8; 2145 -3.9; 2295 -1.7; 2455 0.5; 2627 2.5; 2811 4.1; 3008 5.5; 3219 5.9; 3444 5.7; 3685 5.8; 3943 6.0; 4219 6.0; 4514 6.0; 4830 6.0; 5168 6.0; 5530 5.2; 5917 1.0; 6331 -1.1; 6775 -3.3; 7249 -4.2; 7756 -3.1; 8299 -2.6; 8880 -3.7; 9502 -5.1; 10167 -3.6; 10879 -0.1; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 -0.6; 17469 -1.4; 18692 -0.3; 20000 0.0
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Sonoma%20Model%20One/headphoncecom/onear/Marshall%20Major/Marshall%20Major.png)