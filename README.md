## Problems

| # | Problem Name | Difficulty | Question | Remarks |
|---:|-------------|------------|----------|---------|
| 1 | Sum of Array | Basic | https://www.geeksforgeeks.org/problems/sum-of-array2326/1 | Use a loop and accumulate the sum. |
| 2 | Remove duplicates from unsorted array | Easy | https://www.geeksforgeeks.org/problems/remove-duplicates-from-unsorted-array4141/1 | Use a map to track seen elements map.find(arr[i])==map.end(); add [...] |
| 3 | Second Largest | Easy | https://www.geeksforgeeks.org/problems/second-largest3735/1?page=1&sprint=63af446b97dfa5601c7b06b52b991d07&sortBy=submissions | (Add solution file link here) |
| 4 | Binary Search | Easy | https://www.geeksforgeeks.org/problems/binary-search-1587115620/1?page=1&sprint=63af446b97dfa5601c7b06b52b991d07&sortBy=submissions | Use two pointers (low=0, high=n-1). |
| 5 | Equilibrium Point | Easy | https://www.geeksforgeeks.org/problems/equilibrium-point-1587115620/1?page=1&sprint=63af446b97dfa5601c7b06b52b991d07&sortBy=submissions | Use prefix sums (or keep totalSum as[...]. |
| 6 | Two Sum (Key Pair) | Easy | https://www.geeksforgeeks.org/problems/key-pair5616/1?page=1&sprint=63af446b97dfa5601c7b06b52b991d07&sortBy=submissions | Sort the array, then use two pointers (l=0, r=n-1).[...] |
| 7 | First Repeating Element | Easy | https://www.geeksforgeeks.org/problems/first-repeating-element4018/1?page=3&category=Arrays,two-pointer-algorithm,Pointers&sortBy=submissions | Use unordered_map to cou[...] |
| 8 | Frequency of Array Elements | Easy | https://www.geeksforgeeks.org/problems/frequency-of-array-elements-1587115620/1?page=1&sprint=63af446b97dfa5601c7b06b52b991d07&sortBy=submissions | Convert array in[...] |
| 9 | Reverse an Array | Basic | https://www.geeksforgeeks.org/problems/reverse-an-array/1?page=2&category=Arrays,Pointers&difficulty=Basic,Easy&sortBy=submissions | Use two pointers (l=0, r=n-1) and swap whi[...] |
| 10 | Count Pairs with Given Sum 0 | Easy | https://www.geeksforgeeks.org/problems/count-pairs-with-given-sum5022/1?page=1&category=Arrays,Pointers&difficulty=Basic,Easy&sortBy=submissions |  |
| 11 | Reverse a Number | Basic | [https://www.geeksforgeeks.org/problems/reverse-a-number/0](https://www.geeksforgeeks.org/problems/reverse-digit0316/1) | rev = rev*10 + (n%10); n/=10; stop when n==0. If inpu[...] |
| 12 | Sum of AP | Basic | https://www.geeksforgeeks.org/problems/sum-of-ap-series4512/1 | Use AP sum formula: n*(2*a + (n-1)*d)/2 (use long long). |
| 13 | Prime Number | Basic | https://www.geeksforgeeks.org/problems/prime-number2314/1 | Handle n<=1 as not prime; check divisibility from 2 to (or i*i<=n) and return prime if none. |
| 14 | Number of Factors | Easy | https://www.geeksforgeeks.org/problems/number-of-factors1435/1 | Count divisors by looping i=1..sqrt(n). If i divides n, add 2 (i and n/i); add 1 if i*i==n. |
| 15 | Palindrome Number | Basic | https://www.geeksforgeeks.org/problems/palindrome0746/1 | Reverse the number and compare with original (store a copy). Or compare digits from both ends without converting to[...] |
| 16 | LCM | Easy | https://www.geeksforgeeks.org/problems/gcd-of-two-numbers3459/1 | Compute gcd using Euclid (while b { a%=b; swap }), then lcm = (a/gcd)*b (use long long to avoid overflow). |