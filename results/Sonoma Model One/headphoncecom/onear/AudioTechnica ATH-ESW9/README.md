# AudioTechnica ATH-ESW9
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 6.0; 32 6.0; 35 6.0; 37 6.0; 40 6.0; 42 6.0; 45 6.0; 49 6.0; 52 6.0; 56 6.0; 59 6.0; 64 6.0; 68 6.0; 73 6.0; 78 6.0; 83 6.0; 89 6.0; 95 6.0; 102 6.0; 109 6.0; 117 5.9; 125 6.0; 134 5.6; 143 4.8; 153 4.3; 164 4.3; 175 4.1; 188 4.2; 201 4.2; 215 3.9; 230 3.7; 246 3.4; 263 3.1; 282 2.7; 301 2.6; 323 3.1; 345 3.5; 369 3.6; 395 3.8; 423 4.1; 452 4.3; 484 4.5; 518 4.4; 554 4.4; 593 4.3; 635 4.0; 679 3.5; 726 2.8; 777 2.4; 832 1.8; 890 1.1; 952 0.3; 1019 -0.1; 1090 -0.2; 1167 0.3; 1248 0.8; 1336 1.0; 1429 1.0; 1529 0.8; 1636 0.2; 1751 -0.3; 1873 -0.2; 2004 0.1; 2145 1.0; 2295 2.0; 2455 3.1; 2627 4.5; 2811 5.9; 3008 6.0; 3219 6.0; 3444 6.0; 3685 6.0; 3943 5.8; 4219 4.6; 4514 4.5; 4830 5.9; 5168 6.0; 5530 6.0; 5917 5.9; 6331 5.0; 6775 1.7; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 -1.0; 15258 -2.0; 16326 -2.8; 17469 -3.9; 18692 -2.3; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 6.0; 32 6.0; 35 6.0; 37 6.0; 40 6.0; 42 6.0; 45 6.0; 49 6.0; 52 6.0; 56 6.0; 59 6.0; 64 6.0; 68 6.0; 73 6.0; 78 6.0; 83 6.0; 89 6.0; 95 6.0; 102 6.0; 109 6.0; 117 5.9; 125 6.0; 134 5.6; 143 4.8; 153 4.3; 164 4.3; 175 4.1; 188 4.2; 201 4.2; 215 3.9; 230 3.7; 246 3.4; 263 3.1; 282 2.7; 301 2.6; 323 3.1; 345 3.5; 369 3.6; 395 3.8; 423 4.1; 452 4.3; 484 4.5; 518 4.4; 554 4.4; 593 4.3; 635 4.0; 679 3.5; 726 2.8; 777 2.4; 832 1.8; 890 1.1; 952 0.3; 1019 -0.1; 1090 -0.2; 1167 0.3; 1248 0.8; 1336 1.0; 1429 1.0; 1529 0.8; 1636 0.2; 1751 -0.3; 1873 -0.2; 2004 0.1; 2145 1.0; 2295 2.0; 2455 3.1; 2627 4.5; 2811 5.9; 3008 6.0; 3219 6.0; 3444 6.0; 3685 6.0; 3943 5.8; 4219 4.6; 4514 4.5; 4830 5.9; 5168 6.0; 5530 6.0; 5917 5.9; 6331 5.0; 6775 1.7; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 -1.0; 15258 -2.0; 16326 -2.8; 17469 -3.9; 18692 -2.3; 20000 0.0
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Sonoma%20Model%20One/headphoncecom/onear/AudioTechnica%20ATH-ESW9/AudioTechnica%20ATH-ESW9.png)