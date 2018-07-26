# AKG K81 DJ
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 6.0; 32 6.0; 35 6.0; 37 6.0; 40 6.0; 42 6.0; 45 6.0; 49 6.0; 52 6.0; 56 6.0; 59 6.0; 64 6.0; 68 6.0; 73 6.0; 78 6.0; 83 6.0; 89 6.0; 95 6.0; 102 6.0; 109 6.0; 117 6.0; 125 6.0; 134 5.7; 143 5.1; 153 4.6; 164 4.2; 175 4.4; 188 4.2; 201 4.1; 215 4.5; 230 4.5; 246 4.1; 263 3.7; 282 3.0; 301 2.4; 323 1.5; 345 0.4; 369 -0.6; 395 -1.6; 423 -2.0; 452 -2.3; 484 -2.3; 518 -2.0; 554 -1.6; 593 -1.1; 635 -0.6; 679 -0.6; 726 -0.4; 777 0.0; 832 0.1; 890 0.2; 952 0.1; 1019 -0.1; 1090 -0.3; 1167 -0.5; 1248 -0.7; 1336 -0.8; 1429 -1.0; 1529 -1.3; 1636 -1.4; 1751 -1.1; 1873 -1.1; 2004 -1.2; 2145 -1.8; 2295 -1.3; 2455 -0.0; 2627 0.9; 2811 2.0; 3008 3.5; 3219 4.3; 3444 4.4; 3685 3.9; 3943 4.0; 4219 3.8; 4514 4.2; 4830 5.4; 5168 6.0; 5530 5.9; 5917 1.7; 6331 -1.5; 6775 -2.5; 7249 -1.7; 7756 -0.6; 8299 -0.0; 8880 -0.1; 9502 -0.5; 10167 -0.2; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 -0.3; 15258 -2.7; 16326 -3.0; 17469 -1.8; 18692 -0.6; 20000 -0.1
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 6.0; 32 6.0; 35 6.0; 37 6.0; 40 6.0; 42 6.0; 45 6.0; 49 6.0; 52 6.0; 56 6.0; 59 6.0; 64 6.0; 68 6.0; 73 6.0; 78 6.0; 83 6.0; 89 6.0; 95 6.0; 102 6.0; 109 6.0; 117 6.0; 125 6.0; 134 5.7; 143 5.1; 153 4.6; 164 4.2; 175 4.4; 188 4.2; 201 4.1; 215 4.5; 230 4.5; 246 4.1; 263 3.7; 282 3.0; 301 2.4; 323 1.5; 345 0.4; 369 -0.6; 395 -1.6; 423 -2.0; 452 -2.3; 484 -2.3; 518 -2.0; 554 -1.6; 593 -1.1; 635 -0.6; 679 -0.6; 726 -0.4; 777 0.0; 832 0.1; 890 0.2; 952 0.1; 1019 -0.1; 1090 -0.3; 1167 -0.5; 1248 -0.7; 1336 -0.8; 1429 -1.0; 1529 -1.3; 1636 -1.4; 1751 -1.1; 1873 -1.1; 2004 -1.2; 2145 -1.8; 2295 -1.3; 2455 -0.0; 2627 0.9; 2811 2.0; 3008 3.5; 3219 4.3; 3444 4.4; 3685 3.9; 3943 4.0; 4219 3.8; 4514 4.2; 4830 5.4; 5168 6.0; 5530 5.9; 5917 1.7; 6331 -1.5; 6775 -2.5; 7249 -1.7; 7756 -0.6; 8299 -0.0; 8880 -0.1; 9502 -0.5; 10167 -0.2; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 -0.3; 15258 -2.7; 16326 -3.0; 17469 -1.8; 18692 -0.6; 20000 -0.1
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Innerfidelity%202017/headphoncecom/onear/AKG%20K81%20DJ/AKG%20K81%20DJ.png)