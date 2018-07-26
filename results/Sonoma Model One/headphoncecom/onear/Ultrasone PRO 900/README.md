# Ultrasone PRO 900
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-55**.
```
GraphicEQ: 10 -84; 20 5.5; 22 4.7; 23 4.3; 25 3.6; 26 3.3; 28 2.7; 30 2.1; 32 1.6; 35 0.9; 37 0.5; 40 -0.0; 42 -0.2; 45 -0.3; 49 -0.3; 52 -0.6; 56 -1.1; 59 -1.2; 64 -1.2; 68 -1.4; 73 -1.4; 78 -1.5; 83 -2.0; 89 -2.8; 95 -3.8; 102 -4.7; 109 -5.4; 117 -5.9; 125 -6.3; 134 -6.8; 143 -7.0; 153 -7.1; 164 -6.7; 175 -6.5; 188 -6.1; 201 -5.2; 215 -3.8; 230 -2.7; 246 -1.1; 263 0.9; 282 2.2; 301 1.0; 323 -1.2; 345 -2.4; 369 -3.1; 395 -3.6; 423 -3.4; 452 -3.0; 484 -2.0; 518 0.8; 554 0.3; 593 -0.5; 635 -1.2; 679 -0.7; 726 -0.2; 777 0.1; 832 -0.0; 890 -0.2; 952 -0.2; 1019 0.2; 1090 1.2; 1167 2.6; 1248 3.3; 1336 2.7; 1429 2.5; 1529 2.0; 1636 0.9; 1751 -0.3; 1873 -0.5; 2004 0.6; 2145 2.7; 2295 1.4; 2455 -1.4; 2627 -3.2; 2811 -3.7; 3008 -3.9; 3219 -4.3; 3444 -4.9; 3685 -6.2; 3943 -7.1; 4219 -8.2; 4514 -8.3; 4830 -7.8; 5168 -7.0; 5530 -10.1; 5917 -11.4; 6331 -10.0; 6775 -7.9; 7249 -4.6; 7756 -3.3; 8299 -1.9; 8880 -0.2; 9502 0.0; 10167 0.0; 10879 -1.5; 11640 -4.5; 12455 -7.2; 13327 -10.3; 14260 -13.9; 15258 -16.4; 16326 -16.0; 17469 -13.2; 18692 -10.0; 20000 -7.5
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 5.5; 22 4.7; 23 4.3; 25 3.6; 26 3.3; 28 2.7; 30 2.1; 32 1.6; 35 0.9; 37 0.5; 40 -0.0; 42 -0.2; 45 -0.3; 49 -0.3; 52 -0.6; 56 -1.1; 59 -1.2; 64 -1.2; 68 -1.4; 73 -1.4; 78 -1.5; 83 -2.0; 89 -2.8; 95 -3.8; 102 -4.7; 109 -5.4; 117 -5.9; 125 -6.3; 134 -6.8; 143 -7.0; 153 -7.1; 164 -6.7; 175 -6.5; 188 -6.1; 201 -5.2; 215 -3.8; 230 -2.7; 246 -1.1; 263 0.9; 282 2.2; 301 1.0; 323 -1.2; 345 -2.4; 369 -3.1; 395 -3.6; 423 -3.4; 452 -3.0; 484 -2.0; 518 0.8; 554 0.3; 593 -0.5; 635 -1.2; 679 -0.7; 726 -0.2; 777 0.1; 832 -0.0; 890 -0.2; 952 -0.2; 1019 0.2; 1090 1.2; 1167 2.6; 1248 3.3; 1336 2.7; 1429 2.5; 1529 2.0; 1636 0.9; 1751 -0.3; 1873 -0.5; 2004 0.6; 2145 2.7; 2295 1.4; 2455 -1.4; 2627 -3.2; 2811 -3.7; 3008 -3.9; 3219 -4.3; 3444 -4.9; 3685 -6.2; 3943 -7.1; 4219 -8.2; 4514 -8.3; 4830 -7.8; 5168 -7.0; 5530 -10.1; 5917 -11.4; 6331 -10.0; 6775 -7.9; 7249 -4.6; 7756 -3.3; 8299 -1.9; 8880 -0.2; 9502 0.0; 10167 0.0; 10879 -1.5; 11640 -4.5; 12455 -7.2; 13327 -10.3; 14260 -13.9; 15258 -16.4; 16326 -16.0; 17469 -13.2; 18692 -10.0; 20000 -7.5
Copy: L=-5.5dB*l, R=-5.5dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Sonoma%20Model%20One/headphoncecom/onear/Ultrasone%20PRO%20900/Ultrasone%20PRO%20900.png)