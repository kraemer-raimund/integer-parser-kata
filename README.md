# Integer Parser Kata

A coding kata focusing on TDD. Intended as the next step after being introduced to TDD with trivial katas like FizzBuzz.

## Goal

Test-drive a parser that parses an integer from a string.

Note: Your language's standard library can probably do that, but for this exercise pretend that it can't. The problem's
difficulty level is good for developers who are new to TDD but not new to programming, and who have been introduced
to TDD with trivial katas like FizzBuzz but struggle with bridging the gap between those beginner exercises and a real
enterprise codebase.

## Exercise 1: Think

Note down (in bullet points, not in code) a list of potential test cases you can think of. What's the
expected behavior for each test case?

Did you also think of these cases?

<details>
<summary>Reveal hints</summary>
  - "normal" integers (like 42)<br/>
  - negative integers<br/>
  - 0 and -0<br/>
  - min and max values<br/>
  - out of bounds values (like max + 1 and min - 1)<br/>
  - hex/octal/binary representations<br/>
  - empty string<br/>
  - invalid string (like "asdf" or "§$%&")<br/>
  <br/>
  You can choose (or negotiate with your instructor) which of these to include in the exercise and how to handle the others.
</details>

## Exercise 2: Implement with TDD

1. Choose the simplest test case. Write a test. "But wait, how can I write a test if I don't even know what the code
will look like?" What do you *want* it to look like? Design (!) a simple, easy to use, self-explanatory API
[from the caller's perspective](https://raimund-kraemer.dev/2023/11/28/technical-empathy/). Don't think of the
algorithm, focus on the behavior. "For input X I expect Y to happen."

2. Run your tests, but before you do, ask yourself "Do I expect this test case to pass or fail? And why?".
   Check your hypothesis.<br/>
   (In case you were wrong, what did you miss? Double-check the test, and rethink your
   reasoning for your hypothesis.)

3. Implement the code that makes your new test pass (without changing the test). Choose the simplest implementation.
   (The simplest implementation may involve hardcoding.) Run your tests again. Now, do you expect them to pass or
   fail (and why)?<br/>
   All tests are green? Commit!

4. Refactor the implementation for clarity. This means that the behavior *must* stay the same. Run your tests after each change.<br/>
   All tests are green? Commit!

5. Go to 1, choosing the next test case. Which one you choose depends on a number of factors and is mostly based on experience
   or trade-offs. Try to think of reasons why you would choose a certain test over another one. If you can't think of good reasons
   why any particular one should be the next, choose a random test case and learn from the result.

___

© 2024 Raimund Krämer - Use with attribution.

Links to third party sites are included for convenience only and I am not responsible for their contents.
