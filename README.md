# Solid Principles
These are the fundamental principles for writing a software that is-:
1. Extensible
2. Maintainable
3. Readable
4. Testable

It stands for following terms-:
1. Single Responsibility Principle
2. Open Close Principle
3. Liskov Substitution Principle
4. Interface Segregation principle
5. Dependency Inversion Principle

## Single Responsibility Principle
This principle states that a class should not have more than one reason to change.
It means a class or method should have clear defined responsibilities, what it does 
and what it not.<br/><br/>
For example- A Employee model class should have only responsibility of holding data
related to employee info like name, age, designation.
If Employee class contains the fuctions like processSalary, provideReview, applyForLeave etc.
Then we have given more than one responsibility on the employee class.

## Open Close Principle
It states that any software component should be open for extension and close for modification i.e.
new functionality can be added to it without breaking the existing functionality.

## Liskov Substitution Principle
Substitutability is a principle in object-oriented programming stating that, in a computer program,
if S is a subtype of T, then objects of type T may be replaced with objects of type S without altering 
any of the desirable properties of the program.<br/><br/>
In simple terms this principle states that the object of child class can be captured inside 
the parent class without any issues and it should be like we are using the parent class object.
We should avoid wrong abstraction where child class is not the proper child class of parent.

## Interface Segregation Principle
This principle states that you should not a god/bulk interface that define all the functionality,
but we should split our interfaces into interfaces which has specific functionality so that for client it makes 
easier to choose and implement.(Client is not forced to implement a method which it doesn't require)

## Dependency Inversion Principle
According to Robert Martin, Dependency Inversion principle is defined as-:
1. High level module shouldn't depend on low level modules. Both should depend on abstraction.
2. Abstraction should not depend on details, details should not depend on abstraction.
<p>
In simple terms all the high level modules that is your business logic should depend on low level
modules and there should be proper abstraction for accessing low level modules from high level modules
so that they can be replaced easily without affecting the high level modules.
<br/><br/>
**Always program to interfaces**
</p>
