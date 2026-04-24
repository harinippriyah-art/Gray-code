Gray Code
The sequence is generated using the bitwise formula `i ^ (i >> 1)`. This mathematical approach ensures that consecutive values differ by exactly one bit, satisfying all Gray code properties including the "cyclic" requirement where the last and first elements also differ by one bit.

- **Complexity:** $O(2^n)$ time and $O(1)$ extra space.
