"""Exo Drill : Basics python syntax ex6"""
age = 32
age += 10
divAge = age / 7
textDiv =f"{age} divided by 7 equals {divAge}"
restDiv = age % 7
expDiv = restDiv ** 3
print(expDiv)

"""7"""
a=int(5)
b=int(10)
print(type(a+b))

"""8"""
#Define price
bottle_milk=0.45
bottle_cider=3.85
bag_of_flour=0.9
packet_of_butter=0.77
jar_of_nutella=1.87

order_price = (2*bottle_milk)+(3*bottle_cider)+bag_of_flour+packet_of_butter+jar_of_nutella

#define allowanceMoney
allowanceMoney = 20

#Calcule de balance après substracte order_price
available_money = allowanceMoney - order_price

if available_money >= 0:
    message = f"You have spent {order_price:.2f} , you have {available_money:.2f} left."
    allowanceMoney = available_money
elif available_money < 0:
    amount_missing = abs(available_money)
    message = f"sorry You're missing € {amount_missing:.2f}."
else:
    message= "You are broke!"
        
print(message)

#9
num1 = float(input("Entrez le premier numero"))
num2 = float(input("Entrez un deuxième numéro"))

if num1 < num2:
    print("le plus petit numero est", num1)
else: 
    print("le plus petit numero est", num2)
    
    
    #10
string1 = input("Enter the first string: ")
string2 = input("Enter the second string: ")

if len(string1) > len(string2):
    print("The largest string is:", string1)
else:
    print("The largest string is:", string2)
    
    
#11
string1 = input("Enter the first string: ")
string2 = input("Enter the second string: ")

if len(string1) > len(string2):
    print("The largest string is:", string1)
else:
    print("The largest string is:", string2)
    
#12

studentsTuring = ["Redouane", "Justine", "Ruben", "Edouard"]
name = "Julie"

if name in studentsTuring:
    print("You are at the Turing's")
else:
    print("You are not part of the Turing's")
    
    
   #retry

currency = input("Entrez 'E' pour EUROS ou '^$' pour DOLLARS")
amount = float(input("Entrez le montant"))

if currency == 'E':
    conversion_rate = 1.06 
    converted_amount = amount*conversion_rate
    print(f"vos {amount} euros valent {converted_amount} DOLLARS" )
elif currency == '$':
    conversion_rate = 0.94
    converted_amount = amount*conversion_rate
    print(f"vos  {amount} $ valent {converted_amount} euros")
else: 
    print("Recommencez")
    
    
#1.1
count_alpha = len("Hello World")
print(count_alpha)

#1.2
count_alpha = 10
count_float = float(count_alpha)

#1.3
import math
pi = math.pi
round_pi = round(pi, 2)
print(round_pi)

#1.4
text = "Hello world"
reversed_text = list(reversed(text))
print(reversed_text)
#1.5
age  = input("Quel est votre âge?")
print(f"vous avez {age} ans")
print(type(age))
#1.6
num  = [2,8,1,4,6,3,7]
sorted_num = sorted (num)
#1.7
num = [2,8,1,4,6,3,7]
sum_of_list = sum (num)
#1.8
num = [2,8,1,4,6,3,7]
max_value = max (num)

print(num)

    


    

