f = int(input ("What is the temperature in Fahrenheit? "))

c = 5*(f-32)//9

print ("A temperature of " + str(f) + " Fahrenheit is " + str(c) + " in Celsius.")

if c >= 100:
	print ("Water does boil at this temperature (under typical conditions)")
else:
	print ("Water does not boil at this temperature (under typical conditions)")
