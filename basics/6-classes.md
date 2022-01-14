# Inventory

Model an inventory system where customers, products and orders have to be managed. Design classes for Customer, Product and Order.

# Cartesian Coordinate System

Model a Cartesian coordinate system.

## Point

Design the Point class. Calculate and print the distance between two points (x<sub>1</sub>, y<sub>1</sub>) and (x<sub>2</sub>, y<sub>2</sub>) using the following formula:

sqrt((x<sub>1</sub> - x<sub>2</sub>)<sup>2</sup> + (y<sub>1</sub> - y<sub>2</sub>)<sup>2</sup>)

Add a new method to the Point class to calculate distance from another point.

```Java
class Point {
    double getDistance(Point p) {
        // TODO
    }
}
```

## Triangle

Design the Triangle class. Implement a method in the Triangle class to calculate the perimeter of the triangle.

```Java
class Triangle {
    double getPerimeter() {
        // TODO
    }
}
```

## Square

Design the Square class. Implement methods in the Square class to calculate the perimeter and area of the square.

```Java
class Square {
    double getPerimeter() {
        // TODO
    }
    
    double getArea() {
        // TODO
    }
}
```

## Rectangle

Design the Rectangle class. Implement methods in the class to calculate the perimeter and the area of the rectangle.

```Java
class Rectangle {
    double getPerimeter() {
        // TODO
    }
    
    double getArea() {
        // TODO
    }
}
```

## Circle

Design the Circle class. Implement a method in the Circle class to check if a point is inside the circle or not. The method should return true if the point is inside the circle and false otherwise.

```Java
class Circle {
    double isInside(Point p) {
        // TODO
    }
}
```

### Intersection

Implement a method in the Circle class to check if two circles c1 and c2 intersect or not. The method should return the state of intersection of the two circles.

```Java
IntersectionState getIntersectionState(Circle c1, Circle c2) {
    // TODO
}

enum IntersectionState {
    Disjoint,
    Touching,
    Intersecting,
    Inside
}
```

## Distance from Line

Extend the Line class to implement a function to get the distance of a point from the line. 

Note: if the line passes through two points P<sub>1</sub> = (x<sub>1</sub>, y<sub>1</sub>) and P<sub>2</sub> = (x<sub>2</sub>, y<sub>2</sub>) then the distance of (x<sub>0</sub>, y<sub>0</sub>) from the line is:

![image](../.media/point-distance-from-line.svg)

```Java
class Line {
  double getDistance(Point p) {
      // TODO
  }
}
```

# DigitalClock

Model a digital clock by designing the DigitalClock class. The class should support hours, minutes and seconds as properties. Implement the following methods. With every operation, when the total time exceeds the max time possible, the time should be rolled over. For example 23:59:59 + 00:00:01 would be 00:00:00.

```Java
class DigitalClock {
    DigitalClock(this.hours, this.minutes, this.seconds);
    
    addHours(int h) { ... }
    addMinutes(int m) { ... }
    addSeconds(int s) { ... }
    add(DigitalClock d) { ... }
    
    // This should display the current time in hh:mm:ss format. For example: 19:30:00 would be 7:30 PM
    display() { ... }
}
```

# Array Class

Create a class Array which:
1. Consumes the size in the constructor and prefills it with random numbers from 0 to 100. The size needs to obtained from the user.
2. Implements `Array.print()` method, which prints the contents of the array in a single line, separated by `,`.

Expected Input:

```
Input a value for array size: 5
```

Expected Ouptut:

```
Array: 3, 66, 90, 4, 12
```

3. Implements `Array.getSum()`, which returns the sum of values in the array.
4. Implements `Array.getAverage()`, which returns the average of the values in the array.
5. Implements `Array.getProduct()`, which returns the product of the values in the array.
6. Implements `Array.getMinimum()` and `Array.getMaximum()`, which return the minimum and maximum values in the array respectively.

Expected Ouptut:

```
Sum: 175
Average: 35
Product: 855360
Maximum: 90
Minimum: 3
```

7. Implements `Array.find(int key)`, which checks if `key` is present in the array and returns its index and `-1` otherwise.

Expected Input:

```
Input a value for key: 3
```

Expected Ouptut:

```
3 is present in the array at index 0
```

Expected Input:

```
Input a value for key: 5
```

Expected Ouptut:

```
5 is not present in the array
```
