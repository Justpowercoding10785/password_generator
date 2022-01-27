# password_generator
-------Created By Justpowercoding10785-------
This program was created in python using Visual Studio Code .
Source code of the program will be pasted here .
You are free to distrubute and reproduce this program in the following conditions :- 
$ You should mention who the original author was ( Me - Justpowercoding10785 ) .
$ You are also free to add code to contribute and make this project better .
$ You can also mention the areas you added your own code .
$ This program is free and shouldn't be sold as a paid software .
-------Thank You for you Co-operation-------

-------Source Code-------
# Created by Justpowercoding10785
import random

chars = "abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ!@#$%^&*()-_=+[]\/<>,.?`~1234567890"

while 1:
    print("-------------------Created By BOSS-------------------")
    password_len = int(input("What length would you like your password to be : "))
    password_count = int(input("How many passwords would you like : "))
    for x in range(0,password_count):
        password = ""
        for x in range(0,password_len):
            password_char = random.choice(chars)
            password      = password + password_char
        print("Here is your password : ", password)  
        
