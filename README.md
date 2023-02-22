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


