# ConcurrentModificationException in Java

This repository demonstrates a common error in Java programming: the `ConcurrentModificationException`.  This exception occurs when attempting to modify a collection (like an ArrayList) while iterating over it using a method that doesn't support concurrent modification. 

The `ConcurrentModificationExceptionExample.java` file shows the problematic code. The `ConcurrentModificationExceptionSolution.java` shows how to fix the problem using an `Iterator`.

This is a great example for illustrating the importance of understanding how Java handles collection iteration and modification.