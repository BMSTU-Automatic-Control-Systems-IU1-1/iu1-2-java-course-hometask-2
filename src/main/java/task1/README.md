# IU1-22B Java course (GUI application development)
## Hometask 2

### Task #1 (Geometric Shapes)

Дописать методы таким образом, чтобы можно было создавать прямую призму с разными основаниями и вычислять площадь поверхности и объем. 
Написать тесты.

Абстрактный класс ```Фигур```
```java
public abstract class Figure2D {
    abstract double area();
}
```

Класс: ```Призма```
```java
public class Prism {
    private Figure2D base;
    private double h;

    public Prism(Figure2D base, double h) {
        this.base = base;
        this.h = h;
    }

    // метод вычисления объема
    public double volume() {
        return 0.0;
    }

    // площадь поверхности
    public double surfaceArea() {
        return 0.0;
    }
}
```

Класс: ```Круг```
```java
public class Circle implements Figure2D{
}
```

Класс: ```Прямоугольник```
```java
public class Rectangular implements Figure2D{
}
```

Класс: ```Трапеция```
```java
public class Trapezoid implements Figure2D{
}
```

Класс: ```Треугольник```
```java
public class Triangle implements Figure2D{
}
```
