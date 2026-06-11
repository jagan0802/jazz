# Area Calculator Using Method Overloading in Java

## Overview
This project demonstrates the concept of **Method Overloading** in Java by calculating the area of different geometric shapes using the same method name `Area()` with different parameters.

The program calculates:
- Area of a Square
- Area of a Circle
- Area of a Rectangle

## Concepts Used
- Object-Oriented Programming (OOP)
- Classes and Objects
- Method Overloading
- Compile-Time Polymorphism

## Program Description

### AreaCalculator Class
The `AreaCalculator` class contains three overloaded methods:

1. `Area(int side)`
   - Calculates the area of a square.
   - Formula: Side × Side

2. `Area(double radius)`
   - Calculates the area of a circle.
   - Formula: π × r²

3. `Area(double length, double width)`
   - Calculates the area of a rectangle.
   - Formula: Length × Width

### Allan Class
The `Allan` class contains the `main()` method, which:
- Creates an object of `AreaCalculator`.
- Calls the overloaded methods.
- Displays the calculated areas.

## Sample Output

Area of square: 25
Area of circle: 28.26
Area of rectangle: 24.0

## How to Run

1. Save the file as `Allan.java`
2. Compile the program:
   ```bash
   javac Allan.java
   ```
3. Run the program:
   ```bash
   java Allan
   ```

## Example Values Used

| Shape | Input Values | Area |
|---------|-------------|------|
| Square | Side = 5 | 25 |
| Circle | Radius = 3.0 | 28.26 |
| Rectangle | Length = 4.0, Width = 6.0 | 24.0 |

## Future Improvements
- Take user input using Scanner.
- Add area calculations for Triangle and Cylinder.
- Use `Math.PI` for more accurate circle calculations.
- Add input validation.

## Conclusion
This project is a simple demonstration of Java Method Overloading, showing how multiple methods with the same name can perform different tasks based on their parameters.
