# Uncommon Assembly Language Bugs

This repository demonstrates two uncommon yet potentially devastating bugs that can occur in assembly language programming:

1. **Out-of-Bounds Memory Access:**  This bug arises from incorrect calculation of memory addresses, leading to access violations and program crashes.
2. **Stack Frame Corruption:** This bug arises from improper handling of stack frames during function calls, leading to unpredictable behavior and data corruption.

The `bug.asm` file showcases these errors. The `bugSolution.asm` file provides corrected code that avoids these errors.  This example highlights the importance of careful memory management and stack frame handling in low-level programming.