# C++ Type Casting

This repository contains examples of various type casting operations in C++. The examples demonstrate the usage of `static_cast`, `const_cast`, `reinterpret_cast`, and `dynamic_cast` keywords for different scenarios.

## Overview

- **static_cast**: Demonstrates how to perform type conversion between related types.
- **const_cast**: Shows how to remove the `const` qualifier from a variable.
- **reinterpret_cast**: Illustrates how to reinterpret the binary representation of a variable.
- **dynamic_cast**: Shows how to perform safe downcasting in inheritance hierarchies.

## Usage

- Compile the code using a C++ compiler.
- Run the compiled executable to observe the output of each type casting operation.

## Contents

1. **static_cast**: Converts a `double` variable to an `int`.
2. **const_cast**: Modifies a `const int` variable through a pointer.
3. **reinterpret_cast**: Reinterprets the memory layout of an `int` variable as a `double`.
4. **dynamic_cast**: Demonstrates safe downcasting from a base class pointer to a derived class pointer.

## Example Output

The output of each example includes the before and after states of the variables involved, along with their sizes.

```cpp
Befor converting double Variable to int: 3.14   ,Its size: 8
After converting double Variable to int: 3      ,Its size: 4

Befor modifing casted away const Variable: 10
After modifing casted away const Variable: 20

Before reinterpret: 10                  ,Its size: 4        
After reinterpret : 4.24399e-313        ,Its size: 8        

Dynamic cast successful.
Derived function called.

```

## Author

[Abdullah Reda]