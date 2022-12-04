# python program to compound interest 
p = float(input("enter the principal amount:"))
t = float (input("enter the number of year:"))
r = float (input("entet the rate of interest :"))
ci = p *(pow((1+r/100 ),t))
print("compaund interest :{}".format(ci))
