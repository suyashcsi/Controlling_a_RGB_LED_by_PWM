////Note/////

You cannot distinguish between the common cathode and common anode type by just looking at the RGB led because both look same. You will have to make the connections to see that either it is common cathode or common anode.

The RGB led has one big lead than the other leads. In the common cathode case, it will be connected to GND and in the common anode case; it will be connected to 5V.

///Working///


Inside the RGB led, there are three more led’s. So by changing the brightness of these led’s, we can obtain many other colors. 
To change brightness of RGB led, we can use the PWM pins of Arduino. The PWM pins will give signal different duty cycles to the RGB led to obtain different colors.
