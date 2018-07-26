# Monster Beats Studio
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 6.0; 22 5.6; 23 4.9; 25 2.7; 26 1.3; 28 -1.8; 30 -4.4; 32 -6.0; 35 -7.1; 37 -7.3; 40 -7.3; 42 -7.1; 45 -6.8; 49 -6.4; 52 -6.2; 56 -6.0; 59 -5.9; 64 -5.6; 68 -5.4; 73 -5.2; 78 -5.4; 83 -5.9; 89 -6.4; 95 -7.0; 102 -7.5; 109 -8.0; 117 -8.3; 125 -8.7; 134 -8.9; 143 -9.2; 153 -9.2; 164 -9.1; 175 -9.3; 188 -9.3; 201 -9.1; 215 -9.2; 230 -9.0; 246 -8.9; 263 -8.7; 282 -8.5; 301 -8.4; 323 -8.4; 345 -8.1; 369 -7.7; 395 -7.8; 423 -7.6; 452 -7.2; 484 -6.5; 518 -6.0; 554 -5.4; 593 -4.4; 635 -2.8; 679 -1.7; 726 -0.5; 777 0.3; 832 0.8; 890 0.9; 952 0.5; 1019 -0.2; 1090 -0.9; 1167 -1.9; 1248 -2.8; 1336 -3.5; 1429 -3.5; 1529 -3.7; 1636 -4.1; 1751 -4.3; 1873 -4.1; 2004 -3.5; 2145 -2.7; 2295 -1.8; 2455 -0.7; 2627 0.7; 2811 1.8; 3008 2.9; 3219 4.2; 3444 4.1; 3685 1.2; 3943 1.3; 4219 1.9; 4514 -1.2; 4830 0.5; 5168 4.6; 5530 1.8; 5917 0.9; 6331 0.8; 6775 0.1; 7249 -1.9; 7756 -4.7; 8299 -7.1; 8880 -7.7; 9502 -5.7; 10167 -1.8; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 6.0; 22 5.6; 23 4.9; 25 2.7; 26 1.3; 28 -1.8; 30 -4.4; 32 -6.0; 35 -7.1; 37 -7.3; 40 -7.3; 42 -7.1; 45 -6.8; 49 -6.4; 52 -6.2; 56 -6.0; 59 -5.9; 64 -5.6; 68 -5.4; 73 -5.2; 78 -5.4; 83 -5.9; 89 -6.4; 95 -7.0; 102 -7.5; 109 -8.0; 117 -8.3; 125 -8.7; 134 -8.9; 143 -9.2; 153 -9.2; 164 -9.1; 175 -9.3; 188 -9.3; 201 -9.1; 215 -9.2; 230 -9.0; 246 -8.9; 263 -8.7; 282 -8.5; 301 -8.4; 323 -8.4; 345 -8.1; 369 -7.7; 395 -7.8; 423 -7.6; 452 -7.2; 484 -6.5; 518 -6.0; 554 -5.4; 593 -4.4; 635 -2.8; 679 -1.7; 726 -0.5; 777 0.3; 832 0.8; 890 0.9; 952 0.5; 1019 -0.2; 1090 -0.9; 1167 -1.9; 1248 -2.8; 1336 -3.5; 1429 -3.5; 1529 -3.7; 1636 -4.1; 1751 -4.3; 1873 -4.1; 2004 -3.5; 2145 -2.7; 2295 -1.8; 2455 -0.7; 2627 0.7; 2811 1.8; 3008 2.9; 3219 4.2; 3444 4.1; 3685 1.2; 3943 1.3; 4219 1.9; 4514 -1.2; 4830 0.5; 5168 4.6; 5530 1.8; 5917 0.9; 6331 0.8; 6775 0.1; 7249 -1.9; 7756 -4.7; 8299 -7.1; 8880 -7.7; 9502 -5.7; 10167 -1.8; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Headphone.com/innerfidelity/onear/Monster%20Beats%20Studio/Monster%20Beats%20Studio.png)