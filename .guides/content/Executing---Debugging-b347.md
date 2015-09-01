![](.guides/img/run.png)

Flode lets you run your chart as a program. There are 3 buttons for controlling execution.

- **Run** this runs your program at full speed and stops when it reaches an End block or has no block left to execute.
- **Step** is a very useful feature that lets you step through your chart one block at a time. This is useful for debugging your chart.
- **Stop** terminates execution of your code immediately.

## Console and Variables
When you enter Run or Step modes, you will be shown the Console and Variables windows at the bottom of the screen. These, together with Step mode especially, are very useful for exactly following the behavior of your chart at your own speed.

To hide (and show) this window, press the Console button.

![](.guides/img/console.png)

## Debugging
Debugging is something that is an integral part of all programming. The best way to debug your Flode chart is to press the Step button.

This will highlight the block that is about to execute. You can inspect your variables in the Variable window at the bottom of the screen.

Each time you press the Step button, the currently highlighted block will execute and it will move on to the next block.

The example below shows a chart in Step mode with the block about to be executed highlighted. You can see how a Debug block has written to the Console. You can also see the current state of the variables.

![](.guides/img/step.png)