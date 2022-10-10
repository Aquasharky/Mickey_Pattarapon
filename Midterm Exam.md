SEND "please enter temperature" TO DISPLAY
RECIEVE temperature_number FROM KEYBOARD
IF temperature_number < 18 THEN
SEND "Cold, the perfect temperature for sleep is 18-21 degrees" TO DISPLAY
ELSE IF temperature_number > 21 THEN
SEND "Perfect" TO DISPLAY
ELSE SEND "No, the perfect temperature for sleep is 18-21 degrees"
END IF
END IF
