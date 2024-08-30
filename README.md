# Classes-Objects

## AIM:- <br>
To make depository using classes and object and find the volume <br>

## Software Used :- <br>
VS Code <br>

## Theory :- <br>

- **Class:**
  - A class is a blueprint for creating objects. It defines a type of object according to the data it contains and the functions it can perform.
  - **Syntax:**
    ```cpp
    class ClassName {
    public:
        // Data members
        // Member functions
    };
    ```

- **Object:**
  - An object is an instance of a class. It is a self-contained unit that contains both data and functions that operate on that data.
  - Objects are created based on the class blueprint and can interact with each other and with functions.
 
## Algorithm for Using a Class in C++

1. **Define Class**:
   - Create a class named `student`.
   - Inside the class, declare the following public data members:
     - `name`: a string to hold the student's name.
     - `branch`: a string to hold the student's branch.
     - `subject`: a string to hold the subject.
     - `year`: a string to hold the academic year.
     - `result`: a float to hold the result (not used in this example).

2. **Main Function**:
   - **Create Object**:
     - Instantiate an object `s1` of the `student` class.
   - **Initialize Object**:
     - Assign values to `s1`'s data members:
       - `s1.name = "Divyansh"`
       - `s1.branch = "ENTC-A2"`
       - `s1.subject = "cds"`
       - `s1.year = "2023-2027"`
   - **Display Object Data**:
     - Print the values of the `s1`'s data members:
       - `s1.name`
       - `s1.branch`
       - `s1.subject`
       - `s1.year`

3. **End Program**:
   - Conclude the program after displaying the student's details.

## Algorithm for Using a Class Method defined inside the class

1. **Define Class**:
   - Create a class named `student`.
   - Inside the class, define a public method `studyyear()`:
     - The method prints the string `"2023-2027"` when called.

2. **Main Function**:
   - **Create Object**:
     - Instantiate an object `s1` of the `student` class.
   - **Call Method**:
     - Call the `studyyear()` method on the object `s1`.

3. **End Program**:
   - Conclude the program after the method has been executed.

## Algorithm for Using a Class Method Defined Outside the Class

1. **Define Class**:
   - Create a class named `student`.
   - Inside the class, declare a public method `studyyear()`.

2. **Define Method Outside the Class**:
   - Implement the `studyyear()` method outside the class using the scope resolution operator (`::`):
     - The method prints `"2023-2027"` when called.

3. **Main Function**:
   - **Create Object**:
     - Instantiate an object `s1` of the `student` class.
   - **Call Method**:
     - Call the `studyyear()` method on the object `s1`.

4. **End Program**:
   - Conclude the program after the method has been executed.

## Algorithm for Cuboid Volume Calculation

1. **Define Class**:
   - **Class Name**: `Cuboid`
   - **Private Data Members**:
     - `length`: float, stores the length of the cuboid.
     - `width`: float, stores the width of the cuboid.
     - `height`: float, stores the height of the cuboid.

   - **Public Methods**:
     - `inputDimensions()`:
       - Prompts the user to input the length, width, and height of the cuboid.
       - Stores these values in the private data members.
     - `calculateVolume() const`:
       - Computes and returns the volume of the cuboid using the formula: `length * width * height`.
     - `displayVolume() const`:
       - Calls `calculateVolume()` and prints the volume of the cuboid.

2. **Main Function**:
   - **Create Object**:
     - Instantiate an object `cuboid` of the `Cuboid` class.
   - **Call Methods**:
     - Call `inputDimensions()` on the object `cuboid` to input dimensions from the user.
     - Call `displayVolume()` on the object `cuboid` to display the calculated volume.

3. **End Program**:
   - Conclude the program after displaying the cuboid's volume.


## Conclusion :- <br>
By this experiment we learned the use of classes and objects in c++ . <br>
