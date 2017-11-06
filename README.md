# HP-23er-23es-Monitor-Calibration
Calibrated HP 23er 23es Monitor Settings


## Brightness and Contrast
`Main Menu > Brightness... > 43` (or desired brightness).

`Main Menu > Contrast... > 65`.


## Colour Calibration

By default, the monitor appears too yellow / green.
```
Main Menu > Color Control... > Custom RGB... 
R: 245
G: 239
B: 254
```

## Gamma Calibration

By default, the gamma is set too high. There is OSD controls to fix this. Hence, use the gamma-calibrated icc file.

Download [HP 23es Calibrated.icc](https://raw.githubusercontent.com/younglim/HP-23er-23es-Monitor-Calibration/master/HP%2023es%20Calibrated.icc) profile.


### Mac OS X / maOS
- Copy and Paste the .icc file to `/Users/YOUR_USERNAME/Library/ColorSync/Profiles` .
- Go to  > System Preferences > Displays > Color > HP 23es Calibrated.icc.


### Windows
- Open Start. Search for Color Management and click the result.
- On the Devices tab, select the display for which you want to change the color profile from the drop-down menu.
- Check the Use my settings for this device option.
- Click the Add button.
- On the Associate Color Profile page, click the Browse button and locate the color profile downloaded earlier.
- Double-click the .icc file to install the new profile.


## Sharpness

By default, the sharpess is set too high. 

```
Main Menu > Image Control > Sharpness > Level 3
```