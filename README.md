
# awesome-resources
List of worth reading articles on many categories that I came across

1. __SICP__: 
  * Description: 
   
   > Structure and Interpretation of Computer Programs (SICP) is a textbook aiming to teach the principles of computer programming, such as abstraction in programming, metalinguistic abstraction, recursion, interpreters, and modular programming. (Wikipedia)
  
  * Link e-book: https://sicpebook.files.wordpress.com/2011/06/sicp.pdf

# Software Engineering Principles

1. __FIRST__ (Unit testing):

 * Fast
 > Tests should be fast. They should run quickly. When tests run slow, you won’t want
 to run them frequently. If you don’t run them frequently, you won’t find problems early
 enough to fix them easily. You won’t feel as free to clean up the code. Eventually the code
 will begin to rot.
 * Independent
 > Tests should not depend on each other. One test should not set up the conditions
 for the next test. You should be able to run each test independently and run the tests in
 any order you like. When tests depend on each other, then the first one to fail causes a cascade
 of downstream failures, making diagnosis difficult and hiding downstream defects
 * Repeatable
 > Tests should be repeatable in any environment. You should be able to run the
 tests in the production environment, in the QA environment, and on your laptop while
 riding home on the train without a network. If your tests aren’t repeatable in any environment,
 then you’ll always have an excuse for why they fail. You’ll also find yourself unable
 to run the tests when the environment isn’t available
 * Self-checking
 > The tests should have a boolean output. Either they pass or fail. You
 should not have to read through a log file to tell whether the tests pass. You should not have
 to manually compare two different text files to see whether the tests pass. If the tests aren’t
 self-validating, then failure can become subjective and running the tests can require a long
 manual evaluation.
 * Timely
 > The tests need to be written in a timely fashion. Unit tests should be written just
 before the production code that makes them pass. If you write tests after the production
 code, then you may find the production code to be hard to test. You may decide that some
 production code is too hard to test. You may not design the production code to be testable.
 
2. __SOLID__ (Clean architecture):
 * Single Responsibility 
 > A class or module should have one, and only one, reason to change.
 * Open Closed 
 > Software entities (classes, modules, functions, etc.) should be open for extension, but closed for modification
 * Liskov Substitution 
 > Let q(x) be a property provable about objects of x of type T. Then q(y) should be provable for objects y of type S where S is a subtype of T
 * Interface Segregation 
 > A client should never be forced to implement an interface that it doesn’t use or clients shouldn’t be forced to depend on methods they do not use.
 * Dependency Inversion principle
 > Entities must depend on abstractions not on concretions. It states that the high level module must not depend on the low level module, but they should depend on abstractions.
 
  A worth reading article can be found at: https://scotch.io/bar-talk/s-o-l-i-d-the-first-five-principles-of-object-oriented-design
 
