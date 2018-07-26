# Audio Technica ATH M50x
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 1.8; 22 1.4; 23 1.2; 25 0.8; 26 0.7; 28 0.4; 30 0.2; 32 -0.0; 35 -0.3; 37 -0.4; 40 -0.5; 42 -0.7; 45 -0.8; 49 -1.0; 52 -1.0; 56 -1.0; 59 -0.8; 64 -0.3; 68 0.6; 73 1.9; 78 3.2; 83 3.8; 89 3.7; 95 2.9; 102 1.2; 109 -0.1; 117 -0.9; 125 -2.1; 134 -3.3; 143 -4.0; 153 -3.9; 164 -2.4; 175 -2.9; 188 -3.3; 201 -2.6; 215 -1.9; 230 -1.0; 246 -0.2; 263 0.6; 282 1.3; 301 1.8; 323 1.9; 345 1.7; 369 1.4; 395 1.1; 423 0.9; 452 0.7; 484 0.5; 518 0.1; 554 -0.1; 593 -0.1; 635 0.1; 679 0.3; 726 0.5; 777 0.7; 832 0.5; 890 0.2; 952 0.1; 1019 0.1; 1090 0.7; 1167 1.7; 1248 2.0; 1336 1.8; 1429 1.6; 1529 1.1; 1636 0.0; 1751 -1.2; 1873 -1.9; 2004 -1.8; 2145 -1.4; 2295 -0.8; 2455 0.4; 2627 1.4; 2811 2.5; 3008 4.0; 3219 4.5; 3444 4.9; 3685 4.2; 3943 2.3; 4219 0.0; 4514 0.7; 4830 3.7; 5168 5.9; 5530 6.0; 5917 5.0; 6331 4.2; 6775 3.8; 7249 1.3; 7756 0.3; 8299 0.0; 8880 -0.4; 9502 -1.7; 10167 -2.1; 10879 -1.3; 11640 -0.1; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 -0.9; 18692 -0.8; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 1.8; 22 1.4; 23 1.2; 25 0.8; 26 0.7; 28 0.4; 30 0.2; 32 -0.0; 35 -0.3; 37 -0.4; 40 -0.5; 42 -0.7; 45 -0.8; 49 -1.0; 52 -1.0; 56 -1.0; 59 -0.8; 64 -0.3; 68 0.6; 73 1.9; 78 3.2; 83 3.8; 89 3.7; 95 2.9; 102 1.2; 109 -0.1; 117 -0.9; 125 -2.1; 134 -3.3; 143 -4.0; 153 -3.9; 164 -2.4; 175 -2.9; 188 -3.3; 201 -2.6; 215 -1.9; 230 -1.0; 246 -0.2; 263 0.6; 282 1.3; 301 1.8; 323 1.9; 345 1.7; 369 1.4; 395 1.1; 423 0.9; 452 0.7; 484 0.5; 518 0.1; 554 -0.1; 593 -0.1; 635 0.1; 679 0.3; 726 0.5; 777 0.7; 832 0.5; 890 0.2; 952 0.1; 1019 0.1; 1090 0.7; 1167 1.7; 1248 2.0; 1336 1.8; 1429 1.6; 1529 1.1; 1636 0.0; 1751 -1.2; 1873 -1.9; 2004 -1.8; 2145 -1.4; 2295 -0.8; 2455 0.4; 2627 1.4; 2811 2.5; 3008 4.0; 3219 4.5; 3444 4.9; 3685 4.2; 3943 2.3; 4219 0.0; 4514 0.7; 4830 3.7; 5168 5.9; 5530 6.0; 5917 5.0; 6331 4.2; 6775 3.8; 7249 1.3; 7756 0.3; 8299 0.0; 8880 -0.4; 9502 -1.7; 10167 -2.1; 10879 -1.3; 11640 -0.1; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 -0.9; 18692 -0.8; 20000 0.0
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Sonoma%20Model%20One/innerfidelity/onear/Audio%20Technica%20ATH%20M50x/Audio%20Technica%20ATH%20M50x.png)