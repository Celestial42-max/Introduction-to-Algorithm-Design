# Introduction-to-Algorithm-Design
# Task 1 Write pseudo code that reads two numbers and multiplies them together and print out their product. 
BEGIN
READ number1
READ number2
product ← number1 * number2
PRINT product
END



  # Task 2 Write pseudo code that tells a user that the number they entered is not a 5 or a 6. 
BEGIN
  READ number
  IF number ≠ 5 AND number ≠ 6 THEN
    PRINT "The number is not a 5 or a 6."
    ENDIF
END


# Task 3 Write pseudo code that performs the following: Ask a user to enter a number. If the number is between 0 and 10, write the word blue. If the number is between 10 and 20, write the word red. if the number is between 20 and 30, write the word green. If it is any other number, write that it is not a correct color option.
BEGIN
READ number
IF number >= 0 AND number <= 10 THEN
PRINT "blue"
ELSEIF number > 10 AND number <= 20 THEN
PRINT "red"
ELSEIF number > 20 AND number <= 30 THEN
PRINT "green"
ELSE PRINT " it is not correct color"
END

