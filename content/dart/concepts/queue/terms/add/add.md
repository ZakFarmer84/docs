---
Title: add
Description: 'A Dart method to append or concatenate two strings.' 
Subjects: 
  - 'Developer Tools'
  - 'Code Foundations'
  - 'Computer Science'
Tags:
  - 'Dart'
  - 'Programming'
  - 'Queue'
CatalogContent: 
  - 'learn-dart'
  - 'paths/dart'
---

Dart allows the user to append or concatenate a string and add it to the end of an existing string using the **`.add()`** method. Since Dart strings are immutable (unable to be changed once created), the `.add()` method creates a new string rather than modifying the original string.

## Syntax

The `.add()` syntax within Dart is specifically related to the 'String' class.

## Example
In this example we are attempting to create a standard "Hello, World!" message. Unfortunately we forgot the second part of the message and will need to append the original string so it is correct. We can do this using the following code example.

```dart 
void main() {
  String startingString = "Hello, ";
  String fogottenString = "World!";
  String correctString = startingString.add(forgottenString);
  print(combinedString); // Output = intended  "Hello, World!" instead of the orignal mistake of "Hello, "
}
```
