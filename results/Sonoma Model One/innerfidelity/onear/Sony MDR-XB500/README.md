# Sony MDR-XB500
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 -2.3; 22 -2.7; 23 -2.9; 25 -3.3; 26 -3.4; 28 -3.7; 30 -3.9; 32 -4.1; 35 -4.4; 37 -4.5; 40 -4.8; 42 -4.9; 45 -5.2; 49 -5.6; 52 -5.8; 56 -5.9; 59 -5.8; 64 -5.3; 68 -4.9; 73 -4.7; 78 -4.8; 83 -5.2; 89 -5.9; 95 -6.6; 102 -7.8; 109 -8.7; 117 -9.5; 125 -10.4; 134 -11.2; 143 -12.1; 153 -12.5; 164 -12.4; 175 -12.8; 188 -12.9; 201 -13.1; 215 -13.6; 230 -13.6; 246 -13.5; 263 -13.1; 282 -12.6; 301 -12.4; 323 -11.8; 345 -11.1; 369 -10.6; 395 -10.2; 423 -9.5; 452 -8.7; 484 -7.8; 518 -6.9; 554 -5.9; 593 -4.6; 635 -3.1; 679 -1.6; 726 -0.1; 777 1.0; 832 1.5; 890 1.4; 952 0.6; 1019 0.0; 1090 -0.1; 1167 -0.1; 1248 -0.8; 1336 -1.6; 1429 -2.1; 1529 -2.3; 1636 -2.9; 1751 -3.5; 1873 -3.6; 2004 -3.1; 2145 -2.2; 2295 -1.2; 2455 0.2; 2627 1.9; 2811 3.4; 3008 5.0; 3219 6.0; 3444 6.0; 3685 6.0; 3943 4.3; 4219 0.9; 4514 -1.1; 4830 -3.7; 5168 -5.0; 5530 -6.2; 5917 -5.3; 6331 -4.4; 6775 -2.3; 7249 -0.6; 7756 0.2; 8299 0.0; 8880 -0.8; 9502 -2.7; 10167 -2.9; 10879 -0.9; 11640 0.0; 12455 0.0; 13327 0.0; 14260 -0.9; 15258 -1.5; 16326 -0.7; 17469 -0.0; 18692 0.0; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 -2.3; 22 -2.7; 23 -2.9; 25 -3.3; 26 -3.4; 28 -3.7; 30 -3.9; 32 -4.1; 35 -4.4; 37 -4.5; 40 -4.8; 42 -4.9; 45 -5.2; 49 -5.6; 52 -5.8; 56 -5.9; 59 -5.8; 64 -5.3; 68 -4.9; 73 -4.7; 78 -4.8; 83 -5.2; 89 -5.9; 95 -6.6; 102 -7.8; 109 -8.7; 117 -9.5; 125 -10.4; 134 -11.2; 143 -12.1; 153 -12.5; 164 -12.4; 175 -12.8; 188 -12.9; 201 -13.1; 215 -13.6; 230 -13.6; 246 -13.5; 263 -13.1; 282 -12.6; 301 -12.4; 323 -11.8; 345 -11.1; 369 -10.6; 395 -10.2; 423 -9.5; 452 -8.7; 484 -7.8; 518 -6.9; 554 -5.9; 593 -4.6; 635 -3.1; 679 -1.6; 726 -0.1; 777 1.0; 832 1.5; 890 1.4; 952 0.6; 1019 0.0; 1090 -0.1; 1167 -0.1; 1248 -0.8; 1336 -1.6; 1429 -2.1; 1529 -2.3; 1636 -2.9; 1751 -3.5; 1873 -3.6; 2004 -3.1; 2145 -2.2; 2295 -1.2; 2455 0.2; 2627 1.9; 2811 3.4; 3008 5.0; 3219 6.0; 3444 6.0; 3685 6.0; 3943 4.3; 4219 0.9; 4514 -1.1; 4830 -3.7; 5168 -5.0; 5530 -6.2; 5917 -5.3; 6331 -4.4; 6775 -2.3; 7249 -0.6; 7756 0.2; 8299 0.0; 8880 -0.8; 9502 -2.7; 10167 -2.9; 10879 -0.9; 11640 0.0; 12455 0.0; 13327 0.0; 14260 -0.9; 15258 -1.5; 16326 -0.7; 17469 -0.0; 18692 0.0; 20000 0.0
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Sonoma%20Model%20One/innerfidelity/onear/Sony%20MDR-XB500/Sony%20MDR-XB500.png)