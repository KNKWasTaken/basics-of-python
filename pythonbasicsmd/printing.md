# Printing
Printing in Python means printing something a value in your console/terminal/prompt
It works using the `print()` function
Example:-
```py
print('Hello World!')
```
## How `print()` works:-
`print()` is a function that uses its parameters to print a certain value/object.
Complete print syntax:-
```py
print(*values, sep=' ', end='\n', file=sys.stdout, flush=False)
```
It's parameters are:-
1. `values`:- These are the objects that are going to be printed. There can be more than one object provided. Example, `print('Hello', 'World')`
2. `sep`:- It stands for 'separator'. It is the string that seperates the different values provided in `values`. It is optional and if not provided, results to a whitespace ( ). Example, `print('Hello', 'World', sep=' to the ')`
3. `end`:- It is the string that is added to the end of a printed output. It is optional and if not provided, results to a newline character (\n). Example, `print('Hello', 'World', end='!')`
4. `file`:- It is the writable object where the output of the function is sent to. It accepts writable objects like sys.stdout, sys.stderr, file objects or even custom writable objects. It will be explained in detail in another tutorial (File Handling). It is optional and if not provided, results to the standard output (sys.stdout). Example, `print('Error: Something not found', file=sys.stderr)`
5. `flush`:- It confirms whether the data given to the function should immediately write it (flush) or write it after the buffer is complete. It is a boolean value. It is optional if not provided, results to False. Example, `print('Hello World', flush=False)`.
Detailed examples are given in other files.
