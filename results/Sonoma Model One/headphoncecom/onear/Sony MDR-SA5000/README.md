# Sony MDR-SA5000
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 6.0; 32 6.0; 35 6.0; 37 6.0; 40 6.0; 42 6.0; 45 6.0; 49 6.0; 52 6.0; 56 6.0; 59 6.0; 64 6.0; 68 6.0; 73 6.0; 78 6.0; 83 6.0; 89 6.0; 95 6.0; 102 6.0; 109 5.7; 117 5.3; 125 4.8; 134 4.5; 143 4.2; 153 4.0; 164 4.2; 175 4.2; 188 4.3; 201 4.3; 215 4.4; 230 4.4; 246 4.5; 263 4.6; 282 4.8; 301 5.0; 323 5.1; 345 4.0; 369 4.0; 395 4.1; 423 4.2; 452 4.1; 484 3.8; 518 3.4; 554 2.8; 593 2.4; 635 2.4; 679 2.4; 726 2.3; 777 2.0; 832 1.3; 890 0.4; 952 -0.1; 1019 0.2; 1090 1.9; 1167 4.1; 1248 5.7; 1336 6.0; 1429 6.0; 1529 6.0; 1636 6.0; 1751 4.7; 1873 3.4; 2004 2.2; 2145 1.5; 2295 0.6; 2455 -1.9; 2627 -4.7; 2811 -5.7; 3008 -3.6; 3219 -2.0; 3444 -0.5; 3685 2.4; 3943 1.7; 4219 -2.0; 4514 -1.5; 4830 2.2; 5168 6.0; 5530 6.0; 5917 5.9; 6331 4.7; 6775 1.1; 7249 -2.0; 7756 -4.3; 8299 -5.3; 8880 -6.0; 9502 -6.4; 10167 -5.0; 10879 -1.9; 11640 -0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 -1.3
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 6.0; 32 6.0; 35 6.0; 37 6.0; 40 6.0; 42 6.0; 45 6.0; 49 6.0; 52 6.0; 56 6.0; 59 6.0; 64 6.0; 68 6.0; 73 6.0; 78 6.0; 83 6.0; 89 6.0; 95 6.0; 102 6.0; 109 5.7; 117 5.3; 125 4.8; 134 4.5; 143 4.2; 153 4.0; 164 4.2; 175 4.2; 188 4.3; 201 4.3; 215 4.4; 230 4.4; 246 4.5; 263 4.6; 282 4.8; 301 5.0; 323 5.1; 345 4.0; 369 4.0; 395 4.1; 423 4.2; 452 4.1; 484 3.8; 518 3.4; 554 2.8; 593 2.4; 635 2.4; 679 2.4; 726 2.3; 777 2.0; 832 1.3; 890 0.4; 952 -0.1; 1019 0.2; 1090 1.9; 1167 4.1; 1248 5.7; 1336 6.0; 1429 6.0; 1529 6.0; 1636 6.0; 1751 4.7; 1873 3.4; 2004 2.2; 2145 1.5; 2295 0.6; 2455 -1.9; 2627 -4.7; 2811 -5.7; 3008 -3.6; 3219 -2.0; 3444 -0.5; 3685 2.4; 3943 1.7; 4219 -2.0; 4514 -1.5; 4830 2.2; 5168 6.0; 5530 6.0; 5917 5.9; 6331 4.7; 6775 1.1; 7249 -2.0; 7756 -4.3; 8299 -5.3; 8880 -6.0; 9502 -6.4; 10167 -5.0; 10879 -1.9; 11640 -0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 -1.3
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Sonoma%20Model%20One/headphoncecom/onear/Sony%20MDR-SA5000/Sony%20MDR-SA5000.png)