# AudioQuest NightHawk Stock Pads
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 -7.6; 22 -7.6; 23 -7.5; 25 -7.5; 26 -7.5; 28 -7.5; 30 -7.4; 32 -7.4; 35 -7.3; 37 -7.3; 40 -7.2; 42 -7.2; 45 -7.1; 49 -7.1; 52 -7.0; 56 -6.9; 59 -6.8; 64 -6.8; 68 -6.8; 73 -6.8; 78 -6.9; 83 -7.2; 89 -7.7; 95 -8.4; 102 -9.3; 109 -9.6; 117 -9.5; 125 -10.1; 134 -10.9; 143 -11.2; 153 -11.3; 164 -10.7; 175 -11.1; 188 -11.4; 201 -11.4; 215 -11.4; 230 -11.3; 246 -11.3; 263 -11.3; 282 -11.1; 301 -11.0; 323 -10.8; 345 -10.5; 369 -10.3; 395 -9.9; 423 -9.5; 452 -9.1; 484 -8.9; 518 -8.2; 554 -7.2; 593 -6.0; 635 -5.1; 679 -4.4; 726 -3.6; 777 -2.8; 832 -2.1; 890 -1.2; 952 -0.4; 1019 -0.1; 1090 -0.6; 1167 -1.0; 1248 -1.2; 1336 -2.2; 1429 -3.1; 1529 -3.7; 1636 -4.0; 1751 -4.1; 1873 -3.8; 2004 -3.2; 2145 -2.6; 2295 -1.9; 2455 -0.2; 2627 1.8; 2811 2.7; 3008 2.8; 3219 1.3; 3444 0.3; 3685 1.7; 3943 4.6; 4219 5.6; 4514 6.0; 4830 5.8; 5168 4.5; 5530 1.8; 5917 -0.4; 6331 -1.0; 6775 -1.9; 7249 -3.3; 7756 -4.4; 8299 -5.0; 8880 -5.1; 9502 -4.4; 10167 -2.6; 10879 -0.4; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 -0.7; 18692 -3.1; 20000 -4.9
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 -7.6; 22 -7.6; 23 -7.5; 25 -7.5; 26 -7.5; 28 -7.5; 30 -7.4; 32 -7.4; 35 -7.3; 37 -7.3; 40 -7.2; 42 -7.2; 45 -7.1; 49 -7.1; 52 -7.0; 56 -6.9; 59 -6.8; 64 -6.8; 68 -6.8; 73 -6.8; 78 -6.9; 83 -7.2; 89 -7.7; 95 -8.4; 102 -9.3; 109 -9.6; 117 -9.5; 125 -10.1; 134 -10.9; 143 -11.2; 153 -11.3; 164 -10.7; 175 -11.1; 188 -11.4; 201 -11.4; 215 -11.4; 230 -11.3; 246 -11.3; 263 -11.3; 282 -11.1; 301 -11.0; 323 -10.8; 345 -10.5; 369 -10.3; 395 -9.9; 423 -9.5; 452 -9.1; 484 -8.9; 518 -8.2; 554 -7.2; 593 -6.0; 635 -5.1; 679 -4.4; 726 -3.6; 777 -2.8; 832 -2.1; 890 -1.2; 952 -0.4; 1019 -0.1; 1090 -0.6; 1167 -1.0; 1248 -1.2; 1336 -2.2; 1429 -3.1; 1529 -3.7; 1636 -4.0; 1751 -4.1; 1873 -3.8; 2004 -3.2; 2145 -2.6; 2295 -1.9; 2455 -0.2; 2627 1.8; 2811 2.7; 3008 2.8; 3219 1.3; 3444 0.3; 3685 1.7; 3943 4.6; 4219 5.6; 4514 6.0; 4830 5.8; 5168 4.5; 5530 1.8; 5917 -0.4; 6331 -1.0; 6775 -1.9; 7249 -3.3; 7756 -4.4; 8299 -5.0; 8880 -5.1; 9502 -4.4; 10167 -2.6; 10879 -0.4; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 -0.7; 18692 -3.1; 20000 -4.9
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Innerfidelity%202017/innerfidelity/onear/AudioQuest%20NightHawk%20Stock%20Pads/AudioQuest%20NightHawk%20Stock%20Pads.png)