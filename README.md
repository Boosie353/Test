# Test

This is a test I had to do in order to show my ability to be able to assist in reviewing coding work submitted by others.

I trust the different files will show my ability and provide clarity on my skill set.

# The Section A: Code Review files

This section required that we assist a student who submitted code for review that they had done.
The code was an SMS Simulation using Classes and OOP (Object Oriented Programming).

The student submission was as follows:
Student Question
Hi there,
I'm having a bit of an issue with figuring out how to exactly implement the class
methods so that I may call them outside of the class when trying to create a new
SMS object.
Thanks,
Student

> An SMS Simulation class SMSMessage(object):
hasBeenRead = False messageText = text fromNumber = number
def __init__(self,hasBeenRead,messageText,fromNumber):
self.hasBeenRead = False self.messageText = text
self.fromNumber = number
def MarkASRead(self):
if userChoice == read:
self.hasBeenRead = True
def add_sms():
def get_count():
def get_message():
def get_unread_messages():
def remove():
no_1 = SMSMessage(False, "Hello", "0798653452")
no_2 = SMSMessage(False, "WYD", "0845673864")
no_3 = SMSMessage(False, "How are you?", "0631873298")
SMSStore = [] userChoice = ""
while userChoice != "quit":
userChoice = raw_input("What would you like to do -
read/send/quit?")
if userChoice == "read":
> Place your logic here elif userChoice == "send": 
>Place your logic here elif userChoice == "quit":
print("Goodbye")
else:
print("Oops - incorrect input")


# Section B: Domain Speciality

The Jupyter Notebook used in this section was coded for JavaScript.
In this section we were required to perform Exploratory Data Analysis on a dataset of our choosing and required to do the following:
You then need to:
● Read in the dataset.
● Clean the dataset, motivating your steps.
● Analyse the dataset, including appropriate visualisations
Note down all the findings and conclusions you’re making in a report at the end

# Section C: Problem-Solving

Please implement the K-means algorithm and meet the following requirements:
● For the dataset, generate the dataset using built-in tools from the
programming language. Use your preferred labels for the outputs.
● There should be two options to train the model: either train the model with
defaults for the number of iterations and the “k” value or accept user input
for the same values.
● Present your findings regarding the clusters, either using visualisations (for
this, pick any library you see fit) or by printing them in a tabular format.
● Pick any evaluation metric(s) you see fit and report on your findings.
