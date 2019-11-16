## Android Interview Questions

After so many interview with many android developer, I decided to document my questions which ask in the interview meeting.

<br>


#### This document is suitable for you if ...

1. You want to interview with a new company.
2. You are working in a company but want to know which questions are typically mentioned in interviews.
3. You are an interviewer and need some useful questions or want to  challenge the interviewee
4. You just want to improve your knowledge about android problems and basics.


<br>


| <span style="color:red">IMPORTANT NOTICE: There is no need to know and read all the questions will be mentioned later. According to the field, size, products and requirements of the company, select and read the appropriate questions. </span>     
| :-------------


<br>

---
#### Table of contents

1. [Object-oriented](https://github.com/javadhme/android-interview-questions#Lifestyle "Object-oriented")
2. [Java](https://github.com/javadhme/android-interview-questions#Lifestyle "Java")
3. [Kotlin](https://github.com/javadhme/android-interview-questions#Lifestyle "Kotlin")
4. [Android](https://github.com/javadhme/android-interview-questions#Android "Android")
5. [Architecture and coding](https://github.com/javadhme/android-interview-questions#"Android "Architecture and coding")
6. [Tools and libraries](https://github.com/javadhme/android-interview-questions#"Android "Tools and libraries")
7. [Gradle](https://github.com/javadhme/android-interview-questions#Gradle "Gradle")
8. [Design patterns](https://github.com/javadhme/android-interview-questions# "Design patterns")
9. [Data structure and algoritms](https://github.com/javadhme/android-interview-questions# "Data structure and algoritms")
10. [Git](https://github.com/javadhme/android-interview-questions# "Git")

---
<br>

### 1. Object-Oriented

- What is and Object?
- What is the main feature of OOP ? <br>
    `Encapsulation`, `Polymorphism`, `Inheritance`, `Abstraction`

- What is encapsulation?
- What is Polymorphism?
- Difference between abstract and interface?
- What is the difference between static and dynamic Polymorphism?
- What is the difference between overriding and overloading?

| Method Overloading      | Method Overriding     |
| :-------------   | :------------- |
| Method overloading is a compile time polymorphism.         | Method overriding is a run time polymorphism.       |
| It help to rise the readability of the program. | While it is used to grant the specific implementation of the method which is already provided by its parent class or super class. |
| It is occur within the class.	 | 	While it is performed in two classes with inheritance relationship. |
| Method overloading may or may not require inheritance. | While method overriding always needs inheritance. |
| In this, methods must have same name and different signature. | While in this, methods must have same name and same signature. |
| In method overloading, return type can or can not be be same, but we must have to change the parameter. | While in this, return type must be same or co-variant. |

<br>

### 2. JAVA

- How to prevent a class to be extended?

- What is the use of the finalize method?
- Overriding for static method, possible?
- What is an abstract class? Benefits?
- What is an object cloning? Is it enable for all objects?
- Multiple inheritances? Possible? How can we do that?
- Object scopes?
- Override private methods, possible?
- What is a static variable in Java?
- Java reference types?
- What is Generic in Java?
- How String class is implemented? Is it mutable or immutable? Why was it made immutable?
- What is the difference between int and Integer?
- What are Autoboxing and unboxing?
- What is the difference between initialization and instantiation?
- How does a static block work?
- What does the keyword `synchronized` mean?
- What is the memory leak? How to handle it?
- What is `transient` modifier?
- What is the difference between `==` and `.equal`?
- What is `reflection`?
- What is the `volatile` modifier?
- What is the `hashCode()` used for?
- What are "annotations"?

<br>

### 3. Kotlin

- What are the benefits of Kotlin?

- What does "Null safety" meaning?
- Why Kotlin does not support primitive type?
- What is Lazy initialization?
- What is the data class?
- Is it possible to inherit a class/method/property by default?
- Difference between apply, also?
- What `==` exactly do in Kotlin in comparison to Java?
- What is the difference between parameter and argument?
- What is the difference between function and method?
- What is the "receiver" in the extension function?
- What is operator overloading?
- Is it possible to write a static method as java as has?
- What is a sealed class?
- How does an extension function work?
- What is `reified` keyword?
- What is an inline function?
- What are the cons of using an inline function?
- What is the best practice of using an inline function?
- How does the `companion object` block work?
- Is it possible to create an extension function on the `companion object` of a class?
- Extension function as a member, possible? What are the benefits of declaring an extension function as a member?
- What is a spread operator? What is the recommended place to use it?
- What is the producer’s function? how to demonstrate it in Kotlin?
- What is the consumer’s function? how to demonstrate it in Kotlin?
- What is the higher-order function?
- How to compare two Strings in Kotlin?
- What is the difference between `==` and `===` ?
