# House of Marley Stir It Up
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 -1.7; 22 -2.0; 23 -2.1; 25 -2.3; 26 -2.4; 28 -2.6; 30 -2.8; 32 -2.9; 35 -3.0; 37 -3.1; 40 -3.1; 42 -3.1; 45 -3.0; 49 -2.7; 52 -2.5; 56 -2.4; 59 -2.6; 64 -2.9; 68 -3.1; 73 -3.2; 78 -3.3; 83 -3.5; 89 -3.8; 95 -4.2; 102 -4.5; 109 -4.5; 117 -4.7; 125 -5.1; 134 -5.3; 143 -5.2; 153 -5.0; 164 -4.5; 175 -4.6; 188 -4.3; 201 -4.0; 215 -3.7; 230 -3.2; 246 -2.9; 263 -2.7; 282 -2.5; 301 -2.4; 323 -2.5; 345 -2.6; 369 -2.8; 395 -3.2; 423 -4.1; 452 -4.9; 484 -5.6; 518 -5.5; 554 -5.1; 593 -4.6; 635 -4.2; 679 -4.0; 726 -3.5; 777 -2.7; 832 -2.1; 890 -1.5; 952 -0.7; 1019 0.1; 1090 0.9; 1167 1.4; 1248 1.8; 1336 2.5; 1429 3.3; 1529 4.0; 1636 4.5; 1751 5.0; 1873 5.7; 2004 6.0; 2145 6.0; 2295 6.0; 2455 6.0; 2627 6.0; 2811 6.0; 3008 6.0; 3219 6.0; 3444 6.0; 3685 6.0; 3943 6.0; 4219 6.0; 4514 6.0; 4830 6.0; 5168 6.0; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 -1.7; 22 -2.0; 23 -2.1; 25 -2.3; 26 -2.4; 28 -2.6; 30 -2.8; 32 -2.9; 35 -3.0; 37 -3.1; 40 -3.1; 42 -3.1; 45 -3.0; 49 -2.7; 52 -2.5; 56 -2.4; 59 -2.6; 64 -2.9; 68 -3.1; 73 -3.2; 78 -3.3; 83 -3.5; 89 -3.8; 95 -4.2; 102 -4.5; 109 -4.5; 117 -4.7; 125 -5.1; 134 -5.3; 143 -5.2; 153 -5.0; 164 -4.5; 175 -4.6; 188 -4.3; 201 -4.0; 215 -3.7; 230 -3.2; 246 -2.9; 263 -2.7; 282 -2.5; 301 -2.4; 323 -2.5; 345 -2.6; 369 -2.8; 395 -3.2; 423 -4.1; 452 -4.9; 484 -5.6; 518 -5.5; 554 -5.1; 593 -4.6; 635 -4.2; 679 -4.0; 726 -3.5; 777 -2.7; 832 -2.1; 890 -1.5; 952 -0.7; 1019 0.1; 1090 0.9; 1167 1.4; 1248 1.8; 1336 2.5; 1429 3.3; 1529 4.0; 1636 4.5; 1751 5.0; 1873 5.7; 2004 6.0; 2145 6.0; 2295 6.0; 2455 6.0; 2627 6.0; 2811 6.0; 3008 6.0; 3219 6.0; 3444 6.0; 3685 6.0; 3943 6.0; 4219 6.0; 4514 6.0; 4830 6.0; 5168 6.0; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Innerfidelity%202017/innerfidelity/onear/House%20of%20Marley%20Stir%20It%20Up/House%20of%20Marley%20Stir%20It%20Up.png)