# Expression examples:
If you don't understand any example, don't worry, just skip it for now. Understanding will come naturally as you progress through the course.
## Arithmetic Expressions
Here, we have simple arithmetic expressions. sum_result stores the sum of x and y, product_result stores the product of x and y, and division_result stores the result of dividing y by x.
```
x = 5
y = 10

sum_result = x + y
product_result = x * y
division_result = y / x
```

## String concatenation
full_name contains the concatenation of first_name and last_name with a space in between.
```
first_name = "John"
last_name = "Doe"

full_name = first_name + " " + last_name
```

## Boolean Expressions
is_adult will be True if age is greater than or equal to 18, and False otherwise.
```
age = 25

is_adult = age >= 18
```

## List Comprehension
squared_numbers contains the squares of each number in the numbers list.
```
numbers = [1, 2, 3, 4, 5]

squared_numbers = [x**2 for x in numbers]
```

## Function Call
Here, a function calculate_area is defined to calculate the area of a circle. The result is stored in area_of_circle by passing a radius of 4 to the function.
```
def calculate_area(radius):
    return 3.14 * radius**2

area_of_circle = calculate_area(4)
```

## Logical Expression
This example uses logical expressions. should_stay_inside is True only if it is raining (is_raining is True) and it is not cold (not is_cold is True).
```
is_raining = True
is_cold = False

should_stay_inside = is_raining and not is_cold
```
