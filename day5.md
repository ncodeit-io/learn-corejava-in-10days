# 🎉 Object-Oriented Programming (OOP) Concepts in Java 🎉

![What is Object Oriented Programming (OOP)? Explain its advantages. Also  describe concept of data hiding in OOP.](https://1.bp.blogspot.com/-GRNuxO0n9ys/YG_wiYUHCnI/AAAAAAAAbh0/ZciwwXqrm_sLU3fMhLHz_HgFwa0oKG_dgCNcBGAsYHQ/s577/oops-IN-JAVA.png)

| Concept | Description |
|---------|-------------|
| 🔒 Encapsulation | Hiding data and methods within a class to prevent them from being accessed by code outside the class |
| 📚 Inheritance | A mechanism that allows a new class to be based on an existing class, enabling the new class to inherit the properties and methods of the existing class |
| 🎭 Polymorphism | The ability of an object to take on many forms, achieved through method overriding and method overloading |
| 🧐 Abstraction | Defining a set of properties and methods that represent the essential features of an object, without including unnecessary details |


Object-Oriented Programming (OOP) is a programming paradigm that uses objects to represent and manipulate data. In Java, OOP is a fundamental concept that enables developers to write modular and reusable code. 😎

Here are the key OOP concepts in Java:

## 💡 Encapsulation

Encapsulation is the practice of hiding data and methods within a class to prevent them from being accessed by code outside the class. This ensures that the data is protected and only accessible through defined methods. 🔒

## 🚀 Inheritance

Inheritance is a mechanism that allows a new class to be based on an existing class. This enables the new class to inherit the properties and methods of the existing class, which can help reduce code duplication and increase code reuse. 📚

## 💪 Polymorphism

Polymorphism is the ability of an object to take on many forms. In Java, this is achieved through method overriding and method overloading. This allows developers to write code that can work with different types of objects, without needing to know the specific type of object at compile-time. 🎭

## 🤝 Abstraction

Abstraction is the practice of defining a set of properties and methods that represent the essential features of an object, without including unnecessary details. This enables developers to write code that is easy to understand and modify. 🧐

With these OOP concepts, Java developers can write modular, scalable, and maintainable code. So go ahead and start coding with Java! 💻


# 🌟Encapsulation in Java🌟

![Encapsulation in Java, Real Life Example of Encapsulation in Java](https://www.sitesbay.com/java/images/encapsulation-in-java.png)

In object-oriented programming, Encapsulation is one of the fundamental concepts that helps developers to achieve data security and maintainability of their code.

👉🏽Encapsulation is a mechanism that binds code and data together and keeps them safe from external interference.🔒

## 📚Understanding Encapsulation

In Java, Encapsulation is implemented using access modifiers such as `private`, `public`, `protected`. By using these access modifiers, we can control the accessibility of methods and variables.

👀Encapsulation ensures that a user cannot modify the data without the appropriate access level. This is important because it protects the data from unauthorized changes and makes it easier to maintain and debug the code.🔍

## 🚀Benefits of Encapsulation

-   🛡️Encapsulation helps protect data from unwanted access and manipulation.
-   🚧It helps in maintaining the integrity of the code.
-   🎓Encapsulation also improves code readability, as it reduces the complexity of the code.

## 🌈Conclusion

Encapsulation is an essential aspect of object-oriented programming, and it helps to build secure, robust, and maintainable software. By using encapsulation, we can make our code more organized and easier to maintain. So, make sure to use encapsulation whenever possible!🌟

## 🚀 Example 1: Encapsulation with Getters and Setters 🚀

In this example, we will create a class called `Person` with private variables `name` and `age`. We will use getters and setters to encapsulate the data.

**java code**


``` java
public class Person {
    private String name;
    private int age;

    // Getter for name
    public String getName() {
        return name;
    }

    // Setter for name
    public void setName(String name) {
        this.name = name;
    }

    // Getter for age
    public int getAge() {
        return age;
    }

    // Setter for age
    public void setAge(int age) {
        this.age = age;
    }
}
```

In this example, we are encapsulating the `name` and `age` variables using the `private` access modifier. We are providing access to these variables using public getter and setter methods.

This approach ensures that the data is secure from external interference, and any modifications to the data are made through the setter methods.

## 🌟 Example 2: Encapsulation with Constructor 🌟

In this example, we will use a constructor to encapsulate data in the `Person` class.

**java code**


``` java
public class Person {
    private String name;
    private int age;

    // Constructor to set the name and age
    public Person(String name, int age) {
        this.name = name;
        this.age = age;
    }

    // Getter for name
    public String getName() {
        return name;
    }

    // Getter for age
    public int getAge() {
        return age;
    }
}
```


In this example, we are using a constructor to set the `name` and `age` variables. This approach ensures that the data is set when the object is created and cannot be modified externally.

The `getName()` and `getAge()` methods are providing access to the data, but the data is still secure because it cannot be modified once the object is created.

# 🚗 Classes and Objects 🛣️
![Object oriented programming (OOP) in Python – Data stories](https://nonlineardata.com/wp-content/uploads/2020/11/Car_Class.png)

In object-oriented programming, a class is like a blueprint 📝 for creating objects 🧩. It defines a set of attributes and methods that are common to all objects of that class.

For example, let's say we have a class called `Car` 🚘. The attributes of this class might include things like `make`, `model`, `year`, `color`, and `miles`. The methods of this class might include things like `drive()`, `stop()`, `accelerate()`, and `decelerate()`.

Once we have defined a class, we can create objects of that class, which are also known as instances 🚗. Each object has its own set of values for the attributes defined in the class.

####  For example, we can create an object of the `Car` class called `myCar` with the following code:

**java code**

``` java
public class Car {
    private String make;
    private String model;
    private int year;

    public Car(String make, String model, int year) {
        this.make = make;
        this.model = model;
        this.year = year;
    }

    public void start() {
        System.out.println("The car has started.");
    }

    public void stop() {
        System.out.println("The car has stopped.");
    }
}
```
``` java
Car myCar = new Car("Toyota", "Camry", 2022);
```

We can then set the attributes of `myCar` using dot notation:

**java code**

``` java
myCar.make = "Ford";
myCar.model = "Mustang";
myCar.year = 2020;
```

We can also call methods on `myCar` using dot notation:

**java code**

``` java
myCar.start();
myCar.stop();
```


🎉 Classes and objects are essential concepts in object-oriented programming. They allow us to create code that is modular, reusable, and easier to maintain. By defining a class and creating objects of that class, we can create complex systems with many different types of objects that interact with each other in meaningful ways.

# 🌟Inheritance in OOP with Java
![OOPs: Inheritance and Polymorphism | by Mukesh Chaudhary | Medium](https://miro.medium.com/v2/resize:fit:904/1*rddNpQyOeBl_jQ3Rmet5dg.png)

Inheritance is one of the 🗝️ key concepts in object-oriented programming. It allows you to create new classes based on existing classes, inheriting their attributes and methods. This can save you a lot of time and effort, as you can reuse code from existing classes rather than starting from scratch. 🙌

In Java, you can create a new class that inherits from an existing class using the `extends` keyword. For example, let's say we have a class called `Vehicle` with attributes `make`, `model`, `year`, and `miles`, as well as methods `drive()`, `stop()`, `accelerate()`, and `decelerate()`: 🚗

**java code**


``` java
public class Vehicle {
    String make;
    String model;
    int year;
    int miles;

    public void drive() {
        System.out.println("The vehicle is being driven.");
    }

    public void stop() {
        System.out.println("The vehicle has stopped.");
    }

    public void accelerate() {
        System.out.println("The vehicle is accelerating.");
    }

    public void decelerate() {
        System.out.println("The vehicle is decelerating.");
    }
}
```



We can now create a new class called `Car` that inherits from `Vehicle`, adding its own attributes and methods: 🚘

**java code**


``` java
public class Car extends Vehicle {
    int doors;
    String color;

    public void honk() {
        System.out.println("The car is honking.");
    }
}
```


Here, the `Car` class extends the `Vehicle` class using the `extends` keyword. It adds two new attributes, `doors` and `color`, as well as a new method called `honk()`.

We can now create objects of the `Car` class just like we did with the `Vehicle` class: 🚀

**java code**

``` java
Car myCar = new Car();
myCar.make = "Toyota";
myCar.model = "Corolla";
myCar.year = 2020;
myCar.miles = 5000;
myCar.doors = 4;
myCar.color = "Red";
```


Here, we have created an object of the `Car` class called `myCar` and set its attributes using dot notation.

Because `Car` inherits from `Vehicle`, it has access to all of the attributes and methods defined in the `Vehicle` class. For example, we can call `myCar.accelerate()` to make the car go faster, or `myCar.stop()` to make it stop. 💨💥

Inheritance is a powerful tool in object-oriented programming that allows you to create complex systems with many different types of objects. By inheriting from existing classes, you can reuse code and create new classes that are more specific to your needs. 🤖🔍

I hope this helps! Let me know if you have any questions or need further clarification. 🤗

# 🧬 Inheriting from base classes🐶🐾🦁🐯🦊
![Inheritance in OOPs- Logicmojo](https://logicmojo.com/assets/dist/new_pages/images/inheritance-image.png)

Inheritance is a 🔑 concept in object-oriented programming 🖥️ that allows you to create new classes 🆕 based on existing classes, inheriting their attributes and methods. In Java, you can use the 🤝 extends keyword to create a new class that inherits from an existing class.

For example, let's say we have a 🐕 base class called Animal with attributes name, age, and species, as well as methods eat(), sleep(), and makeSound(). We can create a new class called Dog 🐶 that inherits from Animal 🦁 and adds its own attributes and methods.

**java code**


``` java
public class Animal {
    String name;
    int age;
    String species;

    public void eat() {
        System.out.println("The animal is eating.");
    }

    public void sleep() {
        System.out.println("The animal is sleeping.");
    }

    public void makeSound() {
        System.out.println("The animal is making a sound.");
    }
}
```


Here, the 🐶 Dog class extends the 🦁 Animal class using the 🔍 extends keyword. It adds two new attributes, breed and isTrained, as well as a new method called bark().

We can now create objects of the 🐶 Dog class just like we did with the 🦁 Animal class:

**java code**

``` java
public class Dog extends Animal {
    String breed;
    boolean isTrained;

    public void bark() {
        System.out.println("The dog is barking.");
    }
}
```

Here, we have created an object of the 🐶 Dog class called myDog and set its attributes using dot notation.

``` java
Dog myDog = new Dog();
myDog.name = "Buddy";
myDog.age = 3;
myDog.species = "Canis lupus familiaris";
myDog.breed = "Golden Retriever";
myDog.isTrained = true;
```

Because 🐶 Dog inherits from 🦁 Animal, it has access to all of the attributes and methods defined in the 🦁 Animal class. For example, we can call myDog.eat() to make the dog eat, or myDog.makeSound() to make it make a sound.

Inheritance allows you to create classes that are more specific to your needs by inheriting from existing classes. This can save you a lot of time and effort by allowing you to reuse code and build on existing functionality. 🚀


# 🌟 Polymorphism in Object-Oriented Programming
![Polymorphism in java - Pianalytix: Build Real-World Tech Projects](https://sp-ao.shortpixel.ai/client/to_auto,q_glossy,ret_img,w_1024,h_427/https://pianalytix.com/wp-content/uploads/2020/11/Polymorphism-in-Java-1024x427.jpg)

Polymorphism is another important concept in object-oriented programming. 🤝 It allows you to write code that can work with objects of multiple classes, as long as those classes share a common interface or base class.

There are two main types of polymorphism in Java:

## 🎭Method Overloading

Method overloading allows you to define multiple methods with the same name in a class, but with different parameters. 🧑‍💻 This means that you can have a single method name that can be used with different types of data. For example, you might have a method called "calculate" that can accept both integers and floating-point numbers:

**java code**


``` java
public class Calculator {
    // Method to add two integers
    public int calculate(int a, int b) {
        return a + b;
    }

    // Method to add two doubles
    public double calculate(double a, double b) {
        return a + b;
    }
}
```

Here, the `Calculator` class defines two methods with the same name, but with different parameter types. Depending on the type of data passed to the method, Java will automatically choose the correct method to call. 📞

## 🎭Method Overriding

Method overriding allows you to define a method in a subclass that has the same name and parameters as a method in the superclass. 🐾 This means that when you call the method on an object of the subclass, the overridden method in the subclass will be called instead of the original method in the superclass.

For example, let's say we have a base class called `Animal` with a method called `makeSound()`:

**java code**

``` java
public class Animal {
    public void makeSound() {
        System.out.println("The animal makes a sound.");
    }
}
```


We can create a subclass called `Dog` that overrides the `makeSound()` method:

**java code**

``` java
public class Dog extends Animal {
    @Override
    public void makeSound() {
        System.out.println("The dog barks.");
    }
}
```


Here, the `Dog` class overrides the `makeSound()` method in the `Animal` class. When we call the `makeSound()` method on a `Dog` object, the overridden method in the `Dog` class will be called instead of the original method in the `Animal` class.

Polymorphism allows you to write more flexible and reusable code, as well as to take advantage of the power of inheritance. 🚀

# 💪 Using polymorphism to write flexible code
Polymorphism is a powerful concept in object-oriented programming that allows you to write flexible and reusable code. It allows you to treat objects of different classes as if they were objects of the same class, by defining a common interface for those classes.💻

In Java, polymorphism is often achieved through the use of interfaces and inheritance. For example, let's say we have a base class called Shape, which has a method called draw(). We can then create subclasses of Shape, such as Circle and Square, which override the draw() method to provide their own implementation.🤖

**java code**


``` java
public interface Shape {
    void draw();
}
```


Now, we can create an array of Shape objects that contains both Circle and Square objects:

**java code**

``` java
public class Circle implements Shape {
    @Override
    public void draw() {
        System.out.println("Drawing a circle.");
    }
}
```

``` java
public class Square implements Shape {
    @Override
    public void draw() {
        System.out.println("Drawing a square.");
    }
}
```


Because both Circle and Square inherit from Shape, we can call the draw() method on each object in the array using a for loop:

**java code**

``` java
public class Main {
    public static void main(String[] args) {
        Shape[] shapes = new Shape[2];
        shapes[0] = new Circle();
        shapes[1] = new Square();

        for (Shape shape : shapes) {
            shape.draw();
        }
    }
}
```

This code will call the draw() method on each object in the array, regardless of whether it's a Circle or a Square. This is an example of polymorphism, because we're treating objects of different classes as if they were objects of the same class (Shape).💻

Polymorphism allows you to write more flexible and reusable code, because you can create interfaces and base classes that define a common set of methods or attributes, and then create subclasses that provide their own implementation of those methods or attributes.💪

So next time you're writing code, think about how you can use polymorphism to make your code more flexible and reusable! 💻

# 🌈Summary - Object-Oriented Programming: 

Object-Oriented Programming (OOP) is a programming paradigm that enables you to create objects that have properties and behaviors. 🧑‍💻

The main idea behind OOP is to break down your code into manageable pieces called objects, which can be used and reused throughout your code. 🤖

OOP provides four main concepts to help you create these objects:

🟢 Encapsulation: This concept involves hiding the implementation details of an object from the outside world, making it easier to change or update the object without affecting other parts of your code.

🔴 Inheritance: This allows you to create new objects that are based on existing ones, inheriting their properties and behaviors.

🟡 Polymorphism: This concept enables objects to take on many forms, allowing them to be used in a variety of different ways.

🟣 Abstraction: This involves focusing on the essential features of an object and ignoring the details that aren't important.

Using OOP, you can create programs that are easier to read, write, and maintain. 💻

In summary, OOP is a colorful and flexible programming paradigm that enables you to create objects with unique properties and behaviors. By using encapsulation, inheritance, polymorphism, and abstraction, you can create code that is easier to manage and maintain. 🌟

# 🚀 Applications of Object-Oriented Programming: 

Object-Oriented Programming (OOP) has become an essential part of software development across many industries. 🧑‍💻

Here are some of the exciting applications of OOP:

📱 **Mobile App Development:** OOP is widely used in mobile app development, as it provides a flexible and scalable approach to building apps with complex functionality.

🎮 **Game Development:** OOP is an ideal programming paradigm for game development, as it allows developers to create objects that can interact with each other in complex ways.

🌍 **Web Development:** Many modern web frameworks, such as Ruby on Rails and Django, use OOP to organize code and create web applications that are easy to maintain.

📈 **Data Analysis:** OOP is often used in data analysis, as it enables developers to create custom objects that can be used to manipulate and analyze data in a variety of ways.

🔍 **Computer Vision:** OOP is also used in computer vision applications, as it provides a flexible way to create objects that can process and analyze visual data.

Using OOP, developers can create software applications that are flexible, scalable, and easy to maintain. 💻

In summary, OOP has a wide range of applications across many different industries, including mobile app development, game development, web development, data analysis, and computer vision. By leveraging the power of OOP, developers can create complex software applications that are easy to maintain and update. 🚀

# 🤔Quiz on Object-Oriented Programming 🧐

Test your Object-Oriented Programming (OOP) knowledge with these tricky multiple-choice questions! 🤓

**🟢 Question 1:** Which OOP concept involves focusing on the essential features of an object and ignoring the details that aren't important? - a) Encapsulation 📦 
b) Inheritance 🏰 
c) Polymorphism 🦄 
d) Abstraction 🧐

🔴 Answer: d) Abstraction 🧐

**🟡 Question 2:** Which OOP concept involves creating new objects that are based on existing ones, inheriting their properties and behaviors? 
- a) Encapsulation 📦 
- b) Inheritance 🏰 
- c) Polymorphism 🦄 
- d) Abstraction 🧐

🔴 Answer: b) Inheritance 🏰

**🟣 Question 3:** Which OOP concept involves hiding the implementation details of an object from the outside world, making it easier to change or update the object without affecting other parts of your code? 
- a) Encapsulation 📦 
- b) Inheritance 🏰 
- c) Polymorphism 🦄 d
- ) Abstraction 🧐

🔴 Answer: a) Encapsulation 📦

**🔵 Question 4:** Which keyword in Java is used to create an object? 
- a) create 🤖 
- b) new 🆕 
- c) make 🛠️ 
- d) object 📦

🔴 Answer: b) new 🆕

**🟢 Question 5:** Which OOP principle suggests that you should depend on abstractions rather than concrete implementations? 
- a) Encapsulation 📦 
- b) Inheritance 🏰 
- c) Polymorphism 🦄 
- d) Dependency Inversion 🕸️

🔴 Answer: d) Dependency Inversion 🕸️

**🟡 Question 6:** Which OOP principle suggests that you should have only one reason to change a class? 
- a) Single Responsibility Principle 🏋️‍♂️ 
- b) Open-Closed Principle 🔓 
- c) Liskov Substitution Principle 🔄
-  d) Interface Segregation Principle 🎭

🔴 Answer: a) Single Responsibility Principle 🏋️‍♂️

**🟣 Question 7:** Which OOP principle suggests that you should be able to extend a class's behavior without modifying it? 
- a) Single Responsibility Principle 🏋️‍♂️ 
- b) Open-Closed Principle 🔓 
- c) Liskov Substitution Principle 🔄 
- d) Interface Segregation Principle 🎭

🔴 Answer: b) Open-Closed Principle 🔓

**🔵 Question 8:** Which OOP principle suggests that objects of a superclass should be replaceable with objects of a subclass without affecting the correctness of the program? 
- a) Single Responsibility Principle 🏋️‍♂️ 
- b) Open-Closed Principle 🔓 
- c) Liskov Substitution Principle 🔄 
- d) Interface Segregation Principle 🎭

🔴 Answer: c) Liskov Substitution Principle 🔄

**🟢 Question 9:** Which keyword in Python is used to create an object? 
- a) create 🤖 
- b) new 🆕 
- c) make 🛠️ 
- d) None of the above ❌

🔴 Answer: d) None of the above (Objects are created automatically in Python)

**🟡 Question 10:** Which OOP principle suggests that you should keep interfaces small and focused, instead of creating large and complex ones? 
- a) Single Responsibility Principle 🏋️‍♂️ 
- b) Open-Closed Principle 🔓 
- c) Liskov Substitution Principle 🔄 
- d) Interface Segregation Principle 🎭

🔴 Answer : d) Interface Segregation Principle 🎭

I hope you enjoyed this quiz! Keep learning and exploring the fascinating world of Object-Oriented Programming! 🚀

