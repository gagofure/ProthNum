# Proth-Prime

 A function that takes in a Proth Number and uses Proth's theorem to determine if said number is prime.

# Why is it a bad idea to use recursion method to find the fibonacci of a number

Recursion uses more memory; Because the function has to add to the stack with each recursive call and keep the values there until the call is finished, the memory allocation is greater than that of an iterative function. Thus, recursion may cause memory overflow if your stack space is large, and is also inefficient in cases where the same value is calculated again and again

Recursion can be slow. If not implemented correctly, it can be much slower than iteration. It is actually pretty difficult to write a recursive function where the speed and memory will be less than that of an iterative function completing the same task. The reason that recursion is slow is that it requires the allocation of a new stack frame.

Time Complexity: O(2^n)  which is exponential as opposed to liner O(n) of iteration
