# Audeze SINE
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 4.5; 22 3.7; 23 3.4; 25 2.8; 26 2.6; 28 2.1; 30 1.7; 32 1.4; 35 1.0; 37 0.8; 40 0.6; 42 0.5; 45 0.4; 49 0.2; 52 0.1; 56 0.0; 59 0.0; 64 -0.0; 68 -0.1; 73 -0.2; 78 -0.4; 83 -0.6; 89 -0.9; 95 -1.4; 102 -1.9; 109 -2.3; 117 -2.8; 125 -3.3; 134 -3.5; 143 -3.7; 153 -3.9; 164 -3.9; 175 -4.0; 188 -4.1; 201 -4.1; 215 -4.0; 230 -3.9; 246 -3.7; 263 -3.5; 282 -3.5; 301 -3.6; 323 -3.5; 345 -3.5; 369 -3.3; 395 -3.1; 423 -2.9; 452 -2.6; 484 -2.2; 518 -1.7; 554 -1.3; 593 -0.9; 635 -0.4; 679 0.1; 726 0.4; 777 0.3; 832 0.3; 890 0.4; 952 0.1; 1019 -0.0; 1090 0.4; 1167 0.5; 1248 0.4; 1336 0.4; 1429 0.8; 1529 1.1; 1636 0.9; 1751 0.6; 1873 0.5; 2004 0.6; 2145 0.7; 2295 1.2; 2455 1.9; 2627 1.6; 2811 1.4; 3008 1.1; 3219 1.4; 3444 1.2; 3685 1.1; 3943 2.7; 4219 4.5; 4514 5.9; 4830 6.0; 5168 6.0; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 4.5; 22 3.7; 23 3.4; 25 2.8; 26 2.6; 28 2.1; 30 1.7; 32 1.4; 35 1.0; 37 0.8; 40 0.6; 42 0.5; 45 0.4; 49 0.2; 52 0.1; 56 0.0; 59 0.0; 64 -0.0; 68 -0.1; 73 -0.2; 78 -0.4; 83 -0.6; 89 -0.9; 95 -1.4; 102 -1.9; 109 -2.3; 117 -2.8; 125 -3.3; 134 -3.5; 143 -3.7; 153 -3.9; 164 -3.9; 175 -4.0; 188 -4.1; 201 -4.1; 215 -4.0; 230 -3.9; 246 -3.7; 263 -3.5; 282 -3.5; 301 -3.6; 323 -3.5; 345 -3.5; 369 -3.3; 395 -3.1; 423 -2.9; 452 -2.6; 484 -2.2; 518 -1.7; 554 -1.3; 593 -0.9; 635 -0.4; 679 0.1; 726 0.4; 777 0.3; 832 0.3; 890 0.4; 952 0.1; 1019 -0.0; 1090 0.4; 1167 0.5; 1248 0.4; 1336 0.4; 1429 0.8; 1529 1.1; 1636 0.9; 1751 0.6; 1873 0.5; 2004 0.6; 2145 0.7; 2295 1.2; 2455 1.9; 2627 1.6; 2811 1.4; 3008 1.1; 3219 1.4; 3444 1.2; 3685 1.1; 3943 2.7; 4219 4.5; 4514 5.9; 4830 6.0; 5168 6.0; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Headphone.com/innerfidelity/onear/Audeze%20SINE/Audeze%20SINE.png)