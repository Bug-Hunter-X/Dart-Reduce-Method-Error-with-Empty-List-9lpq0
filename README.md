# Dart Reduce Method Error with Empty List
This repository demonstrates a common error encountered when using the `reduce` method in Dart with an empty list.  The `reduce` method requires at least one element to operate; otherwise, it throws a `StateError`.

The `bug.dart` file shows the error scenario, and `bugSolution.dart` offers solutions to handle this situation gracefully.

This is a helpful example of defensive programming practices in Dart, ensuring your code is robust and handles edge cases effectively.  Remember to always check for empty collections before applying `reduce` or other similar methods that assume a minimum number of elements.