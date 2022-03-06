## Method Man

1. Make a new class called `Mac` which extends `Computer` and also has a method `switchOn` like
this:
```java
public void switchOn () {
  System.out.println("Display Apple and make irritating sound.");
}
```
2. Add another class `WindowsPC` which extends `Computer` and also has a `switchOn` method which
prints "Turn screen blue and crash."

3. Make the `main` method create an *object* of each of your classes and call `switchOn` on
each object.

4. Make your `switchOn` methods in `Mac` and `WindowsPC` call the parent `Computer.switchOn`
method (using `super.switchOn()`). See how this affects your program’s output.