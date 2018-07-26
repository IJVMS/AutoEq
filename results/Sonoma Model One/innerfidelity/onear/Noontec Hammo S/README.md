# Noontec Hammo S
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 3.4; 22 3.2; 23 3.2; 25 3.0; 26 3.0; 28 2.8; 30 2.8; 32 2.7; 35 2.5; 37 2.4; 40 2.2; 42 2.2; 45 2.0; 49 1.7; 52 1.5; 56 1.3; 59 1.4; 64 1.7; 68 2.0; 73 2.5; 78 2.9; 83 2.7; 89 2.3; 95 1.8; 102 1.4; 109 1.2; 117 0.8; 125 -0.3; 134 -1.6; 143 -2.6; 153 -3.3; 164 -2.7; 175 -2.5; 188 -3.3; 201 -3.3; 215 -3.2; 230 -3.0; 246 -2.6; 263 -2.2; 282 -1.7; 301 -1.2; 323 -0.7; 345 -0.0; 369 0.3; 395 0.8; 423 1.4; 452 1.5; 484 1.9; 518 2.0; 554 1.8; 593 1.5; 635 1.3; 679 1.2; 726 1.5; 777 1.8; 832 1.8; 890 1.3; 952 0.8; 1019 -0.1; 1090 -0.2; 1167 0.1; 1248 0.3; 1336 0.5; 1429 0.5; 1529 0.5; 1636 -0.0; 1751 -0.6; 1873 -1.0; 2004 -0.5; 2145 0.2; 2295 1.0; 2455 2.3; 2627 3.3; 2811 4.1; 3008 4.7; 3219 4.2; 3444 1.9; 3685 -0.1; 3943 1.2; 4219 0.4; 4514 1.1; 4830 4.1; 5168 5.5; 5530 5.5; 5917 4.5; 6331 5.3; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 -1.6; 9502 -3.2; 10167 -3.5; 10879 -1.5; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 3.4; 22 3.2; 23 3.2; 25 3.0; 26 3.0; 28 2.8; 30 2.8; 32 2.7; 35 2.5; 37 2.4; 40 2.2; 42 2.2; 45 2.0; 49 1.7; 52 1.5; 56 1.3; 59 1.4; 64 1.7; 68 2.0; 73 2.5; 78 2.9; 83 2.7; 89 2.3; 95 1.8; 102 1.4; 109 1.2; 117 0.8; 125 -0.3; 134 -1.6; 143 -2.6; 153 -3.3; 164 -2.7; 175 -2.5; 188 -3.3; 201 -3.3; 215 -3.2; 230 -3.0; 246 -2.6; 263 -2.2; 282 -1.7; 301 -1.2; 323 -0.7; 345 -0.0; 369 0.3; 395 0.8; 423 1.4; 452 1.5; 484 1.9; 518 2.0; 554 1.8; 593 1.5; 635 1.3; 679 1.2; 726 1.5; 777 1.8; 832 1.8; 890 1.3; 952 0.8; 1019 -0.1; 1090 -0.2; 1167 0.1; 1248 0.3; 1336 0.5; 1429 0.5; 1529 0.5; 1636 -0.0; 1751 -0.6; 1873 -1.0; 2004 -0.5; 2145 0.2; 2295 1.0; 2455 2.3; 2627 3.3; 2811 4.1; 3008 4.7; 3219 4.2; 3444 1.9; 3685 -0.1; 3943 1.2; 4219 0.4; 4514 1.1; 4830 4.1; 5168 5.5; 5530 5.5; 5917 4.5; 6331 5.3; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 -1.6; 9502 -3.2; 10167 -3.5; 10879 -1.5; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Sonoma%20Model%20One/innerfidelity/onear/Noontec%20Hammo%20S/Noontec%20Hammo%20S.png)