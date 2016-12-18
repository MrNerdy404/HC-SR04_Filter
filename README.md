# HC-SR04_Filter
Custom noise filter function for operation of SR04 ultrasonic sensor in Arduino. 
Limits maximum detection range, establishes wide range sensing of object/target, 
and establishes target ranges/sensor parking range.

No added library needed for Arduino code function
Capable of handling implementation into larger sensor array of SR04's
For more sensors, reappl the structure dictating the run of the shown sonar operation
for as many sensors as needed.
This filter particularly targets limiting erronous false readings of too great a value
as well as limiting the ability for lower value false readings to interfere with readings

Ownership and all rights to the HC-SR04 sensor and its design are reserved by the manufacturer
Datasheet specifications are as per the manufacuters publication.
Provided CAD file may be inported into most platforms and parsed into specific file types.
CAD assembly freely availble through online community sharing. 
