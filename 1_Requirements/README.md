# OBJECTIVE
 When the button is pressed, one set of LEDs is turned on, and when the button is released, the LEDs are turned off. The reverse result occurs in the other set.
# INTRODUCTION
 The push button switch is a type of control switch appliance that is frequently used to turn on and off the control circuit. It's utilised to provide manual control signals to contactors, relays, and electromagnetic starters in electrical automatic control circuits. Its distinctive feature is that it is installed in a machine or instrument in the course of work, remains in the initial free state position for the majority of the time, and is only converted to the second state (position) when required by an external force.
# PRINCIPLE
 We'll learn how to use a push button switch to regulate the operation of two LEDs. We'll connect the two LEDs to PB2 and PB3 of the microcontroller's PORTB. A push button switch is connected to the PB0 pin and a 10K resistor is used to pull it up. The switch's remaining terminal is grounded. The purpose of a pull-up resistor is to ensure that the status of the PB0 pin remains high while the switch is not pressed. The ATmega chip has 20K pull-up resistors that can also be accessible through software. However, we're using an external pull-up circuit in this case. The two LEDs will illuminate when the switch is pressed.
 # COMPONENTS USED
  1.Two Push Button
  2.Resistor 10k(2)
  3.ATMEGA328 Microcontroller
  4.Light Emitting Diode(2)
  5.Resistor 330(2)
  
