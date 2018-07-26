# Beats Powerbeats2 Bluetooth
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 2.0; 22 1.9; 23 1.9; 25 1.8; 26 1.8; 28 1.7; 30 1.7; 32 1.6; 35 1.5; 37 1.4; 40 1.2; 42 1.1; 45 0.9; 49 0.6; 52 0.4; 56 0.3; 59 0.3; 64 0.5; 68 0.8; 73 1.2; 78 1.4; 83 1.1; 89 0.4; 95 -0.4; 102 -1.3; 109 -1.8; 117 -2.4; 125 -3.1; 134 -3.7; 143 -4.2; 153 -4.6; 164 -4.8; 175 -4.7; 188 -4.8; 201 -4.9; 215 -4.9; 230 -4.8; 246 -4.9; 263 -4.9; 282 -4.6; 301 -4.6; 323 -4.4; 345 -4.2; 369 -4.1; 395 -4.0; 423 -3.6; 452 -3.2; 484 -2.9; 518 -2.6; 554 -2.4; 593 -1.9; 635 -1.3; 679 -0.6; 726 0.1; 777 0.6; 832 0.5; 890 0.4; 952 0.1; 1019 0.0; 1090 0.5; 1167 1.5; 1248 2.3; 1336 2.9; 1429 3.2; 1529 3.3; 1636 2.9; 1751 2.3; 1873 2.0; 2004 2.2; 2145 2.7; 2295 3.5; 2455 4.7; 2627 5.9; 2811 6.0; 3008 6.0; 3219 6.0; 3444 6.0; 3685 6.0; 3943 6.0; 4219 5.5; 4514 4.3; 4830 3.7; 5168 3.1; 5530 1.5; 5917 -0.0; 6331 -0.3; 6775 -0.3; 7249 -1.5; 7756 -2.7; 8299 -3.6; 8880 -3.7; 9502 -3.6; 10167 -3.4; 10879 -2.9; 11640 -1.6; 12455 -0.5; 13327 -1.3; 14260 -4.3; 15258 -7.5; 16326 -8.8; 17469 -7.9; 18692 -5.7; 20000 -2.6
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 2.0; 22 1.9; 23 1.9; 25 1.8; 26 1.8; 28 1.7; 30 1.7; 32 1.6; 35 1.5; 37 1.4; 40 1.2; 42 1.1; 45 0.9; 49 0.6; 52 0.4; 56 0.3; 59 0.3; 64 0.5; 68 0.8; 73 1.2; 78 1.4; 83 1.1; 89 0.4; 95 -0.4; 102 -1.3; 109 -1.8; 117 -2.4; 125 -3.1; 134 -3.7; 143 -4.2; 153 -4.6; 164 -4.8; 175 -4.7; 188 -4.8; 201 -4.9; 215 -4.9; 230 -4.8; 246 -4.9; 263 -4.9; 282 -4.6; 301 -4.6; 323 -4.4; 345 -4.2; 369 -4.1; 395 -4.0; 423 -3.6; 452 -3.2; 484 -2.9; 518 -2.6; 554 -2.4; 593 -1.9; 635 -1.3; 679 -0.6; 726 0.1; 777 0.6; 832 0.5; 890 0.4; 952 0.1; 1019 0.0; 1090 0.5; 1167 1.5; 1248 2.3; 1336 2.9; 1429 3.2; 1529 3.3; 1636 2.9; 1751 2.3; 1873 2.0; 2004 2.2; 2145 2.7; 2295 3.5; 2455 4.7; 2627 5.9; 2811 6.0; 3008 6.0; 3219 6.0; 3444 6.0; 3685 6.0; 3943 6.0; 4219 5.5; 4514 4.3; 4830 3.7; 5168 3.1; 5530 1.5; 5917 -0.0; 6331 -0.3; 6775 -0.3; 7249 -1.5; 7756 -2.7; 8299 -3.6; 8880 -3.7; 9502 -3.6; 10167 -3.4; 10879 -2.9; 11640 -1.6; 12455 -0.5; 13327 -1.3; 14260 -4.3; 15258 -7.5; 16326 -8.8; 17469 -7.9; 18692 -5.7; 20000 -2.6
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Sonoma%20Model%20One/innerfidelity/onear/Beats%20Powerbeats2%20Bluetooth/Beats%20Powerbeats2%20Bluetooth.png)