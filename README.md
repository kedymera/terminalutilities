# terminalutilities
A set of utilities for use in a terminal.

## Progress Bar
A progress bar used to track the progress of a value from 0 to some maximum value, printing in-place (overwriting) this progress.
### Use
Initialise the bar by creating a `ProgressBar` object, passing at least a title and a maximum value, then call `Update` with the new value. Once the value has reached its maximum, call `Complete` to finalise the bar and continue with the program.
### Example
```python
n = 999999
pb = terminalutilities.ProgressBar("Doing", n)
x = 0
while x < n:
    x += 1
    pb.Update(x)
pb.Complete()
```
