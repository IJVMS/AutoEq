# Audeze EL8 Closed
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 1.5; 22 1.4; 23 1.3; 25 1.3; 26 1.3; 28 1.2; 30 1.2; 32 1.3; 35 1.4; 37 1.5; 40 1.5; 42 1.5; 45 1.6; 49 2.2; 52 2.5; 56 2.2; 59 1.6; 64 0.7; 68 0.4; 73 0.2; 78 0.0; 83 -0.1; 89 -0.5; 95 -0.9; 102 -1.2; 109 -1.4; 117 -1.5; 125 -1.5; 134 -1.2; 143 -0.9; 153 -0.4; 164 0.4; 175 0.1; 188 0.7; 201 1.1; 215 1.5; 230 1.8; 246 1.9; 263 2.0; 282 2.0; 301 1.9; 323 1.7; 345 1.6; 369 1.5; 395 1.3; 423 1.0; 452 0.7; 484 0.3; 518 0.3; 554 0.6; 593 0.9; 635 0.8; 679 0.5; 726 0.3; 777 0.3; 832 0.2; 890 0.2; 952 0.1; 1019 -0.0; 1090 0.0; 1167 -0.3; 1248 -0.7; 1336 -0.9; 1429 -1.2; 1529 -1.5; 1636 -1.9; 1751 -2.3; 1873 -2.4; 2004 -2.1; 2145 -1.6; 2295 -1.0; 2455 -0.3; 2627 0.2; 2811 -0.1; 3008 -0.2; 3219 -0.5; 3444 -0.8; 3685 -0.2; 3943 1.1; 4219 1.7; 4514 0.4; 4830 -0.9; 5168 2.3; 5530 5.7; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 -0.3; 9502 -0.5; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 -1.3
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 1.5; 22 1.4; 23 1.3; 25 1.3; 26 1.3; 28 1.2; 30 1.2; 32 1.3; 35 1.4; 37 1.5; 40 1.5; 42 1.5; 45 1.6; 49 2.2; 52 2.5; 56 2.2; 59 1.6; 64 0.7; 68 0.4; 73 0.2; 78 0.0; 83 -0.1; 89 -0.5; 95 -0.9; 102 -1.2; 109 -1.4; 117 -1.5; 125 -1.5; 134 -1.2; 143 -0.9; 153 -0.4; 164 0.4; 175 0.1; 188 0.7; 201 1.1; 215 1.5; 230 1.8; 246 1.9; 263 2.0; 282 2.0; 301 1.9; 323 1.7; 345 1.6; 369 1.5; 395 1.3; 423 1.0; 452 0.7; 484 0.3; 518 0.3; 554 0.6; 593 0.9; 635 0.8; 679 0.5; 726 0.3; 777 0.3; 832 0.2; 890 0.2; 952 0.1; 1019 -0.0; 1090 0.0; 1167 -0.3; 1248 -0.7; 1336 -0.9; 1429 -1.2; 1529 -1.5; 1636 -1.9; 1751 -2.3; 1873 -2.4; 2004 -2.1; 2145 -1.6; 2295 -1.0; 2455 -0.3; 2627 0.2; 2811 -0.1; 3008 -0.2; 3219 -0.5; 3444 -0.8; 3685 -0.2; 3943 1.1; 4219 1.7; 4514 0.4; 4830 -0.9; 5168 2.3; 5530 5.7; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 -0.3; 9502 -0.5; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 -1.3
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Innerfidelity%202017/innerfidelity/onear/Audeze%20EL8%20Closed/Audeze%20EL8%20Closed.png)