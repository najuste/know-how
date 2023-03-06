# Basic design patters:

## Abstraction
Abstractions allow developers to generalize complex types and define contracts within their code and with code outside of their project. 
In TypeScript, interfaces are used to define complex types, which result in strict checks and reduce the number of possible bugs.
In React abstraction is done by using composition, where higher-level components combine standardized lower-level components to be part of the user interface together.

## Encapsulation
In Typescript achieved with public private and static functions.
In React encapsuation is commonly used for style splitting into modules.
And a great idea about using custom hooks for logic encapsulation:
https://kyleshevlin.com/use-encapsulation

## Polymorphism
Enables the same code(component, function...) to be used with different types of data. This helps to reduce code duplication and increase code reusability.

Polymorphism can be achieved in different ways:
</br>
<strong>Ad hoc polymorphism</strong> is used when a common interface is needed for a set of individually specified types.
<i>In React it would be function overloading. https://medium.com/@dmkolesnikov/ad-hoc-polymorphism-in-typescript-with-implicit-context-5c11dd668dd </i>.
  
<strong>Parametric polymorphism</strong> uses abstract symbols that can substitute for any type.
<i>In React it would be a component that can be rendered with any html tag or component by adding prop "as" to the component.
https://www.benmvp.com/blog/polymorphic-react-components-typescript/</i>

<strong>Subtype polymorphism</strong> allows different classes related by some common superclass to be used in place of that superclass.
<i>It is achieved through class inheritance, where a child class can inherit properties and methods from a parent class.</i>

## Inheritance
TypeScript supports single inheritance and multilevel inheritance but does not support hybrid and multiple inheritances.
Use the 'extends' keyword to allow a class to inherit from another class.
React recommends using composition over inheritance to reuse code between components. https://reactjs.org/docs/composition-vs-inheritance.html
