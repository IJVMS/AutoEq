# V-Moda Crossfade Wireless Wired Mode
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 2.9; 22 2.1; 23 1.8; 25 1.1; 26 0.8; 28 0.2; 30 -0.3; 32 -0.7; 35 -1.3; 37 -1.7; 40 -2.1; 42 -2.3; 45 -2.6; 49 -2.9; 52 -3.0; 56 -3.2; 59 -3.2; 64 -3.1; 68 -2.7; 73 -2.5; 78 -3.1; 83 -4.2; 89 -4.7; 95 -4.5; 102 -4.2; 109 -4.9; 117 -5.8; 125 -6.3; 134 -6.6; 143 -6.7; 153 -6.7; 164 -5.9; 175 -5.9; 188 -5.7; 201 -5.2; 215 -4.4; 230 -3.4; 246 -2.3; 263 -1.3; 282 0.2; 301 1.3; 323 2.7; 345 4.0; 369 5.6; 395 6.0; 423 6.0; 452 6.0; 484 6.0; 518 6.0; 554 6.0; 593 5.9; 635 5.4; 679 4.5; 726 3.7; 777 3.0; 832 2.1; 890 1.2; 952 0.4; 1019 -0.2; 1090 -0.8; 1167 -1.1; 1248 -1.5; 1336 -2.0; 1429 -2.4; 1529 -2.7; 1636 -2.9; 1751 -2.9; 1873 -2.4; 2004 -2.0; 2145 -2.0; 2295 -2.4; 2455 -2.1; 2627 -1.0; 2811 -1.5; 3008 -2.1; 3219 -3.0; 3444 -4.2; 3685 -3.7; 3943 -1.3; 4219 0.2; 4514 3.5; 4830 5.9; 5168 6.0; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 -1.2; 8880 -3.8; 9502 -4.3; 10167 -3.3; 10879 -1.2; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 2.9; 22 2.1; 23 1.8; 25 1.1; 26 0.8; 28 0.2; 30 -0.3; 32 -0.7; 35 -1.3; 37 -1.7; 40 -2.1; 42 -2.3; 45 -2.6; 49 -2.9; 52 -3.0; 56 -3.2; 59 -3.2; 64 -3.1; 68 -2.7; 73 -2.5; 78 -3.1; 83 -4.2; 89 -4.7; 95 -4.5; 102 -4.2; 109 -4.9; 117 -5.8; 125 -6.3; 134 -6.6; 143 -6.7; 153 -6.7; 164 -5.9; 175 -5.9; 188 -5.7; 201 -5.2; 215 -4.4; 230 -3.4; 246 -2.3; 263 -1.3; 282 0.2; 301 1.3; 323 2.7; 345 4.0; 369 5.6; 395 6.0; 423 6.0; 452 6.0; 484 6.0; 518 6.0; 554 6.0; 593 5.9; 635 5.4; 679 4.5; 726 3.7; 777 3.0; 832 2.1; 890 1.2; 952 0.4; 1019 -0.2; 1090 -0.8; 1167 -1.1; 1248 -1.5; 1336 -2.0; 1429 -2.4; 1529 -2.7; 1636 -2.9; 1751 -2.9; 1873 -2.4; 2004 -2.0; 2145 -2.0; 2295 -2.4; 2455 -2.1; 2627 -1.0; 2811 -1.5; 3008 -2.1; 3219 -3.0; 3444 -4.2; 3685 -3.7; 3943 -1.3; 4219 0.2; 4514 3.5; 4830 5.9; 5168 6.0; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 -1.2; 8880 -3.8; 9502 -4.3; 10167 -3.3; 10879 -1.2; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/SBAF-Serious/innerfidelity/onear/V-Moda%20Crossfade%20Wireless%20Wired%20Mode/V-Moda%20Crossfade%20Wireless%20Wired%20Mode.png)