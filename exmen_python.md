# THE DATACLASSES

## Introduction

Python Data Classes provide an intuitive way of building composite data types from simple components, much as classes are often used as the foundational building blocks of object-oriented programming. Built on top of the language's powerful typing system, data classes provide a straightforward way for developers to efficiently manipulate complex data. 

Since version 3.7, Python has introduced a very interesting new feature, known as dataclasses. This is a feature that aims to simplify the task of creating classes that only store data.

## Présentation du concept 

Dataclasses are an extension of the popular object-oriented programming language. They are a particular approach to creating structured data types that are easy to work with, allowing developers to easily store, track and manipulate data. They also offer an extensible, reusable way to build the composite data structures necessary for advanced programming tasks. 

Data classes are classes that contain one or more elements that are collected and associated together in a data class. Each element is called a field and is defined by its type, name, and other optional parameters. The field definitions for a data class must also include an init signature that specifies the arguments used to initialize an object as a data class. 

Data classes allow developers to build powerful data structures without needing to write large amounts of code. They combine the best of object-oriented programming - inheritance, encapsulation, abstraction - and the increased flexibility and modularity of functional programming. 

![Alt text](url "https://miro.medium.com/v2/resize:fit:626/1*h6WKhKfK3PU169NGy7DUCw.png")

## Theory
Dataclasses are based on Python's 'dataclasses' extension. These new data types are a subclass of the "object" class, with attributes and methods specific to an instance. Classes can contain various values such as strings, integers, lists etc.

Dataclasses are designed for use when you need to process data in an application. They are a quick and easy way to store information because they are very simple to create and use. Dataclasses can be defined using a specific @dataclass decorator on a class. Using this decorator, you can specify the type of fields and the default values.
