SEND "Enter Height(meters)" TO DISPLAY
RECIEVE h FROM KEYBOARD
SEND "Enter Weight(kilograms)" TO DISPLAY
RECIEVE w FROM KEYBOARD
SET bmi TO (w/h)^2
IF bmi < 18.5:
  SEND "Under Weight" TO DISPLAY
ELIF bmi <= 24.9:
  SEND "Normal Weight" TO DISPLAY
ELSE:
  SEND "Over Weight" TO DISPLAY
END IF
