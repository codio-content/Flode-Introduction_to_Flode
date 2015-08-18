![](.guides/img/input.png)

An Input block should be used for challenges that tell you they will be passing in some data for your chart to work with. 

- For each value you expect to receive, use a single Input block.
- You can see the input values in the variable list. This is explained in the 'Console & Variables' section.
- You can enter test data into each Input block by doube-clicking.
- Each Input block gets an automatically assigned variable name, `input0`, `input1`, `input2` etc.

## Test data
Before you run your challenge, you will want some test data to test your chart with. You can enter your test data by double-clicking on the Input block and then entering your test data.

The examples below show test data already entered in the Input blocks.

## Example 1
Here is an example challenge.

> We pass in a number, N, and we want you to add 100 to N and then output the result.

In this case, you would create one Input block to receive the value. This will be assigned to a Flode variable called `input0`.

Here is how you would represent this in Flode (we are also outputting the result).

![](.guides/img/input-exp1.png)

## Example 2
Here's another example that requires 2 inputs.

> We will pass you person's name and their age. You should output a single string that says 'Hello [person's name], you are [age]'.

If you look at the chart below, you can see how this chart expects 2 inputs. The first input gets the variable name `input0` and the second one `input1`. 

![](.guides/img/input-exp2.png)

## Example 3
The final example (we will explain what an array is in a later Unit) shows you you would process 2 array input. The first is an array of numbers, the second an array of strings.

![](.guides/img/input-exp3.png)

