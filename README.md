#Convert Celsius to Fahrenheit and vice versa
#Fahrenheit = (C*9/5)+32
#Celsius = (F -32) *5/9

quarry=input("Are you wanting to convert to Celsius 'c' or Fahrenheit 'f':  ")
if quarry == "c":
    c_convert = input("What is the temperature in Fahrenheit that you want to convert?  ")
    c = float(c_convert)
    c = ((c-32)*5)/9
    c = int(c)
    print(f"The converted temperature is {c} degrees Celsius")
elif quarry == "f":
    f_convert = input("What is the temperature in Celsius that you want to convert?  ")
    f = float(f_convert)
    f = ((f*9)/5)+32
    f = int(f)
    print(f"The converted temperature is {f} degrees Fahrenheit")
else:
    print("Please enter c or f to perform conversion")
