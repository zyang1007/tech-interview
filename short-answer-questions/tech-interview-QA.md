### 1. `final` keyword:
- If the `final` keyword is added on a string, like a final String name is “jack”, the name can not be changed to Bob. 
- If the `final` keyword is added for the object type, like a final List is already initialized using new ArrayList<>(), the content in this list can be changed, but the list can not be initialized by using a new keyword again. 
- If the `final` keyword is added to the method of a class, it will not be overridden in the subclass of this class. 
- If the `final` keyword is added to a class, it will not be extended.

### 2. `static` keyword:
- Static fields are also known as class fields. They are simply fields that have the static modifier in their declarations.
- Static methods are the methods in Java that can be called without creating an object of class. They are referenced by the class name itself or reference to the Object of that class. Static method is not allowed override
- Static class is that it does not allows us to access the non-static members of the outer class.A class can be declared static only if it is a nested class.

### 3. Primitive data types:
- byte, short, int, double, float, long, char, boolean.

### 4. Passing by value / reference:
- Passing by value means that a copy of the actual parameter's value is made in memory. When accessing or modifying the variable within the function, it accesses only the copy rather than the original value.

- Passing by reference means that the memory address of a variable is passed to a function. When the function modify the value of the parameter.
