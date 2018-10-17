# CSharp Interview Questions #
***
Q1: What is a namespace?
> A namespace is what is used in order to organize its classes.

Q2: What are value types?
> Value types are variable that can be assigned a value.

Q3: What are reference types?
> Reference types are variables that store a reference to their data.

Q4: What is an automatic property and how is it useful?
> Automatic properties allow you to write a shorter code by when you don't need additional information in the property accessors.

Q5: What is the purpose of using statement?
> The using statement is used when an object is only used in within a block of code.

Q6: What are dynamic type variables?
> A dynamic type variable will behave as though it has an object type, but it supports any operation.

Q7: What is the purpose of the is operator?
> The is operator is used to compare objects that could be different types.

Q8: What are generics and how is using them useful?
> Generics are useful because you are able to make classes and methods and their types are only specified when declared and instigated.

Q9: What is the scope of a public member of a class?
> The scope is what allows the member to be accepted by outside classes.

Q10: Can you create a function that can accept a varying number of arguments?
 ``` C#
 public static void UseParams(params int[] list)
    {
        for (int n = 0; n < list.Length; n++)
        {
            Console.Write(list[n] + " ");
        }
        Console.WriteLine();
    }
```
Q11: How do you sort an array?
> Sort an array you would use the following command.
``` C#
Array.Sort(nameOfArray)
```

Q12: What is a nullable type and what purpose does it serve?
> A nullable type is what is used to store any variables that have the value of NULL. It's used where values can be undefined or missing.

Q13: What is an enumeration?
> An enumeration is used to set the number of integral constants, which can then be assigned to variables.

Q14: What is inheritance?
> Inheritance carries the attributes from an existing class.

Q15: Is multiple inheritance supported?
> No, multiple inheritance is not supported by C#.

Q16: What is the purpose of as operator
> The as operator used to compare reference types to each other.

Q17: What is an object?
> An object is a block of memory that is located and configured to the class.

Q18: What is the difference between a struct and a class?
> A class is a reference type and can therefore inherit from other classes. A struct is a value type and cannot inherit anything.

Q19: What is the difference between continue and break statements?
> The break statement completely removes you from the loop. The continue statement will just skip a certain section while staying in the loop.

Q20: What is this and how is it used?
> The keyword this refers to your current class instance. It can be used to pass objects to other methods or declaring indexers.

Q21: What is try and catch and when are they used?
> Try is used to find exceptions and catch is used to correct them.

Q22: How is exception handling done?
> An exception caught during execution. It is normally when there is a red flag in the code, and we can use the try function in order to correct it.

Q23: What is finally and what is its purpose?
> Finally, for the most part, is used after the control leaves the try statement, and is used to clean up any extra resources left over in a try block.

Q24: List the differences between Array and ArrayList.
> Arrays can only store set types of items and only a set number of them, which makes them easier to call because you don't need to define the type. ArrayList can contain multiple types and will grow with the code, however, you must define type when calling.

Q25: What is an object?
> An object is a block where you assign any data types. 

Q26: Define constructor.
> A constructor initializes the data members of a recently created object.

Q27: When can var be used to declare a variable and how is the type for the variable determined?
> Var can be used when you want to instruct the compiler to infer the variable type. Normally, the type is determined by a user defined type or is defined by the .NET Framework.

Q28: What is an abstract class?
> Abstract classes is a class that is used to declare methods, and are the only classes that can store abstract methods.

Q29: What is an interface?
> An interface is what contains the definitions for related functions. These can then be implemented in a class or struct.

Q30: What is a method?
> A method is a block of code that can contain a series of statements.

Q31: What is a property?
> Properties are similar to field, except that they are implemented with accessors.

Q32: What is an access specifier?
> Access specifiers are used to control the accessibility of an object.

Q33: What access specifiers are supported and what do they mean?
* Public- Allows access from anywhere.
* Private- Access only inside the class it's declared in.
* Protected- Access in classes or structs inherited from this type.
* Internal- Access within the program where the declarations were made.
* Protected Internal- Access in the same program and in inherited classes.

Q34: What is a collection?
> A collection is used for data storage and retrieval. They can contain lists and queues and hash tables.

Q35: What is a Hash Table?
> A hash table is a class that will assign a key to each value, which allows you to call the key.