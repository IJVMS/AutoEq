# Blue MOFI Active On
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 2.3; 22 2.0; 23 1.9; 25 1.6; 26 1.5; 28 1.4; 30 1.2; 32 1.1; 35 0.9; 37 0.8; 40 0.7; 42 0.7; 45 0.7; 49 0.6; 52 0.6; 56 0.6; 59 0.5; 64 0.4; 68 0.3; 73 0.2; 78 0.0; 83 -0.2; 89 -0.5; 95 -1.0; 102 -1.5; 109 -1.7; 117 -2.0; 125 -2.3; 134 -2.8; 143 -3.4; 153 -3.7; 164 -3.3; 175 -3.0; 188 -3.5; 201 -3.5; 215 -3.3; 230 -2.9; 246 -2.4; 263 -1.8; 282 -0.9; 301 -0.3; 323 -0.1; 345 -0.3; 369 -0.2; 395 -0.2; 423 1.0; 452 2.3; 484 2.7; 518 2.6; 554 2.3; 593 2.3; 635 2.2; 679 2.0; 726 1.7; 777 1.4; 832 1.1; 890 0.7; 952 0.2; 1019 -0.0; 1090 -0.0; 1167 0.1; 1248 0.6; 1336 1.2; 1429 1.7; 1529 2.1; 1636 2.5; 1751 2.8; 1873 3.2; 2004 4.1; 2145 4.9; 2295 5.3; 2455 5.3; 2627 6.0; 2811 6.0; 3008 6.0; 3219 6.0; 3444 6.0; 3685 6.0; 3943 5.5; 4219 2.7; 4514 5.6; 4830 6.0; 5168 6.0; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 2.3; 22 2.0; 23 1.9; 25 1.6; 26 1.5; 28 1.4; 30 1.2; 32 1.1; 35 0.9; 37 0.8; 40 0.7; 42 0.7; 45 0.7; 49 0.6; 52 0.6; 56 0.6; 59 0.5; 64 0.4; 68 0.3; 73 0.2; 78 0.0; 83 -0.2; 89 -0.5; 95 -1.0; 102 -1.5; 109 -1.7; 117 -2.0; 125 -2.3; 134 -2.8; 143 -3.4; 153 -3.7; 164 -3.3; 175 -3.0; 188 -3.5; 201 -3.5; 215 -3.3; 230 -2.9; 246 -2.4; 263 -1.8; 282 -0.9; 301 -0.3; 323 -0.1; 345 -0.3; 369 -0.2; 395 -0.2; 423 1.0; 452 2.3; 484 2.7; 518 2.6; 554 2.3; 593 2.3; 635 2.2; 679 2.0; 726 1.7; 777 1.4; 832 1.1; 890 0.7; 952 0.2; 1019 -0.0; 1090 -0.0; 1167 0.1; 1248 0.6; 1336 1.2; 1429 1.7; 1529 2.1; 1636 2.5; 1751 2.8; 1873 3.2; 2004 4.1; 2145 4.9; 2295 5.3; 2455 5.3; 2627 6.0; 2811 6.0; 3008 6.0; 3219 6.0; 3444 6.0; 3685 6.0; 3943 5.5; 4219 2.7; 4514 5.6; 4830 6.0; 5168 6.0; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Headphone.com/innerfidelity/onear/Blue%20MOFI%20Active%20On/Blue%20MOFI%20Active%20On.png)