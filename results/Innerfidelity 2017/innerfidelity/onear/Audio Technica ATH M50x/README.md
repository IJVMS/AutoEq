# Audio Technica ATH M50x
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 -1.5; 22 -2.0; 23 -2.2; 25 -2.6; 26 -2.8; 28 -3.1; 30 -3.3; 32 -3.5; 35 -3.7; 37 -3.8; 40 -3.8; 42 -3.9; 45 -3.9; 49 -3.8; 52 -3.7; 56 -3.5; 59 -3.4; 64 -3.1; 68 -2.6; 73 -1.7; 78 -0.7; 83 -0.1; 89 0.3; 95 0.1; 102 -1.2; 109 -2.2; 117 -2.9; 125 -3.8; 134 -4.8; 143 -5.2; 153 -4.9; 164 -3.3; 175 -3.7; 188 -4.2; 201 -3.5; 215 -2.8; 230 -1.8; 246 -1.1; 263 -0.3; 282 0.4; 301 0.8; 323 0.8; 345 0.6; 369 0.2; 395 -0.1; 423 -0.4; 452 -0.9; 484 -1.4; 518 -1.7; 554 -1.5; 593 -1.1; 635 -1.1; 679 -1.3; 726 -1.2; 777 -1.0; 832 -0.8; 890 -0.5; 952 -0.1; 1019 0.0; 1090 0.1; 1167 0.3; 1248 -0.1; 1336 -0.8; 1429 -1.1; 1529 -1.6; 1636 -2.1; 1751 -2.8; 1873 -3.0; 2004 -2.8; 2145 -2.4; 2295 -1.8; 2455 -0.6; 2627 0.3; 2811 1.5; 3008 3.1; 3219 3.9; 3444 4.7; 3685 5.1; 3943 4.7; 4219 3.7; 4514 4.4; 4830 5.9; 5168 6.0; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 -1.5; 22 -2.0; 23 -2.2; 25 -2.6; 26 -2.8; 28 -3.1; 30 -3.3; 32 -3.5; 35 -3.7; 37 -3.8; 40 -3.8; 42 -3.9; 45 -3.9; 49 -3.8; 52 -3.7; 56 -3.5; 59 -3.4; 64 -3.1; 68 -2.6; 73 -1.7; 78 -0.7; 83 -0.1; 89 0.3; 95 0.1; 102 -1.2; 109 -2.2; 117 -2.9; 125 -3.8; 134 -4.8; 143 -5.2; 153 -4.9; 164 -3.3; 175 -3.7; 188 -4.2; 201 -3.5; 215 -2.8; 230 -1.8; 246 -1.1; 263 -0.3; 282 0.4; 301 0.8; 323 0.8; 345 0.6; 369 0.2; 395 -0.1; 423 -0.4; 452 -0.9; 484 -1.4; 518 -1.7; 554 -1.5; 593 -1.1; 635 -1.1; 679 -1.3; 726 -1.2; 777 -1.0; 832 -0.8; 890 -0.5; 952 -0.1; 1019 0.0; 1090 0.1; 1167 0.3; 1248 -0.1; 1336 -0.8; 1429 -1.1; 1529 -1.6; 1636 -2.1; 1751 -2.8; 1873 -3.0; 2004 -2.8; 2145 -2.4; 2295 -1.8; 2455 -0.6; 2627 0.3; 2811 1.5; 3008 3.1; 3219 3.9; 3444 4.7; 3685 5.1; 3943 4.7; 4219 3.7; 4514 4.4; 4830 5.9; 5168 6.0; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Innerfidelity%202017/innerfidelity/onear/Audio%20Technica%20ATH%20M50x/Audio%20Technica%20ATH%20M50x.png)