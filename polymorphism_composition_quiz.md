# Polymorphism & Composition Homework - Quiz

# Polymorphism

1. What does the ___word___ 'polymorphism' mean?

Many forms

2. What does it mean when we apply polymorphism to OO design? Give a simple Java example.

public class Drink(){
    private name;
}

public interface IBrew () {
    public String isBrewing(){}
}

public class Tea extends Drink implements IBrew(){}
public class Coffee extends Drink implements IBrew(){}

Both tea and cofee are drinks and both have methods isBrewing that can return seperate data.

3. What can we use to implement polymorphism in Java?

Inheritance

4. How many 'forms' can an object take when using polymorphism?

any number

5. Give an example of when you could use polymorphism.



# Composition

6. What do we mean by 'composition' in reference to object-oriented programming?

Composition is an OO design technique describing associations between objects and classes

7. When would you use composition? Provide a simple example in Java.

When an object contains another object, diplaying a has a relation.
A cup of tea has, a tea bag, milk, and sugar.

public class Tea() {
    private TeaBag teabag;
    private Milk milk;
    private Sugar sugar;
}



8. What is/are the advantage(s) of using composition?

Allows for dynamic changing and flexibility.

9. When an object is destroyed, what happens to all the objects it is composed of?

They are deleted too