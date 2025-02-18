### 01. Instance variables:

- Instance variables in Java are variables that belong to an instance of a class and are declared inside a class but outside any method, constructor, or block.
- They have different values for different objects of the class.

Example 01: Here are 30 examples of Java classes demonstrating instance variables

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

Example 02: Full Program: Using Instance Variables

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

Output:

```text
Name: John Doe, Age: 28
Car Brand: Toyota, Model: Camry, Year: 2022
Account Holder: Alice, Balance: $5000.75
```

Example 03: Program: Using Constructors with Instance Variables

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
Output:

```text

Name: John Doe, Age: 28
Name: Emma Watson, Age: 25
Car Brand: Toyota, Model: Camry, Year: 2022
Car Brand: Honda, Model: Civic, Year: 2021
Account Holder: Alice, Balance: $5000.75
Account Holder: Bob, Balance: $12000.5

```

Example 04: Program: Using Getters and Setters with Instance Variables

```java

// Class 1: Person
class Person {
    private String name;
    private int age;

    // Constructor
    Person(String name, int age) {
        this.name = name;
        this.age = age;
    }

    // Setter methods
    public void setName(String name) {
        this.name = name;
    }

    public void setAge(int age) {
        if (age > 0) { // Ensuring a valid age
            this.age = age;
        } else {
            System.out.println("Age must be positive.");
        }
    }

    // Getter methods
    public String getName() {
        return name;
    }

    public int getAge() {
        return age;
    }

    void display() {
        System.out.println("Name: " + getName() + ", Age: " + getAge());
    }
}

// Class 2: Car
class Car {
    private String brand;
    private String model;
    private int year;

    // Constructor
    Car(String brand, String model, int year) {
        this.brand = brand;
        this.model = model;
        this.year = year;
    }

    // Setters
    public void setBrand(String brand) {
        this.brand = brand;
    }

    public void setModel(String model) {
        this.model = model;
    }

    public void setYear(int year) {
        if (year > 1885) { // Ensuring a valid car year
            this.year = year;
        } else {
            System.out.println("Year must be greater than 1885.");
        }
    }

    // Getters
    public String getBrand() {
        return brand;
    }

    public String getModel() {
        return model;
    }

    public int getYear() {
        return year;
    }

    void display() {
        System.out.println("Car Brand: " + getBrand() + ", Model: " + getModel() + ", Year: " + getYear());
    }
}

// Class 3: BankAccount
class BankAccount {
    private String accountHolder;
    private double balance;

    // Constructor
    BankAccount(String accountHolder, double balance) {
        this.accountHolder = accountHolder;
        this.balance = balance;
    }

    // Setters
    public void setAccountHolder(String accountHolder) {
        this.accountHolder = accountHolder;
    }

    public void deposit(double amount) {
        if (amount > 0) {
            this.balance += amount;
        } else {
            System.out.println("Deposit amount must be positive.");
        }
    }

    public void withdraw(double amount) {
        if (amount > 0 && amount <= balance) {
            this.balance -= amount;
        } else {
            System.out.println("Invalid withdrawal amount.");
        }
    }

    // Getters
    public String getAccountHolder() {
        return accountHolder;
    }

    public double getBalance() {
        return balance;
    }

    void display() {
        System.out.println("Account Holder: " + getAccountHolder() + ", Balance: $" + getBalance());
    }
}

// Main Class
public class InstanceVariableEncapsulation {
    public static void main(String[] args) {

        // Creating Person objects using the constructor
        Person p1 = new Person("John Doe", 28);
        p1.setAge(30); // Updating age using setter
        p1.display();

        // Creating Car objects using the constructor
        Car c1 = new Car("Toyota", "Camry", 2022);
        c1.setYear(2023); // Updating year using setter
        c1.display();

        // Creating BankAccount objects using the constructor
        BankAccount acc1 = new BankAccount("Alice", 5000.75);
        acc1.deposit(1000.25); // Depositing money
        acc1.withdraw(1500.50); // Withdrawing money
        acc1.display();
    }
}
```

Output:

```text
Name: John Doe, Age: 30
Car Brand: Toyota, Model: Camry, Year: 2023
Account Holder: Alice, Balance: $4500.5
```

