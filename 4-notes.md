## 4. Advanced Typing

### Video List:
4. Base Types, Primitives, Arrays, Object Types, and Type Inference.

We will be discussing...

1. Understand and apply advanced types such as unions, aliases, and intersections.

2. Explore generics and how they promote code reusability.

- Union types
allows more than one type to your assignment

- Type Alias
Use an alias rather than repeat a bunch of type definitions

type (added by TS, does not exist in JS)

type Person = {
    name: string;
    age: number;
};

OR

let people: Person[];

- Functions and Types
Just as we can set types for variables, we can also do this for paremeters!


- Generic Types

Helps you write type functions that are flexible, but safe! Once a type is used, that type is locked and known. Get flexibility and type safety all wrapped in one.

Use the function throughout other arrays... or uses throughout the code
Only be available inside of a function

<T> = type, but any identifier is okay