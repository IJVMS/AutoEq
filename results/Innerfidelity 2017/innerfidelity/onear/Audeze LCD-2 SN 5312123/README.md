# Audeze LCD-2 SN 5312123
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 0.8; 22 0.8; 23 0.8; 25 0.8; 26 0.8; 28 0.9; 30 0.9; 32 1.0; 35 1.1; 37 1.2; 40 1.2; 42 1.0; 45 0.6; 49 0.2; 52 0.2; 56 0.3; 59 0.3; 64 0.1; 68 -0.0; 73 -0.0; 78 -0.1; 83 -0.3; 89 -0.6; 95 -0.9; 102 -1.3; 109 -1.6; 117 -2.0; 125 -2.5; 134 -2.9; 143 -3.2; 153 -3.4; 164 -3.5; 175 -3.5; 188 -3.5; 201 -3.7; 215 -3.8; 230 -4.0; 246 -4.2; 263 -4.4; 282 -4.4; 301 -4.3; 323 -4.2; 345 -4.3; 369 -4.2; 395 -4.2; 423 -3.9; 452 -4.1; 484 -4.1; 518 -3.7; 554 -3.1; 593 -2.6; 635 -2.5; 679 -2.8; 726 -2.5; 777 -2.0; 832 -1.9; 890 -1.4; 952 -0.5; 1019 0.1; 1090 0.8; 1167 1.0; 1248 0.9; 1336 0.8; 1429 0.6; 1529 0.6; 1636 1.0; 1751 1.2; 1873 1.7; 2004 1.5; 2145 1.2; 2295 1.0; 2455 1.6; 2627 1.5; 2811 1.8; 3008 2.7; 3219 2.7; 3444 3.1; 3685 4.9; 3943 6.0; 4219 6.0; 4514 6.0; 4830 5.2; 5168 3.1; 5530 1.3; 5917 1.6; 6331 1.8; 6775 0.2; 7249 -0.1; 7756 -0.4; 8299 -0.1; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 -0.7; 18692 -2.8; 20000 -3.5
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 0.8; 22 0.8; 23 0.8; 25 0.8; 26 0.8; 28 0.9; 30 0.9; 32 1.0; 35 1.1; 37 1.2; 40 1.2; 42 1.0; 45 0.6; 49 0.2; 52 0.2; 56 0.3; 59 0.3; 64 0.1; 68 -0.0; 73 -0.0; 78 -0.1; 83 -0.3; 89 -0.6; 95 -0.9; 102 -1.3; 109 -1.6; 117 -2.0; 125 -2.5; 134 -2.9; 143 -3.2; 153 -3.4; 164 -3.5; 175 -3.5; 188 -3.5; 201 -3.7; 215 -3.8; 230 -4.0; 246 -4.2; 263 -4.4; 282 -4.4; 301 -4.3; 323 -4.2; 345 -4.3; 369 -4.2; 395 -4.2; 423 -3.9; 452 -4.1; 484 -4.1; 518 -3.7; 554 -3.1; 593 -2.6; 635 -2.5; 679 -2.8; 726 -2.5; 777 -2.0; 832 -1.9; 890 -1.4; 952 -0.5; 1019 0.1; 1090 0.8; 1167 1.0; 1248 0.9; 1336 0.8; 1429 0.6; 1529 0.6; 1636 1.0; 1751 1.2; 1873 1.7; 2004 1.5; 2145 1.2; 2295 1.0; 2455 1.6; 2627 1.5; 2811 1.8; 3008 2.7; 3219 2.7; 3444 3.1; 3685 4.9; 3943 6.0; 4219 6.0; 4514 6.0; 4830 5.2; 5168 3.1; 5530 1.3; 5917 1.6; 6331 1.8; 6775 0.2; 7249 -0.1; 7756 -0.4; 8299 -0.1; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 -0.7; 18692 -2.8; 20000 -3.5
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Innerfidelity%202017/innerfidelity/onear/Audeze%20LCD-2%20SN%205312123/Audeze%20LCD-2%20SN%205312123.png)