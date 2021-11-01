## Input
There are many ways to get user input. We are going to use the `Scanner` class. In order to use the class to get input, we must 

1. `import java.util.Scanner;`
2. create a scanner object

`Scanner user = new Scanner(System.in);

### Input Types
1. `nextInt()` reads integer value from user
2. `nextFloat()` or `nextDouble()` reads a decimal value from user
3. `nextBoolean()` 	reads boolean value from user
4. `nextLine()` reads a String value

## String
A collection of characters. Strings are immutable, which means they cannot be changed. 

Ex: "My name is Catherine"

### Contructing String Objects

we can create string objects similar to primitive data Types

`String name = "catherine";`

### Concantentaion of Strings

String can be added together using an operators called concantentation. (+)

Example:

`String firstName = "catherine";`

`String lastName = "hu";`

`String fullName = firstName + lastName`

Example:

`String id = 5;`

### Comparing Strings

In Java, you can compare strings using two different methods.
- 'equals()' method
- 'compareTo()' method

**For the equals() method**

`string1.equals(string2);`, this returns a boolean value, either true if the two strings are equal, or false otherwise.

Example:

`String dog = "dog";`

`String cat = "cat";`

`System.out.println(dog.equals(cat));`

**For the compareTo() method**

`string1.compareTo(string2);`

This method returns:
- returns 0 if the two strings are equal 
- returns a value greater than 0 if the second string precedes the first string in the dictionary
- returns a value less than 0 if the first string precedes the second string in the dictionary

`"Miles".compareTo("Ryan");`

1. "Miles"
2. "Ryan"

First Character: "M" - "R" = 77-82 = -5


### Indexing String

Even though strings are immutable, you are able to take parts of a string to use for a new string.

**Method: substring**

The substring() method has two different forms:
- string1.substring(Interger num)
  - The first for takes a single integer input and returns the characters of the string from the index of the input to the end

Example:

`String dinosaur = "Triceratops";`

`String half = dinosaur.substring(5);`

- `string1.substring(Integer num1, Integer num2);`
  - The second form takes two integer inputs and returns the characters of the string from the index of the first input to the character before the index of the second input 

Example:

`String dinosaur = "Triceratops";`

`String part = dinosaur.substring(2, 6);`

String Length:

To find the length of a string, you can use the method string.length(). This method returns the string as an integer.

Example:

`String name = "catherine";`

`int length = name.length();` returns the integer value 9

