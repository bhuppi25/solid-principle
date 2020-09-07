#Solid Principles
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

##Open Close Principle
It states that any software component should be open for extension and close for modification i.e.
new functionality can be added to it without breaking the existing functionality.

##Liskov Substitution Principle
Substitutability is a principle in object-oriented programming stating that, in a computer program,
if S is a subtype of T, then objects of type T may be replaced with objects of type S without altering 
any of the desirable properties of the program.<br/><br/>
In simple terms this principle states that the object of child class can be captured inside 
the parent class without any issues and it should be like we are using the parent class object.
We should avoid wrong abstraction where child class is not the proper child class of parent.
