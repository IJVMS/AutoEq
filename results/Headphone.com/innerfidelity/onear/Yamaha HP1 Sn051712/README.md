# Yamaha HP1 Sn051712
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 4.9; 22 4.7; 23 4.5; 25 4.2; 26 4.0; 28 3.6; 30 3.3; 32 3.1; 35 2.8; 37 2.6; 40 2.4; 42 2.2; 45 2.1; 49 1.8; 52 1.7; 56 1.6; 59 1.6; 64 1.7; 68 1.6; 73 1.4; 78 1.4; 83 1.2; 89 0.9; 95 0.5; 102 -0.3; 109 -0.8; 117 -1.2; 125 -1.7; 134 -2.0; 143 -2.3; 153 -2.5; 164 -2.5; 175 -2.6; 188 -2.7; 201 -2.8; 215 -2.8; 230 -2.8; 246 -2.7; 263 -2.6; 282 -2.4; 301 -2.4; 323 -2.6; 345 -2.6; 369 -2.5; 395 -2.5; 423 -2.4; 452 -2.1; 484 -2.0; 518 -1.9; 554 -1.9; 593 -1.8; 635 -1.6; 679 -1.5; 726 -1.4; 777 -1.3; 832 -1.1; 890 -0.6; 952 -0.2; 1019 0.2; 1090 0.9; 1167 1.9; 1248 3.2; 1336 4.3; 1429 5.3; 1529 5.9; 1636 6.0; 1751 6.0; 1873 5.9; 2004 5.3; 2145 4.4; 2295 3.7; 2455 3.9; 2627 4.6; 2811 5.0; 3008 5.2; 3219 5.9; 3444 6.0; 3685 6.0; 3943 6.0; 4219 6.0; 4514 6.0; 4830 6.0; 5168 6.0; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 4.9; 22 4.7; 23 4.5; 25 4.2; 26 4.0; 28 3.6; 30 3.3; 32 3.1; 35 2.8; 37 2.6; 40 2.4; 42 2.2; 45 2.1; 49 1.8; 52 1.7; 56 1.6; 59 1.6; 64 1.7; 68 1.6; 73 1.4; 78 1.4; 83 1.2; 89 0.9; 95 0.5; 102 -0.3; 109 -0.8; 117 -1.2; 125 -1.7; 134 -2.0; 143 -2.3; 153 -2.5; 164 -2.5; 175 -2.6; 188 -2.7; 201 -2.8; 215 -2.8; 230 -2.8; 246 -2.7; 263 -2.6; 282 -2.4; 301 -2.4; 323 -2.6; 345 -2.6; 369 -2.5; 395 -2.5; 423 -2.4; 452 -2.1; 484 -2.0; 518 -1.9; 554 -1.9; 593 -1.8; 635 -1.6; 679 -1.5; 726 -1.4; 777 -1.3; 832 -1.1; 890 -0.6; 952 -0.2; 1019 0.2; 1090 0.9; 1167 1.9; 1248 3.2; 1336 4.3; 1429 5.3; 1529 5.9; 1636 6.0; 1751 6.0; 1873 5.9; 2004 5.3; 2145 4.4; 2295 3.7; 2455 3.9; 2627 4.6; 2811 5.0; 3008 5.2; 3219 5.9; 3444 6.0; 3685 6.0; 3943 6.0; 4219 6.0; 4514 6.0; 4830 6.0; 5168 6.0; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Headphone.com/innerfidelity/onear/Yamaha%20HP1%20Sn051712/Yamaha%20HP1%20Sn051712.png)