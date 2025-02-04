# Sparkfun TMP102 Examples Reference
Below is a brief summary of each of the example programs included in this repository. To report a bug in any of these examples or to request a new feature or example [submit an issue in our GitHub issues.](https://github.com/sparkfun/qwiic_tmp102_py/issues). 

NOTE: Any numbering of examples is to retain consistency with the Arduino library from which this was ported. 

## Example1-Gettemperature
Simple Example for the Qwiic TMP102 Device

## Example2 One-Shot Temperature Reading
This sketch connects to the TMP102 temperature sensor and enables the
 one-shot temperature measurement mode using the one_shot() function.
 The function returns 0 until the temperature measurement is ready to
 read (takes around 25ms). After the measurment is read, the TMP102 is
 placed back into sleep mode before the loop is repeated. This can be 
 useful to save power or increase the continuous conversion rate from
 8Hz up to a maximum of 40Hz.

 This code is beerware; if you see me (or any other SparkFun employee) at
 the local, and you've found our code helpful, please buy us a round!

 Distributed as-is; no warranty is given.


