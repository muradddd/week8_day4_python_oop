Write a superclass called Shape (as shown in the class diagram), which contains:

    Two instance variables color (String) and filled (boolean).
    The constructors: constructor that initializes the color and filled to the given values.
    A toString() method that returns "A Shape with color of xxx and filled/Not filled".
    Write a test program to test all the methods defined in Shape.
    Write two subclasses of Shape called Circle and Rectangle, as shown in the class diagram.
    The Circle class contains:
    An instance variable radius (double).
    The constructor get radius of circle. 
    Methods getArea() and getPerimeter().
    Override the toString() method inherited, to return "A Circle with radius=xxx, which is a subclass of yyy", where yyy is the output of the toString() method from the superclass.
    The Rectangle class contains:
    Two instance variables width (double) and length (double).
    The constructor get width (double) and length (double). 
    Methods getArea() and getPerimeter().
    Override the toString() method inherited, to return "A Rectangle with width=xxx and length=zzz, which is a subclass of yyy", where yyy is the output of the toString() method from the superclass.
    Write a class called Square, as a subclass of Rectangle. Convince yourself that Square can be modeled as a subclass of Rectangle. Square has no instance variable, but inherits the instance variables width and length from its superclass Rectangle.

