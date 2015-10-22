This repo mainly treated as note of this course.
Furthermore, I may write down some my own thoughts on Unit Testing.


### Test Driven Development
#### Intro
- Test failure first
- Make the simplest test passes first
- Step by step
- !Freedom to refactor
- Drive yourself to work with small unit, more smaller unit, break your code into pieces
- Coverage -- it depends on what you want to accomplish. Whether necessary, time enough.
  - Generally over emphasize
  - It's not an accurate product property
  - Usually used by manager


#### Hypothetical Feature (Discovery Testing)
- Negotiate what the input & output
- Make a tree to divide responsibilities
- Focusing on one subtree each time (What TDD mainly about is --> FOCUS)
  - The hardest test writing is NOT a pure function
- Therefore, if we want to write simple test we must give simple code too (No mocks)
- Collaborators, no logic ONLY mocks --> validating the interaction what we wanna to be
  - ONLY make sure things glued correctly, make sure function invoked correctly
- If you do like this, you will find that there is no CODE REUSE
- Don't be so attached to your code
- Pay technical debt by trusting future-us to know better
