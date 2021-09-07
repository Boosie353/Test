So you need to first create the SMSMessage Class():
You would then need to initialise the class through a constructor and set the parameters ie. self.messageText = messageText for example
This will need to be done for all 3 parameters by defining them in the initialisation

Below is an example using a Person class and how it is initialised using a constructor. See the style in which the code is written. 
You will need to mind the indents when writing your code otherwise you will get an error

class Person:
   def __init__(self, name, age):
     self.name = name
     self.age = age

You will then have to create define functions for each parameter as you have begun to do for the MarkAsRead parameter

You will then need to complete the userschoice if function with elif for all the other options available to the user ie. read, send etc.

userChoice "" needs to be on it's own line so the object can be called on its own to present the user with the userchoice= raw_input option

Please look at the following site https://docs.python.org/3/tutorial/classes.html for examples on classes and objects in order to complete this task to the best of your ability and observe the code writing style in each of the examples provided.

Remember to make notes using # on your code to provide a better understanding of your code