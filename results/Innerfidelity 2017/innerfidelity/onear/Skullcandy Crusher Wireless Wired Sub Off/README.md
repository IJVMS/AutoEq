# Skullcandy Crusher Wireless Wired Sub Off
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-14**.
```
GraphicEQ: 10 -84; 20 -5.6; 22 -6.0; 23 -6.2; 25 -6.6; 26 -6.7; 28 -7.0; 30 -7.3; 32 -7.5; 35 -7.9; 37 -8.0; 40 -8.2; 42 -8.2; 45 -8.2; 49 -8.2; 52 -8.5; 56 -8.9; 59 -8.6; 64 -7.6; 68 -6.5; 73 -5.4; 78 -5.8; 83 -7.2; 89 -8.9; 95 -9.5; 102 -9.3; 109 -9.5; 117 -10.1; 125 -11.3; 134 -12.0; 143 -12.1; 153 -11.5; 164 -10.2; 175 -11.1; 188 -10.5; 201 -9.8; 215 -9.0; 230 -8.0; 246 -7.1; 263 -6.3; 282 -5.3; 301 -4.5; 323 -4.0; 345 -3.3; 369 -2.5; 395 -2.0; 423 -1.5; 452 -1.1; 484 -1.0; 518 -0.6; 554 0.3; 593 1.0; 635 0.6; 679 -0.0; 726 -0.8; 777 -0.9; 832 -0.7; 890 -0.3; 952 -0.1; 1019 0.0; 1090 -0.1; 1167 -0.0; 1248 0.2; 1336 0.2; 1429 -0.1; 1529 -0.4; 1636 -0.8; 1751 -1.3; 1873 -1.7; 2004 -2.1; 2145 -2.7; 2295 -3.1; 2455 -3.2; 2627 -3.6; 2811 -4.0; 3008 -4.2; 3219 -4.2; 3444 -3.5; 3685 -2.7; 3943 -1.1; 4219 -0.7; 4514 0.1; 4830 0.9; 5168 1.3; 5530 -0.9; 5917 -4.0; 6331 -4.0; 6775 -4.3; 7249 -5.3; 7756 -6.5; 8299 -7.6; 8880 -8.2; 9502 -8.5; 10167 -8.8; 10879 -8.7; 11640 -7.8; 12455 -5.2; 13327 -1.2; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 -5.6; 22 -6.0; 23 -6.2; 25 -6.6; 26 -6.7; 28 -7.0; 30 -7.3; 32 -7.5; 35 -7.9; 37 -8.0; 40 -8.2; 42 -8.2; 45 -8.2; 49 -8.2; 52 -8.5; 56 -8.9; 59 -8.6; 64 -7.6; 68 -6.5; 73 -5.4; 78 -5.8; 83 -7.2; 89 -8.9; 95 -9.5; 102 -9.3; 109 -9.5; 117 -10.1; 125 -11.3; 134 -12.0; 143 -12.1; 153 -11.5; 164 -10.2; 175 -11.1; 188 -10.5; 201 -9.8; 215 -9.0; 230 -8.0; 246 -7.1; 263 -6.3; 282 -5.3; 301 -4.5; 323 -4.0; 345 -3.3; 369 -2.5; 395 -2.0; 423 -1.5; 452 -1.1; 484 -1.0; 518 -0.6; 554 0.3; 593 1.0; 635 0.6; 679 -0.0; 726 -0.8; 777 -0.9; 832 -0.7; 890 -0.3; 952 -0.1; 1019 0.0; 1090 -0.1; 1167 -0.0; 1248 0.2; 1336 0.2; 1429 -0.1; 1529 -0.4; 1636 -0.8; 1751 -1.3; 1873 -1.7; 2004 -2.1; 2145 -2.7; 2295 -3.1; 2455 -3.2; 2627 -3.6; 2811 -4.0; 3008 -4.2; 3219 -4.2; 3444 -3.5; 3685 -2.7; 3943 -1.1; 4219 -0.7; 4514 0.1; 4830 0.9; 5168 1.3; 5530 -0.9; 5917 -4.0; 6331 -4.0; 6775 -4.3; 7249 -5.3; 7756 -6.5; 8299 -7.6; 8880 -8.2; 9502 -8.5; 10167 -8.8; 10879 -8.7; 11640 -7.8; 12455 -5.2; 13327 -1.2; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
Copy: L=-1.4dB*l, R=-1.4dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Innerfidelity%202017/innerfidelity/onear/Skullcandy%20Crusher%20Wireless%20Wired%20Sub%20Off/Skullcandy%20Crusher%20Wireless%20Wired%20Sub%20Off.png)