# terminalutilities
A set of utilities for use in a terminal

## Utilities
### Progress Bar
A progress bar used to track the progress of a value from 0 to some maximum value, printing in-place (overwriting) this progress.
#### Use
Initialise the bar by creating a `ProgressBar` object, and call `Update` to inform the bar of the new value. Once the value has reached its maximum, call `Complete` to finalise the bar and continue with the program.
    test
