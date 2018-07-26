# Torque t402v OnEar Blue
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 -3.1; 22 -3.8; 23 -4.1; 25 -4.7; 26 -5.0; 28 -5.4; 30 -5.9; 32 -6.2; 35 -6.7; 37 -7.0; 40 -7.4; 42 -7.5; 45 -7.8; 49 -8.0; 52 -8.2; 56 -8.5; 59 -8.6; 64 -8.9; 68 -9.0; 73 -9.2; 78 -9.3; 83 -9.5; 89 -9.9; 95 -10.3; 102 -11.1; 109 -11.6; 117 -12.2; 125 -12.6; 134 -13.0; 143 -13.2; 153 -13.4; 164 -13.4; 175 -13.4; 188 -13.4; 201 -13.3; 215 -13.2; 230 -12.9; 246 -12.6; 263 -12.2; 282 -11.6; 301 -11.1; 323 -10.6; 345 -10.3; 369 -9.8; 395 -9.0; 423 -8.3; 452 -7.6; 484 -6.8; 518 -5.8; 554 -4.6; 593 -3.2; 635 -1.6; 679 -0.1; 726 1.2; 777 2.2; 832 2.5; 890 2.2; 952 1.1; 1019 -0.4; 1090 -2.0; 1167 -3.3; 1248 -4.2; 1336 -3.4; 1429 -2.0; 1529 -1.9; 1636 -0.4; 1751 0.8; 1873 1.2; 2004 1.0; 2145 0.4; 2295 -0.3; 2455 -0.6; 2627 -0.5; 2811 -0.4; 3008 -0.1; 3219 0.4; 3444 0.8; 3685 0.9; 3943 1.1; 4219 1.5; 4514 2.4; 4830 4.4; 5168 6.0; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 -3.1; 22 -3.8; 23 -4.1; 25 -4.7; 26 -5.0; 28 -5.4; 30 -5.9; 32 -6.2; 35 -6.7; 37 -7.0; 40 -7.4; 42 -7.5; 45 -7.8; 49 -8.0; 52 -8.2; 56 -8.5; 59 -8.6; 64 -8.9; 68 -9.0; 73 -9.2; 78 -9.3; 83 -9.5; 89 -9.9; 95 -10.3; 102 -11.1; 109 -11.6; 117 -12.2; 125 -12.6; 134 -13.0; 143 -13.2; 153 -13.4; 164 -13.4; 175 -13.4; 188 -13.4; 201 -13.3; 215 -13.2; 230 -12.9; 246 -12.6; 263 -12.2; 282 -11.6; 301 -11.1; 323 -10.6; 345 -10.3; 369 -9.8; 395 -9.0; 423 -8.3; 452 -7.6; 484 -6.8; 518 -5.8; 554 -4.6; 593 -3.2; 635 -1.6; 679 -0.1; 726 1.2; 777 2.2; 832 2.5; 890 2.2; 952 1.1; 1019 -0.4; 1090 -2.0; 1167 -3.3; 1248 -4.2; 1336 -3.4; 1429 -2.0; 1529 -1.9; 1636 -0.4; 1751 0.8; 1873 1.2; 2004 1.0; 2145 0.4; 2295 -0.3; 2455 -0.6; 2627 -0.5; 2811 -0.4; 3008 -0.1; 3219 0.4; 3444 0.8; 3685 0.9; 3943 1.1; 4219 1.5; 4514 2.4; 4830 4.4; 5168 6.0; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Headphone.com/innerfidelity/onear/Torque%20t402v%20OnEar%20Blue/Torque%20t402v%20OnEar%20Blue.png)