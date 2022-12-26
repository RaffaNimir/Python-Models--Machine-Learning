# Python-Programs-Fun

# Airline Ticket Number Creator 
### Program asks to put their name, airline , destination and creates a unique ticket number per user
import random 


First_Name = input("Enter Your First Name : ")
while First_Name =='':
  print('You did not enter anaything please re-type your name')
else:
    print('Hello'+ First_Name)
Last_Name = input("Enter Your Last Name : ")
while Last_Name =='':
  print('You did not enter anaything please re-type your answer')

airlines = input("What are your flying with: ")
while airlines =='':
  print('You did not enter anaything please re-type your answer')


destination = input('Where are you flying ? :')
while destination =='':
  print('You did not enter anaything please re-type your answer')

print('Your Ticket Number is: ',First_Name[1:3]+Last_Name[1:3]+airlines+destination[1:2])
