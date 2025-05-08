# What is the use of enums in TypeScript? Provide an example of a numeric and string enum.
enum is a group of variables which is unchangeable. It can be defined as both string and number.

Example of enum using numeric values:
```
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
```
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

