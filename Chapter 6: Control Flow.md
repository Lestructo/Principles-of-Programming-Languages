Sequencing:
- Statements are to be executed in a certain specified order (normally the order in they appear in text).

Selection:
- Depending on some run-time condition, a choice is to be made among two or more statements or expressions. The most common selection constructs are if and case (switch) statements.

Iteration:
- A given fragment of code is to be executed repeatedly, either acertain number of times, or until a certain run-time condition is true. Iteration constructs include for/do, while, and repeat loops.

Procedural Abstraction:
- Potentially complex collection of control constructs (a subroutine) is encapsulated in a way that allows it to be treated as a single unit, usually subject to parameterization.
- Procedural Language applies to any language, no matter what the units are called.

Recursion:
- An expression is defined in terms of (simpler versions of) itself, either directly or indirectly; the computational model requires a stack on which to save information about partially evaluated instances of the expression.
- Recursion is usually defined by means of self-referential subroutines (functoins).

Concurrency:
- Two or more program fragments are to be executed/evaluated “at the same time,” either in parallel on separate processors, or interleaved on a single processor in a way that achieves the same effect.

Exception handling and speculation:
- Exception handling: mechanism used to manage and respond to runtime errors without crashing or producing incorrect results.
- Try-Catch:
    - Try block: Contains the code that may throw an exception.
    - Catch block: Code to handle the exception if it occurs.

Speculation:
- A program fragment is executed optimistically, on the assumption that some expected condition will be true.

Nondeterminacy:
- The ordering or choice among statements or expressions is deliberately left unspecified, implying that any alternative will lead to correct results.

