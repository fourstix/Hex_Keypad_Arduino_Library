Hexadecimal 4x4 Keypad
======================
based on [Sparkfun's Qwiic Keypad Arduino Library](https://github.com/sparkfun/SparkFun_Qwiic_Keypad_Arduino_Library)

![4x4 Hex Keypad - 16 Button](https://cdn.sparkfun.com//assets/parts/1/3/1/6/0/14881-Keypad_-_16_Button-01.jpg)

[*SparkFun 4x4 Keypad - 16 Button (Retired Product DD-1481)*](https://www.sparkfun.com/products/retired/14881)

Adafruit sells a similar keypad [*Adafruit 4x4 Matrix Keypad*](https://www.adafruit.com/product/3844)

Keypads are very handy input devices. And there are many great libraries written to interface to keypads! Using this firmware that scans the keys and an 3.3v 8MHz Arduino Pro-Mini, it's easy to create a Hexadecimal Keypad monitors all 16 buttons and allows you to read in any button presses by simply reading over I2C. It also implements a stack with time stamps for each key press so you don't need to constantly poll the keypad.  The asterisk key is mapped to E and the hash key is mapped to F.

With this convenient Arduino Library, you don't need to worry about I2C communication protocol or register addresses. "readButton()" and "readTimeSincePressed()" take care of all the I2C stuff, and simply return the data you want.
Try out the examples in this library and you'll be up and running in no time.

Add a [Sparkfun Qwiic adapter](https://www.sparkfun.com/products/14495), and you have a a Hex Keypad that is very low power and uses less than 4mA at 3.3V.

The Qwiic adapter allows one to use the simple Qwiic interface. No soldering, no voltage translation, no figuring out which pin is SDA or SCL, just plug and go!


Repository Contents
-------------------

* **/examples** - Example sketches for the library (.ino). Run these from the Arduino IDE. 
* **/src** - Source files for the library (.cpp, .h).
* **/firmware/Hex_Keypad_I2C** - Source files for the Arduino firmware (.ino).
* **/docs** - Pinout digram for the Sparfkun 16 Button keypad (.pdf).
* **keywords.txt** - Keywords from this library that will be highlighted in the Arduino IDE. 
* **library.properties** - General library properties for the Arduino package manager. 

Original Sparkfun Qwiic Keypad Documentation
--------------------------------------------
* **[Qwiic Keypad Hookup Guide](https://learn.sparkfun.com/tutorials/qwiic-keypad-hoookup-guide)** - Hookup guide for the Qwiic Joystick
* **[Qwiic Keypad Arduino Library](https://github.com/sparkfun/SparkFun_Qwiic_Keypad_Arduino_Library)** - Arduino library for Qwiic Keypad.
* **[Product Repository](https://github.com/sparkfun/Qwiic_Keypad)** - Main repository (including firmware and hardware files)

License Information
-------------------

This product is _**open source**_! 

Please review the LICENSE file for license information. 

