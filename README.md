Modified Files


display.cpp: edited displayCharPositionWrite function to remove cases '2' and '3' because we are only utilizing cases '0' and '1', considering we only have a 2 row LCD display


user_interface.cpp: edited userInterfaceDisplayUpdate function to change and reposition the text that is sent to the LCD display to make it all fit, and also add in ° before the C
