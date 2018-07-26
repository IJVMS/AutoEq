# Sennheiser Momentum
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 2.8; 22 2.6; 23 2.5; 25 2.2; 26 2.2; 28 2.0; 30 1.8; 32 1.7; 35 1.6; 37 1.5; 40 1.4; 42 1.3; 45 1.2; 49 1.1; 52 1.1; 56 0.9; 59 0.8; 64 0.8; 68 0.7; 73 0.6; 78 0.4; 83 0.3; 89 0.1; 95 -0.1; 102 -0.4; 109 -0.7; 117 -0.8; 125 -1.1; 134 -1.3; 143 -1.6; 153 -2.1; 164 -2.4; 175 -1.9; 188 -2.3; 201 -2.6; 215 -2.6; 230 -2.4; 246 -2.4; 263 -2.3; 282 -1.9; 301 -1.9; 323 -1.4; 345 -0.9; 369 -0.5; 395 -0.3; 423 -0.2; 452 -0.3; 484 -0.4; 518 -0.4; 554 -0.1; 593 0.4; 635 0.3; 679 -0.0; 726 -0.3; 777 -0.1; 832 -0.1; 890 -0.1; 952 0.0; 1019 -0.0; 1090 0.1; 1167 0.0; 1248 -0.3; 1336 -0.7; 1429 -1.0; 1529 -1.1; 1636 -1.0; 1751 -1.2; 1873 -1.0; 2004 -0.5; 2145 0.4; 2295 1.7; 2455 3.3; 2627 4.9; 2811 5.8; 3008 6.0; 3219 6.0; 3444 6.0; 3685 6.0; 3943 6.0; 4219 6.0; 4514 6.0; 4830 6.0; 5168 6.0; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 2.8; 22 2.6; 23 2.5; 25 2.2; 26 2.2; 28 2.0; 30 1.8; 32 1.7; 35 1.6; 37 1.5; 40 1.4; 42 1.3; 45 1.2; 49 1.1; 52 1.1; 56 0.9; 59 0.8; 64 0.8; 68 0.7; 73 0.6; 78 0.4; 83 0.3; 89 0.1; 95 -0.1; 102 -0.4; 109 -0.7; 117 -0.8; 125 -1.1; 134 -1.3; 143 -1.6; 153 -2.1; 164 -2.4; 175 -1.9; 188 -2.3; 201 -2.6; 215 -2.6; 230 -2.4; 246 -2.4; 263 -2.3; 282 -1.9; 301 -1.9; 323 -1.4; 345 -0.9; 369 -0.5; 395 -0.3; 423 -0.2; 452 -0.3; 484 -0.4; 518 -0.4; 554 -0.1; 593 0.4; 635 0.3; 679 -0.0; 726 -0.3; 777 -0.1; 832 -0.1; 890 -0.1; 952 0.0; 1019 -0.0; 1090 0.1; 1167 0.0; 1248 -0.3; 1336 -0.7; 1429 -1.0; 1529 -1.1; 1636 -1.0; 1751 -1.2; 1873 -1.0; 2004 -0.5; 2145 0.4; 2295 1.7; 2455 3.3; 2627 4.9; 2811 5.8; 3008 6.0; 3219 6.0; 3444 6.0; 3685 6.0; 3943 6.0; 4219 6.0; 4514 6.0; 4830 6.0; 5168 6.0; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Innerfidelity%202017/headphoncecom/onear/Sennheiser%20Momentum/Sennheiser%20Momentum.png)