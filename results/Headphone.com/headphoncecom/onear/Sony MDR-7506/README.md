# Sony MDR-7506
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 6.0; 32 6.0; 35 6.0; 37 6.0; 40 6.0; 42 5.9; 45 5.6; 49 5.0; 52 4.5; 56 4.0; 59 3.7; 64 3.7; 68 4.0; 73 4.0; 78 3.6; 83 3.2; 89 2.9; 95 2.6; 102 2.2; 109 1.8; 117 1.5; 125 1.2; 134 1.1; 143 1.1; 153 1.1; 164 1.1; 175 1.2; 188 1.4; 201 1.5; 215 1.6; 230 1.5; 246 1.2; 263 0.6; 282 0.1; 301 -0.2; 323 -1.0; 345 -1.7; 369 -2.3; 395 -2.9; 423 -3.1; 452 -3.0; 484 -3.1; 518 -3.2; 554 -2.7; 593 -2.1; 635 -1.6; 679 -1.6; 726 -1.4; 777 -1.3; 832 -1.0; 890 -0.7; 952 -0.1; 1019 0.0; 1090 0.0; 1167 0.2; 1248 0.4; 1336 0.6; 1429 1.1; 1529 1.2; 1636 1.3; 1751 1.4; 1873 1.4; 2004 1.7; 2145 1.7; 2295 2.0; 2455 1.9; 2627 1.4; 2811 0.8; 3008 0.2; 3219 0.5; 3444 0.3; 3685 1.4; 3943 2.4; 4219 1.4; 4514 0.4; 4830 1.7; 5168 4.7; 5530 6.0; 5917 5.9; 6331 5.1; 6775 1.8; 7249 0.8; 7756 0.3; 8299 -0.2; 8880 -1.9; 9502 -3.1; 10167 -1.6; 10879 -0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 6.0; 32 6.0; 35 6.0; 37 6.0; 40 6.0; 42 5.9; 45 5.6; 49 5.0; 52 4.5; 56 4.0; 59 3.7; 64 3.7; 68 4.0; 73 4.0; 78 3.6; 83 3.2; 89 2.9; 95 2.6; 102 2.2; 109 1.8; 117 1.5; 125 1.2; 134 1.1; 143 1.1; 153 1.1; 164 1.1; 175 1.2; 188 1.4; 201 1.5; 215 1.6; 230 1.5; 246 1.2; 263 0.6; 282 0.1; 301 -0.2; 323 -1.0; 345 -1.7; 369 -2.3; 395 -2.9; 423 -3.1; 452 -3.0; 484 -3.1; 518 -3.2; 554 -2.7; 593 -2.1; 635 -1.6; 679 -1.6; 726 -1.4; 777 -1.3; 832 -1.0; 890 -0.7; 952 -0.1; 1019 0.0; 1090 0.0; 1167 0.2; 1248 0.4; 1336 0.6; 1429 1.1; 1529 1.2; 1636 1.3; 1751 1.4; 1873 1.4; 2004 1.7; 2145 1.7; 2295 2.0; 2455 1.9; 2627 1.4; 2811 0.8; 3008 0.2; 3219 0.5; 3444 0.3; 3685 1.4; 3943 2.4; 4219 1.4; 4514 0.4; 4830 1.7; 5168 4.7; 5530 6.0; 5917 5.9; 6331 5.1; 6775 1.8; 7249 0.8; 7756 0.3; 8299 -0.2; 8880 -1.9; 9502 -3.1; 10167 -1.6; 10879 -0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Headphone.com/headphoncecom/onear/Sony%20MDR-7506/Sony%20MDR-7506.png)