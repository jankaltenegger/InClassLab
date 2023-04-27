#  Answer to each question in details (You can google to find answers)
## 
```


```

- What is Java and what are its key features?

Java is an Object-Oriented Programming language and supports OOP features such as Objects, Classes and more.


- How do you declare and use variables in Java? 

By declaring the type, giving it a name and initializing it. You can then call it by its name.


- What is a class in Java and how do you define one? 

A class is a collection of methods and variables and can be defined by naming its visibility(public, private) and the keyword class and its name.


- What is encapsulation and how is it achieved in Java?

Encapsulation is how data and methods can be working together and no other method can interfere in this pact. This is achieved by the visibility keywords.


- How do you create objects in Java and what is their role in the program?

Objects in java can be called for things such as instance methods, which require an object to be executed. For example, you can create a class object by writing Classname objectname = new Classname();


- What is the difference between a method and a constructor in Java? 

A constructor has the same name as a class and is used for tasks such as initializing instance variables which can then be used by the remaining class methods. A Method is used for running snippets of reusable code.


- How do you implement inheritance in Java and what are its benefits?

Inheritance can be used to extend classes by using the class almost like a method in the beginning of the subclass. It lessens repetition of code.


- What is abstraction and how is it achieved in Java?

Abstraction is used to show only what is important to the user, because if you are playing a videogame you don't want to see details a developer would need to debug the game. It is achieved through abstract classes and or interfaces.


- How do you work with arrays and ArrayLists in Java and what are their differences?

Arrays are the ArrayList's stiffer and more socially awkward cousin. They are less flexible but still have most of the ArrayLists functionality, but their size cannot be increased or decreased and their contents only changed.


- How do you use control statements such as if, else, and switch in Java?

They are used by confirming if a boolean statement is true. It will only execute if its boolean is true, else will only execute if If or Else If are false. Switch can choose from a variety of different cases and match the best case to the comparison value. If not used with the break; keyword, it will continue iterating through its cases.


- What is a loop and how do you implement it in Java?

A loop can be a for, while, do-while, or for-each loop in java. These can be implemented by using their syntax and giving them a condition to iterate until said condition is reached.


- What is a method signature in Java and why is it important?

A method is the mixture of the method name and its parameters. It is important because the method signature is needed to call it.


- What is a package in Java and how do you create one?

A package is a container of classes and can be created by writing it on top of the code (package XYZ;) or creating one with the IDE interface.


- How do you use the String class in Java and what are some of its useful methods?

The string class can be used as a data type that can store an array of characters and concatenate them. Some of its useful methods are .toUpperCase, .matches, .toLowerCase.


- What is a constructor in Java and how is it used to create objects?

A constructor has the same name as a class and is used for tasks such as initializing instance variables which can then be used by the remaining class methods.


- How do you implement encapsulation in Java and why are they important in OOP?

Encapsulation is implemented by things such as access keywords (public, private, protected) and involves hiding information from users and secures code from intentional or accidental changes.


- What is object-oriented programming and what are its main principles? 

OOP is based around objects and their interactions with one another. OOP has key characteristics such as classes, objects, etc. Its main principles are Abstraction, Polymorphism, Encapsulation and Inheritance.


- What is the difference between a class and an object in OOP?

A class defines the properties (attributes) and behaviors (methods) that are common to a group of objects. It provides a way to organize and structure code, and makes it possible to create multiple instances of the same type with different values for their attributes.


- What are the access modifiers in Java and how are they used to control access to class members? 

The access modifiers are public, private and protected. These keywords restrict where they can be called and how they interact with the world outside of its own class.


- How do you implement method overloading and overriding in Java?

For overloading you can write the same name with different parameters, overriding can be done inside a subclass by writing the exact same method signature but with a different body.


- How do you create and manipulate String objects in Java? 

You can use either the String literal or the constructor. Using String literals is like creating a variable whereas using String constructors is like creating actual objects.


- What is the purpose of the length() method in the String class? 

The purpose of the length() method is to count the amount of characters in a String.



- How do you concatenate Strings in Java and what is the most efficient way to do so? 

The most efficient way is to use the + sign in the form of STRING + STRING. For more complex applications you might want to use the StringBuilder class.



- What is a substring in Java and how do you extract it from a String? 

A substring is like a cutout of a String. One can be created by taking a string object and appending .substring(int startIndex, int endIndex).



- How do you compare Strings in Java and what is the difference between == and equals()? 

The operator "==" compares reference addresses wheras the .equals() function works to check if each character matches with eachother. You would preferably use the .equals() method for Strings.



- What is the role of the char data type in Java and how is it used? 

The char data type is used for a single character and can be denoted by using '' instead of "". The char data type is actually just a ASCII integer value that is translated to show up as a letter, hence you can add or subtract from it and it will change its character.



- What is Unicode and how does it relate to the char data type in Java? 

Unicode is how all characters are stored, as a integer value. Characters in java are single 16-bit unicode characters.



- How do you convert a char to a String in Java and vice versa?

You can convert a char to string using the String constructor, or a string literal with "" + character. You can convert a string to char by using the .charAt() method.



- What is the difference between char and Character in Java? 

char is a data type, Character is a class.



- What are escape sequences and how are they used with characters in Java? 

Escape sequences are ways to write characters that usually would have significance in Java and being able to display this in text/Strings.



- How do you create a char array in Java and what are its uses? 

char[] name = new char[x]. You can more easily iterate and move around these characters in an char array than you can in a string.



- What is the ASCII code and how is it related to the char data type?

ASCII is similar to unicode in that it gives singular characters different digits, you can add or subtract to the these digits and this will change the character.



- How do you convert a character to its corresponding ASCII value in Java? 

By type casting it to an int.



- What is a Unicode character and how is it represented in Java? 

By writing it as \u and a hexdec code.



- How do you determine the type of a character in Java? 
?



- How do you perform case conversion on a character in Java? 

You can add + 32 to the character and it will change its case.



- What are some of the useful methods available in the Character class in Java?

.isLetter(), .isDigit(), .isWhitespace, .toUpperCase(), .toLowerCase()



- How do you compare characters in Java and what is the difference between == and equals() when used with characters?

You would want to use == for characters and .equals for Character objects. == checks for value equality, whereas .equals() checks for object equality


## Write a Java class to represent a Point in a two-dimensional space. The class should have methods to set and get the x and y coordinates, calculate the distance to another Point, and return a String representation of the Point.

