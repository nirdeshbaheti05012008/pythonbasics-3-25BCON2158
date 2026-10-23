# README Audit

## README Fact-Check Table

| Claim Made in README | True? | Evidence / Correction Made |
|---|---|---|
| Program defines a `Student` class | Yes | `class Student:` defines the class. |
| Program creates a student object | Yes | `s1 = Student()` creates an instance. |
| Program assigns the student's name | Yes | `s1.name = "Rahul"` |
| Program assigns a roll number | Yes | `s1.roll = 101` |
| Program assigns marks | Yes | `s1.marks = 87.5` |
| Program displays student details | Yes | Three `print()` statements display the attributes. |
| Program uses dot notation to access attributes | Yes | The code accesses `s1.name`, `s1.roll`, and `s1.marks`. |
| Marks are formatted to one decimal place | Yes | `format(s1.marks, ".1f")` specifies one digit after the decimal point. |
| Output shows `Name: Rahul` | Yes | The first print statement displays the name. |
| Output shows `Roll: 101` | Yes | The second print statement displays the roll number. |
| Output shows `Marks: 87.5` | Yes | The third print statement formats and displays the marks. |
| Program uses a constructor to initialize attributes | No | The class contains only `pass`; no custom `__init__()` method is defined. |
| Program converts a structure into a dictionary | No | No dictionary or conversion operation appears in the code. |
| Program creates a dictionary using `dict()` | No | The code does not call `dict()` or create a dictionary literal. |
| Program takes student details from user input | No | The values are hard-coded; there is no `input()` function. |
| Program requires external libraries | No | The code uses built-in Python functionality only. |
| Program validates student data | No | No validation logic is present. |
| Program handles invalid input or errors | No | No explicit input handling or `try/except` block exists. |
| The script is named `struct_to_dict.py` | Cannot Verify | The code snippet does not establish the actual filename. |
| The repository contains `README.md` | Cannot Verify | The repository structure cannot be confirmed from the code alone. |
| The project has no license | Cannot Verify | The code does not establish the repository's license status. |

## Audit Conclusion

The README's claims about class creation, object creation, attribute assignment, printing, and number formatting are supported by the code.

However, the name `Struct to Dict` suggests a structure-to-dictionary conversion, which the current code does not perform. The program creates a `Student` object and assigns attributes to it; it does not convert that object into a dictionary.

Repository structure, filename, and license status require separate verification.
