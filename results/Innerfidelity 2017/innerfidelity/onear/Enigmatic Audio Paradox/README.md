# Enigmatic Audio Paradox
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 3.4; 22 3.1; 23 2.9; 25 2.6; 26 2.5; 28 2.3; 30 2.1; 32 2.0; 35 1.8; 37 1.7; 40 1.7; 42 1.7; 45 1.7; 49 1.7; 52 1.6; 56 1.4; 59 1.1; 64 0.9; 68 0.9; 73 0.9; 78 1.0; 83 1.0; 89 0.6; 95 -0.2; 102 -1.5; 109 -2.6; 117 -3.4; 125 -4.2; 134 -4.5; 143 -4.7; 153 -4.7; 164 -4.1; 175 -4.8; 188 -5.2; 201 -5.2; 215 -5.1; 230 -5.0; 246 -5.0; 263 -4.9; 282 -4.6; 301 -4.4; 323 -4.2; 345 -3.3; 369 -1.9; 395 -1.5; 423 -1.3; 452 -1.3; 484 -1.4; 518 -1.3; 554 -0.7; 593 -0.1; 635 1.1; 679 1.4; 726 1.0; 777 1.1; 832 1.3; 890 0.9; 952 0.3; 1019 -0.2; 1090 -0.4; 1167 -0.6; 1248 -0.5; 1336 -0.4; 1429 -0.0; 1529 0.4; 1636 1.0; 1751 1.1; 1873 1.5; 2004 2.2; 2145 3.1; 2295 4.0; 2455 4.9; 2627 5.6; 2811 6.0; 3008 6.0; 3219 6.0; 3444 5.8; 3685 5.7; 3943 6.0; 4219 6.0; 4514 6.0; 4830 6.0; 5168 6.0; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 -0.3; 8880 -2.1; 9502 -1.4; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 3.4; 22 3.1; 23 2.9; 25 2.6; 26 2.5; 28 2.3; 30 2.1; 32 2.0; 35 1.8; 37 1.7; 40 1.7; 42 1.7; 45 1.7; 49 1.7; 52 1.6; 56 1.4; 59 1.1; 64 0.9; 68 0.9; 73 0.9; 78 1.0; 83 1.0; 89 0.6; 95 -0.2; 102 -1.5; 109 -2.6; 117 -3.4; 125 -4.2; 134 -4.5; 143 -4.7; 153 -4.7; 164 -4.1; 175 -4.8; 188 -5.2; 201 -5.2; 215 -5.1; 230 -5.0; 246 -5.0; 263 -4.9; 282 -4.6; 301 -4.4; 323 -4.2; 345 -3.3; 369 -1.9; 395 -1.5; 423 -1.3; 452 -1.3; 484 -1.4; 518 -1.3; 554 -0.7; 593 -0.1; 635 1.1; 679 1.4; 726 1.0; 777 1.1; 832 1.3; 890 0.9; 952 0.3; 1019 -0.2; 1090 -0.4; 1167 -0.6; 1248 -0.5; 1336 -0.4; 1429 -0.0; 1529 0.4; 1636 1.0; 1751 1.1; 1873 1.5; 2004 2.2; 2145 3.1; 2295 4.0; 2455 4.9; 2627 5.6; 2811 6.0; 3008 6.0; 3219 6.0; 3444 5.8; 3685 5.7; 3943 6.0; 4219 6.0; 4514 6.0; 4830 6.0; 5168 6.0; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 -0.3; 8880 -2.1; 9502 -1.4; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Innerfidelity%202017/innerfidelity/onear/Enigmatic%20Audio%20Paradox/Enigmatic%20Audio%20Paradox.png)