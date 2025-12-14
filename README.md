# C++ Modules - 42 School

This repository contains a series of C++ modules designed to progressively learn and master C++ programming fundamentals and advanced concepts. Each module focuses on specific aspects of the language, following the 42 School curriculum.

## 📚 Module Overview

### CPP Module 00 - Basics
Introduction to C++ basics, namespaces, classes, member functions, I/O streams, and initialization lists.
- **ex00**: Megaphone - String manipulation and basic output
- **ex01**: PhoneBook - Contact management system with classes

### CPP Module 01 - Memory Allocation
Memory allocation, pointers to members, references, and the switch statement.
- **ex00**: Zombie - Stack vs heap allocation
- **ex01**: Zombie Horde - Dynamic array allocation
- **ex02**: Brain - References and pointers
- **ex03**: Weapon - References in practice
- **ex04**: File Processing - String manipulation and file I/O
- **ex05**: Harl - Function pointers and switch cases

### CPP Module 02 - Ad-hoc Polymorphism
Fixed-point numbers, operator overloading, and orthodox canonical class form.
- **ex00**: Fixed - Basic fixed-point class
- **ex01**: Fixed - Conversion and output operators
- **ex02**: Fixed - Arithmetic and comparison operators

### CPP Module 03 - Inheritance
Introduction to inheritance and basic class hierarchies.
- **ex00**: ClapTrap - Base class implementation
- **ex01**: ScavTrap - Single inheritance
- **ex02**: FragTrap - Multiple derived classes

### CPP Module 04 - Polymorphism
Subtype polymorphism, abstract classes, and interfaces.
- **ex00**: Animal - Virtual functions and polymorphism
- **ex01**: Brain - Deep copy and memory management
- **ex02**: Abstract classes - Pure virtual functions

### CPP Module 05 - Exceptions
Exception handling, try-catch blocks, and custom exceptions.
- **ex00**: Bureaucrat - Basic exception handling
- **ex01**: Form - Exception propagation
- **ex02**: Concrete Forms - Specialized form classes (Shrubbery, Robotomy, Presidential Pardon)
- **ex03**: Intern - Form creation and factory pattern

### CPP Module 06 - Type Casting
C++ casts (static_cast, dynamic_cast, reinterpret_cast, const_cast) and type conversion.
- **ex00**: Scalar type conversion
- **ex01**: Serialization
- **ex02**: Type identification

### CPP Module 07 - Templates
Function templates, class templates, and generic programming.
- **ex00**: Function templates basics
- **ex01**: Iterator templates
- **ex02**: Array template class

### CPP Module 08 - STL
Standard Template Library - containers, iterators, and algorithms.
- **ex00**: Easy find algorithm
- **ex01**: Span container
- **ex02**: Mutated stack

### CPP Module 09 - Containers
Advanced STL containers and practical applications.
- **ex00**: Bitcoin exchange
- **ex01**: Reverse Polish Notation
- **ex02**: PmergeMe sorting algorithm

## 🛠️ Building and Running

Each exercise contains a `Makefile` for compilation. To build an exercise:

```bash
cd CPP_Module_XX/exYY
make
```

To run the compiled program:

```bash
./program_name
```

To clean object files:

```bash
make clean
```

To remove all compiled files:

```bash
make fclean
```

To rebuild everything:

```bash
make re
```

## 📋 Requirements

- C++ compiler with C++98 standard support (g++ or clang++)
- Make

## 🎯 Learning Objectives

Throughout these modules, you will learn:

- C++ syntax and basic programming concepts
- Object-oriented programming (OOP) principles
- Memory management (stack vs heap, RAII)
- Operator overloading
- Inheritance and polymorphism
- Exception handling
- Templates and generic programming
- STL containers and algorithms
- Design patterns and best practices

## 📖 Coding Standards

All code follows the 42 School norm:
- Orthodox Canonical Form for classes (when applicable)
- No forbidden functions or external libraries
- Proper memory management (no leaks)
- Separation of interface and implementation
- Clear and descriptive naming conventions

## 🏫 About 42 School

42 is a coding school with a peer-to-peer learning methodology. Students learn through practical projects without traditional teachers or lectures.

## 📝 Notes

- Each module builds upon concepts from previous modules
- Some exercises may contain incomplete implementations or experimental code
- Focus is on understanding C++ fundamentals before moving to modern standards

## 📄 License

This is an educational project for 42 School. Feel free to use it as a reference for learning purposes.

---

*Happy coding! 🚀*
