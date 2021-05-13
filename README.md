# reimagined-design-patterns

Give a summary description of Four design patterns that you choose from the following design patterns: **Adapter,  Builder, Composite, Decorator, Observer, Interpreter, State, Mediator, Memento, Prototype, Proxy**. In your summaries say:

- what kind of problem(s) you can solve with that pattern and when you use it, maybe with a short example
- how the pattern works, what the basic idea of the pattern is
- what the main advantage and what the the main disadvantage is of using this pattern
- Write a short summary for each of the four patterns, about half a page for each pattern (rather less than more). 

> Do not add diagrams, and do not try to give a complete description of the patterns as found in the books. Rather think of how you would explain the essential ideas of these patterns in a few sentences to a colleague while drinking coffee.

# Adapter Pattern:-
Adapter pattern works as a bridge between two incompatible interfaces. This design pattern comes under structural design pattern.This pattern involves a single class which is responsible to join functionalities of independent or incompatible interfaces.
## Eample:-
- Type C port to Universal port converter 

## Advantages:-
- Achieve reusability and flexibility.
- Client class is not complicated by having to use a different interface and can use polymorphism to swap between different implementations of adapters.

## Disadvantages:-
- All requests are forwarded, so there is a slight increase in the overhead.


# Builder Pattern:-
Builder pattern builds a complex object using simple objects and using a step by step approach. This design pattern comes under creational design pattern. It is mostly used when object can't be created in single step like in the de-serialization of a complex object

## Eample:
- Construction of house with foundation, pillars, build walls, door, windows.

## Advantages:-
- Provides clear separation between the construction and representation of an object.
- Better control over construction process.
- Supports to change the internal representation of objects

## Disadvantage:-
- Lines code may increase.
- Requried separate builder for different products.

# Mediator Pattern:-
Mediator pattern is used to reduce communication complexity between multiple objects or classes. This pattern provides a mediator class which normally handles all the communications between different classes and supports easy maintenance of the code by loose coupling. Mediator pattern falls under behavioral pattern category.

## Example:-
- Commonly used in message-based systems likewise chat applications.

## Advantages:-
- Decouples the number of classes.
- Simplifies object protocols.
- Centralizes the control.

## Disadvantage:-
- Centralizes control. The mediator pattern trades complexity of interaction for complexity in the mediator. Because a mediator encapsulates protocols, it can become more complex than any individual colleague. This can make the mediator itself a monolith that’s hard to maintain.

# Decorator pattern
Decorator pattern allows a user to add new functionality to an existing object without altering its structure. This pattern creates a decorator class which wraps the original class and provides additional functionality keeping class methods signature intact.

## Example:-
- Wearing clothes is an example of using decorators. When you’re cold, you wrap yourself in a sweater. If you’re still cold with a sweater, you can wear a jacket on top. If it’s raining, you can put on a raincoat.

## Advantages:-
- Provides greater flexibility than static inheritance.
- Enhances the extensibility of the object, because changes are made by coding new classes.
- Simplifies the coding by allowing you to develop a series of functionality from targeted classes instead of coding all of the behavior into the object.

## Disadvantages:-
- It can be complicated to have decorators keep track of other decorators, because to look back into multiple layers of the decorator chain starts to push the decorator pattern beyond its true intent.
