# Inheritance-OOPS

## Aim 
To study Inheritance

## Theory
Inheritance is a fundamental concept in C++ that allows a class (derived class) to inherit properties and behaviors (data members and member functions) from another class (base class). This promotes code reusability and establishes a hierarchical relationship between classes.
### Key Concepts
1. **Base Class:** The class whose properties and methods are inherited.
2. **Derived Class:** The class that inherits from the base class.
3. **Access Specifiers:** Control the visibility of base class members in the derived class.
   - **They include:**
     - **Public Inheritance: Publ**ic members of the base class remain public, and protected 
       members  remain protected in the derived class.
     - **Protected Inheritance:** Public and protected members of the base class become protected 
       in the derived class.
     - **Private Inheritance:** Public and protected members of the base class become private in 
       the derived class.
> Syntax:
```cpp
class Base {
    // Base class members
};

class Derived : access_specifier Base {
    // Derived class members
};

```
### Types of Inheritance
1. **Single Inheritance:** A derived class inherits from one base class.

2. **Multiple Inheritance:** A derived class inherits from multiple base classes.
```cpp
class Base1 {};
class Base2 {};
class Derived : public Base1, public Base2 {};
```

3. **Multilevel Inheritance:** A class is derived from a derived class.
```cpp
class Base {};
class Derived1 : public Base {};
class Derived2 : public Derived1 {};
```

4. **Hierarchical Inheritance:** Multiple derived classes inherit from a single base class.
```cpp
class Base {};
class Derived1 : public Base {};
class Derived2 : public Base {};
```

## Conclusion 
In this experiment we learnt about Inheritance which is an essential part of Object oriented programming.
