SEND "Temperature: " TO DISPLAY
RECEIVE Temp FROM KEYBOARD
IF Temp < 18 THEN
  SEND "Cold, the perfect temperature for sleep is 18-21 degrees." TO DISPLAY
ELSE
  IF Temp > 21 THEN
    SEND "No!, the perfect temperature for sleep is 18-21 degrees." TO DISPLAY
  ELSE
    SEND "Perfect" TO DISPLAY
  END IF
END IF
