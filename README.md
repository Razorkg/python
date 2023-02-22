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
bottle_milk=0.45
bottle_cider=3.85
bag_of_flour=0.9
packet_of_butter=0.77
jar_of_nutella=1.87

order_price = (2*bottle_milk)+(3*bottle_cider)+bag_of_flour+packet_of_butter+jar_of_nutella
print(f"prix total à payer €{order_price:.2f}")



