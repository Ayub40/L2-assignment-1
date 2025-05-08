1.TypeScript, both interface and types can used to defines the shape of a object. Their are some different in their feature and use: 

Interface:

1. Declared using the interface keyword.
2. Typically used to define the shape of objects or classes.

Example:
   interface User {
  name: string;
}

interface User {
  age: number;
}

const user: User = {
  name: "Ayub",
  age: 30,
};

Type:
 1. You can’t types with same name.
 2. Can still describe objects, like interface.

Example: 
  type EmilabWatch = {
        brand: string;
        model: string;
        display: string;
    }

2.What is type inference in TypeScript? Why is it helpful?

 Type inference in TypeScript automaticly determines types based on value or context, reducing the need for explicit annotation.

 Why is it helpful?
  a. Code is more concise.
  b. Errors are caught early.

   
