SEND 'what is the temperature?' TO DISPLAY 
RECEIVE Temperature FROM KEYBOARD 
IF Temperature < 18 THEN 
SEND "Cold, the perfect temperature for sleep is 18-21 degrees" TO DISPLAY 
ELSE 
IF Temperature > 21 THEN
SEND "Perfect!" TO DISPLAY 
ELSE 
SEND "No!, the perfect temperature for sleep is 18-21 degrees" TO DISPLAY 
END IF 
END IF
