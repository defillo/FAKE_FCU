# FAKE_FCU
Get Battery voltage and altimeter reading on DJI FPV googles without using a 'real' FCU
Measure pressure at startup and show altitude in DJI GOOGLES in upper left side, in meter
Only positive altitude. no bother to calculate negative
handling the BMP280 device was a pain in the ass :-) due to floating point calculations for calibration. anyway it works. amazing to notice that all data is retreived msb first, while conversion parameters are stored lsb first. just need some time to realize it.. 
THIS DEVICE IS FREE FOR PERSONAL USE ONLY
HERE YOU WILL FIND EVERYTHING NEEDED FOR REALIZE YOUR BOARD FOR PERSONAL USE
IF YOU WANT TO PRODUCE FOR COMMERCIAL PURPOSES, PLEASE CONTACT ME AT defilippis1962@gmail.com
with shown resistors values, (51K, 10K) board does not need any calibration, better if you use 1% type
IF you need to calibrate, there are 3 pins in the lower part of the board. shortening the mid one with the rightmost one, will decrease the voltage reading. Shorten the middle one with the leftmost pin, will increase. once set, data is saved in eeprom.While tuning, check the voltage reading in the googles after reading with a voltmeter

use pickit2, pickit3, pickit 4 to program board. only 4 pins are used: Vpp (dotted one), GND, PGD, PGC
 Power the board from the two right pins, up to 6S (only vista)
 Power air unit or vista on the left side. pins from upper side are +V, GND, TX, RX. same sequence as air unit cable
 
 
