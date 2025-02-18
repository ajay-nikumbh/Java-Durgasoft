### 01. Instance variables:

- Instance variables in Java are variables that belong to an instance of a class and are declared inside a class but outside any method, constructor, or block.
- They have different values for different objects of the class.

Example 01: 

```java
// Example 1: Basic instance variable
class Person {
    String name;
    int age;
}

// Example 2: Car class with instance variables
class Car {
    String brand;
    String model;
    int year;
}

// Example 3: BankAccount with instance variables
class BankAccount {
    String accountHolder;
    double balance;
}

// Example 4: Book class
class Book {
    String title;
    String author;
    double price;
}

// Example 5: Student class
class Student {
    String name;
    int rollNumber;
    double grade;
}

// Example 6: Employee class
class Employee {
    String name;
    int id;
    double salary;
}

// Example 7: Laptop class
class Laptop {
    String brand;
    int ram;
    double price;
}

// Example 8: Mobile class
class Mobile {
    String brand;
    String model;
    int storage;
}

// Example 9: House class
class House {
    String address;
    int numRooms;
    boolean hasGarage;
}

// Example 10: City class
class City {
    String name;
    int population;
    double area;
}

// Example 11: Movie class
class Movie {
    String title;
    String director;
    int duration; // in minutes
}

// Example 12: Product class
class Product {
    String name;
    double price;
    int quantity;
}

// Example 13: Bicycle class
class Bicycle {
    String brand;
    int gearCount;
}

// Example 14: Television class
class Television {
    String brand;
    double screenSize;
    boolean isSmartTV;
}

// Example 15: MusicAlbum class
class MusicAlbum {
    String albumName;
    String artist;
    int year;
}

// Example 16: CarRental class
class CarRental {
    String carModel;
    double dailyRate;
    boolean isAvailable;
}

// Example 17: Game class
class Game {
    String title;
    String genre;
    int rating;
}

// Example 18: Plane class
class Plane {
    String airline;
    int capacity;
}

// Example 19: Camera class
class Camera {
    String brand;
    double resolution; // in megapixels
}

// Example 20: Refrigerator class
class Refrigerator {
    String brand;
    double capacity; // in liters
}

// Example 21: SmartWatch class
class SmartWatch {
    String brand;
    boolean hasHeartRateMonitor;
}

// Example 22: Tablet class
class Tablet {
    String brand;
    double screenSize;
}

// Example 23: Animal class
class Animal {
    String species;
    boolean isDomestic;
}

// Example 24: Chair class
class Chair {
    String material;
    double price;
}

// Example 25: Speaker class
class Speaker {
    String brand;
    int powerOutput; // in watts
}

// Example 26: School class
class School {
    String name;
    int numOfStudents;
}

// Example 27: Bus class
class Bus {
    String route;
    int capacity;
}

// Example 28: Restaurant class
class Restaurant {
    String name;
    String cuisineType;
    double rating;
}

// Example 29: Lamp class
class Lamp {
    String color;
    boolean isLED;
}

// Example 30: Watch class
class Watch {
    String brand;
    boolean isDigital;
}
```

Example 02:

```java
// Class 1: Person
class Person {
    String name;
    int age;
    
    void display() {
        System.out.println("Name: " + name + ", Age: " + age);
    }
}

// Class 2: Car
class Car {
    String brand;
    String model;
    int year;

    void display() {
        System.out.println("Car Brand: " + brand + ", Model: " + model + ", Year: " + year);
    }
}

// Class 3: BankAccount
class BankAccount {
    String accountHolder;
    double balance;

    void display() {
        System.out.println("Account Holder: " + accountHolder + ", Balance: $" + balance);
    }
}

// Main Class
public class InstanceVariableExample {
    public static void main(String[] args) {

        // Creating Person object
        Person p1 = new Person();
        p1.name = "John Doe";
        p1.age = 28;
        p1.display();

        // Creating Car object
        Car c1 = new Car();
        c1.brand = "Toyota";
        c1.model = "Camry";
        c1.year = 2022;
        c1.display();

        // Creating BankAccount object
        BankAccount acc1 = new BankAccount();
        acc1.accountHolder = "Alice";
        acc1.balance = 5000.75;
        acc1.display();
    }
}
```

Example 03:

```java
// Class 1: Person
class Person {
    String name;
    int age;

    // Constructor
    Person(String name, int age) {
        this.name = name;
        this.age = age;
    }

    void display() {
        System.out.println("Name: " + name + ", Age: " + age);
    }
}

// Class 2: Car
class Car {
    String brand;
    String model;
    int year;

    // Constructor
    Car(String brand, String model, int year) {
        this.brand = brand;
        this.model = model;
        this.year = year;
    }

    void display() {
        System.out.println("Car Brand: " + brand + ", Model: " + model + ", Year: " + year);
    }
}

// Class 3: BankAccount
class BankAccount {
    String accountHolder;
    double balance;

    // Constructor
    BankAccount(String accountHolder, double balance) {
        this.accountHolder = accountHolder;
        this.balance = balance;
    }

    void display() {
        System.out.println("Account Holder: " + accountHolder + ", Balance: $" + balance);
    }
}

// Main Class
public class InstanceVariableWithConstructor {
    public static void main(String[] args) {

        // Creating Person objects using the constructor
        Person p1 = new Person("John Doe", 28);
        Person p2 = new Person("Emma Watson", 25);

        // Creating Car objects using the constructor
        Car c1 = new Car("Toyota", "Camry", 2022);
        Car c2 = new Car("Honda", "Civic", 2021);

        // Creating BankAccount objects using the constructor
        BankAccount acc1 = new BankAccount("Alice", 5000.75);
        BankAccount acc2 = new BankAccount("Bob", 12000.50);

        // Displaying values
        p1.display();
        p2.display();
        c1.display();
        c2.display();
        acc1.display();
        acc2.display();
    }
}
```


