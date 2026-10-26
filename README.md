# Experiment No. 1

## Title: Programs on Classes and Objects

## 1. Program Code

**File Name: Main.java**

```java
class Rectangle {
    int length;
    int width;

    void setDimensions(int l, int w) {
        length = l;
        width = w;
    }

    int getArea() {
        return length * width;
    }
}

public class Main {
    public static void main(String[] args) {
        Rectangle rect = new Rectangle();

        rect.setDimensions(5, 10);

        System.out.println("Area: " + rect.getArea());
    }
}
```

## 2. Aim

To write a Java program to demonstrate the concept of classes and objects by calculating the area of a rectangle.

## 3. Theory

- **Class:** A class is a blueprint used to create objects.
- **Object:** An object is an instance of a class.
- **Data Members:** Variables declared inside a class.
- **Methods:** Functions used to perform operations.
- **setDimensions():** Assigns length and width to the rectangle.
- **getArea():** Calculates and returns the area of the rectangle.

## 4. Output

```text
Area: 50
```

## 5. Conclusion

Thus, the Java program using classes and objects was successfully implemented to calculate the area of a rectangle.
