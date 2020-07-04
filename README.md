# Ultrasonic-Security-System
 security device using an Arduino
link:https://www.tinkercad.com/things/enJg2YdoTCo   |SCHEMATICS|


The  wires connected to the LEDs should be connected in line to the positive side of the LED, while the negative side of the LED should be connected to the
negative channel of the breadboard using a 220 ohm resistor.

To get started, visit Tinkercad's website and create an account or log into an existing one. Then select “Circuits” on the left side of the screen:

Assembly - Breadboard

Time to connect the HC-SRO4 ultrasonic sensor! A great tip is to place the ultrasonic sensor as far right to the breadboard as possible and make sure that it is facing out. 
Referring back to the setup picture, you should connect the GND pin on the ultrasonic sensor to the negative channel on the breadboard. Next connect the Trig pin on the sensor
to pin 2 on the Arduino and connect the Echo pin on the sensor to pin 3 on the Arduino. Lastly, connect the VCC pin on the ultrasonic sensor to the positive channel on the 
breadboard. Refer to the picture above if anything gets confusing.

Assembly - LEDs

The next step is to connect the LED's to the breadboard and Arduino. If you need to, I highly recommend that you refer back to the setup picture (Step 2), attaching the 
LEDs is pretty easy, there's a lot of repetition. Let's first attach the Green LED. So the way to do this, is to connect the anode (the longer leg) to pin 6 on the Arduino
with a green wire, and to connect the cathode (the shorter leg) to the negative channel on the breadboard, using a 220 ohm resistor. Then repeat that step for the Yellow and 
then the Red LED, make sure to connect the anode (the longer leg) of the yellow LED to pin 5 on the Arduino and then connect the anode of the red LED to pin 4. Once you have 
done that, your setup should look similar to the picture above.

Assembly - Buzzer

The last part of the setup for this, is connecting the buzzer to the breadboard and the Arduino. This is one of the easiest parts of the whole setup. All that is required 
to do is to connect the longer leg of the buzzer to pin 7 of the Arduino using a green wire and then connect the shorter leg of the buzzer to the negative channel of the
breadboard using a 220 ohm resistor.

It is HIGHLY recommended to use a resistor in connecting the shorter leg of the buzzer to the negative channel of the breadboard. This greatly reduces the volume of the buzzer
and prevent it from dying to quickly.
