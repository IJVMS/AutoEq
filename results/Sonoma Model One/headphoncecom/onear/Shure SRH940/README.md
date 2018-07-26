# Shure SRH940
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 6.0; 32 6.0; 35 6.0; 37 6.0; 40 5.5; 42 5.1; 45 4.5; 49 3.9; 52 3.5; 56 3.1; 59 3.0; 64 3.2; 68 3.9; 73 5.1; 78 5.9; 83 6.0; 89 5.7; 95 4.1; 102 2.6; 109 1.9; 117 1.8; 125 1.7; 134 0.6; 143 -0.1; 153 -0.5; 164 -0.2; 175 -1.1; 188 -2.0; 201 -2.5; 215 -2.9; 230 -3.2; 246 -3.4; 263 -3.6; 282 -3.3; 301 -3.2; 323 -4.2; 345 -4.1; 369 -3.3; 395 -2.9; 423 -2.5; 452 -2.1; 484 -1.8; 518 -1.6; 554 -1.5; 593 -1.0; 635 -0.5; 679 0.0; 726 0.5; 777 1.0; 832 1.3; 890 0.5; 952 0.1; 1019 0.1; 1090 0.5; 1167 1.2; 1248 1.7; 1336 1.8; 1429 1.8; 1529 1.4; 1636 0.6; 1751 -0.3; 1873 -0.7; 2004 -0.9; 2145 -0.9; 2295 -0.6; 2455 0.9; 2627 0.9; 2811 0.8; 3008 1.0; 3219 0.4; 3444 -0.5; 3685 -1.4; 3943 -2.2; 4219 -2.8; 4514 -2.6; 4830 -1.5; 5168 -0.1; 5530 0.6; 5917 -0.1; 6331 0.9; 6775 3.6; 7249 1.3; 7756 -1.8; 8299 -7.1; 8880 -11.1; 9502 -11.0; 10167 -5.7; 10879 -0.2; 11640 0.0; 12455 0.0; 13327 -1.4; 14260 -6.0; 15258 -7.3; 16326 -6.7; 17469 -6.7; 18692 -6.7; 20000 -5.7
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 6.0; 32 6.0; 35 6.0; 37 6.0; 40 5.5; 42 5.1; 45 4.5; 49 3.9; 52 3.5; 56 3.1; 59 3.0; 64 3.2; 68 3.9; 73 5.1; 78 5.9; 83 6.0; 89 5.7; 95 4.1; 102 2.6; 109 1.9; 117 1.8; 125 1.7; 134 0.6; 143 -0.1; 153 -0.5; 164 -0.2; 175 -1.1; 188 -2.0; 201 -2.5; 215 -2.9; 230 -3.2; 246 -3.4; 263 -3.6; 282 -3.3; 301 -3.2; 323 -4.2; 345 -4.1; 369 -3.3; 395 -2.9; 423 -2.5; 452 -2.1; 484 -1.8; 518 -1.6; 554 -1.5; 593 -1.0; 635 -0.5; 679 0.0; 726 0.5; 777 1.0; 832 1.3; 890 0.5; 952 0.1; 1019 0.1; 1090 0.5; 1167 1.2; 1248 1.7; 1336 1.8; 1429 1.8; 1529 1.4; 1636 0.6; 1751 -0.3; 1873 -0.7; 2004 -0.9; 2145 -0.9; 2295 -0.6; 2455 0.9; 2627 0.9; 2811 0.8; 3008 1.0; 3219 0.4; 3444 -0.5; 3685 -1.4; 3943 -2.2; 4219 -2.8; 4514 -2.6; 4830 -1.5; 5168 -0.1; 5530 0.6; 5917 -0.1; 6331 0.9; 6775 3.6; 7249 1.3; 7756 -1.8; 8299 -7.1; 8880 -11.1; 9502 -11.0; 10167 -5.7; 10879 -0.2; 11640 0.0; 12455 0.0; 13327 -1.4; 14260 -6.0; 15258 -7.3; 16326 -6.7; 17469 -6.7; 18692 -6.7; 20000 -5.7
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Sonoma%20Model%20One/headphoncecom/onear/Shure%20SRH940/Shure%20SRH940.png)