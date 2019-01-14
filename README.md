Arduino CW decoder
================================

http://www.skovholm.com/cwdecoder

EASY BUILD CW DECODER BASED ON DSP GOERTZEL CODE
--------------------------------------

 If you want to build a cw decoder without using other active components than an atmel 328 - Arduino UNO , then this is sure something for you.

The magic in this code is the tone detection based on the goertzel formular, which means that you just put in the audio on an analog pin and then the processor make some calculations and if there is a tone you will get a magnitude value.

Here is a video where you can see the decoder in function ..Hardware build by OZ2HNS for use in our clubstation OZ8SMA

[Arduino morse decoder cw goertzel DSP](https://www.youtube.com/watch?v=zbQFlzbDb8w "Arduino morse decoder cw goertzel DSP")

You can read about the goertzel formular here :

[Goertzel algorithm](http://en.wikipedia.org/wiki/Goertzel_algorithm "Goertzel algorithm")

[The Goertzel Algorithm](http://courses.cs.washington.edu/courses/cse466/12au/calendar/Goertzel-EETimes.pdf "The Goertzel Algorithm")

![Schematic](https://raw.githubusercontent.com/mrgadotti/skovholm_cw_decoder/master/doc/cwdecoder%20_%20www.skovholm.com_files/decoder_schem.png)
