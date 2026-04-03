# 🐍 Python Exception Handling & Debugging Assignment
A beginner-level Python assignment covering exception handling and debugging techniques — with theory explanations, real-life examples, and working code programs.


# 📚 Topics Covered
## Section A — Exception Handling

What is an exception and why it occurs
Real-life examples of exceptions
Handling ZeroDivisionError
Handling ValueError from user input
Handling FileNotFoundError when opening a file
Using try–except–else to add two numbers
Using finally block to always run cleanup code

## Section B — Debugging Techniques

What is debugging and why it matters
Three types of Python errors with 5 examples each:

Syntax Error
Runtime Error
Logical Error


Identifying error type from code
Print debugging to track variable values
Reading and understanding error messages
Using try–except as a debugging technique for ValueError and ZeroDivisionError


▶️ How to Run
Option 1 — Google Colab (Recommended)

Open Google Colab
Create a new notebook
Paste the full code into a cell OR upload the .py file and run:

pythonexec(open("exception_debugging_assignment.py").read())

Run the cell — all sections execute automatically

Option 2 — Run Locally
bashpython exception_debugging_assignment.py

⚠️ Exception Types Reference
ExceptionCauseZeroDivisionErrorDividing a number by zeroValueErrorWrong type of value (e.g. int("abc"))FileNotFoundErrorOpening a file that does not existTypeErrorWrong data type used in operationIndexErrorAccessing a list index that does not existNameErrorUsing a variable that was never defined

🔴 Three Types of Errors
Error TypeWhen it occursExampleSyntax ErrorBefore program runsMissing colon in if statementRuntime ErrorWhile program is runningDividing by zeroLogical ErrorProgram runs but gives wrong answerUsing + instead of * for area

🛠️ try–except–else–finally Structure
pythontry:
    # code that might cause an error
except ValueError:
    # runs if ValueError occurs
except ZeroDivisionError:
    # runs if ZeroDivisionError occurs
else:
    # runs ONLY if no error occurred
finally:
    # ALWAYS runs, error or not
---
## 💡 Key Concepts Used

try, except, else, finally
raise keyword for exceptions
Multiple except blocks
Print debugging technique
Reading Python error messages
int(), float() conversion with error handling
