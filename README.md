# TypeScript Fundamentals & Advanced Concepts Assignment

This repository contains the complete strictly-typed solutions for the TypeScript assignment, along with technical blog posts covering advanced programming concepts.

## Coding Overview (`solutions.ts`)

The `solutions.ts` file contains production-ready solutions for all 8 assignment problems with strict type-checking, explicit parameter and return types:

* **`multiplyValue`**: Multiplies numbers using default parameters.
* **`processInput`**: Handles union types (`string | number | boolean`) using `typeof` type narrowing.
* **`formatCoordinate`**: Uses a `readonly` tuple with destructuring to format location data.
* **`concatenateArrays`**: Implements generic types `<T>` with rest parameters (`...arrays`).
* **`Course` & `getPopularCourses`**: Interface definition and filtered course array management.
* **`pluckValues`**: Advanced generic function constrained with the `keyof` operator.
* **`Employee` & `Manager`**: Object-Oriented Programming (OOP) classes featuring `protected`/`private` access modifiers, constructors, and inheritance (`super`).
* **`validateAgeAsync`**: Asynchronous function returning a `Promise<string>` with `setTimeout` and `Error` handling.

## Technical Blog Posts

* **Blog 1:** [Type Aliases vs Interfaces](./type-vs-interface.md)
* **Blog 2:** [Understanding TypeScript Type Hierarchy (any, unknown, never)](./type-hierachy.md)

