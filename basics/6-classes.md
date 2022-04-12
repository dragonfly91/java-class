# Shopping App

Model objects in a shopping app where customers, products and orders have to be managed. Design classes for Customer, Product and Order.

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
    bool isInside(Point p) {
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
// JAVA
class DigitalClock {
    DigitalClock(int hours, int minutes, int seconds);
    
    public void addHours(int hours) { ... }
    public void addMinutes(int minutes) { ... }
    public void addSeconds(int seconds) { ... }
    public void add(DigitalClock digitalClock) { ... }
    
    // This should display the current time in hh:mm:ss format. For example: 19:30:00 would be 7:30 PM
    public void display() { ... }
}
```

```Dart
// DART
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

# Reservation System

Design a system (`ReservationSystem`) to reserve slots in a flexible teaching class. The system should model a list of teachers (`Teacher`) and a list of students (`Student`). Each teacher can teach their class within a set of fixed time ranges (`AvailableSpan`) on any given day (`Date`). Implement the following methods:

```Java
class ReservationSystem {
    List<AvailableSlot> getAvailableSlots(Teacher teacher, Date date) { ... }
}
```

Please feel free to create as many other classes and / or methods as you need.
