# Sennheiser PXC 550 Wired Power On
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 0.9; 22 0.3; 23 0.1; 25 -0.3; 26 -0.5; 28 -0.8; 30 -0.9; 32 -1.1; 35 -1.3; 37 -1.4; 40 -1.5; 42 -1.6; 45 -1.7; 49 -1.8; 52 -1.8; 56 -1.8; 59 -1.8; 64 -1.7; 68 -1.6; 73 -1.5; 78 -1.2; 83 -1.2; 89 -1.3; 95 -1.4; 102 -1.8; 109 -2.3; 117 -2.8; 125 -3.4; 134 -3.6; 143 -3.9; 153 -4.2; 164 -2.5; 175 -2.3; 188 -2.6; 201 -2.0; 215 -1.2; 230 -0.1; 246 0.7; 263 1.3; 282 2.1; 301 2.4; 323 2.7; 345 2.8; 369 2.8; 395 2.8; 423 2.8; 452 2.8; 484 2.6; 518 2.5; 554 2.5; 593 2.6; 635 2.4; 679 2.1; 726 1.8; 777 1.6; 832 1.0; 890 0.6; 952 0.3; 1019 -0.0; 1090 -0.2; 1167 0.4; 1248 0.4; 1336 -0.9; 1429 -1.3; 1529 -2.0; 1636 -2.5; 1751 -2.2; 1873 -1.6; 2004 -1.7; 2145 -1.3; 2295 -0.7; 2455 0.2; 2627 1.2; 2811 1.6; 3008 2.4; 3219 3.1; 3444 3.4; 3685 2.4; 3943 3.3; 4219 6.0; 4514 3.2; 4830 -2.6; 5168 -1.9; 5530 2.4; 5917 5.4; 6331 5.4; 6775 3.6; 7249 1.3; 7756 0.3; 8299 -1.7; 8880 -4.6; 9502 -5.2; 10167 -2.2; 10879 -0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 -0.0; 20000 -1.4
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 0.9; 22 0.3; 23 0.1; 25 -0.3; 26 -0.5; 28 -0.8; 30 -0.9; 32 -1.1; 35 -1.3; 37 -1.4; 40 -1.5; 42 -1.6; 45 -1.7; 49 -1.8; 52 -1.8; 56 -1.8; 59 -1.8; 64 -1.7; 68 -1.6; 73 -1.5; 78 -1.2; 83 -1.2; 89 -1.3; 95 -1.4; 102 -1.8; 109 -2.3; 117 -2.8; 125 -3.4; 134 -3.6; 143 -3.9; 153 -4.2; 164 -2.5; 175 -2.3; 188 -2.6; 201 -2.0; 215 -1.2; 230 -0.1; 246 0.7; 263 1.3; 282 2.1; 301 2.4; 323 2.7; 345 2.8; 369 2.8; 395 2.8; 423 2.8; 452 2.8; 484 2.6; 518 2.5; 554 2.5; 593 2.6; 635 2.4; 679 2.1; 726 1.8; 777 1.6; 832 1.0; 890 0.6; 952 0.3; 1019 -0.0; 1090 -0.2; 1167 0.4; 1248 0.4; 1336 -0.9; 1429 -1.3; 1529 -2.0; 1636 -2.5; 1751 -2.2; 1873 -1.6; 2004 -1.7; 2145 -1.3; 2295 -0.7; 2455 0.2; 2627 1.2; 2811 1.6; 3008 2.4; 3219 3.1; 3444 3.4; 3685 2.4; 3943 3.3; 4219 6.0; 4514 3.2; 4830 -2.6; 5168 -1.9; 5530 2.4; 5917 5.4; 6331 5.4; 6775 3.6; 7249 1.3; 7756 0.3; 8299 -1.7; 8880 -4.6; 9502 -5.2; 10167 -2.2; 10879 -0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 -0.0; 20000 -1.4
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/SBAF-Serious/innerfidelity/onear/Sennheiser%20PXC%20550%20Wired%20Power%20On/Sennheiser%20PXC%20550%20Wired%20Power%20On.png)