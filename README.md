# Lab Reflection: Unit 8 Lab 1 - Git Version Control + Debugging (BuggyProgram)

## Student Name
Matthew Gordon

## GitHub Repository URL
https://github.com/Smokeworks/cmsc115-unit8lab1
---

# Commit 1: Initial Commit

## What did you include in this commit?
BuggyProgram starter with JUnit tests and the files for this project

## What was the purpose of this commit?
Uploading the baseline of the project to github

---

# Commit 2: Task 1 (getGrade)

## Which tests in Task1Test were failing before your fix?
- Both testGrades() and testEdges() were failing.

## What was the issue in the code?
The grade levels were reversed and the boundary conditions were incorrect.

## What change did you make to fix it?
I corrected the grade levels and changed > to >= for 90 and 80.

## How did the tests help guide your fix?
The tests showed the expected results and helped identify the incorrect boundaries.

---

# Commit 3: Task 2 (sumEvenNumbers)

## Which tests in Task2Test were failing before your fix?
- testEmpty(), testOddNumbers(), and testSumEvenNumbers().

## What was the issue in the code?
- The loop went past the array bounds, causing an ArrayIndexOutOfBoundsException.

## What change did you make to fix it?
- I changed the loop condition so it stops at the last valid array index and set sum to 0.

## How did the tests help guide your fix?
- The tests showed that the loop was going outside the array bounds.

---

# Commit 4: Task 3 (sumRange)

## Which tests in Task3Test were failing before your fix?
- testSumRangeReverseOrder() was failing.

## What was the issue in the code?
- The method did not handle a range given in reverse order.

## What change did you make to fix it?
- I added logic to count down when the range is reversed.

## How did the tests help guide your fix?
- The test showed that a reversed range process failed helping me pin point what to work on

---

# Overall Reflection

## Which task was the easiest to fix? Why?
Task two because all the errors were the same and really had one simple change error-wise.

## Which task was the most difficult? Why?
Wouldn't say difficult but the reverse one took me a second, because it worked one way

## How did Git help you track your progress through the debugging process?
Its like a save point of what you did last and where you left off

## Why is it important to make small, frequent commits when debugging code?
Because if you make a mistake you dont lose unrelated work when reverting and revising, its just good work flow

## What did you learn about using JUnit tests to guide debugging?
JUnit tests were quick and efficient because they pinpoint what failed and help you get straight to the problem.


# Commit 5: Final Reflection

## What did you complete or update before making this final commit?
- I completed all three tasks, made sure the tests passed, and finished the README reflections.

## Why is it useful to document your work after completing a programming task?
- It helps keep track of what was changed, why it was changed, and how the problems were fixed.

Just a note I don't know why my other github account became a contributor, This is still Matthew BTW