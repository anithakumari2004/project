#define the menu of restaurant
menu = {
    "pizza":150,
    "Burger":60,
    "Pasta":90,
    "Maggie":30,
    "Coffee":100,
    }

#Greet
print("Welcome to Anita Restaurant")
print("pizza=150\nBurger=60\nPasta=90\nMaggie=30\nCoffee=100")

order_total = 0

item_1 = input("Enter the name of item you want to order:")
if item_1 in menu:
    order_total+=menu[item_1]
    print(f"your item {item_1} has been added to youur order")
else:
    print(f"ordered item {item_1} is not available yet!")
          
another_order = input("Do you want to add another item? ")
if another_order == "yes":
    item_2 = input("Enter the name of second item:")
    if item_2 in menu:
        order_total+=menu[item_2]
        print(f"Item {item_2} has been added to order")
    else:
        print(f"ordered item {item_2} is not available!")
another_order2 = input("Do you want to add more item?")
if another_order2 =="Yes":
    item_3 = input("Enter the name of third item:")
    if item_3 in menu:
        order_total+=menu[item_3]
        print(f"Item {item_3} has been added to your order")
    else:
            print(f"ordered item {item_3} is not available")
print(f"The total amount of item is {order_total}")


