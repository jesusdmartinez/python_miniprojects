# Trip Cost Calculator

Create a command-line program that follows the outlined specs.

Receive the following arguments from the user:

- kilometers to drive
- liters-per-kilometer usage of the car 
- price per liter of fuel

Display the cost of the trip to the user in the console.

kilo = int(input("enter kilometers to drive pls"))
liters_p_kilo = int(input("enter liters per kilo your car uses yo"))
price_p_liter = int(input("enter the price g"))
print(kilo * price_p_liter * liters_p_kilo)
