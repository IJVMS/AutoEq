# beyerdynamic DT880 - 600 Ohm
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 5.9; 32 5.7; 35 5.5; 37 5.3; 40 5.0; 42 4.8; 45 4.4; 49 3.9; 52 3.6; 56 3.4; 59 3.3; 64 3.4; 68 3.6; 73 4.0; 78 4.6; 83 4.9; 89 4.0; 95 2.5; 102 1.3; 109 0.6; 117 -0.2; 125 -0.9; 134 -1.7; 143 -2.2; 153 -2.6; 164 -2.8; 175 -2.9; 188 -3.0; 201 -3.1; 215 -3.1; 230 -3.1; 246 -3.1; 263 -3.1; 282 -3.1; 301 -3.0; 323 -2.8; 345 -2.6; 369 -2.6; 395 -2.4; 423 -2.1; 452 -1.8; 484 -1.3; 518 -1.1; 554 -1.3; 593 -1.0; 635 -0.4; 679 0.2; 726 0.9; 777 1.5; 832 1.3; 890 0.6; 952 0.2; 1019 0.2; 1090 1.2; 1167 2.0; 1248 2.8; 1336 3.2; 1429 3.2; 1529 3.0; 1636 2.3; 1751 1.1; 1873 0.1; 2004 0.1; 2145 0.6; 2295 1.3; 2455 1.6; 2627 1.4; 2811 1.3; 3008 1.6; 3219 1.8; 3444 2.5; 3685 2.5; 3943 2.0; 4219 0.9; 4514 0.2; 4830 0.6; 5168 -0.3; 5530 -4.4; 5917 -6.9; 6331 -5.7; 6775 -2.4; 7249 -2.3; 7756 -5.0; 8299 -8.3; 8880 -10.1; 9502 -9.8; 10167 -7.9; 10879 -4.9; 11640 -1.4; 12455 0.0; 13327 0.0; 14260 0.0; 15258 -0.1; 16326 -2.3; 17469 -4.9; 18692 -5.0; 20000 -0.7
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 5.9; 32 5.7; 35 5.5; 37 5.3; 40 5.0; 42 4.8; 45 4.4; 49 3.9; 52 3.6; 56 3.4; 59 3.3; 64 3.4; 68 3.6; 73 4.0; 78 4.6; 83 4.9; 89 4.0; 95 2.5; 102 1.3; 109 0.6; 117 -0.2; 125 -0.9; 134 -1.7; 143 -2.2; 153 -2.6; 164 -2.8; 175 -2.9; 188 -3.0; 201 -3.1; 215 -3.1; 230 -3.1; 246 -3.1; 263 -3.1; 282 -3.1; 301 -3.0; 323 -2.8; 345 -2.6; 369 -2.6; 395 -2.4; 423 -2.1; 452 -1.8; 484 -1.3; 518 -1.1; 554 -1.3; 593 -1.0; 635 -0.4; 679 0.2; 726 0.9; 777 1.5; 832 1.3; 890 0.6; 952 0.2; 1019 0.2; 1090 1.2; 1167 2.0; 1248 2.8; 1336 3.2; 1429 3.2; 1529 3.0; 1636 2.3; 1751 1.1; 1873 0.1; 2004 0.1; 2145 0.6; 2295 1.3; 2455 1.6; 2627 1.4; 2811 1.3; 3008 1.6; 3219 1.8; 3444 2.5; 3685 2.5; 3943 2.0; 4219 0.9; 4514 0.2; 4830 0.6; 5168 -0.3; 5530 -4.4; 5917 -6.9; 6331 -5.7; 6775 -2.4; 7249 -2.3; 7756 -5.0; 8299 -8.3; 8880 -10.1; 9502 -9.8; 10167 -7.9; 10879 -4.9; 11640 -1.4; 12455 0.0; 13327 0.0; 14260 0.0; 15258 -0.1; 16326 -2.3; 17469 -4.9; 18692 -5.0; 20000 -0.7
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Sonoma%20Model%20One/headphoncecom/onear/beyerdynamic%20DT880%20-%20600%20Ohm/beyerdynamic%20DT880%20-%20600%20Ohm.png)