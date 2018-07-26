# Ultrasone HFI-450
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 6.0; 32 6.0; 35 6.0; 37 6.0; 40 6.0; 42 6.0; 45 6.0; 49 5.8; 52 5.3; 56 4.4; 59 3.8; 64 2.7; 68 2.3; 73 2.4; 78 3.0; 83 2.7; 89 1.4; 95 0.3; 102 -0.5; 109 -0.9; 117 -1.2; 125 -0.9; 134 -0.9; 143 -1.1; 153 -1.2; 164 -0.7; 175 -0.1; 188 -0.2; 201 -0.1; 215 -0.1; 230 -0.1; 246 -0.5; 263 -1.5; 282 -2.5; 301 -3.2; 323 -3.7; 345 -4.0; 369 -3.5; 395 -3.2; 423 -3.6; 452 -3.6; 484 -3.3; 518 -2.8; 554 -2.1; 593 -1.5; 635 -1.2; 679 -1.2; 726 -1.1; 777 -0.6; 832 -0.3; 890 -0.3; 952 -0.2; 1019 0.0; 1090 0.0; 1167 -0.1; 1248 -0.2; 1336 -0.1; 1429 0.4; 1529 0.6; 1636 0.5; 1751 -1.0; 1873 -2.1; 2004 -2.1; 2145 -1.6; 2295 -0.7; 2455 0.3; 2627 1.5; 2811 2.7; 3008 3.4; 3219 3.0; 3444 2.2; 3685 3.7; 3943 6.0; 4219 6.0; 4514 6.0; 4830 6.0; 5168 4.9; 5530 2.2; 5917 5.0; 6331 5.5; 6775 1.5; 7249 1.2; 7756 0.3; 8299 -0.2; 8880 -1.8; 9502 -2.7; 10167 -2.5; 10879 -2.1; 11640 -1.8; 12455 -1.5; 13327 -0.2; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 6.0; 32 6.0; 35 6.0; 37 6.0; 40 6.0; 42 6.0; 45 6.0; 49 5.8; 52 5.3; 56 4.4; 59 3.8; 64 2.7; 68 2.3; 73 2.4; 78 3.0; 83 2.7; 89 1.4; 95 0.3; 102 -0.5; 109 -0.9; 117 -1.2; 125 -0.9; 134 -0.9; 143 -1.1; 153 -1.2; 164 -0.7; 175 -0.1; 188 -0.2; 201 -0.1; 215 -0.1; 230 -0.1; 246 -0.5; 263 -1.5; 282 -2.5; 301 -3.2; 323 -3.7; 345 -4.0; 369 -3.5; 395 -3.2; 423 -3.6; 452 -3.6; 484 -3.3; 518 -2.8; 554 -2.1; 593 -1.5; 635 -1.2; 679 -1.2; 726 -1.1; 777 -0.6; 832 -0.3; 890 -0.3; 952 -0.2; 1019 0.0; 1090 0.0; 1167 -0.1; 1248 -0.2; 1336 -0.1; 1429 0.4; 1529 0.6; 1636 0.5; 1751 -1.0; 1873 -2.1; 2004 -2.1; 2145 -1.6; 2295 -0.7; 2455 0.3; 2627 1.5; 2811 2.7; 3008 3.4; 3219 3.0; 3444 2.2; 3685 3.7; 3943 6.0; 4219 6.0; 4514 6.0; 4830 6.0; 5168 4.9; 5530 2.2; 5917 5.0; 6331 5.5; 6775 1.5; 7249 1.2; 7756 0.3; 8299 -0.2; 8880 -1.8; 9502 -2.7; 10167 -2.5; 10879 -2.1; 11640 -1.8; 12455 -1.5; 13327 -0.2; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Innerfidelity%202017/headphoncecom/onear/Ultrasone%20HFI-450/Ultrasone%20HFI-450.png)