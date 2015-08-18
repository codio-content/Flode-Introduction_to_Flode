![](.guides/img/output.png)

You should use an Output block to pass data back to a challenge. 

- Output blocks will also write data to the console window.
- If you want to write data to the console but do not want to pass it back to the challenge, then use a Debug block instead.
- You should be careful that you only pass as many outputs as the challenge expects.

The example below shows a Debug block (the one with the dotted outline) writing something only to the console and also an Output block writing the data contained in the `str` variable to the console and also outputting it back to the challenge.

![](.guides/img/output-exp.png)