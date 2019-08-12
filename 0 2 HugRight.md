## Maze Completion Using Right Wall
If you adopted the "Follow the Right Wall" algorithm, you will complete Level 10. 
What is the JavaScript code you got? 

Cut and paste and assign it to the variable level_10_code.

How many blocks did you have left? 
Assign it to the variable remaining_blocks.
```
level_10_code = """while (notDone()) {
      if (isPathRight()) {
        turnRight();
        }
        if (isPathForward()) {
          moveForward();
        } else {
          turnLeft();
        }
       }"""
```
