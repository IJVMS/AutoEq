# Phiaton PS 300 NC
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 3.6; 22 1.6; 23 0.7; 25 -0.8; 26 -1.5; 28 -2.6; 30 -3.5; 32 -4.3; 35 -5.2; 37 -5.7; 40 -6.3; 42 -6.6; 45 -7.0; 49 -7.5; 52 -7.7; 56 -7.9; 59 -7.9; 64 -7.8; 68 -7.8; 73 -8.5; 78 -9.6; 83 -9.8; 89 -9.9; 95 -10.2; 102 -10.4; 109 -10.5; 117 -10.9; 125 -11.3; 134 -11.6; 143 -11.7; 153 -11.9; 164 -11.8; 175 -11.6; 188 -11.4; 201 -11.0; 215 -11.0; 230 -10.9; 246 -10.8; 263 -10.9; 282 -11.1; 301 -11.1; 323 -11.2; 345 -10.9; 369 -10.6; 395 -9.9; 423 -8.8; 452 -7.3; 484 -4.9; 518 -1.5; 554 1.8; 593 3.8; 635 3.5; 679 2.9; 726 2.4; 777 1.9; 832 1.1; 890 0.6; 952 0.3; 1019 -0.1; 1090 -0.9; 1167 -2.2; 1248 -2.6; 1336 -3.9; 1429 -5.8; 1529 -7.7; 1636 -9.2; 1751 -10.5; 1873 -9.6; 2004 -7.9; 2145 -6.1; 2295 -4.6; 2455 -3.0; 2627 -1.3; 2811 -1.1; 3008 -0.2; 3219 2.3; 3444 5.6; 3685 6.0; 3943 6.0; 4219 6.0; 4514 6.0; 4830 6.0; 5168 6.0; 5530 6.0; 5917 5.9; 6331 5.3; 6775 3.2; 7249 1.3; 7756 -0.4; 8299 -2.2; 8880 -1.5; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 3.6; 22 1.6; 23 0.7; 25 -0.8; 26 -1.5; 28 -2.6; 30 -3.5; 32 -4.3; 35 -5.2; 37 -5.7; 40 -6.3; 42 -6.6; 45 -7.0; 49 -7.5; 52 -7.7; 56 -7.9; 59 -7.9; 64 -7.8; 68 -7.8; 73 -8.5; 78 -9.6; 83 -9.8; 89 -9.9; 95 -10.2; 102 -10.4; 109 -10.5; 117 -10.9; 125 -11.3; 134 -11.6; 143 -11.7; 153 -11.9; 164 -11.8; 175 -11.6; 188 -11.4; 201 -11.0; 215 -11.0; 230 -10.9; 246 -10.8; 263 -10.9; 282 -11.1; 301 -11.1; 323 -11.2; 345 -10.9; 369 -10.6; 395 -9.9; 423 -8.8; 452 -7.3; 484 -4.9; 518 -1.5; 554 1.8; 593 3.8; 635 3.5; 679 2.9; 726 2.4; 777 1.9; 832 1.1; 890 0.6; 952 0.3; 1019 -0.1; 1090 -0.9; 1167 -2.2; 1248 -2.6; 1336 -3.9; 1429 -5.8; 1529 -7.7; 1636 -9.2; 1751 -10.5; 1873 -9.6; 2004 -7.9; 2145 -6.1; 2295 -4.6; 2455 -3.0; 2627 -1.3; 2811 -1.1; 3008 -0.2; 3219 2.3; 3444 5.6; 3685 6.0; 3943 6.0; 4219 6.0; 4514 6.0; 4830 6.0; 5168 6.0; 5530 6.0; 5917 5.9; 6331 5.3; 6775 3.2; 7249 1.3; 7756 -0.4; 8299 -2.2; 8880 -1.5; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Innerfidelity%202017/headphoncecom/onear/Phiaton%20PS%20300%20NC/Phiaton%20PS%20300%20NC.png)