# Arduino NMEA Checksum

![](https://github.com/tomashubelbauer/arduino-nmea-checksum/workflows/ci/badge.svg)

[**LIVE**](https://tomashubelbauer.github.io/arduino-nmea-checksum)

NMEA implementation for Arduino.

Example output:

```
$POV,P,1018.35*39..
$test*16..
$POV,P,951.78*05..
$POV,P,951.84*06..
```

Check out `.github/workflows/ci.yml` to see how to run this sketch in an emulator.

## To-Do

### Figure out why using SimAVR through Aptitude results in a crash

See related work in the `apt-simavr` branch.

### Fix the Builder not being able to find dependencies

Currently the optional build with Builder fails because of this.

### Run SimAVR on both the Arduino CLI and the Arduino Builder builds

Compare both to the expected output.
