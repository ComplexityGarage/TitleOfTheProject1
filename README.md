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

By default, the system operates in light-based mode. It can be switched to time-based mode by pressing and holding the button for a few seconds.

The Arduino can also be controlled via the Serial Monitor. Currently, after every power outage, the system resets to the default UNIX time, so the current date and time need to be set manually using the CZAS command.

MANUAL – switches to manual mode. The servos move only when controlled with S1 and S2.
AUTO – switches back to automatic mode.
CALC – switches to calculation mode, where the Sun’s position is calculated from the date and time.
S1 angle – sets the angle of servo 1 (0–180°). Available only in manual mode.
S2 angle – sets the angle of servo 2 (0–180°). Available only in manual mode.
CZAS hour:minute day-month-year – sets the current date and time.
FORMAT – displays the required format for entering the date and time.

# State of the art 
Text & plots here... 
# What next?
Text here... 
# Sources 
- [Writing on GitHub] ( https://docs.github.com/en/get-started/writing-on-github )
