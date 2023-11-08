# Polymorphism & Composition Homework - Quiz

# Polymorphism

1. What does the ___word___ 'polymorphism' mean?

polymorphism is where an object can be treated as being several different types depending on context.

2. What does it mean when we apply polymorphism to OO design? Give a simple Java example.

it means we can store objects of various types in the same variables or as arguments to the same method. an example
would be writing a function which took two objects of the abstract class Fish accepting objects of type Salmon
and Haddock as parameters because they both inherit from Fish.

3. What can we use to implement polymorphism in Java?

we can use abstract classes and interfaces.

4. How many 'forms' can an object take when using polymorphism?

number of interfaces implements, +1 for the abstract class

5. Give an example of when you could use polymorphism.

if we wanted to store objects which use a particular function in one arraylist, we could make an arraylist which 
expects to receive objects that implement that function.

# Composition and Aggregation

6. What do we mean by 'composition' in reference to object-oriented programming?

composition is where an object is made up of other objects which are dependent on it.

7. When would you use composition? Provide a simple example in Java.

whenever a model becomes too complex to reasonably store in one object. an object may need to do several different things,
so it would make sense to separate those responsibilities. a Plane would have various capabilities, so it might make 
sense for example to have the LandingGear as a separate constituent class which can be called upon when needed.

8. Give a difference between composition and aggregation?

composition implies that the subordinate class is dependent on its parent in order to exist, i.e. that the child
would also be deleted if you deleted the parent.

9. What is/are the advantage(s) of using composition/aggregation?

- enables clear separation of responsibilities
- avoids reusing code
- easier to maintain
- adheres to oop design principles

10. When using composition, when an object is destroyed, what happens to all the objects it is composed of?

they are also destroyed

11. When using aggregation, when an object is destroyed, what happens to all the objects it is composed of?

they can still exist independently