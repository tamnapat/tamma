SET mystNumb TO 3
RECIEVE guess FROM KEYBOARD
IF guess > 10
  SEND 'Too high! Your guess must be between 1 and 10.'  
ELSE 
  IF guess = mystNumb  
    SEND 'Well done! Your gussed correctly.'    
  ELSE 
    SEND 'Bad luck! The correct number is' + mystNumb     
  END IF
END IF 
