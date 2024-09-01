# Builder Project Overview

This project is a comprehensive demonstration of the Builder Design Pattern, composed of two distinct versions:

- [**Version 1: Meal Preparation System**](builder_v1/README.md)
- [**Version 2: Multi-Builder House Construction System**](builder_v2/README.md)

Both versions illustrate how the Builder Pattern can be applied to construct complex objects through a step-by-step process, offering flexibility, reusability, and a clear separation of concerns. Below, you'll find a brief overview of each version along with links to their respective detailed README files.

## Version 1: Meal Preparation System

**Description:** This version showcases the Builder Pattern in a meal preparation scenario. It allows users to create Vegetarian and Non-Vegetarian meals, each consisting of a burger and a cold drink. The system demonstrates the flexibility of the Builder Pattern by allowing different meal compositions, ensuring that the correct components are included for each type of meal.

- **Key Components:**
    - **MealBuilder:** Handles the construction of different meals.
    - **Meal:** Represents the complete meal, composed of various `Item` objects like `VegetarianBurger` and `Coke`.
    - **Dialog Classes:** Facilitate user interaction and trigger the meal-building process.

For more details on the Meal Preparation System,  please refer to the following link:

- [Builder Implementation Version 1 README.](builder_v1/README.md)

## Version 2: Multi-Builder House Construction System

**Description:** This version extends the Builder Pattern to a house construction scenario. It demonstrates how the pattern can manage the construction of different types of houses (e.g., Tipi and Igloo) through a common interface. This system is implemented in a virtual construction simulation environment, showcasing how different building processes can be managed in a structured and flexible manner.

- **Key Components:**
    - **HouseBuilder:** Abstract class defining the steps involved in building a house.
    - **IglooHouseBuilder & TipiHouseBuilder:** Concrete builders responsible for constructing specific house types.
    - **House:** Represents the final product being constructed, implementing the `HousePlan` interface.

For more details on the Multi-Builder House Construction System, please refer to the following link:

- [Builder Implementation Version 2 README.](builder_v2/README.md)