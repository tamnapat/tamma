RECIEVE temp FROM KEYBOARD
IF temp < 18 THEN
  SEND 'Cold, the perfect temperature for sleep is 18-21 degrees.' TO DISPLAY  
ELSE
  IF temp > 21 THEN
    SEND 'Perfect!' TO DISPLAY
  ELSE
    Send 'No!, the perfect temperature for sleep is 18-21 degrees.'
  END IF
END IF
