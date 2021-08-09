# Find the area and median of Trapezoid

## what is a trapezoid ?

A trapezoid is four sided shape with two parallel sides , one longer than the other , and two lines that connect those two sides . Few examples of trapeziums in real life are roofs of houses , table tops, windows and doors, pencil boxes etc . A trapezoid is a quadrilateral with one pair of opposite sides parallel .

* area and median of trapezoid using python with functions and without functions .

```
# Area and median of the trapezoid is : 

a+b/2*h

a+b/2
```
Where a and b are the two bases and h is the height of the Trapezoid. And, we can calculate the median of a Trapezoid using the following formula

we can also find area if we know the median :

```
median*h
```
This python program allows the user to enter both sides of the Trapezoid and height . Using those values , this Python program will calculate the Area of a trapezoid and Median of a Trapezoid .

```
a = float(input("enter the 1st parllel line value"))
b = float(input("enter the 2nd parllel line value"))
c = float(input("enter the height value"))

area = 0.5 *(a+b)* h
median = 0.5 *(a+b)
print("\n Area of a Trapezium = %.2f " %area)
print(" Median of a Trapezium = %.2f " %median)
```

The below statements will ask the user to enter a , b and height values and it will assign the user input values to respected variables. Such as first value will be assigned to a , second value to b and third value to c

```
a = float(input("enter the 1st parllel line value"))
b = float(input("enter the 2nd parllel line value"))
c = float(input("enter the height value"))
```

## output
```
enter the 1st parllel line value : 6
enter the 2nd parllel line value : 9
enter the height value : 4
Area of a Trapezium = 30.00 
Median of a Trapezium = 7.50 
```
so now with using of functions we can find area and median of a trpezoid . 

# using functions
```
def Area_of_a_Trapezoid (base1, base2, height):
    Area = 0.5 * (base1 + base2) * height
    Median = 0.5 * (base1+ base2)
    print("\n Area of a Trapezium = %.2f " %Area)
    print(" Median of a Trapezium = %.2f " %Median)
Area_of_a_Trapezoid (9, 6, 4)

```
In this Python Program to find Area of a Trapezoid example, First , We defined the function with three arguments using def keyword. It means, User will enter the base1, base2 and height of a Trapezoid . Next, We are Calculating the Median and Area of a Trapezoid as we described in our first example .