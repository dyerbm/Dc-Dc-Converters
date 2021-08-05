# Dc-Dc-Converters
A place to store all the dc-dc converter designs I make. (If I ever get around to putting them here I guess)


# Buck Boost Converters
## 5V2A_buckboost_LTM4661

Simple buck-boost converter to take 0.7-5.5V and convert to 5V 2A. Uses a right angle xt30 connector to easily interface with a Lipo battery. Initial voltage must be above 1.8V to start but can drop to 0.7 during opperation. Includes a simple ADC communicating over I2C in order to read off battery voltage.

Note: The LTM4661 is a BGA package and will require some skill to solder, however it allows this board to be quite small.
