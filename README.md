x86-instruction-size
====================

A simple C implementation for obtaining the instruction size of the current instruction for x86 and x86_64.

This code will return the size of the first instruction in the input code. For the majority of cases it doesn't try to distinguish from a valid and invalid instruction. 


It should be noted that this may not be up to date in the future or even supported in the future. Also it may have bugs in it, but it has passed my tests so far, such as getting the size of every instruction for a couple of libraries.
