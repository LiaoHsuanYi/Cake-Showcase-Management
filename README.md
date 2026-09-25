# Cake-Showcase-Management

A C++ object-oriented application for managing and analysing a cake showcase.

## Features

- Models three cake types: Chocolate Cake, Geode Cake, and Honey Cake
- Stores each cake’s price and sweetness level
- Tracks the total number of cakes and the count of each cake type
- Lists cakes in a formatted table
- Calculates the total price and sweetness of cakes in a showcase
- Provides index-based access with out-of-range checking

## Concepts

- Abstract classes and inheritance
- Polymorphism
- Class templates
- Static members
- Operator overloading for indexed access
- Unit testing with Google Test

## Build and Run Tests

Requires a C++ compiler, `make`, and Google Test.

```bash
make
./bin/ut_all
