## Problems

| # | Problem Name | Difficulty | Question | Status | Solution | Remarks |
|---:|-------------|------------|----------|--------|----------|---------|
| 1 | Sum of Array | Basic | [GFG](https://www.geeksforgeeks.org/problems/sum-of-array2326/1) | ✅ Done | — | Use a loop and accumulate the sum. |
| 2 | Remove duplicates from unsorted array | Easy | [GFG](https://www.geeksforgeeks.org/problems/remove-duplicates-from-unsorted-array4141/1) | ✅ Done | — | Use a map/unordered_set to track seen elements. |
| 3 | Second Largest | Easy | [GFG](https://www.geeksforgeeks.org/problems/second-largest3735/1?page=1&sprint=63af446b97dfa5601c7b06b52b991d07&sortBy=submissions) | ✅ Done | — | Track largest & second-largest (handle duplicates). |
| 4 | Binary Search | Easy | [GFG](https://www.geeksforgeeks.org/problems/binary-search-1587115620/1?page=1&sprint=63af446b97dfa5601c7b06b52b991d07&sortBy=submissions) | ✅ Done | — | Two pointers: `low=0`, `high=n-1`. |
| 5 | Equilibrium Point | Easy | [GFG](https://www.geeksforgeeks.org/problems/equilibrium-point-1587115620/1?page=1&sprint=63af446b97dfa5601c7b06b52b991d07&sortBy=submissions) | ✅ Done | — | Maintain `totalSum` and `leftSum`; compare after subtracting current. |
| 6 | Two Sum (Key Pair) | Easy | [GFG](https://www.geeksforgeeks.org/problems/key-pair5616/1?page=1&sprint=63af446b97dfa5601c7b06b52b991d07&sortBy=submissions) | ✅ Done | — | Sort + two pointers or use hashing. |
| 7 | First Repeating Element | Easy | [GFG](https://www.geeksforgeeks.org/problems/first-repeating-element4018/1?page=3&category=Arrays,two-pointer-algorithm,Pointers&sortBy=submissions) | ✅ Done | — | Use `unordered_map` frequency; return earliest index with freq > 1. |
| 8 | Frequency of Array Elements | Easy | [GFG](https://www.geeksforgeeks.org/problems/frequency-of-array-elements-1587115620/1?page=1&sprint=63af446b97dfa5601c7b06b52b991d07&sortBy=submissions) | ✅ Done | — | Use freq array/map depending on constraints. |
| 9 | Reverse an Array | Basic | [GFG](https://www.geeksforgeeks.org/problems/reverse-an-array/1?page=2&category=Arrays,Pointers&difficulty=Basic,Easy&sortBy=submissions) | ✅ Done | — | Two pointers swap while `l < r`. |
| 10 | Count Pairs with Given Sum 0 | Easy | [GFG](https://www.geeksforgeeks.org/problems/count-pairs-with-given-sum5022/1?page=1&category=Arrays,Pointers&difficulty=Basic,Easy&sortBy=submissions) | ✅ Done | — | Use hashmap counts to count pairs. |
| 11 | Reverse a Number | Basic | [GFG](https://www.geeksforgeeks.org/problems/reverse-digit0316/1) | ✅ Done | — | `rev = rev*10 + n%10; n/=10` until `n==0`. |
| 12 | Sum of AP | Basic | [GFG](https://www.geeksforgeeks.org/problems/sum-of-ap-series4512/1) | ✅ Done | — | AP sum: `n*(2*a + (n-1)*d)/2` (use `long long`). |
| 13 | Prime Number | Basic | [GFG](https://www.geeksforgeeks.org/problems/prime-number2314/1) | ✅ Done | — | Check divisibility up to `i*i<=n`; handle `n<=1`. |
| 14 | Number of Factors | Easy | [GFG](https://www.geeksforgeeks.org/problems/number-of-factors1435/1) | ✅ Done | — | Count divisors up to `sqrt(n)`; handle perfect squares. |
| 15 | Palindrome Number | Basic | [GFG](https://www.geeksforgeeks.org/problems/palindrome0746/1) | ✅ Done | — | Reverse number and compare with original (store a copy). |
| 16 | GCD | Easy | [GFG](https://www.geeksforgeeks.org/problems/gcd-of-two-numbers3459/1) | ✅ Done | — | `gcd` via Euclid; `lcm=(a/gcd)*b` (use long long). |
| 17 | LCM of Two Numbers | Easy | [GFG](https://www.geeksforgeeks.org/problems/lcm-of-two-numbers/1) | ✅ Done | — | `gcd` via Euclid; `lcm=(a/gcd)*b` (use long long, divide first). |
| 18 | Rotate Array by K (Clockwise) | Easy | [GFG](https://www.geeksforgeeks.org/problems/rotate-array-clockwise/1) | ✅ Done | — | swap(begin to end) -> swap(0 to k-1) -> swap(k to n-1). |
| 19 | Array Subset of Another Array | Medium | [GFG](https://www.geeksforgeeks.org/problems/array-subset-of-another-array2317/1) | ✅ Done | — | issubset |
| 20 | Rotate Array | Medium | [GFG](https://www.geeksforgeeks.org/problems/rotate-array-by-n-elements-1587115621/1) | ✅ Done | — | — |
| 21 | Mean of Array | Easy | [GFG](https://www.geeksforgeeks.org/problems/mean0021/1) | ✅ Done | — | Compute sum (use long long) and return `sum / n` (integer division as per problem). |
| 22 | Check if an Array is Sorted | Easy | [GFG](https://www.geeksforgeeks.org/problems/check-if-an-array-is-sorted0701/1) | ✅ Done | — | — |
| 23 | Max Consecutive One      | Medium     | [GFG](https://www.geeksforgeeks.org/problems/max-consecutive-one/1)          | ✅ Done | —    | Keep current streak of 1s and max; reset on 0. |
| 24 | 1-D Prefix Sum | Medium | [GFG](https://www.geeksforgeeks.org/problems/1-d-prefix-sum/1) | ✅ Done | — | — |
| 25 | Equal Sum | Medium | [GFG](https://www.geeksforgeeks.org/problems/equal-sum0810/1) | ✅ Done | — | Use prefix sum; if left sum == right sum return true else false. |
| 26 | Buy Stock 2 | Medium | [GFG](https://www.geeksforgeeks.org/problems/buy-stock-2/1) |   |Add B into A: matrixA[i][j] += matrixB[i][j] `min).|
| 27.| Addition of Two Square Matrices         | Easy       | [GFG](https://www.geeksforgeeks.org/problems/addition-of-two-square-matrices4916/1)|  ✅ Done | — | Single transaction: keep|
| 28 | Replace elements by its rank | Medium | [GFG](https://www.geeksforgeeks.org/problems/replace-elements-by-its-rank-in-the-array/1) | ✅ Done | — | — |
| 29 | Kadane's Algorithm | Medium | [GFG](https://www.geeksforgeeks.org/problems/kadanes-algorithm-1587115620/1) | ✅ Done | — | Find maximum subarray sum using dynamic programming. |
| 30 | Max Sum Subarray of Size K | Hard | [GFG](https://www.geeksforgeeks.org/problems/max-sum-subarray-of-size-k5313/1) | ✅ Done | — | Sliding window: maintain sum of current window (size k), update max, slide by subtracting outgoing + adding incoming. |
| 31 | Count Distinct Elements in Every Window | Hard | [GFG](https://www.geeksforgeeks.org/problems/count-distinct-elements-in-every-window/1) | ✅ Done | — | Use hashmap (unordered_map) for freq + vector for answers; slide window by decrement/removing left and adding right. |
