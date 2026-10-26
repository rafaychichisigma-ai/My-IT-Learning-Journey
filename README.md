# My-IT-Learning-Journey
### October 26, 2026 - 32-bit vs 64-bit Architecture

**What I learned today:**
*   The difference between 32-bit and 64-bit is the size of the CPU's registers. (32-bit = 4 bytes, 64-bit = 8 bytes).
*   Registers hold the data, but the actual math happens in the ALU (Arithmetic Logic Unit).
*   The biggest difference is memory addressing. A 32-bit CPU can only point to 2^32 addresses (Max 4GB of RAM). A 64-bit CPU can point to 2^64 (practically unlimited).
*   64-bit is much faster for heavy software (like gaming or video editing) because it can process double the data in a single clock cycle.

**My "Aha!" Moment:**
*   *A 32-bit CPU can only generate 2^32 addresses (which equals 4GB of RAM). Even if you install 16GB of physical RAM, the 32-bit CPU physically cannot generate enough addresses to point to the remaining 12GB, so that memory just sits there unused. *
