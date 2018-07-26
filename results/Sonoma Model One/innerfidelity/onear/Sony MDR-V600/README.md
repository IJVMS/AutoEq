# Sony MDR-V600
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 6.0; 32 6.0; 35 6.0; 37 6.0; 40 6.0; 42 6.0; 45 6.0; 49 6.0; 52 5.6; 56 4.9; 59 4.5; 64 4.3; 68 4.6; 73 4.6; 78 4.1; 83 3.4; 89 2.4; 95 1.6; 102 1.3; 109 1.5; 117 1.1; 125 -0.3; 134 -1.5; 143 -2.5; 153 -3.3; 164 -3.1; 175 -3.1; 188 -3.2; 201 -3.8; 215 -4.2; 230 -4.3; 246 -4.5; 263 -4.5; 282 -4.3; 301 -4.1; 323 -3.9; 345 -3.7; 369 -3.6; 395 -3.8; 423 -4.0; 452 -3.9; 484 -3.1; 518 -2.6; 554 -2.8; 593 -2.2; 635 -0.7; 679 -0.3; 726 -0.4; 777 -0.0; 832 -0.1; 890 -0.3; 952 -0.3; 1019 0.2; 1090 1.2; 1167 2.5; 1248 3.8; 1336 4.7; 1429 4.9; 1529 4.5; 1636 3.6; 1751 2.9; 1873 2.9; 2004 3.7; 2145 4.8; 2295 5.7; 2455 6.0; 2627 6.0; 2811 6.0; 3008 6.0; 3219 6.0; 3444 5.9; 3685 4.8; 3943 4.1; 4219 2.0; 4514 2.8; 4830 4.7; 5168 6.0; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 -0.0; 8880 -2.1; 9502 -4.1; 10167 -3.1; 10879 -0.1; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 6.0; 32 6.0; 35 6.0; 37 6.0; 40 6.0; 42 6.0; 45 6.0; 49 6.0; 52 5.6; 56 4.9; 59 4.5; 64 4.3; 68 4.6; 73 4.6; 78 4.1; 83 3.4; 89 2.4; 95 1.6; 102 1.3; 109 1.5; 117 1.1; 125 -0.3; 134 -1.5; 143 -2.5; 153 -3.3; 164 -3.1; 175 -3.1; 188 -3.2; 201 -3.8; 215 -4.2; 230 -4.3; 246 -4.5; 263 -4.5; 282 -4.3; 301 -4.1; 323 -3.9; 345 -3.7; 369 -3.6; 395 -3.8; 423 -4.0; 452 -3.9; 484 -3.1; 518 -2.6; 554 -2.8; 593 -2.2; 635 -0.7; 679 -0.3; 726 -0.4; 777 -0.0; 832 -0.1; 890 -0.3; 952 -0.3; 1019 0.2; 1090 1.2; 1167 2.5; 1248 3.8; 1336 4.7; 1429 4.9; 1529 4.5; 1636 3.6; 1751 2.9; 1873 2.9; 2004 3.7; 2145 4.8; 2295 5.7; 2455 6.0; 2627 6.0; 2811 6.0; 3008 6.0; 3219 6.0; 3444 5.9; 3685 4.8; 3943 4.1; 4219 2.0; 4514 2.8; 4830 4.7; 5168 6.0; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 -0.0; 8880 -2.1; 9502 -4.1; 10167 -3.1; 10879 -0.1; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Sonoma%20Model%20One/innerfidelity/onear/Sony%20MDR-V600/Sony%20MDR-V600.png)