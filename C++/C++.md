# What is Programming

Programming is a method to communicate with a computer to give it instruction to perform task

# Features of C++

1.  Supports Object Oriented Programming which helps in building modular and reusable code.
2.  C++ also has features of procedural programming making it flexible for both procedural programming and object oriented programming
3.  C++ provides manual memory management providing programmers control over memory allocation and deallocation
4.  The Standard Template Library offers generic classes and functions simplifying complex programming problems
5.  C++ supports multiple programming paradigms

# I/O Operations

In C++, I/O Operations occurs in streams, which involve transfer of information of byte. It's a sequence of bytes.

**Stream is involved in two ways:\
- Source\
- Destination of data**

C++ programs input data and output data from a stream. Stream are related with physical device such as the monitor or with a file stored on the secondary disk.

In a text stream, the sequence of characters is divided into lines, with each line being terminated with a new line character. On the other hand, a binary stream contains data values using their memory representation.

# **Cascading of Input and Output Operators**

\<\< operator - It can be used multiple times in the same line. It is called Cascading.

cout, cin can be cascaded

``` cpp
cout << "Enter your marks"
```

# Formatted Input and Output Operations

1.  I/O Class Function and Flags
2.  Manipulators

| Functions   | Purpose                                                        | Syntax            | Usage                                      | Comment                                            |
|-------------|-------------------|-------------|-------------|---------------|
| width()     | Specifies field size                                           | cout.width(w)     | cout.width(6);cout\<\<1239;                | It can specify field width for only one value      |
| precision() | Specifies number of digits to be displayed after decimal point | cout.precision(d) | cout.precision(3);cout\<\<1.234567         | It retains the setting in effect until it is reset |
| fill()      | Specifies a character to fill the unused portion of a field    | cout.fill(ch)     | cout.fill('\#');cout.width(6);cout\<\<1239 | It retains the setting in effect until it is reset |

# Formatted with Flags

The setf() is a member function of the class that is used to set flags for formatting output

``` c++
cout.setf(flag,bit-field)
```

Flag defined in the ios class specifies how the output should be formatted bit-field is a constant that identifies the group to which the formatting belongs to.

There are two types of setf() - one that takes both flag and other that takes only the flag
