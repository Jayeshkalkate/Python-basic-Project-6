# Python-basic-Project-6
By using python programming language .
# Temperature Conversion: 
# Convert temperature from Celsius to Fahrenheit and vice versa.

"""
To convert Fahrenheit to Celsius :- C = (F - 32) x 5 / 9

To convert Celsius to Fahrenheit :- F = (C x 9 / 5) + 32
 
Where :- C is the temperature in Celsius and F is the temperature in Fahrenheit.
"""

user_input_temperature_conversion = (input("To convert temperature in celsius or fahrenheit :- \n"))

print(f"You are choice a temoerature conversion option : \n{user_input_temperature_conversion}")

if ("celsius" == user_input_temperature_conversion) :
    celsius = float(input("\nEnter the temperacture to convert celcius into the fehreneit : "))
    temperature_celsius = (celsius * 9 / 5) + 32
    print(f"\nThe conversion of temperature celcius into the fehreneit : {temperature_celsius}")

elif ("fahrenheit" == user_input_temperature_conversion) :
    fahrenheit = float(input("\nEnter the temperacture to convert fahrenheit into the celcius : "))
    temperature_fahrenheit = (fahrenheit - 32) * 5 / 9
    print(f"\nThe conversion of temperature fahrenheit into the celcius : {temperature_fahrenheit}")

else :
    print("\nSomethings is wrong !\nPlease Try Again Later !")
