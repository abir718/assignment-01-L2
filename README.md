## What is the use of enums in TypeScript? Provide an example of a numeric and string enum.
enum is a group of variables which is unchangeable. It can be defined as both string and number.

Example of enum using numeric values:
```ts
enum Day {
  Monday = 1,
  Tuesday,
  Wednesday,
  Thursday,
  Friday,
  Saturday,
  Sunday
}

```

Example of enum using string values:
```ts
enum Day {
  Monday = "Monday",
  Tuesday = "Tuesday",
  Wednesday = "Wednesday",
  Thursday = "Thursday",
  Friday = "Friday",
  Saturday = "Saturday",
  Sunday = "Sunday"
}

```

## Provide an example of using union and intersection types in TypeScript.

Example of union:

```ts
let value: string | number;

value = "typescript";   
value = 123; 
value = true; // will show error as boolean is not assignable to string or number.

```

Example of intersection:


```ts

type Designation= { designation: string }; 
type Age = { age: number }; 

type Biodata = Designation & Age ; 

const biodata : Biodata = { 
  designation: "jr developer", 
  age: 21 
};

const biodata2 : Biodata = { 
  designation: "jr developer", 
};   // will show error because only one value is provided


```






