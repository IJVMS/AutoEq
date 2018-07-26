# AudioTechnica ATH-ESW9A
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 6.0; 32 6.0; 35 5.9; 37 5.7; 40 5.1; 42 4.7; 45 4.3; 49 3.9; 52 3.6; 56 3.2; 59 3.0; 64 3.0; 68 3.5; 73 3.9; 78 3.5; 83 3.2; 89 3.1; 95 2.8; 102 2.5; 109 2.3; 117 2.3; 125 2.8; 134 2.7; 143 2.2; 153 1.8; 164 1.7; 175 1.5; 188 1.5; 201 1.8; 215 2.0; 230 1.8; 246 1.4; 263 0.9; 282 0.4; 301 0.3; 323 0.6; 345 0.9; 369 1.1; 395 1.2; 423 1.5; 452 1.5; 484 1.2; 518 1.4; 554 1.9; 593 2.5; 635 2.4; 679 1.6; 726 0.9; 777 0.7; 832 0.6; 890 0.5; 952 0.2; 1019 -0.1; 1090 -0.6; 1167 -1.1; 1248 -1.4; 1336 -1.7; 1429 -1.8; 1529 -1.9; 1636 -2.0; 1751 -1.9; 1873 -1.6; 2004 -1.0; 2145 -0.1; 2295 0.8; 2455 1.7; 2627 3.0; 2811 4.8; 3008 6.0; 3219 6.0; 3444 6.0; 3685 6.0; 3943 6.0; 4219 6.0; 4514 6.0; 4830 6.0; 5168 6.0; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 0.9; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 6.0; 32 6.0; 35 5.9; 37 5.7; 40 5.1; 42 4.7; 45 4.3; 49 3.9; 52 3.6; 56 3.2; 59 3.0; 64 3.0; 68 3.5; 73 3.9; 78 3.5; 83 3.2; 89 3.1; 95 2.8; 102 2.5; 109 2.3; 117 2.3; 125 2.8; 134 2.7; 143 2.2; 153 1.8; 164 1.7; 175 1.5; 188 1.5; 201 1.8; 215 2.0; 230 1.8; 246 1.4; 263 0.9; 282 0.4; 301 0.3; 323 0.6; 345 0.9; 369 1.1; 395 1.2; 423 1.5; 452 1.5; 484 1.2; 518 1.4; 554 1.9; 593 2.5; 635 2.4; 679 1.6; 726 0.9; 777 0.7; 832 0.6; 890 0.5; 952 0.2; 1019 -0.1; 1090 -0.6; 1167 -1.1; 1248 -1.4; 1336 -1.7; 1429 -1.8; 1529 -1.9; 1636 -2.0; 1751 -1.9; 1873 -1.6; 2004 -1.0; 2145 -0.1; 2295 0.8; 2455 1.7; 2627 3.0; 2811 4.8; 3008 6.0; 3219 6.0; 3444 6.0; 3685 6.0; 3943 6.0; 4219 6.0; 4514 6.0; 4830 6.0; 5168 6.0; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 0.9; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Innerfidelity%202017/headphoncecom/onear/AudioTechnica%20ATH-ESW9A/AudioTechnica%20ATH-ESW9A.png)