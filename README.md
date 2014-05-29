Simple NeoPixel library
=========================

A drop in replacement for the [AdaFruit NeoPixel library][adafruit_neopixel_library] that uses simplified code and timing for driving the pixels.

The benifits of this appraoch are:

1) Easier to read & understand
2) Easier to change
3) Leaves interrupts on so stuff like [SoftSerial][SoftSerial] and [Manchester][manchester] will work

Note that this code has only been tested on WS2812 Neopixels like the [Adafruit 60 LED/meter Digital LED strip][strip], the [Adafruit FLORA RGB Smart Pixel][flora], the [Adafruit Breadboard-friendly RGB Smart Pixel][pixel], and the [Adafruit NeoPixel Stick][stick], along with lots that you can get on eBay and Alibaba.

After downloading, rename folder to 'Simple_NeoPixel' and install in Arduino Libraries folder. Restart Arduino IDE, then open File->Sketchbook->Library->Simple_NeoPixel->strandtest sketch.

[flora]:  http://adafruit.com/products/1060
[strip]:  http://adafruit.com/products/1138
[pixel]:  http://adafruit.com/products/1312
[stick]:  http://adafruit.com/products/1426
[shield]: http://adafruit.com/products/1430
[adafruit_neopixel_library]: https://github.com/adafruit/Adafruit_NeoPixel
[SoftSerial]: https://github.com/arduino/Arduino/blob/master/libraries/SoftwareSerial/SoftwareSerial.cpp
[manchester]: https://github.com/mchr3k/arduino-libs-manchester
