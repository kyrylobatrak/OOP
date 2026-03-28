# Object-Oriented Programming (OOP) in Python

Welcome to my Python OOP repository! This project contains a structured collection of laboratory works and homework assignments dedicated to learning Object-Oriented Programming concepts in Python. It covers everything from basic class design and inheritance to advanced topics like custom exceptions, iterators, and generators.

## 📂 Repository Structure

The repository is organized into two primary directories:

* **`LAB/` (Laboratory Works):** Step-by-step practical assignments (Labs 1 through 13) focusing on core OOP principles.
* **`HW/` (Homework Assignments):** In-depth exercises and problem-solving tasks that reinforce the concepts learned in the labs.

---

## 🔬 Detailed Breakdown of Laboratory Works (`LAB/`)

The `LAB` directory demonstrates a progressive understanding of Python and OOP. Highlights include:

* **Lab 2 (Linear Algebra & Math):** * Implementation of custom mathematical classes: `Vector2D.py` and `Matrix2D.py`.
  * `Solver.py` for resolving systems of equations.
  * File parsing for matrix and right-hand side (RHS) values.
* **Lab 5 (Polymorphism & Class Hierarchies):** * A geometric shapes hierarchy featuring a base `Figure` class and derived classes (`Circle`, `Quadrate`, `Rectangle`, `Trapezoid`, `Triangle`).
  * Introduction to object composition (`Car.py`).
* **Lab 6 (Encapsulation):** * Implementation of protected attributes and access control via `ProtectedDictInt.py`.
* **Lab 12 (Advanced OOP & Custom Exceptions):** * Creation of custom exception classes (`DIctException.py`, `ValueError.py`, `ZeroDivisonDenominatorError.py`).
  * Building custom iterators (`ProtectedDictIntIterator.py`).
  * Robust fraction math using `Rational.py`.
* **Lab 13 (File Processing):** * Object-oriented approaches to file reading and data extraction (`FileReader.py`).

---

## 📝 Homework Assignments (`HW/`)

The `HW` directory contains extensive modular projects. Key areas of focus include:

### Complex Geometry Hierarchies (`HW/3.3.1/` & `HW/Figure/`)
* A massive class hierarchy covering both 2D and 3D geometric shapes.
* Features classes like `Ball`, `Cone`, `Parallelogram`, `QuadrangularPyramid`, `TriangularPrism`, and more.
* Includes UML diagrams (`UML` file) to represent class relationships visually.

### The "Rational" Number Project (`HW/5.3.1` - `HW/7.3.3`)
* A deep dive into operator overloading and data validation by creating a custom `Rational` number class.
* **Iterators:** Building custom iterable collections (`HW/6.3.1/Iterator.py`).
* **Error Handling:** Designing strict validation with custom exceptions like `RationalValueError` and handling zero denominators.
* **Collections:** Managing lists of objects via `RationalList.py`.

### Recurrence Relations and Generators (`HW/Recurrence relations/` & `HW/Recurrence generators/`)
* **Sections 11.7 - 11.10:** Algorithmic tasks focused on mathematical sequences.
* Implementation of both standard iterative/recursive relations and Python `yield` generators to efficiently compute series and sequences.

---

## 🚀 Key Concepts Demonstrated

Throughout this repository, you will find practical applications of:
1. **Encapsulation:** Protecting data using private/protected naming conventions.
2. **Inheritance:** Building logical relationships between base and derived classes (e.g., Figures).
3. **Polymorphism:** Overriding methods in derived classes for dynamic behavior.
4. **Magic Methods (Dunder Methods):** Overloading operators for custom classes (e.g., math with Rational numbers and Vectors).
5. **Exception Handling:** Writing safe code with custom error types.
6. **Iterators & Generators:** Efficient memory management and custom iteration logic.

## 🛠️ How to Run

1. Ensure you have **Python 3.x** installed.
2. Clone the repository and navigate to the desired directory.
3. Run the scripts using the python interpreter, for example:
   ```bash
   python LAB/2/main.py
