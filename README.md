# 🍔 Burger Factory - Factory Pattern in C++

This project demonstrates the **Factory Design Pattern** using a burger ordering system in C++. It shows how different types of burgers can be created dynamically using concrete factories.

---

## 🧱 Design Pattern: Factory

The **Factory Pattern** is a creational pattern that defines an interface for creating objects, but allows subclasses to decide which class to instantiate. It promotes loose coupling by eliminating the need to bind application-specific classes into your code.

---

## 🏗️ Class Structure

### 🧩 Product Interface
- `Burger` (abstract class): Declares the `prepare()` method.

### 🧱 Concrete Products
- `BasicBurger`, `StandardBurger`, `PremiumBurger`
- `BasicWheatBurger`, `StandardWheatBurger`, `PremiumWheatBurger`

Each implements the `prepare()` method with specific ingredients.

### 🏭 Factory Interface
- `BurgerFactory` (abstract class): Declares the `createBurger(type)` method.

### 🔧 Concrete Factories
- `SinghBurger`: Produces regular bun burgers.
- `KingBurger`: Produces wheat bun burgers.

---

## 🚀 How to Run

1. **Clone the Repository**

```bash
git clone https://github.com/your-username/burger-factory.git
cd burger-factory
