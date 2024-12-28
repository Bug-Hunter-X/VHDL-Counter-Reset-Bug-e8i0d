# VHDL Counter Bug Report

This repository demonstrates a common error in VHDL counter design and its solution. The `buggy_counter.vhdl` file shows a counter that incorrectly resets at the maximum count, while the corrected code in `fixed_counter.vhdl` provides a robust and efficient solution.

The bug stems from a seemingly straightforward conditional assignment within the process. This example highlights a need for careful consideration of signal assignments and process flow when using VHDL for sequential logic.

## Bug Description
The counter doesn't work correctly; it doesn't wrap around smoothly; it resets prematurely at 15 instead of reaching 15 then wrapping around to 0.