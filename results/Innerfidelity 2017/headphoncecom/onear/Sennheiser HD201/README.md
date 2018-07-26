# Sennheiser HD201
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 6.0; 32 6.0; 35 6.0; 37 6.0; 40 6.0; 42 6.0; 45 6.0; 49 6.0; 52 6.0; 56 6.0; 59 6.0; 64 6.0; 68 6.0; 73 6.0; 78 6.0; 83 6.0; 89 6.0; 95 6.0; 102 6.0; 109 6.0; 117 6.0; 125 6.0; 134 6.0; 143 6.0; 153 6.0; 164 6.0; 175 6.0; 188 6.0; 201 6.0; 215 6.0; 230 6.0; 246 6.0; 263 6.0; 282 6.0; 301 6.0; 323 6.0; 345 6.0; 369 6.0; 395 6.0; 423 6.0; 452 5.7; 484 5.2; 518 5.2; 554 5.4; 593 5.9; 635 6.0; 679 5.9; 726 5.5; 777 4.9; 832 3.7; 890 2.2; 952 1.0; 1019 -0.3; 1090 -1.0; 1167 -1.5; 1248 -1.7; 1336 -1.5; 1429 -1.1; 1529 -0.5; 1636 3.8; 1751 2.7; 1873 1.3; 2004 1.2; 2145 1.0; 2295 1.3; 2455 1.4; 2627 2.1; 2811 3.5; 3008 4.9; 3219 5.2; 3444 5.1; 3685 5.2; 3943 6.0; 4219 6.0; 4514 6.0; 4830 6.0; 5168 1.4; 5530 3.2; 5917 4.2; 6331 3.1; 6775 3.3; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 -0.1; 10167 -0.4; 10879 -0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 6.0; 32 6.0; 35 6.0; 37 6.0; 40 6.0; 42 6.0; 45 6.0; 49 6.0; 52 6.0; 56 6.0; 59 6.0; 64 6.0; 68 6.0; 73 6.0; 78 6.0; 83 6.0; 89 6.0; 95 6.0; 102 6.0; 109 6.0; 117 6.0; 125 6.0; 134 6.0; 143 6.0; 153 6.0; 164 6.0; 175 6.0; 188 6.0; 201 6.0; 215 6.0; 230 6.0; 246 6.0; 263 6.0; 282 6.0; 301 6.0; 323 6.0; 345 6.0; 369 6.0; 395 6.0; 423 6.0; 452 5.7; 484 5.2; 518 5.2; 554 5.4; 593 5.9; 635 6.0; 679 5.9; 726 5.5; 777 4.9; 832 3.7; 890 2.2; 952 1.0; 1019 -0.3; 1090 -1.0; 1167 -1.5; 1248 -1.7; 1336 -1.5; 1429 -1.1; 1529 -0.5; 1636 3.8; 1751 2.7; 1873 1.3; 2004 1.2; 2145 1.0; 2295 1.3; 2455 1.4; 2627 2.1; 2811 3.5; 3008 4.9; 3219 5.2; 3444 5.1; 3685 5.2; 3943 6.0; 4219 6.0; 4514 6.0; 4830 6.0; 5168 1.4; 5530 3.2; 5917 4.2; 6331 3.1; 6775 3.3; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 -0.1; 10167 -0.4; 10879 -0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Innerfidelity%202017/headphoncecom/onear/Sennheiser%20HD201/Sennheiser%20HD201.png)