# xtcal

xt touchscreen calibration widget and application

## Building

Simply type `make` to build, or `make debug=1` to get additional info.
To rebuild the Calib widget you'll need `wbuild`.


## Usage

Run `xtcal` and the calibration command will be written on stdout.

**Ex.** `xinput set-prop <device name> 'Coordinate Transformation Matrix' a b c d e f g h i`

xtcal will try to go fullscreen, if this doesn't work you need to run with:

`xtcal -geometry <Width>x<Height>`


## Dependencies

`libxaw7-dev`

**To install**

`sudo apt-get install libxaw7-dev`
