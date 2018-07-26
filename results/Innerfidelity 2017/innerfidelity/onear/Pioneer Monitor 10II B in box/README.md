# Pioneer Monitor 10II B in box
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 -9.8; 22 -9.9; 23 -9.9; 25 -9.9; 26 -10.0; 28 -10.0; 30 -10.0; 32 -10.0; 35 -10.0; 37 -9.9; 40 -9.9; 42 -9.8; 45 -9.7; 49 -9.7; 52 -9.6; 56 -9.6; 59 -9.5; 64 -9.4; 68 -9.3; 73 -9.1; 78 -9.0; 83 -8.9; 89 -8.7; 95 -8.4; 102 -7.8; 109 -7.1; 117 -6.1; 125 -6.0; 134 -8.5; 143 -11.7; 153 -12.9; 164 -10.5; 175 -9.1; 188 -12.4; 201 -12.6; 215 -12.8; 230 -12.8; 246 -12.6; 263 -12.1; 282 -11.6; 301 -11.1; 323 -10.4; 345 -9.7; 369 -8.9; 395 -8.1; 423 -7.2; 452 -6.4; 484 -5.6; 518 -4.5; 554 -2.9; 593 -1.3; 635 -0.2; 679 0.5; 726 0.9; 777 0.8; 832 0.3; 890 -0.2; 952 0.1; 1019 -0.0; 1090 0.4; 1167 1.2; 1248 -0.2; 1336 -2.5; 1429 -5.2; 1529 -8.5; 1636 -11.5; 1751 -14.1; 1873 -13.5; 2004 -9.7; 2145 -5.0; 2295 -1.7; 2455 -0.4; 2627 -1.8; 2811 -2.1; 3008 0.9; 3219 3.6; 3444 3.3; 3685 3.5; 3943 6.0; 4219 6.0; 4514 6.0; 4830 6.0; 5168 6.0; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 -0.9; 10879 -2.8; 11640 -1.7; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 -9.8; 22 -9.9; 23 -9.9; 25 -9.9; 26 -10.0; 28 -10.0; 30 -10.0; 32 -10.0; 35 -10.0; 37 -9.9; 40 -9.9; 42 -9.8; 45 -9.7; 49 -9.7; 52 -9.6; 56 -9.6; 59 -9.5; 64 -9.4; 68 -9.3; 73 -9.1; 78 -9.0; 83 -8.9; 89 -8.7; 95 -8.4; 102 -7.8; 109 -7.1; 117 -6.1; 125 -6.0; 134 -8.5; 143 -11.7; 153 -12.9; 164 -10.5; 175 -9.1; 188 -12.4; 201 -12.6; 215 -12.8; 230 -12.8; 246 -12.6; 263 -12.1; 282 -11.6; 301 -11.1; 323 -10.4; 345 -9.7; 369 -8.9; 395 -8.1; 423 -7.2; 452 -6.4; 484 -5.6; 518 -4.5; 554 -2.9; 593 -1.3; 635 -0.2; 679 0.5; 726 0.9; 777 0.8; 832 0.3; 890 -0.2; 952 0.1; 1019 -0.0; 1090 0.4; 1167 1.2; 1248 -0.2; 1336 -2.5; 1429 -5.2; 1529 -8.5; 1636 -11.5; 1751 -14.1; 1873 -13.5; 2004 -9.7; 2145 -5.0; 2295 -1.7; 2455 -0.4; 2627 -1.8; 2811 -2.1; 3008 0.9; 3219 3.6; 3444 3.3; 3685 3.5; 3943 6.0; 4219 6.0; 4514 6.0; 4830 6.0; 5168 6.0; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 -0.9; 10879 -2.8; 11640 -1.7; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Innerfidelity%202017/innerfidelity/onear/Pioneer%20Monitor%2010II%20B%20in%20box/Pioneer%20Monitor%2010II%20B%20in%20box.png)