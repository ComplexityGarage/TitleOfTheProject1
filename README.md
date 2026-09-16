# Title of the project
# Authors 
- Bartosz Pióro
- Karolina Nowak
# Description of the project 
Text here... 
# Science and tech used 
The entire system is based on an Arduino board that controls two servo motors. Light detection is performed using four photoresistors separated by a partition, allowing the system to determine the general direction of the strongest light source.

The system has two operating modes: a time-based mode and a light-based mode.

The time-based mode is straightforward. The Arduino calculates the Sun’s position based on the current time and geographical location. At present, the location of Kraków is hardcoded into the program.

The light-based mode uses four photoresistors, each combined with a conventional resistor to form a voltage divider. The Arduino measures the resulting voltages and uses them to determine the general direction from which the strongest light is coming.


# State of the art 
Text & plots here... 
# What next?
Text here... 
# Sources 
- [Writing on GitHub] ( https://docs.github.com/en/get-started/writing-on-github )
