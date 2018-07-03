Polymorphism & Composition Homework - Quiz
Polymorphism
What does the word 'polymorphism' mean?
A: As the name implies (poly=many, morph=form) it is the ability of an object to assume another form for a limited purpose.


What does it mean when we apply polymorphism to OO design? Give a simple Java example.
A: An object of a class may share very similar methods with other objects of other classes. To ensure a methodological unity throughout the system, we assign interfaces to these classes. By doing that we can create collection of different classes under one "interface" banner, or use the methods that's been assigned in their declaration to provide similar responses.

What can we use to implement polymorphism in Java?
Interfaces.

How many 'forms' can an object take when using polymorphism?
As much as we like.

Give an example of when you could use polymorphism.
A hotel's HVAC system can adjust AC settings of various rooms and halls. These halls can be instantiated as different objects of different classes. If HVAC adjustments are implemented to this system, each room now can have an IACable interface to access their AC settings.

Composition
What do we mean by 'composition' in reference to object-oriented programming?
Composition is the ability to extend and reuse other classes in a class.

When would you use composition? Provide a simple example in Java.
A car class can have an engine class that retrieves "driving force" and passes into a gear class, which in turn carries that rotational power to the "wheel" classed objects. It doesn't have to do this whole job on its own body. It can call the related objects and their methods to pass necessary i/o.

What is/are the advantage(s) of using composition?
See above. It aids in many ways.
1. cleaner code
2. accountability dispersed
3. relations revealed

What happens to the behaviours when the object composed of them is destroyed?
they are destroyed as well.
