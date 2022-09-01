# -make-a-personal-file
this program make a personal file
import os
import time

def clear_console():
    os.system('cls')

enter = input("do you want to make you a File ?\n\nyes or  no  ? ")

yes = "yes"
no = "no"

while enter != yes :
    print("\nok buy :)\n")
    quit()
    
print("\nok wellcome :)\n")

time.sleep(0.5)

clear_console()

esm_f = input("\nplz enter your first name       ? ")
time.sleep(0.1)
clear_console()

esm_l = input("\nplz enter your last name        ? ")
time.sleep(0.1)
clear_console()

b = int(input("\nplz enter your date of birth    ? "))
time.sleep(0.1)
clear_console()

b_1 = 1401 - b

major = input("\nwhat is your major              ? ")
time.sleep(0.1)
clear_console()

father = input("\nWhat is your father's name      ? ")
time.sleep(0.1)
clear_console()

mother = input("\nWhat is your mother's full name ? ")
time.sleep(0.1)
clear_console()

keshvar = input("\nwhare are you from              ? ")
time.sleep(0.1)
clear_console()

city = input("\nWhich city do you live          ? ")
time.sleep(0.1)
clear_console()

phone_number = int(input("\nEnter your phone number         ? "))
time.sleep(0.1)
clear_console()


print(f"\n\nfirst name : {esm_f}\n\nlast name : {esm_l}\n\nbirthdate : {b_1}\n\nmajor : {major}\n\nfather's name : {father} {esm_l}\n\nmother's fullname : {mother}\n\ncontry : {keshvar}\n\ncity : {city}\n\nphone number : {phone_number}\n")
