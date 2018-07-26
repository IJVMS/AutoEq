# Sony MDR-7505
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 6.0; 32 6.0; 35 6.0; 37 6.0; 40 6.0; 42 6.0; 45 6.0; 49 6.0; 52 6.0; 56 6.0; 59 6.0; 64 6.0; 68 6.0; 73 6.0; 78 6.0; 83 6.0; 89 6.0; 95 5.8; 102 5.1; 109 4.8; 117 4.6; 125 4.5; 134 4.0; 143 3.3; 153 2.7; 164 2.6; 175 2.6; 188 2.4; 201 2.4; 215 2.5; 230 2.5; 246 2.5; 263 2.7; 282 3.0; 301 2.7; 323 2.4; 345 2.0; 369 1.7; 395 1.6; 423 1.8; 452 1.6; 484 0.9; 518 0.5; 554 0.4; 593 0.2; 635 -0.1; 679 -0.6; 726 0.2; 777 1.5; 832 0.8; 890 0.2; 952 -0.0; 1019 -0.1; 1090 0.4; 1167 0.6; 1248 0.9; 1336 1.2; 1429 1.4; 1529 1.6; 1636 2.2; 1751 2.4; 1873 2.8; 2004 3.2; 2145 3.5; 2295 3.5; 2455 3.6; 2627 4.1; 2811 3.5; 3008 3.1; 3219 2.7; 3444 2.7; 3685 2.7; 3943 2.7; 4219 2.0; 4514 2.0; 4830 3.1; 5168 5.2; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 6.0; 32 6.0; 35 6.0; 37 6.0; 40 6.0; 42 6.0; 45 6.0; 49 6.0; 52 6.0; 56 6.0; 59 6.0; 64 6.0; 68 6.0; 73 6.0; 78 6.0; 83 6.0; 89 6.0; 95 5.8; 102 5.1; 109 4.8; 117 4.6; 125 4.5; 134 4.0; 143 3.3; 153 2.7; 164 2.6; 175 2.6; 188 2.4; 201 2.4; 215 2.5; 230 2.5; 246 2.5; 263 2.7; 282 3.0; 301 2.7; 323 2.4; 345 2.0; 369 1.7; 395 1.6; 423 1.8; 452 1.6; 484 0.9; 518 0.5; 554 0.4; 593 0.2; 635 -0.1; 679 -0.6; 726 0.2; 777 1.5; 832 0.8; 890 0.2; 952 -0.0; 1019 -0.1; 1090 0.4; 1167 0.6; 1248 0.9; 1336 1.2; 1429 1.4; 1529 1.6; 1636 2.2; 1751 2.4; 1873 2.8; 2004 3.2; 2145 3.5; 2295 3.5; 2455 3.6; 2627 4.1; 2811 3.5; 3008 3.1; 3219 2.7; 3444 2.7; 3685 2.7; 3943 2.7; 4219 2.0; 4514 2.0; 4830 3.1; 5168 5.2; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/SBAF-Serious/innerfidelity/onear/Sony%20MDR-7505/Sony%20MDR-7505.png)