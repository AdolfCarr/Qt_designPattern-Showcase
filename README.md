# Design Patterns in QT and C++ **(WIP)**

## Project Description: 

- **Design Pattern Demonstrations in OOP using QT and C++**

This project is a Qt application titled "Design Patterns in Qt and C++" that shows some of the most common design patterns using Qt and C++.
This project is an interactive application that showcases the most common design patterns in Object-Oriented Programming (OOP). 
The application is built with event-driven programming principles, allowing users to explore and understand various design patterns through a user-friendly 
interface. The main screen features multiple buttons, each corresponding to a specific design pattern. When a user clicks a button, the application demonstrates 
the implementation of that design pattern in real-time.

## Key Features:
1. **Event-Driven Interface:**

- The main screen serves as the central hub for exploring design patterns. Each button on the screen is linked to a different design pattern, which is executed when the button is clicked. This intuitive interface allows users to engage directly with the underlying OOP concepts.

2. **Design Patterns Included:**

- **Creational Patterns:**

    - [**Singleton:**](singleton/README.md) Demonstrated using the Logger class. When the 'Singleton' button is pressed, the application ensures that only one instance of the Logger class is created, preventing the creation of multiple log files during the application's runtime.
    - [**Factory Method:**](factory_method/README.md) Provides an interface for creating objects in a superclass, but allows subclasses to alter the type of objects that will be created.
    - [**Abstract Factory:**](abstract_factory/README.md)Demonstrates how to provide an interface for creating families of related or dependent objects without specifying their concrete classes.
    - [**Builder:**](builder/README.md) Demonstrates how to provide an interface for constructing complex objects step by step, allowing the creation of different representations of the same object without specifying their concrete details.    

- **Structural Patterns:**

    - **Adapter:** Allows the interface of an existing class to be used as another interface. This pattern demonstrates how to wrap a class to provide a different interface for use.
    - **Decorator:** Showcases how to attach additional responsibilities to an object dynamically. This is useful for adding behavior to objects without altering their structure.
    - **Facade:** Illustrates how to provide a simplified interface to a complex subsystem, making it easier to interact with the system.

- **Behavioral Patterns:**

    - **Observer:** Demonstrates how a subject (the Logger class, for example) maintains a list of its dependents and notifies them automatically of any state changes.
    - **Strategy:** Allows the definition of a family of algorithms, encapsulating each one, and making them interchangeable. This pattern is demonstrated through a dynamic selection of algorithms at runtime.
    - **Command:** Demonstrates how to encapsulate a request as an object, allowing for parameterization and queuing of requests.

3. **Interactive Demonstrations:**

- Each pattern demonstration is fully interactive, allowing users to see the effects of the pattern in action. For example, pressing the 'Singleton' button will trigger the Singleton pattern implementation, and the user can observe how the application prevents multiple instances of the Logger class.

4. **Comprehensive Coverage:**

- The project covers a wide range of design patterns across different classifications:
    - **Creational Patterns:** Focus on object creation mechanisms.
    - **Structural Patterns:** Deal with object composition and the relationships between entities.
    - **Behavioral Patterns:** Concerned with object collaboration and the delegation of responsibilities.

>The clear interactive examples make complex patterns accessible and easy to grasp.
By providing hands-on experience with design patterns, this project serves as both a learning resource and a reference guide for implementing common design patterns in software development.
Perform an showcase of some of the most common Design Patterns in Object Oriented Programming using **QT and C++**.

<p align="center">
  <img src="images/underconstruction.png" width="298" height="169" alt="Main window in Qt of Design Patterns application">
</p>
<p align="center">

<p align="center">
  <em>Fig 1: Main window in Qt of Design Patterns application</em>
</p>


## What's a design pattern?
Design patterns are typical solutions to commonly occurring problems in software design. They are like pre-made blueprints that you can customize
to solve a recurring design problem in your code.

You can’t just find a pattern and copy it into your program, the way you can with off-the-shelf functions or libraries. The pattern is not a 
specific piece of code, but a general concept for solving a particular problem. You can follow the pattern details and implement a solution 
that suits the realities of your own program.

Patterns are often confused with algorithms, because both concepts describe typical solutions to some known problems. While an algorithm always 
defines a clear set of actions that can achieve some goal, a pattern is a more high-level description of a solution. The code of the same pattern 
applied to two different programs may be different.

An analogy to an algorithm is a cooking recipe: both have clear steps to achieve a goal. On the other hand, a pattern is more like a blueprint: 
you can see what the result and its features are, but the exact order of implementation is up to you.

## How to run the project
- **Clone the project**: Get a copy of the project on your computer.

- **Open Qt Creator**: Launch Qt Creator on your computer.

- **Open Project**: Navigate to File -> Open File or Project... in the menu bar.

- **Select Project Directory:** In the dialog box, navigate to the directory containing your CMakeLists.txt file.

  - Select the folder that represents your project (it should contain your CMakeLists.txt file).
  - Click Open to load the project into Qt Creator.
- **Configure the Project**: Qt Creator will automatically detect the CMakeLists.txt file and configure the project. It may prompt 
you to select a build directory if it's the first time opening the project.

- **Build the Project**: After the project is loaded, you will see it in the Projects pane on the left side of Qt Creator.

  - If necessary, configure your build settings (like selecting a build kit or target).
  - Click on the hammer icon (Build Project) in the bottom left corner to build the project. This step compiles your code.

- **Run the Project**: Once the project is successfully built without errors, click on the green play button (or press Ctrl + R) to run the project.

- **View Output**: Qt Creator will show the application's output in the canvas pane at the venter of the screen. 