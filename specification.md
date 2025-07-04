## NeedyVM Specification (Needle vCPU Fantasy Computer)

# Registers:

A - The AAAAAA
B - The BBbbBBb
C - The CccKKckkc
D - The Three Dee Register

# Operators:
nop - Not do anything. \x00

add [a] [b] - Adds. Stores it to the A register.

sub [a] [b] - Subtracts. Stores it to said A register.

mul [a] [b] - Multiplies. Stores it to said A register.

div [a] [b] - Divides. Unlike some **certain** CPUs, we have a divide operator and it's stored to A.

sta [pos] - Stores the value of A to a position in memory.

stb [pos] - Stores the value of B to a position in memory.

stc [pos] - Stores the value of C to a position in memory.

std [pos] - Stores the value of D to a position in memory.

lda [pos] - Loads the value of a position in memory to A.

ldb [pos] - Loads the value of a position in memory to B.

ldc [pos] - Loads the value of a position in memory to C.

ldd [pos] - Loads the value of a position in memory to D.

jmp [pos] - Jumps to a position in memory.

jie [pos] - Jumps if A equal to B.

jne [pos] - Jumps if A not equal to B.

rt - Return from jumping.

hlt - Hault the system's operation.