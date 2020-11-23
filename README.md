# swift_testdrivenpractice

Test-driven development, or TDD, is an iterative way to develop software by iteratively making many small changes backed by tests.

It has four steps:
1. Red: Write a failing test, before writing any production app code.
2. Green: Write the bare minimum code to make the test pass.
          You're only allowed to write the bare minimum code to make a test pass.
          compilation errors fix is included in bare minimum.
3. Refactor: Clean up both your app and test code.

      Duplicate logic:includes properties, methods or classes to eliminate
      
      comments: your comment should explain why not how
      
      codesmells:For example, you might have logic that's making too many assumptions, uses hardcoded strings or has other issues
      
4. Repeat: Do this cycle again until all features are implemented.
This is also called the Red-Green-Refactor Cycle.
