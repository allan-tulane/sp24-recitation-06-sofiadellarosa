# CMPS 2200 Recitation 06
## Answers

**Name:** Sofia Della Rosa
**Name:** Jaimie Morris 


Place all written answers from `recitation-07.md` here for easier grading.



- **2)** W(n) = W(n-1) + W(n-2) + O(1)
  Base n=1
  W(n) = O(2^n-1) + O(2^n-2) + O(1) = O(2^n)

- **3)** S(n-1) + 1
  = O(n)

- **4)** The values in counts start increasing to the fibonacci numbers but it repeats and rewrites many values that were already calculated before getting the series down correctly.

- **6)** It will be called n amount of times. Once for each value because instead of calculating the sequence multiple times recursively it will recheck if the value was already calculated. This makes work and span both O(n)

- **8)** The maximum number of times that $F_i$ will be read for any value $i$ is n-2. The work of fib_bottom_up is O(n) and the span is O(n)

