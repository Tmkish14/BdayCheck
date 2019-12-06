# BdayCheck
This program checks to see if a date corresponds with a birthday.

It also provides the user with the zodiac sign of a date along with a random novelty birthday message.

The program first imports the nescessary modules, then establishes a database of names with their corresponding birthdays.

Next, the program etstablishes a dictionary of novelty birthday messages.

These messages are then converted to a dataframe using the pandas module.

The random module is then utilized to assign a random number to a message, and the mesage is stored in a variable fo use later.

Next, the program then prompts a user to enter a name.

The name is then checked against the database using a while loop.

If it matches, it will return the corresponding birthday.

The program will also print the random message generated earlier.

Next, the program will take input from the user in the form of a day and month.

In order to prevent any errors with capitalization from the input, the month is converted to lowercase.

The month and day are then checked to see if they match the time-frame of an astrological sign using conditional statements.

If the date matches a certain astrological sign, the name of the sign is stored in a variable, then displayed to the console.

If the date is not entered in the correct form, an "invalid answer" message is printed to the console.
