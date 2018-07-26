# Audeze EL8 Open
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 6.0; 22 5.9; 23 5.9; 25 5.8; 26 5.8; 28 5.7; 30 5.6; 32 5.6; 35 5.6; 37 5.6; 40 5.5; 42 5.4; 45 5.3; 49 5.2; 52 5.3; 56 5.3; 59 5.1; 64 4.6; 68 4.3; 73 4.3; 78 4.2; 83 4.1; 89 3.9; 95 3.6; 102 3.1; 109 2.9; 117 2.6; 125 2.2; 134 1.8; 143 1.6; 153 1.4; 164 1.3; 175 1.2; 188 1.1; 201 1.0; 215 1.0; 230 1.1; 246 0.9; 263 0.8; 282 0.9; 301 0.9; 323 0.9; 345 1.1; 369 1.2; 395 1.2; 423 1.2; 452 1.1; 484 1.1; 518 1.1; 554 1.0; 593 1.2; 635 1.1; 679 0.8; 726 0.6; 777 0.6; 832 0.3; 890 0.2; 952 -0.0; 1019 0.1; 1090 -0.0; 1167 -0.5; 1248 -0.4; 1336 -0.3; 1429 -0.1; 1529 0.1; 1636 0.2; 1751 0.3; 1873 -0.4; 2004 -0.9; 2145 -1.3; 2295 -1.2; 2455 -0.4; 2627 1.3; 2811 2.5; 3008 2.3; 3219 2.3; 3444 3.6; 3685 4.2; 3943 5.0; 4219 4.1; 4514 3.5; 4830 1.3; 5168 1.4; 5530 5.7; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 6.0; 22 5.9; 23 5.9; 25 5.8; 26 5.8; 28 5.7; 30 5.6; 32 5.6; 35 5.6; 37 5.6; 40 5.5; 42 5.4; 45 5.3; 49 5.2; 52 5.3; 56 5.3; 59 5.1; 64 4.6; 68 4.3; 73 4.3; 78 4.2; 83 4.1; 89 3.9; 95 3.6; 102 3.1; 109 2.9; 117 2.6; 125 2.2; 134 1.8; 143 1.6; 153 1.4; 164 1.3; 175 1.2; 188 1.1; 201 1.0; 215 1.0; 230 1.1; 246 0.9; 263 0.8; 282 0.9; 301 0.9; 323 0.9; 345 1.1; 369 1.2; 395 1.2; 423 1.2; 452 1.1; 484 1.1; 518 1.1; 554 1.0; 593 1.2; 635 1.1; 679 0.8; 726 0.6; 777 0.6; 832 0.3; 890 0.2; 952 -0.0; 1019 0.1; 1090 -0.0; 1167 -0.5; 1248 -0.4; 1336 -0.3; 1429 -0.1; 1529 0.1; 1636 0.2; 1751 0.3; 1873 -0.4; 2004 -0.9; 2145 -1.3; 2295 -1.2; 2455 -0.4; 2627 1.3; 2811 2.5; 3008 2.3; 3219 2.3; 3444 3.6; 3685 4.2; 3943 5.0; 4219 4.1; 4514 3.5; 4830 1.3; 5168 1.4; 5530 5.7; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/SBAF-Serious/innerfidelity/onear/Audeze%20EL8%20Open/Audeze%20EL8%20Open.png)