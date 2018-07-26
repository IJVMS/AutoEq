# Shure SRH440
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 6.0; 32 6.0; 35 6.0; 37 6.0; 40 6.0; 42 6.0; 45 6.0; 49 6.0; 52 6.0; 56 6.0; 59 6.0; 64 6.0; 68 6.0; 73 6.0; 78 5.9; 83 4.8; 89 3.6; 95 2.8; 102 2.0; 109 1.4; 117 1.2; 125 0.7; 134 0.2; 143 0.1; 153 -0.2; 164 0.2; 175 0.3; 188 0.2; 201 0.2; 215 0.4; 230 0.4; 246 0.2; 263 -0.2; 282 -0.6; 301 -0.9; 323 -1.2; 345 -1.5; 369 -2.3; 395 -2.4; 423 -2.2; 452 -2.3; 484 -2.5; 518 -2.5; 554 -2.0; 593 -1.6; 635 -1.4; 679 -1.4; 726 -1.3; 777 -0.8; 832 -0.8; 890 -0.6; 952 -0.3; 1019 0.3; 1090 0.9; 1167 -0.2; 1248 -0.4; 1336 -0.7; 1429 -1.1; 1529 -1.6; 1636 -2.1; 1751 -2.5; 1873 -2.3; 2004 -1.5; 2145 -0.7; 2295 0.3; 2455 1.3; 2627 1.7; 2811 2.2; 3008 2.9; 3219 2.7; 3444 2.1; 3685 2.4; 3943 4.4; 4219 4.8; 4514 4.4; 4830 5.2; 5168 6.0; 5530 3.6; 5917 3.4; 6331 5.4; 6775 3.9; 7249 1.3; 7756 0.3; 8299 -1.2; 8880 -3.8; 9502 -5.9; 10167 -6.6; 10879 -4.6; 11640 -0.5; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 6.0; 32 6.0; 35 6.0; 37 6.0; 40 6.0; 42 6.0; 45 6.0; 49 6.0; 52 6.0; 56 6.0; 59 6.0; 64 6.0; 68 6.0; 73 6.0; 78 5.9; 83 4.8; 89 3.6; 95 2.8; 102 2.0; 109 1.4; 117 1.2; 125 0.7; 134 0.2; 143 0.1; 153 -0.2; 164 0.2; 175 0.3; 188 0.2; 201 0.2; 215 0.4; 230 0.4; 246 0.2; 263 -0.2; 282 -0.6; 301 -0.9; 323 -1.2; 345 -1.5; 369 -2.3; 395 -2.4; 423 -2.2; 452 -2.3; 484 -2.5; 518 -2.5; 554 -2.0; 593 -1.6; 635 -1.4; 679 -1.4; 726 -1.3; 777 -0.8; 832 -0.8; 890 -0.6; 952 -0.3; 1019 0.3; 1090 0.9; 1167 -0.2; 1248 -0.4; 1336 -0.7; 1429 -1.1; 1529 -1.6; 1636 -2.1; 1751 -2.5; 1873 -2.3; 2004 -1.5; 2145 -0.7; 2295 0.3; 2455 1.3; 2627 1.7; 2811 2.2; 3008 2.9; 3219 2.7; 3444 2.1; 3685 2.4; 3943 4.4; 4219 4.8; 4514 4.4; 4830 5.2; 5168 6.0; 5530 3.6; 5917 3.4; 6331 5.4; 6775 3.9; 7249 1.3; 7756 0.3; 8299 -1.2; 8880 -3.8; 9502 -5.9; 10167 -6.6; 10879 -4.6; 11640 -0.5; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Innerfidelity%202017/headphoncecom/onear/Shure%20SRH440/Shure%20SRH440.png)