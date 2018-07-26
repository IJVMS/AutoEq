# Ultrsone HFI-450
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 6.0; 32 6.0; 35 6.0; 37 6.0; 40 6.0; 42 6.0; 45 6.0; 49 6.0; 52 6.0; 56 6.0; 59 6.0; 64 5.9; 68 5.3; 73 4.5; 78 3.9; 83 3.4; 89 3.1; 95 2.7; 102 1.8; 109 1.3; 117 0.9; 125 0.5; 134 0.3; 143 0.3; 153 0.2; 164 0.7; 175 0.9; 188 0.6; 201 0.6; 215 0.4; 230 0.1; 246 -0.3; 263 -0.8; 282 -1.5; 301 -2.4; 323 -3.1; 345 -3.4; 369 -3.4; 395 -3.4; 423 -3.4; 452 -3.4; 484 -3.5; 518 -3.4; 554 -2.3; 593 -1.4; 635 -0.9; 679 -0.7; 726 -0.6; 777 -0.2; 832 -0.1; 890 -0.1; 952 -0.1; 1019 -0.0; 1090 -0.1; 1167 -0.4; 1248 -0.4; 1336 -0.4; 1429 0.1; 1529 -0.3; 1636 -0.0; 1751 -0.4; 1873 -0.3; 2004 0.3; 2145 0.9; 2295 1.8; 2455 2.9; 2627 4.1; 2811 4.3; 3008 5.0; 3219 5.2; 3444 5.2; 3685 5.9; 3943 6.0; 4219 6.0; 4514 6.0; 4830 4.7; 5168 3.1; 5530 4.9; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 -0.2; 9502 -0.7; 10167 -1.0; 10879 -1.2; 11640 -1.1; 12455 -0.2; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 6.0; 32 6.0; 35 6.0; 37 6.0; 40 6.0; 42 6.0; 45 6.0; 49 6.0; 52 6.0; 56 6.0; 59 6.0; 64 5.9; 68 5.3; 73 4.5; 78 3.9; 83 3.4; 89 3.1; 95 2.7; 102 1.8; 109 1.3; 117 0.9; 125 0.5; 134 0.3; 143 0.3; 153 0.2; 164 0.7; 175 0.9; 188 0.6; 201 0.6; 215 0.4; 230 0.1; 246 -0.3; 263 -0.8; 282 -1.5; 301 -2.4; 323 -3.1; 345 -3.4; 369 -3.4; 395 -3.4; 423 -3.4; 452 -3.4; 484 -3.5; 518 -3.4; 554 -2.3; 593 -1.4; 635 -0.9; 679 -0.7; 726 -0.6; 777 -0.2; 832 -0.1; 890 -0.1; 952 -0.1; 1019 -0.0; 1090 -0.1; 1167 -0.4; 1248 -0.4; 1336 -0.4; 1429 0.1; 1529 -0.3; 1636 -0.0; 1751 -0.4; 1873 -0.3; 2004 0.3; 2145 0.9; 2295 1.8; 2455 2.9; 2627 4.1; 2811 4.3; 3008 5.0; 3219 5.2; 3444 5.2; 3685 5.9; 3943 6.0; 4219 6.0; 4514 6.0; 4830 4.7; 5168 3.1; 5530 4.9; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 -0.2; 9502 -0.7; 10167 -1.0; 10879 -1.2; 11640 -1.1; 12455 -0.2; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Innerfidelity%202017/innerfidelity/onear/Ultrsone%20HFI-450/Ultrsone%20HFI-450.png)