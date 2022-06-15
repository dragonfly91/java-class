# Shopping App(お買い物のアプリ)

Model objects in a shopping app where customers, products and orders have to be managed. Design classes for Customer, Product and Order.

顧客、商品、注文を管理する必要があるショッピングアプリのオブジェクトをモデル化しましょう。顧客、商品、注文のクラスを設計します。

# Cartesian Coordinate System(直交座標系)

Model a Cartesian coordinate system.

直交座標系をモデル化する。

## Point

Design the Point class. Calculate and print the distance between two points (x<sub>1</sub>, y<sub>1</sub>) and (x<sub>2</sub>, y<sub>2</sub>) using the following formula:

sqrt((x<sub>1</sub> - x<sub>2</sub>)<sup>2</sup> + (y<sub>1</sub> - y<sub>2</sub>)<sup>2</sup>)

Add a new method to the Point class to calculate distance from another point.

```Java
class Point {
    double getDistance(Point point) {
        // TODO
    }
}
```

## Triangle(三角形)

Design the Triangle class. Implement a method in the Triangle class to calculate the perimeter of the triangle.

Triangle クラスを設計します。三角形の周囲長を計算するメソッドをTriangleクラスに実装しましょう。

```Java
class Triangle {
    double getPerimeter() {
        // TODO
    }
}
```

## Square(正方形)

Design the Square class. Implement methods in the Square class to calculate the perimeter and area of the square.

Square クラスを設計する。Squareクラスにメソッドを実装して、正方形の周囲と面積を計算します。

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

## Rectangle(長方形)

Design the Rectangle class. Implement methods in the class to calculate the perimeter and the area of the rectangle.

Rectangle クラスを設計する。長方形の周囲と面積を計算するメソッドをクラス内に実装します。

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

## Circle(円)

Design the Circle class. Implement a method in the Circle class to check if a point is inside the circle or not. The method should return true if the point is inside the circle and false otherwise.

Circleクラスを設計する。ある点が円の内側にあるかどうかを調べるメソッドをCircleクラスに実装しましょう。このメソッドは、点が円の内側にある場合はtrueを、そうでない場合はfalseを返す必要があります。

```Java
class Circle {
    boolean isInside(Point point) {
        // TODO
    }
}
```

### Intersection(交差)

Implement a method in the Circle class to check if two circles c1 and c2 intersect or not. The method should return the state of intersection of the two circles.

2つの円c1、c2が交差しているかどうかを調べるメソッドをCircleクラスに実装しましょう。メソッドは2つの円の交差の状態を返すこと。

```Java
IntersectionState getIntersectionState(Circle circle) {
    // TODO
}

enum IntersectionState {
    Disjoint,
    Touching,
    Intersecting,
    Inside
}
```

## Distance from Line(点と直線の距離)

Extend the Line class to implement a function to get the distance of a point from the line. 

Lineクラスを拡張して、直線からの点の距離を取得する関数を実装しましょう。

Note: if the line passes through two points P<sub>1</sub> = (x<sub>1</sub>, y<sub>1</sub>) and P<sub>2</sub> = (x<sub>2</sub>, y<sub>2</sub>) then the distance of (x<sub>0</sub>, y<sub>0</sub>) from the line is:

![image](../.media/point-distance-from-line.svg)

```Java
class Line {
  double getDistance(Point point) {
      // TODO
  }
}
```

# Complex Numbers(複素数)

Create a class to model complex numbers. The class should support basic arithmetic: addition, subtraction, multiplication and division. Use the following formulae to perform the arithmetic:

複素数をモデル化するクラスを作成しましょう。このクラスは、基本的な算術（加算、減算、乗算、除算）をサポートする必要があります。以下の式を用いて算術を行います。

```
(a + ib) + (c + id) = (a + c) + i(b + d)
(a + ib) - (c + id) = (a - c) + i(b - d)
(a + ib) * (c + id) = (a * c - b * d) + i(a * d + b * c)
(a + ib) / (c + id) = ((a * c + b * d) / (c * c + d * d)) + i((b * c - a * d) / (c * c + d * d))
```

```Java
class ComplexNumber {
    ComplexNumber(double real, double imaginary) { ... }
    
    public ComplexNumber add(ComplexNumber other) { ... }
    public ComplexNumber subtract(ComplexNumber other) { ... }
    public ComplexNumber multiply(ComplexNumber other) { ... }
    public ComplexNumber divide(ComplexNumber other) { ... }
}
```

# DigitalClock(デジタル時計)

Model a digital clock by designing the DigitalClock class. The class should support hours, minutes and seconds as properties. Implement the following methods. With every operation, when the total time exceeds the max time possible, the time should be rolled over. For example 23:59:59 + 00:00:01 would be 00:00:00.

DigitalClock クラスを設計して、デジタル時計をモデル化しましょう。このクラスは、プロパティとして時、分、秒をサポートする必要があります。以下のメソッドを実装してください。操作のたびに、合計時間が最大可能時間を超えたら、時間を繰り越すこと。例えば、23:59:59 + 00:00:01 は 00:00:00 になります。

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

# Matrices(行列)

Design a class to model matrices and support arithmetic operations on two matrices of different dimensions. 

行列をモデル化し，異なる次元の2つの行列に対する算術演算をサポートするクラスを設計しましょう。

- Given the number of rows and columns, the constructor should fill the matrix with random test data. 
- Addition and subtraction of two matrices are supported only if the two matrices have the same dimensions. 
- Multiplication is supported between matrices A and B if and only if the dimensions of A = [mxn] and the dimensions of B = [nxl] and the dimensions of output matrix would be [mxl].

```Java
class Matrix {
    Matrix(int rowCount, int columnCount) { ... }
    
    public Matrix transpose() { ... }
    public boolean isEqualTo(Matrix other) { ... }
    public static Matrix generateIdentity(int size) { ... }
    public Matrix add(Matrix other) { ... }
    public Matrix subtract(Matrix other) { ... }
    public Matrix multiply(double constant) { ... }
    public Matrix multiply(Matrix other) { ... }
}
```
