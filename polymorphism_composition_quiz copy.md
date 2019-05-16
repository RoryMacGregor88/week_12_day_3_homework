# Polymorphism & Composition Homework - Quiz

# Polymorphism

1. What does the ___word___ 'polymorphism' mean?

The ability to become many things. 

2. What does it mean when we apply polymorphism to OO design? Give a simple Java example.

The ability for an object to exist as many things simultaneously. For example, a Phone object that implements an ICall interface is both a Phone and an ICall, and can be treated as either or both. 

3. What can we use to implement polymorphism in Java?

By implementing interfaces.

4. How many 'forms' can an object take when using polymorphism?

Infinite.

5. Give an example of when you could use polymorphism.

A list of tech devices like a smartphone, a landline phone, a tablet, a PC, a TV, a laptop, etc, but only the smartphone, tablet and landline implement the ICall interface. We can now group together only the devices with the ability to call, and promise they wil have certain functions.



# Composition

6. What do we mean by 'composition' in reference to object-oriented programming?

An object made up of 1 or more other objects.

7. When would you use composition? Provide a simple example in Java.

A class taking another class in its constructor. For example, a Car object taking an Engine object in its constructor.

8. What is/are the advantage(s) of using composition?

Keeping code dry and re-usable. Using the above example, we don't have to define an what an engine is/can do every timw we make a new Car, we can simply create and Engine one time, then pass a new instance to as many Cars as we like.

9. When an object is destroyed, what happens to all the objects it is composed of?

They are destroyed along with it. The instances only, the classes of those objects will remain. 